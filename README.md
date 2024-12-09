# Awesome Large Vision Language Models (VLLMs)


## 🔥🔥🔥 Visual Large Language Models for Generalized and Specialized Applications

<p align="center">
    <img src="assets/VLM_revolution.png" width="90%" height="90%">
</p>


## 📢 News

🚀 **What's New in This Update**:

2024.12.30: We release our VLLM application paper list repo!
<span id="head-content"><font size=5><center><b> Table of Contents </b> </center></font></span>
- [🔥🔥🔥 Visual Large Language Models for Generalized and Specialized Applications](#awesome-vllms)
  - [Existing VLM surveys](#existing-vlm-surveys)
    - [VLM surveys](#vlm-surveys)
    - [MLLM surveys](#mllm-surveys)
  - [Vision-to-text](#vision-to-text)
    - [Image-to-text](#image-to-text)
        - [General domain](#general-domain)
            - [General ability](#general-ability)
            - [REC](#rec)
            - [RES](#res)
            - [OCR](#ocr)
            - [Retrieval](#retrieval)
        - [VLLM+X](#VLLM+X)
            - [Remote sensing](#remote-sensing)
            - [Medical](#medical)
            - [Science and math](#science-and-math)
            - [Graphics and UI](#graphics-and-ui)
            - [Financial analysis](#financial-analysis)
    - [Video-to-text](#video-to-text)
        - [General domain](#general-domain)
        - [Video conversation](#video-conversation)
        - [Egocentric understanding](#egocentric-understanding)
  - [Vision-to-action](#vision-to-action)
      - [Autonomous driving](#autonomous-driving)
      - [Embodied AI](#embodied-ai)
      - [Automated tool management](#automated-tool-management)
  - [Text-to-vision](#text-to-vision)
      - [Text-to-image](#text-to-image)
      - [Text-to-3D](#text-to-3D)
      - [Text-to-video](#text-to-video)
  - [Other applications](#other-applications)
      - [Face](#face)

## Existing VLM surveys
### VLM surveys
|  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![Star](https://img.shields.io/github/stars/jingyi0000/VLM_survey.svg?style=social&label=Star) <br>[**Vision-Language Models for Vision Tasks: A Survey**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10445007) <br> | T-PAMI | 2024-8-8 | Github | [Project](https://github.com/jingyi0000/VLM_survey) |
| ![Star](https://img.shields.io/github/stars/Yutong-Zhou-cv/Awesome-Text-to-Image.svg?style=social&label=Star) <br> [**Vision + Language Applications: A Survey**](https://openaccess.thecvf.com/content/CVPR2023W/GCV/papers/Zhou_Vision__Language_Applications_A_Survey_CVPRW_2023_paper.pdf) <br> | CVPRW | 2023-5-24 | Github | [Project](https://github.com/Yutong-Zhou-cv/Awesome-Text-to-Image) |
| [**Vision-and-Language Pretrained Models: A Survey**](https://arxiv.org/pdf/2204.07356.pdf) <br> | IJCAI (survey track) | 2022-5-3 | Github | Project |

### MLLM surveys
|  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![Star](https://img.shields.io/github/stars/BradyFU/Awesome-Multimodal-Large-Language-Models.svg?style=social&label=Star) <br> [**A Survey on Multimodal Large Language Models**](https://arxiv.org/pdf/2306.13549.pdf) <br> | T-PAMI | 2024-11-29 | Github | [Project](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models) |
| ![Star](https://img.shields.io/github/stars/BradyFU/Awesome-Multimodal-Large-Language-Models.svg?style=social&label=Star) <br> [**MME-Survey: A Comprehensive Survey on Evaluation of Multimodal LLMs**](https://arxiv.org/pdf/2411.15296) <br> | AriXv | 2024-11-22 | Github | [Project](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models) |
| [**A Survey on Multimodal Large Language Models**](https://academic.oup.com/nsr/advance-article-pdf/doi/10.1093/nsr/nwae403/60676453/nwae403.pdf) <br> | National Science Review | 2024-11-12 | Github | Project |
| [**Video Understanding with Large Language Models: A Survey**](https://arxiv.org/pdf/2312.17432) <br> | ArXiv | 2024-6-24 | Github | [Project](https://github.com/yunlong10/Awesome-LLMs-for-Video-Understanding) |
| ![Star](https://img.shields.io/github/stars/yunlong10/Awesome-LLMs-for-Video-Understanding.svg?style=social&label=Star) <br> [**The Revolution of Multimodal Large Language Models: A Survey**](https://arxiv.org/pdf/2402.12451) <br> | ArXiv | 2024-6-6 | Github | Project |
| ![Star](https://img.shields.io/github/stars/lhanchao777/LVLM-Hallucinations-Survey.svg?style=social&label=Star) <br> [**A Survey on Hallucination in Large Vision-Language Models**](https://arxiv.org/pdf/2402.00253) <br> | ArXiv | 2024-5-6 | Github | [Project](https://github.com/lhanchao777/LVLM-Hallucinations-Survey) |
| [**Exploring the Frontier of Vision-Language Models: A Survey of Current Methodologies and Future Directions**](https://arxiv.org/pdf/2404.07214) <br> | ArXiv | 2024-4-12 | Github | Project |
| ![Star](https://img.shields.io/github/stars/MM-LLMs/mm-llms.github.io.svg?style=social&label=Star) <br> [**MM-LLMs: Recent Advances in MultiModal Large Language Models**](https://arxiv.org/pdf/2401.13601v4) <br> | ArXiv | 2024-2-20 | Github | [Project](https://mm-llms.github.io/) |
| [**Exploring the Reasoning Abilities of Multimodallarge Language Models (mllms): a Comprehensive survey on Emerging Trends in Multimodal Reasonings**](https://arxiv.org/pdf/2401.06805) <br> | AriXv | 2024-1-18 | Github | Project |
| [**Visual Instruction Tuning towards General-Purpose Multimodal Model: A Survey**](https://arxiv.org/pdf/2312.16602) <br> | ArXiv | 2023-12-27 | Github | Project |
| [**Multimodal Large Language Models: A Survey**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10386743) <br> | BigData | 2023-12-15 | Github | Project |

## Vision-to-text
### Image-to-text
#### General domain
##### General ability
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

##### REC
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

##### RES
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

##### OCR
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

##### Retrieval
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

#### VLLM + X
##### Remote sensing
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

##### Medical
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

##### Science and math
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

##### Graphics and UI
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

##### Financial analysis
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

### Video-to-text

[<u><🎯Back to Top></u>](#head-content)
####  General domain
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)
#### Video conversation
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)
#### Egocentric view
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

## Vision-to-action

### Autonomous driving

#### Perception
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|
|DriveLM | ![Star](https://img.shields.io/github/stars/OpenDriveLab/DriveLM.svg?style=social&label=Star) <br> [**DriveLM: Driving with Graph Visual Question Answering**](https://arxiv.org/pdf/2312.14150) <br> | ECCV | 2024-7-17 | [Github](https://github.com/OpenDriveLab/DriveLM) | Project |
|Talk2BEV | ![Star](https://img.shields.io/github/stars/llmbev/talk2bev.svg?style=social&label=Star) <br> [**Talk2BEV: Language-enhanced Bird’s-eye View Maps for Autonomous Driving**](https://arxiv.org/pdf/2310.02251) <br> | ICRA | 2024-5-13 | [Github](https://github.com/llmbev/talk2bev) | [Project](https://llmbev.github.io/talk2bev/) |
|Nuscenes-QA | ![Star](https://img.shields.io/github/stars/qiantianwen/NuScenes-QA.svg?style=social&label=Star) <br> [**TNuScenes-QA: A Multi-Modal Visual Question Answering Benchmark for Autonomous Driving Scenario**](https://ojs.aaai.org/index.php/AAAI/article/view/28253/28499) <br> | AAAI | 2024-3-24 | [Github](https://github.com/qiantianwen/NuScenes-QA) | Project |
|DriveMLM | ![Star](https://img.shields.io/github/stars/OpenGVLab/DriveMLM.svg?style=social&label=Star) <br> [**DriveMLM: Aligning Multi-Modal Large Language Models with Behavioral Planning States for Autonomous Driving**](https://arxiv.org/pdf/2312.09245) <br> | ArXiv | 2023-12-25 | [Github](https://github.com/OpenGVLab/DriveMLM) | Project |
|LiDAR-LLM | [**LiDAR-LLM: Exploring the Potential of Large Language Models for 3D LiDAR Understanding**](https://arxiv.org/pdf/2312.14074v1) <br> | CoRR | 2023-12-21 | Github | [Project](https://sites.google.com/view/lidar-llm) |
|Dolphis | ![Star](https://img.shields.io/github/stars/SaFoLab-WISC/Dolphins.svg?style=social&label=Star) <br> [**Dolphins: Multimodal Language Model for Driving**](https://arxiv.org/abs/2312.00438) <br> | ArXiv | 2023-12-1 | [Github](https://github.com/SaFoLab-WISC/Dolphins) | [Project](https://vlm-driver.github.io/) |

[<u><🎯Back to Top></u>](#head-content)

#### Planning
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

#### Prediction
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

### Embodied AI
#### Perception
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

#### Manipulation
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

#### Planning
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

#### Navigation
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

### Automated tool management
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

## Text-to-vision
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

### Text-to-image
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

### Text-to-3D
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

### Text-to-video
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)

## Other applications
### Face
|  Model  |  Title  |   Venue  |   Date   |   Code   |   Project   |
|:--------|:--------|:--------:|:--------:|:--------:|:--------:|

[<u><🎯Back to Top></u>](#head-content)
