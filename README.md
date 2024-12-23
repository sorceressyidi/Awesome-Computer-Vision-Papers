# Awesome-computer-vision [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)  [![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com) 

## ✨ About

This repo contains a curated list of **Computer Vision papers** , inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision) and [Awesome-Robotics-3D
](https://github.com/zubair-irshad/Awesome-Robotics-3D)

If you find this repository useful, please consider **STARing** ⭐ this repository.

> **Note**: This repository is under active development. If you have any suggestions or want to contribute, feel free to open an issue or a pull request.

**Disclaimer**: This repository is not meant to be a comprehensive list of all computer vision but rather a curated list of papers that I find interesting. I have left out many fundamental papers and focused on the more recent and interesting ones. If you are looking for a comprehensive list of papers, I think the above-mentioned repositories and other resources are a better fit!

## 📚 Table of Contents
- [my-awesome-computer-vision   ](#my-awesome-computer-vision---)
  - [✨ About](#-about)
  - [📚 Table of Contents](#-table-of-contents)
  - [3D Gaussians and its Variants](#3d-gaussians-and-its-variants)
  - [Human Pose Tracking / Human Pose Estimation](#human-pose-tracking--human-pose-estimation)
  - [4D Reconstruction](#4d-reconstruction)
  - [Sparse View/ Uncalibrated / Distorion-free 3D Reconstruction](#sparse-view-uncalibrated--distorion-free-3d-reconstruction)
  - [VLLM](#vllm)
  - [Generative Models](#generative-models)
  - [3D Data Synthesis](#3d-data-synthesis)

## 3D Gaussians and its Variants

**[Compressing 3D Gaussians]**

**[Survey]** : 3DGS.zip: A survey on 3D Gaussian Splatting Compression Methods [[Webpage](https://w-m.github.io/3dgs-compression-survey/)]

* **Context GS** : "ContextGS: Compact 3D Gaussian Splatting with Anchor Level Context Model", *NeurIPS 2024*. [[Paper](https://arxiv.org/pdf/2405.20721)][[Code](https://github.com/wyf0912/ContextGS)]

* **SOG** : "Compact 3D Scene Representation via Self-Organizing Gaussian Grids", *ECCV 2023* [[Paper](https://arxiv.org/pdf/2312.13299)] [[Webpage](https://sogs.github.io/)] [[Code](https://github.com/fraunhoferhhi/Self-Organizing-Gaussians)]

------------------------------

## Human Pose Tracking / Human Pose Estimation

* **Dynamic 3D Gaussians** : "Dynamic 3D Gaussians:Tracking by Persistent Dynamic View Synthesis", *International Conference on 3D Vision (3DV) 2024*. [[Paper](https://arxiv.org/pdf/2308.09713)] [[Webpage](https://dynamic3dgaussians.github.io/)] [[Code](https://github.com/JonathonLuiten/Dynamic3DGaussians)]

------------------------------

## 4D Reconstruction

* **4D Gaussian Splatting** : "Real-time Photorealistic Dynamic Scene Representation and Rendering with 4D Gaussian Splatting", *ICLR 2024*. [[Paper](https://arxiv.org/pdf/2310.10642)] [[Webpage](https://fudan-zvg.github.io/4d-gaussian-splatting/)] [[Code](https://github.com/fudan-zvg/4d-gaussian-splatting)]
* **4D Reconstruction from a Single Video** : "Shape of Motion:
4D Reconstruction from a Single Video", *arXiv Jul 2024*. [[Paper](https://arxiv.org/pdf/2407.13764)] [[Webpage](https://shape-of-motion.github.io/)] [[Code](https://github.com/vye16/shape-of-motion)]

* **Temporal Gaussians** : "Representing Long Volumetric Video
with Temporal Gaussian Hierarchy", *SIGGRAPH Asia 2024 (TOG)*, [[Paper](https://arxiv.org/pdf/2412.09608)] [[Webpage](https://zju3dv.github.io/longvolcap/)] [[Code](https://github.com/zju3dv/EasyVolcap)]

* **Streamable 2D Dynamic Gaussians** : "V^3- Viewing Volumetric Videos on Mobiles via Streamable 2D Dynamic Gaussians", *SIGGRAPH Asia 2024 (TOG)*. [[Paper](https://arxiv.org/pdf/2409.13648)] [[Webpage](https://authoritywang.github.io/v3/)] [[Code](https://github.com/AuthorityWang/VideoGS)]


------------------------------


## Sparse View/ Uncalibrated / Distorion-free 3D Reconstruction

* **pixelSplat** : "pixelSplat: 3D Gaussian Splats from Image Pairs for Scalable Generalizable 3D Reconstruction", *CVPR 2024*. [[Paper](https://arxiv.org/pdf/2312.12337)] [[Webpage](https://davidcharatan.com/pixelsplat/)] [[Code](https://github.com/dcharatan/pixelsplat)]


* **Splatt3R** : "Splatt3R: Zero-shot Gaussian Splatting from Uncalibrated Image Pairs", *arXiv Aug 2024*. [[Paper](https://arxiv.org/pdf/2408.13912)] [[Webpage](https://splatt3r.active.vision/)] [[Code](https://github.com/btsmart/splatt3r)]

* **3DGUT** : "3DGUT: Enabling Distorted Cameras and Secondary Rays in Gaussian Splatting", *arXiv Dec 2024*. [[Paper](https://arxiv.org/pdf/2412.12507)] [[Webpage](https://research.nvidia.com/labs/toronto-ai/3DGUT/)]

* **FreeSplatter** : "FreeSplatter: Pose-free Gaussian Splatting for Sparse-view 3D Reconstruction", arXiv Dec 2024. [[Paper](https://arxiv.org/pdf/2412.09573)] [[Webpage](https://bluestyle97.github.io/projects/freesplatter/)] [[Code](https://github.com/TencentARC/FreeSplatter)]


------------------------------


## VLLM

* **VSI-Bench** : "Thinking in Space:How Multimodal Large Language Models See, Remember and Recall Spaces", *arXiv Aug 2024*. [[Paper](https://arxiv.org/pdf/2412.14171)] [[Webpage](https://vision-x-nyu.github.io/thinking-in-space.github.io/)]


------------------------------


## Generative Models

* **Interactive 3D Scene Generation from a Single Image**: "WonderWorld: Interactive 3D Scene Generation from a Single Image", *CVPR 2024*. [[Paper](https://arxiv.org/pdf/2406.09394)] [[Webpage](https://kovenyu.com/wonderworld/)] [[Code](https://github.com/KovenYu/WonderWorld)]


------------------------------

## 3D Data Synthesis

* **MegaSynth**: "MegaSynth: scaling up feed-forward 3D scene reconstruction with synthesized scenes", *arxiv Dec 2024*. [[Paper](https://arxiv.org/pdf/2412.14166)] [[Webpage](https://hwjiang1510.github.io/MegaSynth/)] [[Code](https://github.com/hwjiang1510/MegaSynth)]
