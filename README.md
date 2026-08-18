<div align="center">

<img src="https://raw.githubusercontent.com/nashory/gans-awesome-applications/master/jpg/gans.jpg" alt="gans-awesome-applications banner" width="100%">

# gans-awesome-applications with stars

**A curated list of awesome GAN *applications* and demonstrations.**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
![Last Commit](https://img.shields.io/github/last-commit/nashory/gans-awesome-applications)
![Stars](https://img.shields.io/github/stars/nashory/gans-awesome-applications?style=social)

</div>

> **Only awesome is awesome. This is a curation, not a collection.**
>
> This list is about what GANs are *used for*. General GAN papers whose contribution is the model
> itself (DCGAN, BEGAN, WGAN, …) are **not** included as entries — only genuine landmarks make the
> short list at the top. Pure theory / loss-function papers are out of scope; diffusion-only work is
> out of scope (GAN+diffusion hybrids are fine).

🏷 **Legend:** 📄 paper · 💻 code · 🌐 project/demo · 🎬 video · 📝 blog

🤝 Contributions welcome — see **[CONTRIBUTING.md](CONTRIBUTING.md)**.

***

## 🏛 The landmark papers that I respect

| Paper                                                                      |  Venue  | Year | Links                                                                                                                                        |
| :------------------------------------------------------------------------- | :-----: | :--: | :------------------------------------------------------------------------------------------------------------------------------------------- |
| Generative Adversarial Networks                                            | NeurIPS | 2014 | [📄](https://arxiv.org/abs/1406.2661) [💻](https://github.com/goodfeli/adversarial) ⭐ 4,076 \| 🐛 7 \| 🌐 Python \| 📅 2020-05-25            |
| Unsupervised Representation Learning with Deep Convolutional GANs (DCGAN)  |   ICLR  | 2016 | [📄](https://arxiv.org/pdf/1511.06434) [💻](https://github.com/soumith/dcgan.torch) ⭐ 1,488 \| 🐛 41 \| 🌐 Lua \| 📅 2021-08-02              |
| Improved Techniques for Training GANs                                      | NeurIPS | 2016 | [📄](https://arxiv.org/pdf/1606.03498.pdf) [💻](https://github.com/openai/improved-gan) ⚠️ Archived                                          |
| BEGAN: Boundary Equilibrium Generative Adversarial Networks                |    —    | 2017 | [📄](https://arxiv.org/pdf/1703.10717) [💻](https://github.com/carpedm20/BEGAN-tensorflow) ⭐ 924 \| 🐛 34 \| 🌐 Python \| 📅 2018-03-26      |
| Training Generative Adversarial Networks with Limited Data (StyleGAN2-ADA) | NeurIPS | 2020 | [📄](https://arxiv.org/abs/2006.06676) [💻](https://github.com/NVlabs/stylegan2-ada-pytorch) ⭐ 4,486 \| 🐛 201 \| 🌐 Python \| 📅 2024-05-10 |
| The GAN is dead; long live the GAN! A Modern GAN Baseline (R3GAN)          | NeurIPS | 2024 | [📄](https://arxiv.org/abs/2501.05441) [💻](https://github.com/brownvc/R3GAN) ⭐ 870 \| 🐛 11 \| 🌐 Python \| 📅 2025-01-23                   |

***

## Contents

<details>
<summary><b>Click to expand the table of contents</b> — or just press <kbd>command</kbd>/<kbd>ctrl</kbd> + <kbd>F</kbd> to search for a keyword.</summary>

* [Applications using GANs](#applications-using-gans)
  * [🔤 Font generation](#-font-generation)
  * [🎴 Anime character generation](#-anime-character-generation)
  * [🎭 Face Stylization](#-face-stylization)
  * [🎮 Interactive Image generation](#-interactive-image-generation)
  * [🔧 GAN Inversion and Latent Space Editing](#-gan-inversion-and-latent-space-editing)
  * [✍ Text2Image (text to image)](#-text2image-text-to-image)
  * [⚡ Adversarial Diffusion Distillation (GAN-hybrid)](#-adversarial-diffusion-distillation-gan-hybrid)
  * [🧊 3D Object generation](#-3d-object-generation)
  * [🌐 3D-aware Image Synthesis](#-3d-aware-image-synthesis)
  * [✏ Image Editing](#-image-editing)
  * [👴 Face Aging](#-face-aging)
  * [🕺 Human Pose Estimation](#-human-pose-estimation)
  * [🗣 Talking Head and Face Reenactment](#-talking-head-and-face-reenactment)
  * [👗 Virtual Try-On](#-virtual-try-on)
  * [🔄 Domain-transfer (e.g. style-transfer, pix2pix, sketch2image)](#-domain-transfer-eg-style-transfer-pix2pix-sketch2image)
  * [🩹 Image Inpainting (hole filling)](#-image-inpainting-hole-filling)
  * [🪄 Image Blending](#-image-blending)
  * [🔍 Super-resolution](#-super-resolution)
  * [🖼 High-resolution image generation (large-scale image)](#-high-resolution-image-generation-large-scale-image)
  * [🛡 Adversarial Examples (Defense vs Attack)](#-adversarial-examples-defense-vs-attack)
  * [👁 Visual Saliency Prediction (attention prediction)](#-visual-saliency-prediction-attention-prediction)
  * [🎯 Object Detection/Recognition](#-object-detectionrecognition)
  * [🎬 Video (generation/prediction)](#-video-generationprediction)
  * [🔊 Audio and Speech Synthesis](#-audio-and-speech-synthesis)
  * [🔡 Text and Sequence Generation](#-text-and-sequence-generation)
  * [🚨 Anomaly Detection](#-anomaly-detection)
  * [🧪 Synthetic Data Generation](#-synthetic-data-generation)
  * [🧩 Others](#-others)
* [Did not use GAN, but still interesting applications](#did-not-use-gan-but-still-interesting-applications)
  * [🧑 Real-time face reconstruction](#-real-time-face-reconstruction)
  * [🔍 Super-resolution](#-super-resolution-1)
  * [🖼 Photorealistic Image generation (e.g. pix2pix, sketch2image)](#-photorealistic-image-generation-eg-pix2pix-sketch2image)
  * [🕺 Human Pose Estimation](#-human-pose-estimation-1)
  * [🧊 3D Object generation](#-3d-object-generation-1)
* [📚 GAN tutorials with easy and simple example code for starters](#-gan-tutorials-with-easy-and-simple-example-code-for-starters)
* [🛠 Awesome GAN GitHub Projects and Tools](#-awesome-gan-github-projects-and-tools)
* [🧰 Implementations of various types of GANs collection](#-implementations-of-various-types-of-gans-collection)
* [📰 Trendy AI-application Articles](#-trendy-ai-application-articles)

</details>

***

## Applications using GANs

### 🔤 Font generation

| Title                                                                     |     Venue     | Year | Links                                                                                                                                                 |
| :------------------------------------------------------------------------ | :-----------: | :--: | :---------------------------------------------------------------------------------------------------------------------------------------------------- |
| Learning Chinese Character Style with Conditional GAN (zi2zi)             |       —       | 2017 | [💻](https://github.com/kaonashi-tyc/zi2zi) ⭐ 2,745 \| 🐛 58 \| 🌐 Python \| 📅 2019-08-09 [📝](https://kaonashi-tyc.github.io/2017/04/06/zi2zi.html) |
| Artistic Glyph Image Synthesis via One-Stage Few-Shot Learning (AGIS-Net) | SIGGRAPH Asia | 2019 | [📄](http://arxiv.org/abs/1910.04987) [💻](https://github.com/hologerry/AGIS-Net) ⭐ 130 \| 🐛 0 \| 🌐 Python \| 📅 2024-02-01                         |
| Attribute2Font: Creating Fonts You Want From Attributes                   |    SIGGRAPH   | 2020 | [📄](https://arxiv.org/abs/2005.07865) [💻](https://github.com/hologerry/Attr2Font) ⭐ 232 \| 🐛 6 \| 🌐 Python \| 📅 2022-04-26                       |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🎴 Anime character generation

| Title                                                     | Venue | Year | Links                                                                                               |
| :-------------------------------------------------------- | :---: | :--: | :-------------------------------------------------------------------------------------------------- |
| Towards the Automatic Anime Characters Creation with GANs |   —   | 2017 | [📄](https://arxiv.org/pdf/1708.05509)                                                              |
| AnimeGANv2: Photo to Anime Style Transfer                 |   —   | 2021 | [💻](https://github.com/TachibanaYoshino/AnimeGANv2) ⭐ 5,370 \| 🐛 51 \| 🌐 Python \| 📅 2024-08-27 |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🎭 Face Stylization

| Title                              | Venue | Year | Links                                                                                                                                    |
| :--------------------------------- | :---: | :--: | :--------------------------------------------------------------------------------------------------------------------------------------- |
| JoJoGAN: One Shot Face Stylization |  ECCV | 2022 | [📄](https://arxiv.org/abs/2112.11641) [💻](https://github.com/mchong6/JoJoGAN) ⭐ 1,438 \| 🐛 18 \| 🌐 Jupyter Notebook \| 📅 2022-09-29 |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🎮 Interactive Image generation

| Title                                                                                          |   Venue  | Year | Links                                                                                                                                     |
| :--------------------------------------------------------------------------------------------- | :------: | :--: | :---------------------------------------------------------------------------------------------------------------------------------------- |
| Generative Visual Manipulation on the Natural Image Manifold (iGAN)                            |   ECCV   | 2016 | [📄](https://arxiv.org/pdf/1609.03552) [💻](https://github.com/junyanz/iGAN) ⭐ 4,003 \| 🐛 14 \| 🌐 Python \| 📅 2020-08-05               |
| Neural Photo Editing with Introspective Adversarial Networks                                   |   ICLR   | 2017 | [📄](http://arxiv.org/abs/1609.07093) [💻](https://github.com/ajbrock/Neural-Photo-Editor) ⭐ 2,074 \| 🐛 10 \| 🌐 Python \| 📅 2017-03-22 |
| Drag Your GAN: Interactive Point-based Manipulation on the Generative Image Manifold (DragGAN) | SIGGRAPH | 2023 | [📄](https://arxiv.org/abs/2305.10973) [💻](https://github.com/XingangPan/DragGAN) ⭐ 35,767 \| 🐛 154 \| 🌐 Python \| 📅 2024-05-18       |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🔧 GAN Inversion and Latent Space Editing

| Title                                                                      | Venue | Year | Links                                                                                                                                               |
| :------------------------------------------------------------------------- | :---: | :--: | :-------------------------------------------------------------------------------------------------------------------------------------------------- |
| StyleCLIP: Text-Driven Manipulation of StyleGAN Imagery                    |  ICCV | 2021 | [📄](https://arxiv.org/abs/2103.17249) [💻](https://github.com/orpatashnik/StyleCLIP) ⭐ 4,122 \| 🐛 64 \| 🌐 HTML \| 📅 2023-05-30                  |
| Encoding in Style: a StyleGAN Encoder for Image-to-Image Translation (pSp) |  CVPR | 2021 | [📄](https://arxiv.org/abs/2008.00951) [💻](https://github.com/eladrich/pixel2style2pixel) ⭐ 3,323 \| 🐛 11 \| 🌐 Jupyter Notebook \| 📅 2022-10-01 |

<sub><a href="#contents">↑ back to Contents</a></sub>

### ✍ Text2Image (text to image)

| Title                                                                                |  Venue  | Year | Links                                                                                                                                                                                                                                |
| :----------------------------------------------------------------------------------- | :-----: | :--: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TAC-GAN: Text Conditioned Auxiliary Classifier GAN                                   |    —    | 2017 | [📄](https://arxiv.org/pdf/1703.06412.pdf) [💻](https://github.com/dashayushman/TAC-GAN) ⭐ 105 \| 🐛 11 \| 🌐 Python \| 📅 2019-04-26                                                                                                |
| StackGAN: Text to Photo-realistic Image Synthesis with Stacked GANs                  |   ICCV  | 2017 | [📄](https://arxiv.org/pdf/1612.03242.pdf) [💻](https://github.com/hanzhanggit/StackGAN) ⭐ 1,860 \| 🐛 55 \| 🌐 Python \| 📅 2020-05-15                                                                                              |
| Generative Adversarial Text to Image Synthesis                                       |   ICML  | 2016 | [📄](https://arxiv.org/pdf/1605.05396.pdf) [💻](https://github.com/paarthneekhara/text-to-image) ⭐ 2,163 \| 🐛 47 \| 🌐 Python \| 📅 2018-01-30 [💻](https://github.com/reedscot/icml2016) ⭐ 911 \| 🐛 31 \| 🌐 Lua \| 📅 2018-09-05 |
| Learning What and Where to Draw                                                      | NeurIPS | 2016 | [📄](http://www.scottreed.info/files/nips2016.pdf) [💻](https://github.com/reedscot/nips2016) ⭐ 335 \| 🐛 4 \| 🌐 Lua \| 📅 2016-11-01                                                                                               |
| AttnGAN: Fine-Grained Text to Image Generation with Attentional GANs                 |   CVPR  | 2018 | [📄](https://arxiv.org/abs/1711.10485) [💻](https://github.com/taoxugit/AttnGAN) ⭐ 1,363 \| 🐛 86 \| 🌐 Python \| 📅 2024-07-25                                                                                                      |
| GigaGAN: Scaling up GANs for Text-to-Image Synthesis                                 |   CVPR  | 2023 | [📄](https://arxiv.org/abs/2303.05511)                                                                                                                                                                                               |
| StyleGAN-T: Unlocking the Power of GANs for Fast Large-Scale Text-to-Image Synthesis |   ICML  | 2023 | [📄](https://arxiv.org/abs/2301.09515) [💻](https://github.com/autonomousvision/stylegan-t) ⭐ 1,197 \| 🐛 14 \| 🌐 Python \| 📅 2023-04-07                                                                                           |

<sub><a href="#contents">↑ back to Contents</a></sub>

### ⚡ Adversarial Diffusion Distillation (GAN-hybrid)

*GANs strike back in 2024–2026: adversarial objectives distill slow diffusion samplers into one/few-step image **and video** generators — where GANs are most alive in 2025–2026.*

| Title                                                                                              |  Venue  | Year | Links                                                                                                                        |
| :------------------------------------------------------------------------------------------------- | :-----: | :--: | :--------------------------------------------------------------------------------------------------------------------------- |
| UFOGen: You Forward Once Large Scale Text-to-Image Generation via Diffusion GANs                   |   CVPR  | 2024 | [📄](https://arxiv.org/abs/2311.09257)                                                                                       |
| Improved Distribution Matching Distillation for Fast Image Synthesis (DMD2)                        | NeurIPS | 2024 | [📄](https://arxiv.org/abs/2405.14867) [💻](https://github.com/tianweiy/DMD2) ⭐ 1,427 \| 🐛 42 \| 🌐 Python \| 📅 2025-03-05 |
| SANA-Sprint: One-Step Diffusion with Continuous-Time Consistency Distillation                      |  arXiv  | 2025 | [📄](https://arxiv.org/abs/2503.09641) [💻](https://github.com/NVlabs/Sana) ⭐ 8,780 \| 🐛 137 \| 🌐 Python \| 📅 2026-08-18  |
| Diffusion Adversarial Post-Training for One-Step Video Generation (Seaweed-APT)                    |   ICML  | 2025 | [📄](https://arxiv.org/abs/2501.08316) [🌐](https://seaweed-apt.com/)                                                        |
| Autoregressive Adversarial Post-Training for Real-Time Interactive Video Generation (Seaweed-APT2) | NeurIPS | 2025 | [📄](https://arxiv.org/abs/2506.09350) [🌐](https://seaweed-apt.com/2)                                                       |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🧊 3D Object generation

| Title                                                                                                  |  Venue  | Year | Links                                                                                                                                                                                                                                                                                |
| :----------------------------------------------------------------------------------------------------- | :-----: | :--: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Parametric 3D Exploration with Stacked Adversarial Networks (pix2vox)                                  |    —    | 2016 | [💻](https://github.com/maxorange/pix2vox) ⭐ 246 \| 🐛 10 \| 🌐 Python \| 📅 2018-03-19 [🎬](https://www.youtube.com/watch?v=ITATOXVvWEM)                                                                                                                                            |
| Learning a Probabilistic Latent Space of Object Shapes via 3D Generative-Adversarial Modeling (3D-GAN) | NeurIPS | 2016 | [📄](http://papers.nips.cc/paper/6096-learning-a-probabilistic-latent-space-of-object-shapes-via-3d-generative-adversarial-modeling.pdf) [💻](https://github.com/zck119/3dgan-release) ⭐ 825 \| 🐛 3 \| 🌐 Python \| 📅 2017-10-21 [🎬](https://www.youtube.com/watch?v=HO1LYJb818Q) |
| 3D Shape Induction from 2D Views of Multiple Objects                                                   |    —    | 2016 | [📄](https://arxiv.org/pdf/1612.05872.pdf)                                                                                                                                                                                                                                           |
| Fully Convolutional Refined Auto-Encoding GANs for 3D Multi Object Scenes                              |    —    | 2017 | [💻](https://github.com/yunishi3/3D-FCR-alphaGAN) ⭐ 104 \| 🐛 2 \| 🌐 Python \| 📅 2019-01-17 [📝](https://becominghuman.ai/3d-multi-object-gan-7b7cee4abf80)                                                                                                                        |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🌐 3D-aware Image Synthesis

| Title                                                              | Venue | Year | Links                                                                                                                      |
| :----------------------------------------------------------------- | :---: | :--: | :------------------------------------------------------------------------------------------------------------------------- |
| Efficient Geometry-aware 3D Generative Adversarial Networks (EG3D) |  CVPR | 2022 | [📄](https://arxiv.org/abs/2112.07945) [💻](https://github.com/NVlabs/eg3d) ⭐ 3,337 \| 🐛 66 \| 🌐 Python \| 📅 2023-06-10 |

<sub><a href="#contents">↑ back to Contents</a></sub>

### ✏ Image Editing

| Title                                                                     | Venue | Year | Links                                                                                                                                |
| :------------------------------------------------------------------------ | :---: | :--: | :----------------------------------------------------------------------------------------------------------------------------------- |
| Invertible Conditional GANs for Image Editing (IcGAN)                     |   —   | 2016 | [📄](https://arxiv.org/abs/1611.06355) [💻](https://github.com/Guim3/IcGAN) ⭐ 284 \| 🐛 2 \| 🌐 Lua \| 📅 2021-09-28                 |
| Image De-raining Using a Conditional GAN (ID-CGAN)                        |   —   | 2017 | [📄](https://arxiv.org/abs/1701.05957) [💻](https://github.com/hezhangsprinter/ID-CGAN) ⭐ 266 \| 🐛 10 \| 🌐 Lua \| 📅 2022-11-20    |
| DeblurGAN: Blind Motion Deblurring Using Conditional Adversarial Networks |  CVPR | 2018 | [📄](https://arxiv.org/abs/1711.07064) [💻](https://github.com/KupynOrest/DeblurGAN) ⭐ 2,639 \| 🐛 148 \| 🌐 Python \| 📅 2019-12-25 |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 👴 Face Aging

| Title                                                                    | Venue | Year | Links                                                                                                                              |
| :----------------------------------------------------------------------- | :---: | :--: | :--------------------------------------------------------------------------------------------------------------------------------- |
| Age Progression/Regression by Conditional Adversarial Autoencoder (CAAE) |  CVPR | 2017 | [📄](https://arxiv.org/pdf/1702.08423) [💻](https://github.com/ZZUTK/Face-Aging-CAAE) ⭐ 657 \| 🐛 36 \| 🌐 Python \| 📅 2021-05-08 |
| CAN: Creative Adversarial Networks Generating "Art"                      |   —   | 2017 | [📄](https://arxiv.org/pdf/1706.07068.pdf)                                                                                         |
| Face Aging with Conditional Generative Adversarial Networks              |   —   | 2017 | [📄](https://arxiv.org/pdf/1702.01983.pdf)                                                                                         |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🕺 Human Pose Estimation

| Title                                                                              |  Venue  | Year | Links                                                                                                                                                                          |
| :--------------------------------------------------------------------------------- | :-----: | :--: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Joint Discriminative and Generative Learning for Person Re-identification (DG-Net) |   CVPR  | 2019 | [📄](https://arxiv.org/abs/1904.07223) [💻](https://github.com/NVlabs/DG-Net) ⭐ 1,298 \| 🐛 48 \| 🌐 Python \| 📅 2023-07-09 [🎬](https://www.youtube.com/watch?v=ubCrEAIpQs4) |
| Pose Guided Person Image Generation                                                | NeurIPS | 2017 | [📄](https://arxiv.org/abs/1705.09368)                                                                                                                                         |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🗣 Talking Head and Face Reenactment

| Title                                                                                |  Venue  | Year | Links                                                                                                                                                           |
| :----------------------------------------------------------------------------------- | :-----: | :--: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| First Order Motion Model for Image Animation                                         | NeurIPS | 2019 | [📄](https://arxiv.org/abs/2003.00196) [💻](https://github.com/AliaksandrSiarohin/first-order-model) ⭐ 15,015 \| 🐛 318 \| 🌐 Jupyter Notebook \| 📅 2024-11-14 |
| A Lip Sync Expert Is All You Need for Speech to Lip Generation In the Wild (Wav2Lip) |  ACM MM | 2020 | [📄](https://arxiv.org/abs/2008.10010) [💻](https://github.com/Rudrabha/Wav2Lip) ⭐ 13,170 \| 🐛 370 \| 🌐 Python \| 📅 2025-06-22                               |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 👗 Virtual Try-On

| Title                                                                         | Venue | Year | Links                                                                                                                             |
| :---------------------------------------------------------------------------- | :---: | :--: | :-------------------------------------------------------------------------------------------------------------------------------- |
| VITON-HD: High-Resolution Virtual Try-On via Misalignment-Aware Normalization |  CVPR | 2021 | [📄](https://arxiv.org/abs/2103.16874) [💻](https://github.com/shadow2496/VITON-HD) ⭐ 1,161 \| 🐛 0 \| 🌐 Python \| 📅 2025-04-27 |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🔄 Domain-transfer (e.g. style-transfer, pix2pix, sketch2image)

| Title                                                                                      | Venue | Year | Links                                                                                                                                                                               |
| :----------------------------------------------------------------------------------------- | :---: | :--: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Image-to-Image Translation with Conditional Adversarial Networks (pix2pix)                 |  CVPR | 2017 | [📄](https://arxiv.org/pdf/1611.07004) [💻](https://github.com/phillipi/pix2pix) ⭐ 10,653 \| 🐛 92 \| 🌐 Lua \| 📅 2021-06-06 [🎬](https://www.youtube.com/watch?v=VVqxbmUJorQ)     |
| Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks (CycleGAN) |  ICCV | 2017 | [📄](https://arxiv.org/pdf/1703.10593.pdf) [💻](https://github.com/junyanz/CycleGAN) ⭐ 12,869 \| 🐛 59 \| 🌐 Lua \| 📅 2023-09-12 [🎬](https://www.youtube.com/watch?v=JzgOfISLNjk) |
| Learning to Discover Cross-Domain Relations with GANs (DiscoGAN)                           |  ICML | 2017 | [📄](https://arxiv.org/pdf/1703.05192.pdf) [💻](https://github.com/carpedm20/DiscoGAN-pytorch) ⭐ 1,095 \| 🐛 13 \| 🌐 Jupyter Notebook \| 📅 2018-03-26                             |
| StarGAN: Unified Multi-Domain Image-to-Image Translation                                   |  CVPR | 2018 | [📄](https://arxiv.org/abs/1711.09020) [💻](https://github.com/yunjey/stargan) ⭐ 5,293 \| 🐛 67 \| 🌐 Python \| 📅 2021-01-23                                                       |
| StarGAN v2: Diverse Image Synthesis for Multiple Domains                                   |  CVPR | 2020 | [📄](https://arxiv.org/abs/1912.01865) [💻](https://github.com/clovaai/stargan-v2) ⭐ 3,615 \| 🐛 116 \| 🌐 Python \| 📅 2023-04-27                                                  |
| Multimodal Unsupervised Image-to-Image Translation (MUNIT)                                 |  ECCV | 2018 | [📄](https://arxiv.org/abs/1804.04732) [💻](https://github.com/NVlabs/MUNIT) ⭐ 2,707 \| 🐛 66 \| 🌐 Python \| 📅 2022-09-20                                                         |
| Unsupervised Creation of Parameterized Avatars                                             |   —   | 2017 | [📄](https://arxiv.org/pdf/1704.05693.pdf)                                                                                                                                          |
| Unsupervised Cross-Domain Image Generation (DTN)                                           |  ICLR | 2017 | [📄](https://openreview.net/pdf?id=Sk2Im59ex)                                                                                                                                       |
| Precomputed Real-Time Texture Synthesis with Markovian GANs (MGANs)                        |  ECCV | 2016 | [📄](http://arxiv.org/abs/1604.04382) [💻](https://github.com/chuanli11/MGANs) ⭐ 291 \| 🐛 7 \| 🌐 Lua \| 📅 2019-10-12                                                             |
| Pixel-Level Domain Transfer (PixelDTGAN)                                                   |  ECCV | 2016 | [📄](https://arxiv.org/pdf/1603.07442) [💻](https://github.com/fxia22/PixelDTGAN) ⭐ 262 \| 🐛 0 \| 🌐 Lua \| 📅 2017-11-01                                                          |
| TextureGAN: Controlling Deep Image Synthesis with Texture Patches                          |  CVPR | 2018 | [📄](https://arxiv.org/pdf/1706.02823.pdf) [🌐](https://github.com/varunagrawal/t-gan-demo)                                                                                         |
| Vincent AI Sketch Demo (NVIDIA, GTC Europe)                                                |   —   | 2017 | [📝](https://blogs.nvidia.com/blog/2017/10/11/vincent-ai-sketch-demo-draws-in-throngs-at-gtc-europe/) [🎬](https://www.youtube.com/watch?v=kIcqXTUMwps)                             |
| Deep Photo Style Transfer                                                                  |  CVPR | 2017 | [📄](https://arxiv.org/pdf/1703.07511.pdf) [💻](https://github.com/luanfujun/deep-photo-styletransfer) ⭐ 9,991 \| 🐛 34 \| 🌐 Matlab \| 📅 2021-08-02                               |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🩹 Image Inpainting (hole filling)

| Title                                                                    | Venue | Year | Links                                                                                                                                                                                                                    |
| :----------------------------------------------------------------------- | :---: | :--: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Context Encoders: Feature Learning by Inpainting                         |  CVPR | 2016 | [📄](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Pathak_Context_Encoders_Feature_CVPR_2016_paper.pdf) [💻](https://github.com/pathak22/context-encoder) ⭐ 907 \| 🐛 117 \| 🌐 Lua \| 📅 2020-07-19 |
| Semantic Image Inpainting with Perceptual and Contextual Losses          |  CVPR | 2017 | [📄](https://arxiv.org/abs/1607.07539) [💻](https://github.com/bamos/dcgan-completion.tensorflow) ⭐ 1,315 \| 🐛 27 \| 🌐 Python \| 📅 2017-07-18                                                                         |
| Semi-Supervised Learning with Context-Conditional GANs                   |   —   | 2016 | [📄](https://arxiv.org/pdf/1611.06430v1.pdf)                                                                                                                                                                             |
| Free-Form Image Inpainting with Gated Convolution (DeepFill v2)          |  ICCV | 2019 | [📄](https://arxiv.org/abs/1806.03589) [💻](https://github.com/JiahuiYu/generative_inpainting) ⭐ 3,466 \| 🐛 76 \| 🌐 Python \| 📅 2024-06-27                                                                            |
| Resolution-robust Large Mask Inpainting with Fourier Convolutions (LaMa) |  WACV | 2022 | [📄](https://arxiv.org/abs/2109.07161) [💻](https://github.com/advimman/lama) ⭐ 10,199 \| 🐛 124 \| 🌐 Jupyter Notebook \| 📅 2025-02-05                                                                                 |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🪄 Image Blending

| Title                                                    |  Venue | Year | Links                                                                                                                       |
| :------------------------------------------------------- | :----: | :--: | :-------------------------------------------------------------------------------------------------------------------------- |
| GP-GAN: Towards Realistic High-Resolution Image Blending | ACM MM | 2019 | [📄](https://arxiv.org/abs/1703.07195) [💻](https://github.com/wuhuikai/GP-GAN) ⭐ 472 \| 🐛 2 \| 🌐 Python \| 📅 2020-03-27 |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🔍 Super-resolution

| Title                                                                            | Venue | Year | Links                                                                                                                                              |
| :------------------------------------------------------------------------------- | :---: | :--: | :------------------------------------------------------------------------------------------------------------------------------------------------- |
| Image Super-Resolution Through Deep Learning (srez)                              |   —   | 2016 | [💻](https://github.com/david-gpu/srez) ⚠️ Archived                                                                                                |
| Photo-Realistic Single Image Super-Resolution Using a GAN (SRGAN)                |  CVPR | 2017 | [📄](https://arxiv.org/abs/1609.04802) [💻](https://github.com/tensorlayer/SRGAN) ⭐ 3,468 \| 🐛 153 \| 🌐 Python \| 📅 2024-02-22                  |
| High-Quality Face Image Super-Resolution Using Conditional GANs                  |   —   | 2017 | [📄](https://arxiv.org/pdf/1707.00737.pdf)                                                                                                         |
| Analyzing Perception-Distortion Tradeoff (EPSR)                                  | ECCVW | 2018 | [📄](https://arxiv.org/pdf/1811.00344.pdf) [💻](https://github.com/subeeshvasu/2018_subeesh_epsr_eccvw) ⭐ 79 \| 🐛 0 \| 🌐 Python \| 📅 2020-07-14 |
| ESRGAN: Enhanced Super-Resolution Generative Adversarial Networks                | ECCVW | 2018 | [📄](https://arxiv.org/abs/1809.00219) [💻](https://github.com/xinntao/ESRGAN) ⭐ 6,570 \| 🐛 100 \| 🌐 Python \| 📅 2022-10-19                     |
| Real-ESRGAN: Training Real-World Blind Super-Resolution with Pure Synthetic Data | ICCVW | 2021 | [📄](https://arxiv.org/abs/2107.10833) [💻](https://github.com/xinntao/Real-ESRGAN) ⭐ 36,497 \| 🐛 646 \| 🌐 Python \| 📅 2024-08-06               |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🖼 High-resolution image generation (large-scale image)

| Title                                                                              |  Venue  | Year | Links                                                                                                                                                                                                                         |
| :--------------------------------------------------------------------------------- | :-----: | :--: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Generating Large Images from Latent Vectors                                        |    —    | 2016 | [💻](https://github.com/hardmaru/cppn-gan-vae-tensorflow) ⭐ 347 \| 🐛 1 \| 🌐 Python \| 📅 2021-04-08 [📝](http://blog.otoro.net/2016/04/01/generating-large-images-from-latent-vectors/)                                     |
| Progressive Growing of GANs for Improved Quality, Stability, and Variation (PGGAN) |   ICLR  | 2018 | [📄](http://research.nvidia.com/sites/default/files/pubs/2017-10_Progressive-Growing-of//karras2017gan-paper.pdf) [💻](https://github.com/tkarras/progressive_growing_of_gans) ⭐ 6,178 \| 🐛 11 \| 🌐 Python \| 📅 2022-02-17 |
| Large Scale GAN Training for High Fidelity Natural Image Synthesis (BigGAN)        |   ICLR  | 2019 | [📄](https://arxiv.org/abs/1809.11096)                                                                                                                                                                                        |
| SinGAN: Learning a Generative Model from a Single Natural Image                    |   ICCV  | 2019 | [📄](https://arxiv.org/abs/1905.01164) [💻](https://github.com/tamarott/SinGAN) ⭐ 3,345 \| 🐛 107 \| 🌐 Python \| 📅 2023-05-26                                                                                               |
| Analyzing and Improving the Image Quality of StyleGAN (StyleGAN2)                  |   CVPR  | 2020 | [📄](https://arxiv.org/abs/1912.04958) [💻](https://github.com/NVlabs/stylegan2) ⭐ 11,184 \| 🐛 25 \| 🌐 Python \| 📅 2024-05-18                                                                                              |
| Alias-Free Generative Adversarial Networks (StyleGAN3)                             | NeurIPS | 2021 | [📄](https://arxiv.org/abs/2106.12423) [💻](https://github.com/NVlabs/stylegan3) ⭐ 6,942 \| 🐛 192 \| 🌐 Python \| 📅 2023-09-12                                                                                              |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🛡 Adversarial Examples (Defense vs Attack)

| Title                                                            | Venue | Year | Links                                      |
| :--------------------------------------------------------------- | :---: | :--: | :----------------------------------------- |
| SafetyNet: Detecting and Rejecting Adversarial Examples Robustly |  ICCV | 2017 | [📄](https://arxiv.org/abs/1704.00103)     |
| Adversarial Examples for Generative Models                       |   —   | 2017 | [📄](https://arxiv.org/pdf/1702.06832.pdf) |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 👁 Visual Saliency Prediction (attention prediction)

| Title                                                                   | Venue | Year | Links                                                                                                                                        |
| :---------------------------------------------------------------------- | :---: | :--: | :------------------------------------------------------------------------------------------------------------------------------------------- |
| SalGAN: Visual Saliency Prediction with Generative Adversarial Networks |   —   | 2017 | [📄](https://arxiv.org/pdf/1701.01081) [💻](https://github.com/imatge-upc/saliency-salgan-2017) ⭐ 380 \| 🐛 34 \| 🌐 Python \| 📅 2022-12-07 |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🎯 Object Detection/Recognition

| Title                                                                             | Venue | Year | Links                                      |
| :-------------------------------------------------------------------------------- | :---: | :--: | :----------------------------------------- |
| Perceptual Generative Adversarial Networks for Small Object Detection             |  CVPR | 2017 | [📄](https://arxiv.org/pdf/1706.05274)     |
| Adversarial Generation of Training Examples for Vehicle License Plate Recognition |   —   | 2017 | [📄](https://arxiv.org/pdf/1707.03124.pdf) |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🎬 Video (generation/prediction)

| Title                                                                                     |   Venue  | Year | Links                                                                                                                                                |
| :---------------------------------------------------------------------------------------- | :------: | :--: | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| Deep Multi-Scale Video Prediction Beyond Mean Square Error                                |   ICLR   | 2016 | [📄](https://arxiv.org/pdf/1511.05440.pdf) [💻](https://github.com/dyelax/Adversarial_Video_Generation) ⭐ 748 \| 🐛 25 \| 🌐 Python \| 📅 2021-10-23 |
| Learning Temporal Coherence via Self-Supervision for GAN-based Video Generation (TecoGAN) | SIGGRAPH | 2020 | [📄](https://arxiv.org/abs/1811.09393) [💻](https://github.com/thunil/TecoGAN) ⭐ 6,141 \| 🐛 87 \| 🌐 Python \| 📅 2023-08-17                        |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🔊 Audio and Speech Synthesis

| Title                                                                                     |  Venue  | Year | Links                                                                                                                               |
| :---------------------------------------------------------------------------------------- | :-----: | :--: | :---------------------------------------------------------------------------------------------------------------------------------- |
| Adversarial Audio Synthesis (WaveGAN)                                                     |   ICLR  | 2019 | [📄](https://arxiv.org/abs/1802.04208) [💻](https://github.com/chrisdonahue/wavegan) ⭐ 1,383 \| 🐛 52 \| 🌐 Python \| 📅 2022-11-27 |
| HiFi-GAN: GANs for Efficient and High Fidelity Speech Synthesis                           | NeurIPS | 2020 | [📄](https://arxiv.org/abs/2010.05646) [💻](https://github.com/jik876/hifi-gan) ⭐ 2,365 \| 🐛 111 \| 🌐 Python \| 📅 2024-07-27     |
| BigVGAN: A Universal Neural Vocoder with Large-Scale Training (v2 2024)                   |   ICLR  | 2023 | [📄](https://arxiv.org/abs/2206.04658) [💻](https://github.com/NVIDIA/BigVGAN) ⭐ 1,226 \| 🐛 20 \| 🌐 Python \| 📅 2024-09-05       |
| Vocos: Closing the Gap between Time-domain and Fourier-based Neural Vocoders              |   ICLR  | 2024 | [📄](https://arxiv.org/abs/2306.00814) [💻](https://github.com/gemelo-ai/vocos) ⭐ 1,149 \| 🐛 48 \| 🌐 Python \| 📅 2024-08-07      |
| BemaGANv2: Discriminator Combination Strategies for GAN-based Vocoders in Long-Term Audio |  arXiv  | 2025 | [📄](https://arxiv.org/abs/2506.09487) [💻](https://github.com/dinhoitt/BemaGANv2) ⭐ 22 \| 🐛 3 \| 🌐 Python \| 📅 2026-03-03       |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🔡 Text and Sequence Generation

| Title                                                             | Venue | Year | Links                                                                                                                          |
| :---------------------------------------------------------------- | :---: | :--: | :----------------------------------------------------------------------------------------------------------------------------- |
| SeqGAN: Sequence Generative Adversarial Nets with Policy Gradient |  AAAI | 2017 | [📄](https://arxiv.org/abs/1609.05473) [💻](https://github.com/LantaoYu/SeqGAN) ⭐ 2,093 \| 🐛 34 \| 🌐 Python \| 📅 2019-03-10 |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🚨 Anomaly Detection

| Title                                                                       | Venue | Year | Links                                  |
| :-------------------------------------------------------------------------- | :---: | :--: | :------------------------------------- |
| Unsupervised Anomaly Detection with GANs to Guide Marker Discovery (AnoGAN) |  IPMI | 2017 | [📄](https://arxiv.org/abs/1703.05921) |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🧪 Synthetic Data Generation

| Title                                                                                 | Venue | Year | Links                                                                                                                                                        |
| :------------------------------------------------------------------------------------ | :---: | :--: | :----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Learning from Simulated and Unsupervised Images through Adversarial Training (SimGAN) |  CVPR | 2017 | [📄](https://arxiv.org/pdf/1612.07828.pdf) [💻](https://github.com/carpedm20/simulated-unsupervised-tensorflow) ⭐ 575 \| 🐛 19 \| 🌐 Python \| 📅 2019-12-10 |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🧩 Others

| Title                                                                          | Venue | Year | Links                                                                                                                                              |
| :----------------------------------------------------------------------------- | :---: | :--: | :------------------------------------------------------------------------------------------------------------------------------------------------- |
| (Physics) Location-Aware Generative Adversarial Networks for Physics Synthesis |   —   | 2017 | [📄](https://arxiv.org/pdf/1701.05927.pdf) [💻](https://github.com/hep-lbdl/adversarial-jets) ⭐ 61 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2017-08-25 |
| (General) Spectral Normalization for Generative Adversarial Networks           |  ICLR | 2018 | [📄](https://openreview.net/pdf?id=B1QRgziT-) [💻](https://github.com/minhnhat93/tf-SNDCGAN) ⭐ 250 \| 🐛 3 \| 🌐 Python \| 📅 2017-09-25           |

<sub><a href="#contents">↑ back to Contents</a></sub>

***

## Did not use GAN, but still interesting applications.

### 🧑 Real-time face reconstruction

| Title                                                                                            | Venue | Year | Links                                                                                                                                                                                |
| :----------------------------------------------------------------------------------------------- | :---: | :--: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Model-based Deep Convolutional Face Autoencoder for Unsupervised Monocular Reconstruction (MoFA) |  ICCV | 2017 | [📄](https://arxiv.org/pdf/1703.10580.pdf) [💻](https://github.com/waxz/MoFA) ⭐ 34 \| 🐛 1 \| 🌐 Jupyter Notebook \| 📅 2017-06-05 [🎬](https://www.youtube.com/watch?v=uIMpHZYB8fI) |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🔍 Super-resolution

| Title                                                                       |   Venue  | Year | Links                                                                                                        |
| :-------------------------------------------------------------------------- | :------: | :--: | :----------------------------------------------------------------------------------------------------------- |
| Learning to Simplify: Fully Convolutional Networks for Rough Sketch Cleanup | SIGGRAPH | 2016 | [🌐](http://hi.cs.waseda.ac.jp/~esimo/en/research/sketch/) [🎬](https://www.youtube.com/watch?v=4MfG9CDufPA) |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🖼 Photorealistic Image generation (e.g. pix2pix, sketch2image)

| Title                                                                          |   Venue  | Year | Links                                                                                                                                                                                                                                                                                                                                    |
| :----------------------------------------------------------------------------- | :------: | :--: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| The Sketchy Database: Learning to Retrieve Badly Drawn Bunnies                 | SIGGRAPH | 2016 | [🎬](https://www.youtube.com/watch?v=a3sgFQjEfp4)                                                                                                                                                                                                                                                                                        |
| PatchMatch: A Randomized Correspondence Algorithm for Structural Image Editing | SIGGRAPH | 2009 | [📄](https://www.researchgate.net/profile/Eli_Shechtman/publication/220184392_PatchMatch_A_Randomized_Correspondence_Algorithm_for_Structural_Image_Editing/links/02e7e520897b12bf0f000000.pdf) [💻](https://github.com/younesse-cv/PatchMatch) ⭐ 132 \| 🐛 5 \| 🌐 C \| 📅 2025-05-07 [🎬](https://www.youtube.com/watch?v=n3aoc36V8LM) |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🕺 Human Pose Estimation

| Title                                                                   | Venue | Year | Links                                                                                                                             |
| :---------------------------------------------------------------------- | :---: | :--: | :-------------------------------------------------------------------------------------------------------------------------------- |
| Knowledge-Guided Deep Fractal Neural Networks for Human Pose Estimation |   —   | 2017 | [📄](https://arxiv.org/pdf/1705.02407.pdf) [💻](https://github.com/Guanghan/GNet-pose) ⭐ 88 \| 🐛 7 \| 🌐 Matlab \| 📅 2018-09-27 |

<sub><a href="#contents">↑ back to Contents</a></sub>

### 🧊 3D Object generation

| Title                                                                          | Venue | Year | Links                                                                                                                           |
| :----------------------------------------------------------------------------- | :---: | :--: | :------------------------------------------------------------------------------------------------------------------------------ |
| 3D-R2N2: A Unified Approach for Single and Multi-view 3D Object Reconstruction |  ECCV | 2016 | [📄](http://arxiv.org/abs/1604.00449) [💻](https://github.com/chrischoy/3D-R2N2) ⭐ 1,410 \| 🐛 44 \| 🌐 Python \| 📅 2021-07-16 |

<sub><a href="#contents">↑ back to Contents</a></sub>

***

## 📚 GAN tutorials with easy and simple example code for starters

* [1D Generative Adversarial Network Demo](http://notebooks.aylien.com/research/gan/gan_simple.html)
* [starter from "How to Train a GAN?" at NIPS2016](https://github.com/soumith/ganhacks) ⭐ 11,617 | 🐛 58 | 📅 2022-01-09
* [NIPS 2016 Tutorial: Generative Adversarial Networks](https://arxiv.org/abs/1701.00160)
* [OpenAI - Generative Models](https://blog.openai.com/generative-models/)

<sub><a href="#contents">↑ back to Contents</a></sub>

***

## 🛠 Awesome GAN GitHub Projects and Tools

Genuinely awesome, widely-used GitHub repos built on GANs — usable code and tools, not just papers. Star counts update automatically.

### Real-world applications and tools

| Repo                                                                                                       |                                                Stars                                               | What it does                                           |
| :--------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------: | :----------------------------------------------------- |
| [TencentARC/GFPGAN](https://github.com/TencentARC/GFPGAN) ⭐ 37,654 \| 🐛 402 \| 🌐 Python \| 📅 2024-07-26 | ![](https://img.shields.io/github/stars/TencentARC/GFPGAN?style=flat\&label=%E2%AD%90\&color=gold) | Practical real-world face restoration                  |
| [jantic/DeOldify](https://github.com/jantic/DeOldify) ⚠️ Archived                                          |  ![](https://img.shields.io/github/stars/jantic/DeOldify?style=flat\&label=%E2%AD%90\&color=gold)  | Colorize and restore old photos and video *(archived)* |

### Foundational model code (official / canonical)

| Repo                                                                                                                                             |                                                         Stars                                                         | What it does                                     |
| :----------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------- |
| [junyanz/pytorch-CycleGAN-and-pix2pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix) ⭐ 25,219 \| 🐛 589 \| 🌐 Python \| 📅 2025-08-06 | ![](https://img.shields.io/github/stars/junyanz/pytorch-CycleGAN-and-pix2pix?style=flat\&label=%E2%AD%90\&color=gold) | Official CycleGAN + pix2pix in PyTorch           |
| [NVlabs/stylegan](https://github.com/NVlabs/stylegan) ⭐ 14,416 \| 🐛 12 \| 🌐 Python \| 📅 2024-04-10                                            |            ![](https://img.shields.io/github/stars/NVlabs/stylegan?style=flat\&label=%E2%AD%90\&color=gold)           | Official StyleGAN                                |
| [NVlabs/SPADE](https://github.com/NVlabs/SPADE) ⭐ 7,714 \| 🐛 100 \| 🌐 Python \| 📅 2023-08-07                                                  |             ![](https://img.shields.io/github/stars/NVlabs/SPADE?style=flat\&label=%E2%AD%90\&color=gold)             | Semantic image synthesis, a.k.a. GauGAN          |
| [NVIDIA/pix2pixHD](https://github.com/NVIDIA/pix2pixHD) ⭐ 6,923 \| 🐛 247 \| 🌐 Python \| 📅 2024-11-04                                          |           ![](https://img.shields.io/github/stars/NVIDIA/pix2pixHD?style=flat\&label=%E2%AD%90\&color=gold)           | High-resolution image synthesis and manipulation |
| [ajbrock/BigGAN-PyTorch](https://github.com/ajbrock/BigGAN-PyTorch) ⭐ 2,922 \| 🐛 49 \| 🌐 Python \| 📅 2023-07-19                               |        ![](https://img.shields.io/github/stars/ajbrock/BigGAN-PyTorch?style=flat\&label=%E2%AD%90\&color=gold)        | The author's PyTorch BigGAN                      |

<sub><a href="#contents">↑ back to Contents</a></sub>

***

## 🧰 Implementations of various types of GANs collection

| Repo                                                                                                                                                                       |                                                                Stars                                                                | Framework                                     |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------- |
| [nashory/gans-collection.torch](https://github.com/nashory/gans-collection.torch) ⭐ 54 \| 🐛 2 \| 🌐 Lua \| 📅 2017-10-14                                                  |            ![](https://img.shields.io/github/stars/nashory/gans-collection.torch?style=flat\&label=%E2%AD%90\&color=gold)           | Torch7                                        |
| [hwalsuklee/tensorflow-generative-model-collections](https://github.com/hwalsuklee/tensorflow-generative-model-collections) ⭐ 3,919 \| 🐛 24 \| 🌐 Python \| 📅 2022-08-08 | ![](https://img.shields.io/github/stars/hwalsuklee/tensorflow-generative-model-collections?style=flat\&label=%E2%AD%90\&color=gold) | TensorFlow                                    |
| [wiseodd/generative-models](https://github.com/wiseodd/generative-models) ⭐ 7,494 \| 🐛 24 \| 🌐 Python \| 📅 2024-03-24                                                   |              ![](https://img.shields.io/github/stars/wiseodd/generative-models?style=flat\&label=%E2%AD%90\&color=gold)             | PyTorch & TensorFlow                          |
| [aboev/arae-tf](https://github.com/aboev/arae-tf) ⭐ 20 \| 🐛 0 \| 🌐 Python \| 📅 2018-02-04                                                                               |                    ![](https://img.shields.io/github/stars/aboev/arae-tf?style=flat\&label=%E2%AD%90\&color=gold)                   | TensorFlow                                    |
| [eriklindernoren/PyTorch-GAN](https://github.com/eriklindernoren/PyTorch-GAN) ⭐ 17,445 \| 🐛 142 \| 🌐 Python \| 📅 2024-06-18                                             |             ![](https://img.shields.io/github/stars/eriklindernoren/PyTorch-GAN?style=flat\&label=%E2%AD%90\&color=gold)            | PyTorch — dozens of GANs                      |
| [eriklindernoren/Keras-GAN](https://github.com/eriklindernoren/Keras-GAN) ⭐ 9,202 \| 🐛 147 \| 🌐 Python \| 📅 2022-12-12                                                  |              ![](https://img.shields.io/github/stars/eriklindernoren/Keras-GAN?style=flat\&label=%E2%AD%90\&color=gold)             | Keras — many GANs                             |
| [NVlabs/imaginaire](https://github.com/NVlabs/imaginaire) ⭐ 4,083 \| 🐛 53 \| 🌐 Python \| 📅 2022-11-29                                                                   |                  ![](https://img.shields.io/github/stars/NVlabs/imaginaire?style=flat\&label=%E2%AD%90\&color=gold)                 | PyTorch — NVIDIA image & video synthesis GANs |

<sub><a href="#contents">↑ back to Contents</a></sub>

***

## 📰 Trendy AI-application Articles

* [Artificial intelligence can say yes to the dress](https://qz.com/1090267/artificial-intelligence-can-now-show-you-how-those-pants-will-fit/)

<sub><a href="#contents">↑ back to Contents</a></sub>

***

## Author

Minchul Shin, [@nashory](https://github.com/nashory)

**Any recommendations to add to the list are welcome — see [CONTRIBUTING.md](CONTRIBUTING.md) and feel free to make pull requests! :)**

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-18._
