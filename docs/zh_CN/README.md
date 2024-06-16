<p align="center">
    <img src="./assets/readme/icon.png" width="250"/>
</p>
<div align="center">
    <a href="https://github.com/hpcaitech/Open-Sora/stargazers"><img src="https://img.shields.io/github/stars/hpcaitech/Open-Sora?style=social"></a>
    <a href="https://hpcaitech.github.io/Open-Sora/"><img src="https://img.shields.io/badge/Gallery-View-orange?logo=&amp"></a>
    <a href="https://discord.gg/kZakZzrSUT"><img src="https://img.shields.io/badge/Discord-join-blueviolet?logo=discord&amp"></a>
    <a href="https://join.slack.com/t/colossalaiworkspace/shared_invite/zt-247ipg9fk-KRRYmUl~u2ll2637WRURVA"><img src="https://img.shields.io/badge/Slack-ColossalAI-blueviolet?logo=slack&amp"></a>
    <a href="https://twitter.com/yangyou1991/status/1769411544083996787?s=61&t=jT0Dsx2d-MS5vS9rNM5e5g"><img src="https://img.shields.io/badge/Twitter-Discuss-blue?logo=twitter&amp"></a>
    <a href="https://raw.githubusercontent.com/hpcaitech/public_assets/main/colossalai/img/WeChat.png"><img src="https://img.shields.io/badge/微信-小助手加群-green?logo=wechat&amp"></a>
    <a href="https://hpc-ai.com/blog/open-sora-v1.0"><img src="https://img.shields.io/badge/Open_Sora-Blog-blue"></a>
    <a href="https://huggingface.co/spaces/hpcai-tech/open-sora"><img src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Gradio Demo-blue"></a>
</div>

## Open-Sora: 让所有人都能轻松制作高效视频

我们设计并实施了**Open-Sora**，这是一项致力于高效制作高质量视频的计划。我们希望让所有人都能使用模型、工具和所有细节。通过采用开源原则，Open-Sora 不仅使高级视频生成技术的使用变得民主化，而且还提供了一个简化且用户友好的平台，简化了视频生成的复杂性。借助 Open-Sora，我们的目标是在内容创作领域促进创新、创造力和包容性。

