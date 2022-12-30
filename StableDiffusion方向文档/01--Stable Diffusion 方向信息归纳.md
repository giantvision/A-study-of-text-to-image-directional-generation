# Stable Diffusion 方向信息归纳

**参考信息源：**

- [Twitter - Gradio](https://twitter.com/Gradio/status/1570519618682519553)
- [Reddit - r/StableDiffusion](https://www.reddit.com/r/StableDiffusion/comments/wqaizj/list_of_stable_diffusion_systems/)
- [Reddit - r/StableDiffusion/index](https://www.reddit.com/r/StableDiffusion/wiki/index/)
- [Reddit - r/bigsleep](https://www.reddit.com/r/bigsleep/comments/xb5cat/wiskkeys_lists_of_texttoimage_systems_and_related/)

**目前的主流技术实现方法( text-to-image)：**

- [Stable Diffusion](https://stability.ai/blog/stable-diffusion-public-release);
- [DALLE](https://openai.com/dall-e-2/);
- [Midjourney](https://www.midjourney.com/);

**Human face image transformation systems:**

- [CodeFormer](https://github.com/sczhou/CodeFormer)：人脸面部修复
- [GFP-GAN](https://github.com/TencentARC/GFPGAN)：人脸修复及着色
-  [GPEN](https://github.com/yangxy/GPEN)：人脸修复





## List of Stable Diffusion Systems

这篇文章有 3 个列表。这些列表不会详尽无遗，而是会尝试专注于流行、优质或独特的商品。 *PICK* 表示我建议在考虑非PICK* 项目之前考虑该项目是否满足您的需求。我还没有尝试过一些列出的项目 - 包括 *PICK* 项目 - 所以请自行决定在此处使用任何内容。欢迎反馈。

**See also**: [Wiskkey's lists of text-to-image systems and related resources](https://www.reddit.com/r/bigsleep/comments/xb5cat/wiskkeys_lists_of_texttoimage_systems_and_related/).

**Systems**:

1. ***PICK\*** (Added Aug. 16, 2022) GitHub repo [stable_diffusion](https://github.com/CompVis/stable-diffusion) by CompVis. Official GitHub repo. This repo requires a GPU with at least 10GB of VRAM. Some forks of this repo require less VRAM. These installation guides are for command-line usage. [Installation guide for Windows](https://www.howtogeek.com/830179/how-to-run-stable-diffusion-on-your-pc-to-generate-ai-images/). [Installation guide for Linux](https://www.assemblyai.com/blog/how-to-run-stable-diffusion-locally-to-generate-images/).
2. ***PICK\*** (Added Aug. 20, 2022) Web app [Stable Diffusion DreamStudio beta](https://beta.dreamstudio.ai/) by Stability AI. Official web app.
3. ***PICK\*** (Added Aug. 22, 2022) Web app [NeuralBlender](https://neuralblender.com/create-art) using Phoebe Blend. Uncensored.
4. (Added Aug. 22, 2022) Web app [NightCafe](https://creator.nightcafe.studio/stable-diffusion-image-generator).
5. ***PICK\*** (Added Aug. 22, 2022) Web app [Stable Diffusion](https://huggingface.co/spaces/stabilityai/stable-diffusion) at site HuggingFace by Stability AI. Official web app. Censored.
6. (Added Aug. 22, 2022) Web app [neural.love AI art generator](https://neural.love/ai-art-generator). Censored.
7. (Added Aug. 22, 2022) Web app [Dezgo](https://dezgo.com/). Uncensored.
8. ***PICK\*** (Added Aug. 22, 2022) Web app [Stable Diffusion](https://replicate.com/stability-ai/stable-diffusion) at site Replicate by Stability AI. Official web app.
9. (Added Aug. 23, 2022) Colab notebook [pharmapsychotic_Stable_Diffusion](https://colab.research.google.com/github/pharmapsychotic/ai-notebooks/blob/main/pharmapsychotic_Stable_Diffusion.ipynb) by pharmapsychotic. [GitHub repo](https://github.com/pharmapsychotic/ai-notebooks/). [Tutorial](https://brainartlabs.com/2022/08/28/stablediffusion-notebook-by-pharmapsychotic-setup-tutorial/). txt2img. img2img. Uses CompVis repo.
10. (Added Aug. 23, 2022) Colab notebook [DrEyeBender's Stable Diffusion notebook - Public copy](https://colab.research.google.com/github/isaac-bender/stable_diffusion_interp/blob/main/DrEyeBender's_Stable_Diffusion_notebook_Public_copy.ipynb) by isaac-bender. [GitHub repo](https://github.com/isaac-bender/stable_diffusion_interp). [Reference](https://www.reddit.com/r/StableDiffusion/comments/wvecza/stable_diffusion_colab_with_prompt_interpolation/). txt2img. "Stuff I added: 1. Prompt interpolation 2. [...] ". Uses CompVis repo.
11. (Added Aug. 23, 2022) Colab notebook [Stable Diffusion](https://colab.research.google.com/drive/1uWCe41_BSRip4y4nlcB8ESQgKtr5BfrN?usp=sharing) by ryan. txt2img. img2img. Allows you to use the CompVis GitHub repo from the command line.
12. (Added Aug. 23, 2022) Colab notebook [Neo Hidamari Diffusion](https://colab.research.google.com/drive/1AfAmwLMd_Vx33O9IwY2TmO9wKZ8ABRRa?usp=sharing) by fuoueternal. [GitHub repo](https://github.com/FuouM/HidamariDiffusionColab). [Reference](https://www.reddit.com/r/StableDiffusion/comments/ww9a0r/colab_notebook_neo_hidamari_diffusion_has_many/). txt2img. img2img. Uses basujindal repo or sd-webui repo.
13. (Added Aug. 24, 2022) Discord bot [Midjourney](https://www.midjourney.com/home/) - specify model in /settings.
14. (Added Aug. 24, 2022) Colab notebook [Stable Diffusion Lite](https://colab.research.google.com/drive/1cJPmCCUFqVMaF--ee51RVFDCOF09Epbc?usp=sharing) by futureart3030. [GitHub repo](https://github.com/vincefav/stable-diffusion-lite). txt2img. img2img. Uses CompVis repo.
15. (Added Aug. 24, 2022) Colab notebook [Stable_Diffusion_Simple_Interpolation](https://colab.research.google.com/drive/1EHZtFjQoRr-bns1It5mTcOVyZzZD9bBc?usp=sharing) by yz5528. txt2img. img2img. Uses CompVis repo.
16. (Added Aug. 24, 2022) Web app [stable-diffusion-wip](https://replicate.com/andreasjansson/stable-diffusion-wip) by andreasjansson. "Inpainting for Stable Diffusion".
17. ***PICK\*** (Added Aug. 24, 2022) Windows program [Stable Diffusion GRisk](https://grisk.itch.io/stable-diffusion-gui). No installation is needed.
18. (Added Aug. 25, 2022) Colab notebook [Stable Diffusion](https://colab.research.google.com/drive/1nptjUvtOh3nHtp1BlzpP1cxSfTvudHEW?usp=sharing) by ssujithkumar010. [Reference](https://www.reddit.com/r/StableDiffusion/comments/wwl47n/i_made_a_step_by_step_guide_to_run_stable/). [Guide](https://sassexplorer.notion.site/sassexplorer/Guide-to-run-Stable-Diffusion-on-Google-Colab-fa803a5cffc04de491eb4a7c036ec15b) (buy [here](https://saasexplorer.gumroad.com/l/mpckg) to support the developer). txt2img. img2img. Uses HuggingFace diffusers repo.
19. (Added Aug. 25, 2022) Paperspace notebook [stable-diffusion](https://console.paperspace.com/github/gradient-ai/stable-diffusion/blob/main/stable-diffusion-notebook.ipynb?machine=Free-GPU). [Reference](https://www.reddit.com/r/StableDiffusion/comments/wwlhjo/you_can_now_run_stable_diffusion_on_paperspace/). Uses HuggingFace diffusers repo.
20. (Updated Aug. 27, 2022) GitHub repo [stable_diffusion](https://github.com/lstein/stable-diffusion) by lstein. [Arkitecc's installation guide for Windows and Linux](https://docs.google.com/document/d/1owAMJGe56sbocCdrv7IO8fM6I4NLqxZ2bJgfI7EsYAw/edit). [Installation guide for Mac with M1 or M2 chip](https://www.reddit.com/r/StableDiffusion/comments/x3yf9i/stable_diffusion_and_m1_chips_chapter_2/). Fork of CompVis repo. "an interactive command-line script that combines text2img and img2img functionality in a dream bot style interface, a WebGUI, and multiple features and other enhancements".
21. (Updated Aug. 27, 2022) Colab notebook [Stable Diffusion with diffusers](https://colab.research.google.com/github/huggingface/notebooks/blob/main/diffusers/stable_diffusion.ipynb) by huggingface. [GitHub repo](https://github.com/huggingface/notebooks/tree/main/diffusers). [Video tutorial](https://www.youtube.com/watch?v=cxJ_cBuBpUU). Official Colab notebook. txt2img. Uses HuggingFace diffusers repo.
22. ***PICK\*** (Updated Aug. 27, 2022) Web app [Artbreeder Collage](https://collage.artbreeder.com/). [Short video demonstration](https://twitter.com/MartinNebelong/status/1562745663376719873). [Video tutorial](https://www.youtube.com/watch?v=HQKRGDHNgR8). img2img. Allows the user to create the initial image using shapes and images.
23. (Added Aug. 27, 2022) Colab notebook [pharmapsychotic_Stable_Diffusion_w_video_init](https://colab.research.google.com/drive/17imvqjQq4BoEqRHBw4HyvBpzirCJh_iA?usp=sharing) by henryamsterfritz. txt2img. img2img. Uses CompVis repo.
24. (Added Aug. 27, 2022) Kaggle notebook [Stable Diffusion (NSFW)](https://www.kaggle.com/code/josepc/stable-diffusion-nsfw/notebook) by josepc. [Tutorial](https://jerry-master.github.io/GranaData/stable_diffusion_tutorial/). Uses HuggingFace diffusers repo.
25. (Updated Aug. 27, 2022) Multiple systems by Pixelmind: [web app](https://beta.pixelmind.ai/) and [Discord bot](https://discord.gg/Pixelmind).
26. (Added Aug. 27, 2022) Web app [stable-diffusion-animation](https://replicate.com/andreasjansson/stable-diffusion-animation) by andreasjansson. "Animate between two prompts using Stable Diffusion".
27. (Added Aug. 27, 2022) Web app [Composable-Diffusion](https://huggingface.co/spaces/Shuang59/Composable-Diffusion) by Shuang59. "Our method can compose multiple diffusion models during inference and generate images containing all the concepts described in the inputs without further training."
28. ***PICK\*** (Added Aug. 28, 2022) Web app [Diffuse The Rest](https://huggingface.co/spaces/huggingface/diffuse-the-rest) by huggingface. img2img.
29. (Added Aug. 28, 2022) Colab notebook [Enhanced Stable Diffusion with diffusers](https://colab.research.google.com/github/Skquark/structured-prompt-generator/blob/main/Enhanced_Stable_Diffusion_with_diffusers.ipynb) by Skquark. [GitHub repo](https://github.com/Skquark/structured-prompt-generator/). txt2img. img2img. Inpainting. Uses [csaluski diffusers repo](https://github.com/csaluski/diffusers).
30. ***PICK\*** (Added Aug. 28, 2022) Colab notebook [Stable Diffusion WebUi - Altryne](https://colab.research.google.com/github/altryne/sd-webui-colab/blob/main/Stable_Diffusion_WebUi_Altryne.ipynb) by altryne. [GitHub repo](https://github.com/altryne/sd-webui-colab). txt2img. img2img. inpainting. Gradio user interface. Uses sd-webui repo.
31. (Updated Aug. 29, 2022) Web app, Apple app, Google Play app, and Discord bot by [Pixelz AI](https://pixelz.ai/).
32. (Updated Aug. 29, 2022) GitHub repo [stable_diffusion.openvino](https://github.com/bes-dev/stable_diffusion.openvino) by bes-dev. Installation guide [CPU RETARD GUIDE](https://rentry.org/cputard) (for Windows). For CPUs compatible with [OpenVINO](https://en.wikipedia.org/wiki/OpenVINO).
33. (Updated Aug. 31, 2022) GitHub repo [stable_diffusion](https://github.com/basujindal/stable-diffusion) by basujindal. Fork of CompVis repo. "modifed to use lesser VRAM than the original by sacrificing on inference speed." [Installation guide #1 for Windows](https://rentry.org/SDInstallation). [Installation guide #2 for Windows](https://rentry.org/optimizedretardsguide). [Installation guide for Windows and Linux](https://docs.google.com/document/d/1owAMJGe56sbocCdrv7IO8fM6I4NLqxZ2bJgfI7EsYAw/edit).
34. ***PICK\*** (Updated Aug. 31, 2022) Windows program [NMKD Stable Diffusion GUI](https://nmkd.itch.io/t2i-gui). [Reference](https://www.reddit.com/r/StableDiffusion/comments/x1hp4u/my_easytoinstall_windows_gui_for_stable_diffusion/). txt2img. img2img.
35. (Added Aug. 31, 2022) Colab notebook [SD_interpolation](https://colab.research.google.com/github/schmidtdominik/stablediffusion-interpolation-tools/blob/main/SD_interpolation.ipynb) by schmidtdominik. [GitHub repo](https://github.com/schmidtdominik/stablediffusion-interpolation-tools). [Reference](https://www.reddit.com/r/StableDiffusion/comments/wzfajz/best_prompt_interpolation_yet_code_in_comments/).
36. ***PICK\*** (Added Aug. 31, 2022) Multiple Stable Diffusion GitHub repos [using keyword search](https://github.com/search?o=desc&p=1&q=stable+diffusion&s=stars&type=Repositories) or [using tag search](https://github.com/topics/stable-diffusion?o=desc&s=stars).
37. (Added Aug. 31, 2022) Web app [Photosonic](https://photosonic.ai/). Censored.
38. (Added Aug. 31, 2022) Web app [scum](https://scum.co/). Censored.
39. (Added Aug. 31, 2022) Web app [Stable Diffusion Demo at Baseten](https://app.baseten.co/apps/VqK2vYP/operator_views/pqvba2q). Censored.
40. (Added Aug. 31, 2022) GitHub repo [Stable Diffusion WebUI Docker](https://github.com/AbdBarho/stable-diffusion-webui-docker) by AbdBarho. "Run Stable Diffusion on your machine with a nice UI without any hassle!" Requires Docker to be installed.
41. (Added Aug. 31, 2022) Apple apps and Google Play app by [Lightricks](https://www.lightricks.com/text-to-image).
42. (Added Aug. 31, 2022) Photoshop plugin [alpaca](https://www.getalpaca.io/).
43. (Added Aug. 31, 2022) Web app [Pollinations Stable Diffusion](https://pollinations.ai/create/stablediffusion). Uncensored.
44. (Added Aug. 31, 2022) Windows program [Visions of Chaos](https://softology.pro/voc.htm). Has many other scripts, including [these text-to-image systems](https://softologyblog.wordpress.com/2021/06/10/text-to-image-summary/).
45. (Added Sep. 1, 2022) Web app [deforum_stable_diffusion](https://replicate.com/deforum/deforum_stable_diffusion) by deforum. "Animating prompts with stable diffusion".
46. ***PICK\*** (Updated Sep. 5, 2022) GitHub repo[ stable-diffusion-ui](https://github.com/cmdr2/stable-diffusion-ui) by cmdr2. Windows program and Linux program. ["](https://www.reddit.com/r/StableDiffusion/comments/ww11mu/made_a_simple_browserbased_ui_for_playing_with/)A simple 1-click way to install and use Stable Diffusion on your own computer. Provides a browser UI for generating images from text prompts and images."
47. ***PICK\*** (Updated Sep 5., 2022) Colab notebook [NSFW Disabled: NOP's Stable Diffusion Colab](https://colab.research.google.com/drive/1jUwJ0owjigpG-9m6AI_wEStwimisUE17?usp=sharing) by david. txt2img. img2img. Inpainting. Uses HuggingFace diffusers repo or [DamascusGit repo](https://github.com/DamascusGit/stable-diffusion).
48. (Added Sep. 5, 2022) Web app [Patience](https://www.patience.ai/). Uncensored.
49. ***PICK\*** (Updated Sep. 5, 2022) Colab notebook [Deforum_Stable_Diffusion + Interpolation](https://colab.research.google.com/github/deforum/stable-diffusion/blob/main/Deforum_Stable_Diffusion.ipynb) by deforum. txt2img. img2img. Uses [deforum repo](https://github.com/deforum/stable-diffusion). [Video tutorial #1](https://www.youtube.com/watch?v=cBT8vEgimz0). [Video tutorial #2](https://www.youtube.com/watch?v=MR7M1HSXgos).
50. (Added Sep. 5, 2022) Web app, Apple app, and Google Play app [Wombo Dream](https://www.wombo.art/). Some styles such as Realistic use Stable Diffusion.
51. (Added Sep. 5, 2022) GitHub repo [Stable Diffusion JupyterLab Docker](https://github.com/pieroit/stable-diffusion-jupyterlab-docker) by pieroit. "Generate images with Stable Diffusion inside JupyterLab!". Requires Docker to be installed.
52. (Added Sep. 5, 2022) Web app [thumbsnap](https://thumbsnap.com/gen). Uncensored.
53. (Added Sep. 5, 2022) Web app, Apple app, and Google Play app [starryai](https://www.starryai.com/). Use Argo method.
54. (Added Sep. 5, 2022) Multiple systems for Wonder: [Apple app](https://apps.apple.com/us/app/wonder-ai-art-generator/id1621278575) and [Google Play app](https://play.google.com/store/apps/details?id=com.codeway.wonder&hl=en_US&gl=US).
55. (Added Sep. 5, 2022) Web app [Pinegraph](https://pinegraph.com/create).
56. (Added Sep. 7, 2022) Colab notebook [StableDiffusionUI-Voldemort](https://colab.research.google.com/drive/1Iy-xW9t1-OQWhb0hNxueGij8phCyluOh?usp=sharing) by 16777216c. txt2img. img2img. Inpainting. Gradio user interface. Uses AUTOMATIC1111 repo.
57. (Added Sep. 7, 2022) Web app [canova.ai](https://canova.ai/). Censored.
58. (Added Sep. 7, 2022) GitHub repo [Yet Another Stable Diffusion Discord Bot](https://github.com/AmericanPresidentJimmyCarter/yasd-discord-bot) by AmericanPresidentJimmyCarter. For Linux.
59. ***PICK\*** (Added Sep. 7, 2022) Colab notebook [Simple Stable](https://colab.research.google.com/drive/1BRvQ6sseZxDDOv_b-ngVR0UdRG8P0Qd4?usp=sharing) by bearsharktopusdev. txt2img. img2img. Easy to use. Uses CompVis repo.
60. (Added Sep. 7, 2022) Web app [sd-aesthetic-guidance](https://replicate.com/afiaka87/sd-aesthetic-guidance) by afiaka87. "guide boring outputs to be more aesthetically pleasing".
61. (Added Sep. 7, 2022) Web app [material_stable_diffusion](https://replicate.com/tommoore515/material_stable_diffusion) by tommoore515. [GitHub repo](https://github.com/TomMoore515/material_stable_diffusion). "for generating tileable outputs".
62. (Added Sep. 8, 2022) Web app [Inpainter](https://inpainter.vercel.app/paint). [GitHub repo](https://github.com/zeke/inpainter).
63. ***PICK\*** (Updated Sep. 9, 2022) GitHub repo [stable-diffusion-webui](https://github.com/sd-webui/stable-diffusion-webui) by sd-webui. [Installation guide #1 for Windows](https://github.com/sd-webui/stable-diffusion-webui/wiki/Installation). [Installation guide #2 for Windows](https://rentry.org/GUItard). [Installation guide for Linux](https://rentry.org/linux-sd). [Installation guide for Windows and Linux](https://docs.google.com/document/d/1owAMJGe56sbocCdrv7IO8fM6I4NLqxZ2bJgfI7EsYAw/edit). "Stable Diffusion web UI".
64. ***PICK\*** (Added Sep. 9, 2022) Colab notebook [StableDiffusionUI-Voldemort](https://colab.research.google.com/drive/1zN99ZouzlYObQaPfzwbgwJr6ZqcpYK5-?usp=sharing) by daswerq123. [GitHub repo](https://github.com/daswer123/stable-diffusion-colab). txt2img. img2img. Inpainting. Gradio user interface. Uses AUTOMATIC1111 repo.
65. ***PICK\*** (Updated Sep. 9, 2022) Colab notebook [SD GUITard](https://colab.research.google.com/drive/1KeNq05lji7p-WDS2BL-86Z8Y9SluGng4?usp=sharing) by daswerq123. [GitHub repo](https://github.com/daswer123/stable-diffusion-colab). txt2img. img2img. Inpainting. Gradio user interface. Uses sd-webui repo.
66. ***PICK\*** (Updated Sep. 10, 2022) GitHub repo [Stable Diffusion web UI](https://github.com/AUTOMATIC1111/stable-diffusion-webui) by AUTOMATIC1111. [Installation guide #1 for Windows](https://rentry.org/voldy). [Installation guide #2 for Windows](https://rentry.org/zfawb). [Usage guide](https://rentry.org/e6is6). "A browser interface based on Gradio library for Stable Diffusion."
67. (Added Sep. 10, 2022) Paperspace notebook [stable-diffusion-paperspace](https://github.com/Engineer-of-Stuff/stable-diffusion-paperspace/blob/main/StableDiffusionUI_Voldemort_paperspace.ipynb) by Engineer-of-Stuff. [Usage guide](https://github.com/Engineer-of-Stuff/stable-diffusion-paperspace/blob/main/Docs/Paperspace Guide for Retards.md). [GitHub repo](https://github.com/Engineer-of-Stuff/stable-diffusion-paperspace/). Uses AUTOMATIC1111 repo.
68. (Added Sep. 10, 2022) Colab notebook [stable_diffusion_videos](https://colab.research.google.com/github/nateraw/stable-diffusion-videos/blob/main/stable_diffusion_videos.ipynb) and web app [stable-diffusion-videos](https://replicate.com/nateraw/stable-diffusion-videos) by nateraw. [GitHub repo](https://github.com/nateraw/stable-diffusion-videos). "Generate videos by interpolating the latent space".
69. (Added Sep. 10, 2022) Multiple Stable Diffusion notebooks at Kaggle [using keyword search](https://www.kaggle.com/search?q=stable+diffusion+in%3Anotebooks).
70. ***PICK\*** (Added Sep. 10, 2022) MacOS app (with M1 or M2 chip) [CHARL-E](https://www.charl-e.com/). "an App that runs Stable Diffusion on your Mac".
71. (Added Sep. 10, 2022) Colab notebook [StableDiffusionUI - Tom Riddle Edition](https://colab.research.google.com/github/WASasquatch/StableDiffusionUI-TomRiddle/blob/main/StableDiffusionUI_Tom_Riddle_Edition.ipynb) by WASasquatch. [GitHub repo](https://github.com/WASasquatch/StableDiffusionUI-TomRiddle). txt2img. img2img. Inpainting. Gradio user interface. Uses AUTOMATIC1111 repo.
72. (Added Sep. 10, 2022) Colab notebook [Stability.AI Easy Diffusion](https://colab.research.google.com/github/WASasquatch/easydiffusion/blob/main/Stability_AI_Easy_Diffusion.ipynb) by WASasquatch. [GitHub repo](https://github.com/WASasquatch/easydiffusion). txt2img. img2img. Uses HuggingFace diffusers repo.
73. (Added Sep. 12, 2022) Web app [Stable Diffusion Image Variations](https://huggingface.co/spaces/lambdalabs/stable-diffusion-image-variations) by lambdalabs. [GitHub repo](https://github.com/justinpinkney/stable-diffusion). Generates variations of an input image without use of a text prompt. Censored.
74. (Updated Sep. 12, 2022) Web app [stable-diffusion-high-resolution](https://replicate.com/cjwbw/stable-diffusion-high-resolution) by cjwbw, and GitHub repo [txt2imghd](https://github.com/jquesnelle/txt2imghd) by jquesnelle. [Reference](https://www.reddit.com/r/StableDiffusion/comments/wxm0cf/txt2imghd_generate_highres_images_with_stable/). "It creates detailed, higher-resolution images by first generating an image from a prompt, upscaling it, and then running img2img on smaller pieces of the upscaled image, and blending the result back into the original image."
75. (Added Sep. 12, 2022) Colab notebook [SeamlessTextureInpainting](https://colab.research.google.com/drive/14gt9Z1wqQRS8jVfzJA1K9_PAYlXUAFrR?usp=sharing) by travis.hoppe. "Generate seamless textures".
76. (Added Sep. 13, 2022) Web app [sd-textual-inversion](https://replicate.com/cjwbw/sd-textual-inversion) by cjwbw. Use textual inversion concepts from the [Hugging Face concepts library](https://huggingface.co/sd-concepts-library).
77. ***PICK\*** (Added Sep. 13, 2022) MacOS app (with M1 or M2 chip) [Diffusion Bee](https://github.com/divamgupta/diffusionbee-stable-diffusion-ui). "one-click installer".
78. (Added Sep. 14, 2022) Colab notebook [StableDiffusionUI_Voldemort_gdrive](https://colab.research.google.com/drive/14yxr38HDM9NajUTtLDg-RYZhVSpn-Ip-?usp=sharing) by jannik.quehl. txt2img. img2img. Inpainting. Gradio user interface. Uses AUTOMATIC1111 repo.
79. (Added Sep. 14, 2022) Web app [waifu-diffusion](https://replicate.com/cjwbw/waifu-diffusion) by cjwbw. "waifu-diffusion is a latent text-to-image diffusion model that has been conditioned on high-quality anime images through fine-tuning."
80. ***PICK\*** (Added Sep. 15, 2022) GitHub repo [stablediffusion-infinity](https://github.com/lkwq007/stablediffusion-infinity) by lkwq007, and Colab notebook [stablediffusion_infinity_colab](https://colab.research.google.com/github/lkwq007/stablediffusion-infinity/blob/master/stablediffusion_infinity_colab.ipynb) by lkwq007. [Tutorial](https://www.youtube.com/watch?v=-8jmBGgGj2E). "Outpainting with Stable Diffusion on an infinite canvas".
81. (Added Sep. 15, 2022) Web app [Stable Diffusion Conceptualizer](https://huggingface.co/spaces/sd-concepts-library/stable-diffusion-conceptualizer) by sd-concepts-library. "Navigate through community created concepts and styles via Stable Diffusion Textual Inversion and pick yours for inference."





**Miscellaneous**

1. (Added Aug. 22, 2022) Webpage [Stable Diffusion models at site HuggingFace](https://huggingface.co/CompVis/stable-diffusion). A free account at HuggingFace is needed to download a model.
2. (Added Aug. 22, 2022) Reddit post [Checkpoint v1.4 Mirror (No Huggingface account required)](https://www.reddit.com/r/StableDiffusion/comments/wv4sqt/checkpoint_v14_mirror_no_huggingface_account/).
3. (Added Aug. 22, 2022) Document [Stable Diffusion Akashic Records: A compendium of information regarding Stable Diffusion](https://github.com/Maks-s/sd-akashic).
4. (Added Aug. 22, 2022) Reddit post [A webpage to search for images in the Stable Diffusion training dataset that are similar to a given generated image](https://www.reddit.com/r/StableDiffusion/comments/wby0ob/it_might_be_possible_for_stable_diffusion_models/).
5. (Added Aug. 23, 2022) Reddit post [Tutorial: How to Remove the Safety Filter in 5 seconds](https://www.reddit.com/r/StableDiffusion/comments/wv2nw0/tutorial_how_to_remove_the_safety_filter_in_5/).
6. (Updated Aug. 28, 2022) Document [AMD guide for Linux](https://rentry.org/sdamd).
7. (Added Aug. 31, 2022) [Awesome Stable-Diffusion](https://github.com/awesome-stable-diffusion/awesome-stable-diffusion).
8. (Updated Sep 5, 2022) Document [SD GUIDE FOR ARTISTS AND NON-ARTISTS: IN-DEPTH TIPS, TRICKS, TUTORIALS AND MORE](https://docs.google.com/document/d/1R2UZi5G-DXiz2HcCrfAFLYJoer_JPDEoZmV7wy1tEz0/edit).
9. (Added Sep. 7, 2022) Document [AMD guide for Windows](https://rentry.org/ayymd-stable-diffustion-v1_4-guide).
10. (Added Sep. 12, 2022) [Tito Castillo's Stable Diffusion Resources](https://rentry.org/h8bnyg).
11. (Added Sep. 13, 2022) [Dreamer's Guide to Getting Started w/ Stable Diffusion!](https://www.reddit.com/r/StableDiffusion/comments/xcq819/dreamers_guide_to_getting_started_w_stable/)
12. (Added Sep. 13, 2022) [Standard Diffusion Models](https://rentry.org/yrpvv) (incorrectly called "datasets").
13. (Added Sep. 13, 2022) [Can we please make a general update on all the "most important" news/repos available?](https://www.reddit.com/r/StableDiffusion/comments/xcclmf/can_we_please_make_a_general_update_on_all_the/)
14. (Added Sep. 14, 2022) [A collection of sites using Stable Diffusion (and other handy links)](https://www.reddit.com/r/StableDiffusion/comments/wzj8kk/a_collection_of_sites_using_stable_diffusion_and/).



## Wiskkey's lists of text-to-image systems and related resources

![img](https://www.redditstatic.com/desktop2x/img/renderTimingPixel.png)

Recommended text-to-image systems (last updated on September 11, 2022):

1. (Tier 1) [DALL-E 2](https://openai.com/dall-e-2/). Subreddit [r/dalle2](https://www.reddit.com/r/dalle2/).
2. (Tier 1) [Stable Diffusion](https://stability.ai/blog/stable-diffusion-public-release). [List of Stable Diffusion systems](https://www.reddit.com/r/StableDiffusion/comments/wqaizj/list_of_stable_diffusion_systems/). Subreddit [r/StableDiffusion](https://www.reddit.com/r/StableDiffusion/).
3. (Tier 1) [Midjourney](https://www.midjourney.com/). Subreddit [r/midjourney](https://www.reddit.com/r/midjourney/).
4. (Tier 1) [Disco Diffusion](https://colab.research.google.com/github/alembics/disco-diffusion/blob/main/Disco_Diffusion.ipynb). Subreddit [r/DiscoDiffusion](https://www.reddit.com/r/DiscoDiffusion/).
5. (Tier 1) [Craiyon](https://www.craiyon.com/) (formerly named DALL-E Mini). Subreddits [r/dallemini](https://www.reddit.com/r/dallemini/) and [r/craiyon](https://www.reddit.com/r/craiyon/). The generated images are small and often not of great quality, but they are often well-related to the text prompt, which makes them well-suited for initial images for other systems.
6. (Tier 1) [ERNIE-ViLG](https://huggingface.co/spaces/PaddlePaddle/ERNIE-ViLG). [Example #1](https://www.reddit.com/r/bigsleep/comments/xbb1ic/photo_of_a_woman_taking_a_selfie_at_mount/). [Example #2](https://www.reddit.com/r/bigsleep/comments/x8rnlo/photo_of_dolls_on_a_store_shelf_ernievilg/). [Example #3](https://www.reddit.com/r/bigsleep/comments/x8sfir/photo_of_jesus_playing_an_electric_guitar_3/).
7. (Tier 1) [Retrieval-augmented latent diffusion from CompVis](https://replicate.com/afiaka87/retrieval-augmented-diffusion).
8. (Tier 1) ruDALL-E Kandinsky model (has 12 billion parameters). Browse rudalle[dot]ru/en/ for details. I obfuscated the link because Reddit doesn't like the unobfuscated link. See [this post](https://www.reddit.com/r/bigsleep/comments/ql9n81/new_texttoimage_ai_models_rudalle_example_from/) and its comments for more ruDALL-E systems. Subreddit [r/rudalle](https://www.reddit.com/r/rudalle/).
9. (Tier 1) [GauGAN2](http://gaugan.org/gaugan2/). [Reference](https://www.reddit.com/r/MediaSynthesis/comments/r04he3/nvidia_releases_web_app_for_gaugan2_which/). For landscapes only.
10. (Tier 2) [Latent Diffusion earlier models](https://www.reddit.com/r/bigsleep/comments/tw8656/woah_there_dragonman_16_output_images_with/).
11. (Tier 2) ruDALL-E Malevich model (has 1.3 billion parameters). Browse rudalle[dot]ru/en/ for details. I obfuscated the link because Reddit doesn't like the unobfuscated link. See [this post](https://www.reddit.com/r/bigsleep/comments/ql9n81/new_texttoimage_ai_models_rudalle_example_from/) and its comments for more ruDALL-E systems. Subreddit [r/rudalle](https://www.reddit.com/r/rudalle/).
12. (Tier 2) [minDALL-E](https://replicate.com/cjwbw/mindall-e). Other minDALL-E systems are available in [this post](https://www.reddit.com/r/bigsleep/comments/rhwany/mindalle_on_conceptual_captions/) and its comments.
13. (Tier 2) [CogView2](https://github.com/THUDM/CogView2). [Examples](https://github.com/THUDM/CogView2/files/8553662/big.1.pdf) (pdf file).
14. (Tier 2) [Laionide v3](https://replicate.com/laion-ai/laionide-v3).
15. (Tier 2) Pixray text2image ([newer version](https://replicate.com/pixray/text2image) with drawer=vqgan, or [older version](https://replicate.com/dribnet/pixray-text2image)). Uses VQGAN+CLIP. See [List of VQGAN+CLIP systems](https://www.reddit.com/user/Wiskkey/comments/p2j673/list_part_created_on_august_11_2021/) for other systems that use VQGAN+CLIP.

My other posts with text-to-image lists:

1. (Added Sep. 10, 2022) [List of Stable Diffusion systems](https://www.reddit.com/r/StableDiffusion/comments/wqaizj/list_of_stable_diffusion_systems/).
2. (Added Sep. 10, 2022) [List of VQGAN+CLIP systems](https://www.reddit.com/user/Wiskkey/comments/p2j673/list_part_created_on_august_11_2021/).
3. (Added Sep. 10, 2022) [List of sites/programs/projects that use OpenAI's CLIP neural network for steering image/video creation to match a text description](https://www.reddit.com/r/bigsleep/comments/tvw5js/list_of_sitesprogramsprojects_that_use_openais/). All items were added in early 2021.

Text-to-image lists from other people (some have broader coverage than text-to-image):

1. (Added Aug. 11, 2021) [Softology's Text-to-Image Summary](https://softologyblog.wordpress.com/2021/06/10/text-to-image-summary/).
2. (Added Aug. 12, 2021) [styler00dollar's list of audiovisual Google Colabs](https://github.com/styler00dollar/dl-colab-notebooks).
3. (Added Mar. 25, 2022) [Hitchhiker's Guide To The Latent Space: Community Notebook Document](https://docs.google.com/document/d/1ON4unvrGC2fSEAHMVb4idopPlWmzM0Lx5cxiOXG47k4/edit).
4. (Added Mar. 25, 2022) [Pharmapsychotic's Tools and Resources for AI Art](https://pharmapsychotic.com/tools.html).
5. (Added Mar. 25, 2022) [Awesome Text-to-Image](https://github.com/Yutong-Zhou-cv/Awesome-Text-to-Image).
6. (Added Mar. 25, 2022) [Awesome CLIP](https://github.com/yzhuoning/Awesome-CLIP).
7. (Added Mar. 25, 2022) [Text-to-Image Generation | Papers With Code](https://paperswithcode.com/task/text-to-image-generation).
8. (Added Mar. 25, 2022) [GitHub topic "text-to-image"](https://github.com/topics/text-to-image).
9. (Added Mar. 31, 2022) [People and Model Credits](https://docs.google.com/document/d/15ZUtpAn6MgCMDSs9I1yS6i_9IkELOWLiQAKa50vCaLI/edit).
10. (Added Apr. 4, 2022) [Multimodal Image Synthesis and Editing: A Survey](https://github.com/fnzhan/MISE).
11. (Added Apr. 4, 2022) [Generative Deep Art](https://github.com/filipecalegario/awesome-generative-deep-art).
12. (Added Apr. 10, 2022) [Awesome Diffusion Models](https://github.com/heejkoo/Awesome-Diffusion-Models/blob/main/README.md).
13. (Added May 22, 2022) [Weekly Multimodal AI art News](https://multimodalaiart.substack.com/).
14. (Added June 6, 2022) [The Checkpoint](http://newsletter.unlimiteddreamco.xyz/) (AI art newsletter).
15. (Added July 10, 2022) [Phygital+ Library](https://library.phygital.plus/).
16. (Added July 12, 2022) [Replicate.com's collection of text-to-image web apps](https://replicate.com/collections/text-to-image). This collection doesn't contain all of the site's text-to-image web apps.
17. (Added July 19, 2022) [Things I Think Are Awesome](https://arnicas.substack.com/).

Image upscaler systems (which use AI to make a higher resolution version of an input image):

1. (Added Mar. 25, 2022) [Wiskkey's test #2 of upscalers](https://www.reddit.com/r/MediaSynthesis/comments/rmdpy0/6_upscalers_tested_with_2_input_images_the_newest/) (newer post).
2. (Added Mar. 25, 2022) [Wiskkey's test #1 of upscalers](https://www.reddit.com/r/MediaSynthesis/comments/qyqmcy/upscaler_model_swinirlarge_was_released_on/) (older post).
3. (Added Sep. 11, 2022) "Image Super-resolution" section of [Tools and Resources for AI Art](https://pharmapsychotic.com/tools.html) by pharmapsychotic.

Human face image fixer systems:

1. (Added Sep. 11, 2022) [CodeFormer](https://github.com/sczhou/CodeFormer).
2. (Added Sep. 11, 2022) [GFP-GAN](https://github.com/TencentARC/GFPGAN).
3. (Added Sep. 11, 2022) [StyleCLIP](https://www.reddit.com/r/dalle2/comments/wcyiik/tutorial_using_styleclip_ai_to_fixupscale_images/).
4. (Added Sep. 11, 2022) [GPEN](https://github.com/yangxy/GPEN).

Image-to-image systems:

1. (Added Sep. 11, 2022) [Looking Glass v1.5](https://colab.research.google.com/drive/1gr0dSCcFH_hYjbAPuThwAxbA1T8DD1Od?usp=sharing). [Examples made with v1.3](https://www.reddit.com/r/MediaSynthesis/comments/rke4cf/colab_notebook_looking_glass_v13_has_been/).
2. (Added Sep. 11, 2022) [IC-GAN](https://github.com/facebookresearch/ic_gan). Uses 1 image.
3. (Added Sep. 11, 2022) Blog post [Training custom Ai generative models](https://pharmapsychotic.com/training.html).
4. (Added Sep. 11, 2022) img2img functionality of Stable Diffusion ([list](https://www.reddit.com/r/StableDiffusion/comments/wqaizj/list_of_stable_diffusion_systems/)).
5. (Added Sep. 11, 2022) Variations feature of DALL-E 2.

Image-to-text systems:

1. (Added Sep. 11, 2022) [OFA Image_Caption](https://huggingface.co/spaces/OFA-Sys/OFA-Image_Caption).
2. (Added Sep. 11, 2022) [BLIP](https://huggingface.co/spaces/Salesforce/BLIP).
3. (Added Sep. 11, 2022) Colab notebook [CLIP Interrogator](https://colab.research.google.com/github/pharmapsychotic/clip-interrogator/blob/main/clip_interrogator.ipynb) by pharmapsychotic and related web app [img2prompt](https://replicate.com/methexis-inc/img2prompt) by methexis-inc.
4. (Added Sep. 11, 2022) "Image to Text" section of [Tools and Resources for AI Art](https://pharmapsychotic.com/tools.html) by pharmapsychotic.

Search engines for finding similar images to a given image:

1. [4 image search engines](https://www.bellingcat.com/resources/how-tos/2019/12/26/guide-to-using-reverse-image-search-for-investigations/).
2. [LAION-5B dataset search using CLIP](https://www.reddit.com/r/StableDiffusion/comments/wby0ob/it_might_be_possible_for_stable_diffusion_models/).

Text-to-image Reddit subreddits:

1. (Added Feb. 5, 2021) [r/bigsleep](https://www.reddit.com/r/bigsleep/) - subreddit for images/videos generated with text-to-image machine learning algorithms.
2. (Added Feb. 5, 2021) [r/deepdream](https://www.reddit.com/r/deepdream/) - subreddit for images/videos generated with machine learning algorithms. This subreddit is broader than text-to-image.
3. (Added Feb. 5, 2021) [r/mediasynthesis](https://www.reddit.com/r/mediasynthesis/) - subreddit for media generation/manipulation techniques that use artificial intelligence. This subreddit is broader than text-to-image.
4. (Added Sep. 2, 2022) Many more in [this list](https://www.reddit.com/r/ImagenAI/comments/vicrzn/comment/idf7w6e/) compiled by [u/grasputin](https://www.reddit.com/u/grasputin/).

Miscellaneous:

1. (Added Sep. 10, 2022) [The Weird and Wonderful World of AI Art](https://jxmo.notion.site/The-Weird-and-Wonderful-World-of-AI-Art-b9615a2e7278435b98380ff81ae1cf09) (January 2022).
2. (Added Sep. 10, 2022) [Alien Dreams: An Emerging Art Scene](https://ml.berkeley.edu/blog/posts/clip-art/) (June 2021).
3. (Added Sep. 11, 2022) [A post of mine with many links about AI copyright-related issues](https://www.reddit.com/r/bigsleep/comments/uevfch/article_ai_authorship_by_a_law_professor_2020/).
4. (Added Sep. 11, 2022) Part 3 (starting at 5:57) of Vox video [The AI that creates any picture you want, explained](https://www.youtube.com/watch?v=SVcsDDABEkM) explains how some (but not all) text-to-image systems work technically.
5. (Added Sep. 11, 2022) [How OpenAI's DALL-E 2 works explained at the level an average 15-year-old might understand](https://www.reddit.com/r/bigsleep/comments/u08sjh/how_openais_dalle_2_works_explained_at_the_level/).
6. (Added Sep. 11, 2022) [How CLIP-guided text-to-image systems work technically](https://www.reddit.com/r/DiscoDiffusion/comments/t84pyw/comment/hzmprlj/).
7. (Added Sep. 12, 2022) [Textual inversion](https://www.reddit.com/r/bigsleep/comments/wfev6j/an_image_is_worth_one_word_personalizing/): a method for assigning a pseudo-word to a concept using 3 to 5 input images. The pseudo-word can be used in text prompts.
8. (Added Sep. 15, 2022) [Practical Deep Learning for Coders 2022](https://course.fast.ai/).