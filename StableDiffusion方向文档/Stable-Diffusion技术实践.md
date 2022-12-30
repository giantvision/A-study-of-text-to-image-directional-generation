# Stable-Diffusion技术实践



**目前的主流技术实现方法( text-to-image)：**

- [Stable Diffusion](https://stability.ai/blog/stable-diffusion-public-release);
- [DALLE](https://openai.com/dall-e-2/);
- [Midjourney](https://www.midjourney.com/);



### Traning Data

模型使用一下数据集训练而成：

- LAION-5B和子集（详情见下文）。训练数据使用LAION的NSFW检测器进一步过滤，"p_unsafe "分数为0.1 (保守)。更多细节，请参考LAION-5B的 [NeurIPS 2022](https://openreview.net/forum?id=M3Y74vmsMcY) 论文和审稿人关于该主题的讨论。

训练程序 Stable Diffusion v2是一个潜伏的扩散模型，它将自动编码器与扩散模型结合起来，在自动编码器的潜伏空间中进行训练。在训练过程中：

- 图像通过一个编码器进行编码，该编码器将图像转化为潜像表示。自动编码器使用8的相对下采样系数，将形状为H x W x 3的图像映射为形状为H/f x W/f x 4的潜像；
- 文本提示是通过OpenCLIP-ViT/H文本编码器编码的；
- 文本编码器的输出通过交叉注意被送入潜伏扩散模型的UNet主干；
- 损失是添加到潜在的噪声与UNET预测的噪声之间的重建目标。还使用所谓的V-Objective，请参阅https://arxiv.org/abs/2202.00512。



**我们目前提供以下检查点：**

- 512-base-ema.ckpt：在 LAION-5B 的一个子集上以 256x256 的分辨率进行 550k 步，使用 punsafe=0.1 和美学分数 >= 4.5 的 LAION-NSFW 分类器过滤明确的色情内容。在分辨率 >= 512x512 的同一数据集上以分辨率 512x512 进行 850k 步。
- 768-v-ema.ckpt。从512-base-ema.ckpt恢复，在同一数据集上使用v-objective训练了150k步。在我们的数据集的768x768子集上，又恢复了14万步。
- 512-depth-ema.ckpt：从 512-base-ema.ckpt 恢复并微调 200k 步。添加了一个额外的输入通道来处理 MiDaS (dpt_hybrid) 生成的（相对）深度预测，用作附加调节。处理这些额外信息的 U-Net 的额外输入通道被零初始化。
- 512-inpainting-ema.ckpt。从512-base-ema.ckpt恢复，又训练了20万步。遵循LAMA中提出的掩码生成策略，与被掩码图像的潜在VAE表示相结合，作为额外的条件。处理这些额外信息的U-Net的额外输入通道是零初始化的。同样的策略被用于训练1.5-intpainting检查点。
- x4-upscaling-ema.ckpt：在包含图像 >2048x2048 的 LAION 的 10M 子集上训练了 125 万步。该模型在 512x512 大小的作物上进行训练，是一个文本引导的潜在放大扩散模型。除了文本输入之外，它还接收一个 noise_level 作为输入参数，可用于根据预定义的扩散计划向低分辨率输入添加噪声。