[[中文文档]](/docs/zh_CN/README.md) [[潞晨云部署视频教程]](https://www.bilibili.com/video/BV141421R7Ag)

## 📰 资讯

* **[2024.06.17]** 🔥
* 我们发布了**Open-Sora 1.2**，其中包括**3D-VAE**，**整流流**和**得分条件**。视频质量大大提高。[[checkpoints]](#open-sora-10-model-weights) [[report]](/docs/report_03.md)
* **[2024.04.25]** 🤗 我们在 Hugging Face Spaces 上发布了 [Open-Sora的Gradio演示](https://huggingface.co/spaces/hpcai-tech/open-sora)。
* **[2024.04.25]** 我们发布了**Open-Sora 1.1**，支持**2s~15s、144p 到 720p、任意比例的文本转图片、文本转视频、图片转视频、视频转视频、无限时间生成**。此外，还发布了完整的视频处理管道。 [[checkpoints]]() [[report]](/docs/report_02.md)
* **[2024.03.18]** 我们发布了 **Open-Sora 1.0**, 一个完全开源的视频生成项目。Open-Sora 1.0 支持完整的视频数据预处理流程、加速训练
  <a href="https://github.com/hpcaitech/ColossalAI"><img src="assets/readme/colossal_ai.png" width="8%" ></a>
、推理等。我们的模型只需 3 天的训练就可以生成 2 秒的 512x512 视频。 [[checkpoints]](#open-sora-10-model-weights)
  [[blog]](https://hpc-ai.com/blog/open-sora-v1.0) [[report]](/docs/report_01.md)
* **[2024.03.04]** Open-Sora 提供培训，成本降低 46%。
  [[blog]](https://hpc-ai.com/blog/open-sora)

## 🎥 Latest Demo

🔥 您可以在HuggingFace上的 [🤗 Gradio应用程序](https://huggingface.co/spaces/hpcai-tech/open-sora)上体验Open-Sora. 我们的[画廊](https://hpcaitech.github.io/Open-Sora/)中提供了更多示例.

<details>
<summary>OpenSora 1.1 演示</summary>

| **2秒 240×426**                                                                                                                                              | **2秒 240×426**                                                                                                                                             |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [<img src="/assets/demo/sample_16x240x426_9.gif" width="">](https://github.com/hpcaitech/Open-Sora-dev/assets/99191637/c31ebc52-de39-4a4e-9b1e-9211d45e05b2) | [<img src="/assets/demo/sora_16x240x426_26.gif" width="">](https://github.com/hpcaitech/Open-Sora-dev/assets/99191637/c31ebc52-de39-4a4e-9b1e-9211d45e05b2) |
| [<img src="/assets/demo/sora_16x240x426_27.gif" width="">](https://github.com/hpcaitech/Open-Sora-dev/assets/99191637/f7ce4aaa-528f-40a8-be7a-72e61eaacbbd)  | [<img src="/assets/demo/sora_16x240x426_40.gif" width="">](https://github.com/hpcaitech/Open-Sora-dev/assets/99191637/5d58d71e-1fda-4d90-9ad3-5f2f7b75c6a9) |

| **2秒 426×240**                                                                                                                                             | **4秒 480×854**                                                                                                                                              |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [<img src="/assets/demo/sora_16x426x240_24.gif" width="">](https://github.com/hpcaitech/Open-Sora-dev/assets/99191637/34ecb4a0-4eef-4286-ad4c-8e3a87e5a9fd) | [<img src="/assets/demo/sample_32x480x854_9.gif" width="">](https://github.com/hpcaitech/Open-Sora-dev/assets/99191637/c1619333-25d7-42ba-a91c-18dbc1870b18) |

| **16秒 320×320**                                                                                                                                        | **16秒 224×448**                                                                                                                                        | **2秒 426×240**                                                                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [<img src="/assets/demo/sample_16s_320x320.gif" width="">](https://github.com/hpcaitech/Open-Sora/assets/99191637/3cab536e-9b43-4b33-8da8-a0f9cf842ff2) | [<img src="/assets/demo/sample_16s_224x448.gif" width="">](https://github.com/hpcaitech/Open-Sora/assets/99191637/9fb0b9e0-c6f4-4935-b29e-4cac10b373c4) | [<img src="/assets/demo/sora_16x426x240_3.gif" width="">](https://github.com/hpcaitech/Open-Sora-dev/assets/99191637/3e892ad2-9543-4049-b005-643a4c1bf3bf) |


</details>

<details>
<summary>OpenSora 1.0 Demo</summary>

| **2秒 512×512**                                                                                                                                                                 | **2秒 512×512**                                                                                                                                                              | **2秒 512×512**                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| [<img src="/assets/readme/sample_0.gif" width="">](https://github.com/hpcaitech/Open-Sora/assets/99191637/de1963d3-b43b-4e68-a670-bb821ebb6f80)                                 | [<img src="/assets/readme/sample_1.gif" width="">](https://github.com/hpcaitech/Open-Sora/assets/99191637/13f8338f-3d42-4b71-8142-d234fbd746cc)                              | [<img src="/assets/readme/sample_2.gif" width="">](https://github.com/hpcaitech/Open-Sora/assets/99191637/fa6a65a6-e32a-4d64-9a9e-eabb0ebb8c16)    |
|森林地区宁静的夜景。 [...] 该视频是一段延时摄影，捕捉了白天到夜晚的转变，湖泊和森林始终作为背景。 | 无人机拍摄的镜头捕捉到了海岸悬崖的壮丽美景，[...] 海水轻轻地拍打着岩石底部和紧贴悬崖顶部的绿色植物。| 瀑布从悬崖上倾泻而下，流入宁静的湖泊，气势磅礴。[...] 摄像机角度提供了瀑布的鸟瞰图。 |
| [<img src="/assets/readme/sample_3.gif" width="">](https://github.com/hpcaitech/Open-Sora/assets/99191637/64232f84-1b36-4750-a6c0-3e610fa9aa94)                                 | [<img src="/assets/readme/sample_4.gif" width="">](https://github.com/hpcaitech/Open-Sora/assets/99191637/983a1965-a374-41a7-a76b-c07941a6c1e9)                              | [<img src="/assets/readme/sample_5.gif" width="">](https://github.com/hpcaitech/Open-Sora/assets/99191637/ec10c879-9767-4c31-865f-2e8d6cf11e65)    |
| 夜晚繁华的城市街道，充满了汽车前灯的光芒和路灯的氛围光。 [...]                                                           | 向日葵田的生机勃勃，美不胜收。向日葵整齐排列，给人一种秩序感和对称感。 [...]                                            |宁静的水下场景，一只海龟在珊瑚礁中游动。这只海龟的壳呈绿褐色 [...]                   |

视频经过降采样以.gif用于显示。单击查看原始视频。提示经过修剪以用于显示，请参阅[此处](/assets/texts/t2v_samples.txt)查看完整提示。

</details>

## 🔆 新功能/更新

* 📍 **Open-Sora 1.2** 发布。模型权重可在[此处](#model-weights)查看。有关更多详细信息，请参阅我们的**[技术报告 v1.2](docs/report_03.md)** 。 
* ✅ 支持整流流调度。
* ✅ 训练我们的 3D-VAE 进行时间维度压缩。
* 📍 **Open-Sora 1.1**发布。模型权重可在[此处](#model-weights)获得。它针对**0s~15s、144p 到 720p、各种宽高比**的视频进行训练。有关更多讨论，请参阅我们的**[技术报告 v1.1](/docs/report_02.md)** 。
* 🔧 **数据处理流程** v1.1发布，提供从原始视频到（文本，视频片段）对的自动处理流程，包括场景剪切$\rightarrow$过滤（美学、光流、OCR 等）$\rightarrow$字幕$\rightarrow$管理。使用此工具，您可以轻松构建视频数据集。
* ✅ 改进的 ST-DiT 架构包括 rope 位置编码、qk 范数、更长的文本长度等。
* ✅ 支持任意分辨率、纵横比和时长（包括图像）的训练。
* ✅ 支持图像和视频调节以及视频编辑，从而支持动画图像，连接视频等。
* 📍 **Open-Sora 1.0**发布。模型权重可在[此处](#model-weights)获得。仅使用 400K 视频片段和 200 个 H800 天（相比稳定视频扩散中的 152M 样本），我们就能生成 2s 512×512 视频。有关更多讨论，请参阅我们的**[技术报告 v1.0](docs/report_01.md)**。
* ✅从图像扩散模型到视频扩散模型的三阶段训练。我们为每个阶段提供权重。
* ✅ 支持训练加速，包括加速 Transformer、更快的 T5 和 VAE 以及序列并行。Open-Sora 在 64x512x512 视频上训练时可将训练速度提高**55%**。详细信息位于[训练加速.md](docs/acceleration.md)。
* 🔧 **数据预处理流程 v1.0**,包括 [下载](tools/datasets/README.md), [视频剪辑](tools/scene_cut/README.md), 和 [字幕](tools/caption/README.md) 工具. 我们的数据收集计划可在 [数据集.md](docs/datasets.md)中找到.

<details>
<summary>查看更多</summary>

✅ 我们发现[VideoGPT](https://wilson1yan.github.io/videogpt/index.html)的 VQ-VAE质量较低，因此采用了[Stability-AI](https://huggingface.co/stabilityai/sd-vae-ft-mse-original)中的更好的 VAE 。我们还发现时间维度的修补会降低质量。有关更多讨论，请参阅我们的**[技术报告v1.0](docs/report_01.md)**。
✅ 我们研究了不同的架构，包括 DiT、Latte 和我们提出的 **STDiT**。我们的STDiT在质量和速度之间实现了更好的平衡。请参阅我们的 **[技术报告v1.0](docs/report_01.md)**以了解更多讨论。
✅ 支持剪辑和T5文本调节。
✅ 通过将图像视为单帧视频，我们的项目支持在图像和视频上训练 DiT（例如 ImageNet 和 UCF101）。有关更多说明，请参阅[commands.md](docs/commands.md) 。
✅ 支持使用[DiT](https://github.com/facebookresearch/DiT), [Latte](https://github.com/Vchitect/Latte),
  和 [PixArt](https://pixart-alpha.github.io/).的官方权重进行推理。
✅ 重构代码库。查看[structure.md](docs/structure.md)以了解项目结构以及如何使用配置文件。

</details>

### 按优先级排序的 TODO 列表

<details>
<summary>查看更多</summary>

* [x] 训练视频 VAE 并使我们的模型适应新的 VAE
* [x] 缩放模型参数和数据集大小
* [x] 纳入更好的调度程序（整流流程）
* [x] 评估流程
* [x] 完成数据处理流程（包括密集光流、美学评分、文本-图像相似度等）。有关更多信息，请参阅[数据集](/docs/datasets.md)
* [x] 支持图像和视频调节
* [x] 支持可变的纵横比、分辨率和持续时间

</details>

## 内容

* [安装](#安装)
* [模型权重](#模型权重)
* [Gradio演示](#gradio演示)
* [推理](#推理)
* [数据处理](#数据处理)
* [训练](#训练)
* [评估](#评估)
* [贡献](#贡献)
* [引用](#引用)
* [致谢](#致谢)

下面列出了其他有用的文档和链接。

* 报告: [技术报告 v1.2](docs/report_v3.md), [技术报告 v1.1](/docs/report_v2.md), [技术报告 v1.0](/docs/report_v1.md), [训练加速.md](docs/acceleration.md)
* Repo 结构: [结构.md](docs/structure.md)
* 配置文件说明: [config.md](docs/config.md)
* Useful commands: [commands.md](docs/commands.md)
* 数据处理管道和数据集: [datasets.md](docs/datasets.md)
* 每个数据处理工具的 README: [dataset conventions and management](/tools/datasets/README.md), [scene cutting](/tools/scene_cut/README.md), [scoring](/tools/scoring/README.md), [caption](/tools/caption/README.md)
* 评估: [eval](/eval/README.md)
* 画廊: [gallery](https://hpcaitech.github.io/Open-Sora/)

## 安装

### 从源头安装

对于 CUDA 12.1，您可以使用以下命令[安装](/docs/installation.md)依赖项。否则，请参阅安装以获取有关不同 cuda 版本的更多说明以及数据预处理的其他依赖项。

```bash
# create a virtual env and activate (conda as an example)
conda create -n opensora python=3.9
conda activate opensora

# install torch, torchvision and xformers
pip install -r requirements/requirements-cu121.txt

# download the repo
git clone https://github.com/hpcaitech/Open-Sora
cd Open-Sora

# the default installation is for inference only
pip install -v . # for development mode, `pip install -v -e .`


(Optional, recommended for fast speed, especially for training) To enable `layernorm_kernel` and `flash_attn`, you need to install `apex` and `flash-attn` with the following commands.

```bash
# install flash attention
# set enable_flash_attn=False in config to disable flash attention
pip install packaging ninja
pip install flash-attn --no-build-isolation

# install apex
# set enable_layernorm_kernel=False in config to disable apex
pip install -v --disable-pip-version-check --no-cache-dir --no-build-isolation --config-settings "--build-option=--cpp_ext" --config-settings "--build-option=--cuda_ext" git+https://github.com/NVIDIA/apex.git
```

### 使用Docker

运行以下命令从提供的Dockerfile 构建docker 镜像。

```bash
docker build -t opensora ./docker
```

运行以下命令以交互模式启动docker容器。

```bash
docker run -ti --gpus all -v {MOUNT_DIR}:/data opensora
```

## 模型权重

### Open-Sora 1.2 模型权重
| 分辨率 | 模型大小 | 数据 | 迭代次数 | 批次大小 | 网址 |
| ---------- | ---------- | ---- | ----------- | ---------- | --- |
| 待定        |

请参阅我们的**[report 1.2](/docs/report_03.md)**以了解更多信息。

### Open-Sora 1.1 模型权重

<details>
<summary>查看更多</summary>

| 分辨率         | M | Data                       | #iterations | Batch Size                                        | URL                                                                  |
| ------------------ | ---------- | -------------------------- | ----------- | ------------------------------------------------- | -------------------------------------------------------------------- |
| mainly 144p & 240p | 700M       | 10M videos + 2M images     | 100k        | [dynamic](/configs/opensora-v1-1/train/stage2.py) | [:link:](https://huggingface.co/hpcai-tech/OpenSora-STDiT-v2-stage2) |
| 144p to 720p       | 700M       | 500K HQ videos + 1M images | 4k          | [dynamic](/configs/opensora-v1-1/train/stage3.py) | [:link:](https://huggingface.co/hpcai-tech/OpenSora-STDiT-v2-stage3) |

请参阅我们的 **[报告 1.1](docs/report_02.md)** 以了解更多信息。

:warning: **局限性**: 此版本包含已知问题，我们将在下一版本中修复这些问题（因为我们为下一版本节省了计算资源）。此外，由于此问题，视频生成可能会长时间失败，高分辨率将产生嘈杂的结果。

</details>

### Open-Sora 1.0 模型权重
<details>
<summary>查看更多</summary>

| 分辨率 | 模型大小 | 数据   | 迭代次数 | 批量大小 | GPU 天数 (H800) | 网址                                                                                           |
| ---------- | ---------- | ------ | ----------- | ---------- | --------------- |
| 16×512×512 | 700M       | 20K HQ | 20k         | 2×64       | 35              | [:link:](https://huggingface.co/hpcai-tech/Open-Sora/blob/main/OpenSora-v1-HQ-16x512x512.pth) |
| 16×256×256 | 700M       | 20K HQ | 24k         | 8×64       | 45              | [:link:](https://huggingface.co/hpcai-tech/Open-Sora/blob/main/OpenSora-v1-HQ-16x256x256.pth) |
| 16×256×256 | 700M       | 366K   | 80k         | 8×64       | 117             | [:link:](https://huggingface.co/hpcai-tech/Open-Sora/blob/main/OpenSora-v1-16x256x256.pth)    |

训练流程: 16x256x256 $\rightarrow$ 16x256x256 高清 $\rightarrow$ 16x512x512 高质量.

我们的模型权重部分由 [PixArt-α](https://github.com/PixArt-alpha/PixArt-alpha)初始化，参数数量为724M.更多信息请参阅  **[技术报告v1.0](docs/report_v1.md)**。数据集相关信息请参阅[数据集文件](docs/datasets.md). HQ 表示高质量.

:warning: **局限性**: 我们的模型是在有限的预算下训练的。质量和文本对齐相对较差。该模型表现不佳，特别是在生成人类时，无法遵循详细的说明。我们正在努力提高质量和文本对齐。

</details>

## Gradio演示

🔥 您可以在Hugging Face 上的[🤗 Gradio 应用程序](https://huggingface.co/spaces/hpcai-tech/open-sora)上在线体验Open-Sora。【由于GPU资源不足，已失效】

### 本地部署

如果您想在本地部署 gradio，我们还在这个存储库中提供了一个[Gradio 应用程序](./gradio) ，您可以使用以下命令启动一个交互式 Web 应用程序来体验使用 Open-Sora 生成视频。

```bash
pip install gradio spaces
python gradio/app.py
```

这将在您的本地主机上启动 Gradio 应用程序。如果您想了解有关 Gradio 应用程序的更多信息，可以参考[Gradio README](./gradio/README.md)。

要启用提示增强和其他语言输入（例如中文输入），您需要OPENAI_API_KEY在环境中进行设置。查看[OpenAI的文档](https://platform.openai.com/docs/quickstart)以获取您的 API 密钥。

```bash
export OPENAI_API_KEY=YOUR_API_KEY
```

### 入门

在 Gradio 应用程序中，基本选项如下：

![Gradio Demo](/assets/readme/gradio_basic.png)

The easiest way to generate a video is to input a text prompt and click the "**Generate video**" button (scroll down if you cannot find). The generated video will be displayed in the right panel. Checking the "**Enhance prompt with GPT4o**" will use GPT-4o to refine the prompt, while "**Random Prompt**" button will generate a random prompt by GPT-4o for you. Due to the OpenAI's API limit, the prompt refinement result has some randomness.

Then, you can choose the **resolution**, **duration**, and **aspect ratio** of the generated video. Different resolution and video length will affect the video generation speed. On a 80G H100 GPU, the generation speed and peak memory usage is:

|   分辨率   | 图像   | 2秒       | 4秒        | 8秒        | 16秒       |
| ---- | ------- | -------- | --------- | --------- | --------- |
| 360p | 3s, 24G | 18s, 27G | 31s, 27G  | 62s, 28G  | 121s, 33G |
| 480p | 2s, 24G | 29s, 31G | 55s, 30G  | 108s, 32G | 219s, 36G |
| 720p | 6s, 27G | 68s, 41G | 130s, 39G | 260s, 45G | 547s, 67G |

Note that besides text to video, you can also use image to video generation. You can upload an image and then click the "**Generate video**" button to generate a video with the image as the first frame. Or you can fill in the text prompt and click the "**Generate image**" button to generate an image with the text prompt, and then click the "**Generate video**" button to generate a video with the image generated with the same model.

![Gradio Demo](assets/readme/gradio_option.png)

Then you can specify more options, including "**Motion Strength**", "**Aesthetic**" and "**Camera Motion**". If "Enable" not checked or the choice is "none", the information is not passed to the model. Otherwise, the model will generate videos with the specified motion strength, aesthetic score, and camera motion.

For the **aesthetic score**, we recommend using values higher than 6. For **motion strength**, a smaller value will lead to a smoother but less dynamic video, while a larger value will lead to a more dynamic but likely more blurry video. Thus, you can try without it and then adjust it according to the generated video. For the **camera motion**, sometimes the model cannot follow the instruction well, and we are working on improving it.

You can also adjust the "**Sampling steps**", this is directly related to the generation speed as it is the number of denoising. A number smaller than 30 usually leads to a poor generation results, while a number larger than 100 usually has no significant improvement. The "**Seed**" is used for reproducibility, you can set it to a fixed number to generate the same video. The "**CFG Scale**" controls how much the model follows the text prompt, a smaller value will lead to a more random video, while a larger value will lead to a more text-following video (7 is recommended).

For more advanced usage, you can refer to [Gradio README](./gradio/README.md#advanced-usage).

## Inference

### Open-Sora 1.2 Command Line Inference

### GPT-4o Prompt Refinement

We find that GPT-4o can refine the prompt and improve the quality of the generated video. With this feature, you can also use other language (e.g., Chinese) as the prompt. To enable this feature, you need prepare your openai api key in the environment:

```bash
export OPENAI_API_KEY=YOUR_API_KEY
```

Then you can inference with `--llm-refine True` to enable the GPT-4o prompt refinement.

### Open-Sora 1.1 Command Line Inference

<details>
<summary>View more</summary>

Since Open-Sora 1.1 supports inference with dynamic input size, you can pass the input size as an argument.

```bash
# text to video
python scripts/inference.py configs/opensora-v1-1/inference/sample.py --prompt "A beautiful sunset over the city" --num-frames 32 --image-size 480 854
```

If your installation do not contain `apex` and `flash-attn`, you need to disable them in the config file, or via the folowing command.

```bash
python scripts/inference.py configs/opensora-v1-1/inference/sample.py --prompt "A beautiful sunset over the city" --num-frames 32 --image-size 480 854 --layernorm-kernel False --flash-attn False
```

See [here](docs/commands.md#inference-with-open-sora-11) for more instructions including text-to-image, image-to-video, video-to-video, and infinite time generation.

</details>

### Open-Sora 1.0 Command Line Inference

<details>
<summary>View more</summary>

We have also provided an offline inference script. Run the following commands to generate samples, the required model weights will be automatically downloaded. To change sampling prompts, modify the txt file passed to `--prompt-path`. See [here](docs/structure.md#inference-config-demos) to customize the configuration.

```bash
# Sample 16x512x512 (20s/sample, 100 time steps, 24 GB memory)
torchrun --standalone --nproc_per_node 1 scripts/inference.py configs/opensora/inference/16x512x512.py --ckpt-path OpenSora-v1-HQ-16x512x512.pth --prompt-path ./assets/texts/t2v_samples.txt

# Sample 16x256x256 (5s/sample, 100 time steps, 22 GB memory)
torchrun --standalone --nproc_per_node 1 scripts/inference.py configs/opensora/inference/16x256x256.py --ckpt-path OpenSora-v1-HQ-16x256x256.pth --prompt-path ./assets/texts/t2v_samples.txt

# Sample 64x512x512 (40s/sample, 100 time steps)
torchrun --standalone --nproc_per_node 1 scripts/inference.py configs/opensora/inference/64x512x512.py --ckpt-path ./path/to/your/ckpt.pth --prompt-path ./assets/texts/t2v_samples.txt

# Sample 64x512x512 with sequence parallelism (30s/sample, 100 time steps)
# sequence parallelism is enabled automatically when nproc_per_node is larger than 1
torchrun --standalone --nproc_per_node 2 scripts/inference.py configs/opensora/inference/64x512x512.py --ckpt-path ./path/to/your/ckpt.pth --prompt-path ./assets/texts/t2v_samples.txt
```

The speed is tested on H800 GPUs. For inference with other models, see [here](docs/commands.md) for more instructions.
To lower the memory usage, set a smaller `vae.micro_batch_size` in the config (slightly lower sampling speed).

</details>

## Data Processing

High-quality data is crucial for training good generation models.
To this end, we establish a complete pipeline for data processing, which could seamlessly convert raw videos to high-quality video-text pairs.
The pipeline is shown below. For detailed information, please refer to [data processing](docs/data_processing.md).
Also check out the [datasets](docs/datasets.md) we use.

![Data Processing Pipeline](assets/readme/report_data_pipeline.png)

## Training

### Open-Sora 1.2 Training

### Open-Sora 1.1 Training

<details>
<summary>View more</summary>

Once you prepare the data in a `csv` file, run the following commands to launch training on a single node.

```bash
# one node
torchrun --standalone --nproc_per_node 8 scripts/train.py \
    configs/opensora-v1-1/train/stage1.py --data-path YOUR_CSV_PATH --ckpt-path YOUR_PRETRAINED_CKPT
# multiple nodes
colossalai run --nproc_per_node 8 --hostfile hostfile scripts/train.py \
    configs/opensora-v1-1/train/stage1.py --data-path YOUR_CSV_PATH --ckpt-path YOUR_PRETRAINED_CKPT
```

</details>

### Open-Sora 1.0 Training

<details>
<summary>View more</summary>

Once you prepare the data in a `csv` file, run the following commands to launch training on a single node.

```bash
# 1 GPU, 16x256x256
torchrun --nnodes=1 --nproc_per_node=1 scripts/train.py configs/opensora/train/16x256x256.py --data-path YOUR_CSV_PATH
# 8 GPUs, 64x512x512
torchrun --nnodes=1 --nproc_per_node=8 scripts/train.py configs/opensora/train/64x512x512.py --data-path YOUR_CSV_PATH --ckpt-path YOUR_PRETRAINED_CKPT
```

To launch training on multiple nodes, prepare a hostfile according
to [ColossalAI](https://colossalai.org/docs/basics/launch_colossalai/#launch-with-colossal-ai-cli), and run the
following commands.

```bash
colossalai run --nproc_per_node 8 --hostfile hostfile scripts/train.py configs/opensora/train/64x512x512.py --data-path YOUR_CSV_PATH --ckpt-path YOUR_PRETRAINED_CKPT
```

For training other models and advanced usage, see [here](docs/commands.md) for more instructions.

</details>

## Evaluation

### VBench

### VBench-i2v

See [here](eval/README.md) for more instructions.

## Contribution

Thanks goes to these wonderful contributors:

<a href="https://github.com/hpcaitech/Open-Sora/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=hpcaitech/Open-Sora" />
</a>

If you wish to contribute to this project, please refer to the [Contribution Guideline](./CONTRIBUTING.md).

## Acknowledgement

Here we only list a few of the projects. For other works and datasets, please refer to our report.

* [ColossalAI](https://github.com/hpcaitech/ColossalAI): A powerful large model parallel acceleration and optimization
  system.
* [DiT](https://github.com/facebookresearch/DiT): Scalable Diffusion Models with Transformers.
* [OpenDiT](https://github.com/NUS-HPC-AI-Lab/OpenDiT): An acceleration for DiT training. We adopt valuable acceleration
  strategies for training progress from OpenDiT.
* [PixArt](https://github.com/PixArt-alpha/PixArt-alpha): An open-source DiT-based text-to-image model.
* [Latte](https://github.com/Vchitect/Latte): An attempt to efficiently train DiT for video.
* [StabilityAI VAE](https://huggingface.co/stabilityai/sd-vae-ft-mse-original): A powerful image VAE model.
* [CLIP](https://github.com/openai/CLIP): A powerful text-image embedding model.
* [T5](https://github.com/google-research/text-to-text-transfer-transformer): A powerful text encoder.
* [LLaVA](https://github.com/haotian-liu/LLaVA): A powerful image captioning model based on [Mistral-7B](https://huggingface.co/mistralai/Mistral-7B-v0.1) and [Yi-34B](https://huggingface.co/01-ai/Yi-34B).
* [PLLaVA](https://github.com/magic-research/PLLaVA): A powerful video captioning model.
* [MiraData](https://github.com/mira-space/MiraData): A large-scale video dataset with long durations and structured caption.

We are grateful for their exceptional work and generous contribution to open source.

## Citation

```bibtex
@software{opensora,
  author = {Zangwei Zheng and Xiangyu Peng and Tianji Yang and Chenhui Shen and Shenggui Li and Hongxin Liu and Yukun Zhou and Tianyi Li and Yang You},
  title = {Open-Sora: Democratizing Efficient Video Production for All},
  month = {March},
  year = {2024},
  url = {https://github.com/hpcaitech/Open-Sora}
}
```

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hpcaitech/Open-Sora&type=Date)](https://star-history.com/#hpcaitech/Open-Sora&Date)
