# Awesome SNN-based Image Restoration

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/wenliang123-debag/awesome-snn-image-restoration/pulls)

A curated collection of papers, code, and resources on **Spiking Neural Networks (SNNs) for Image Restoration (IR)**.

SNNs offer sparse, event-driven computation and are promising for energy-efficient low-level vision. This repository tracks work that applies SNNs to image restoration tasks such as denoising, deraining, dehazing, low-light enhancement, and super-resolution.

> Last updated: August 2026. Contributions and corrections are welcome!

## Contents

- [Scope](#scope)
- [General and All-in-One Restoration](#general-and-all-in-one-restoration)
- [Image Denoising](#image-denoising)
- [Image Deraining](#image-deraining)
- [Low-Light Image Enhancement](#low-light-image-enhancement)
- [Image Super-Resolution](#image-super-resolution)
- [Related Event/Spike-guided Restoration](#related-eventspike-guided-restoration)
- [Contributing](#contributing)

## Scope

The main list includes papers whose restoration model is an SNN or a hybrid SNN–ANN architecture. Pure image classification papers and spike-camera reconstruction methods that do not use spiking neural computation are excluded from the main list.

Legend: **Paper** = publication page or preprint · **Code** = official implementation

## General and All-in-One Restoration

| Year | Paper | Authors | Venue | Resources |
|:---:|---|---|:---:|:---:|
| 2026 | **SpikingIR: A Novel Converted Spiking Neural Network for Efficient Image Restoration** | Yang Ouyang, Zihan Cheng, Xiaotong Luo, Guoqi Li, Yanyun Qu | AAAI | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/37769) |
| 2025 | **SNNSIR: A Simple Spiking Neural Network for Stereo Image Restoration** | Ronghua Xu, Jin Xie, Jing Nie, Jiale Cao, Yanwei Pang | arXiv | [Paper](https://arxiv.org/abs/2508.12271) |
| 2025 | **Bridge the Gap between SNN and ANN for Image Restoration** | Xin Su, Chen Wu, Zhuoran Zheng | arXiv | [Paper](https://arxiv.org/abs/2504.01755) |

## Image Denoising

| Year | Paper | Authors | Venue | Resources |
|:---:|---|---|:---:|:---:|
| 2023 | **SPIDEN: Deep Spiking Neural Networks for Efficient Image Denoising** | Andrea Castagnetti, Alain Pegatoquet, Benoît Miramond | Frontiers in Neuroscience | [Paper](https://doi.org/10.3389/fnins.2023.1224457) · [arXiv](https://arxiv.org/abs/2305.11898) |

## Image Deraining

| Year | Paper | Authors | Venue | Resources |
|:---:|---|---|:---:|:---:|
| 2026 | **SpikeRain: Towards Energy-Efficient Single Image Deraining with Spiking Neural Networks** | Md Tanvir Islam, Inzamamul Alam, Sambit Bakshi, Khan Muhammad, Javier Del Ser, Sangtae Ahn | WACV | [Paper](https://openaccess.thecvf.com/content/WACV2026/html/Islam_SpikeRain_Towards_Energy-Efficient_Single_Image_Deraining_with_Spiking_Neural_Networks_WACV_2026_paper.html) · [Code](https://github.com/tanvirnwu/SpikeRain) |
| 2024 | **Learning a Spiking Neural Network for Efficient Image Deraining** (ESDNet) | Tianyu Song, Guiyue Jin, Pengpeng Li, Kui Jiang, Xiang Chen, Jiyu Jin | IJCAI | [Paper](https://www.ijcai.org/proceedings/2024/139) · [Code](https://github.com/MingTian99/ESDNet) |

## Low-Light Image Enhancement

| Year | Paper | Authors | Venue | Resources |
|:---:|---|---|:---:|:---:|
| 2025 | **Spike-RetinexFormer: Rethinking Low-light Image Enhancement with Spiking Neural Networks** | Hongzhi Wang, Xiubo Liang, Jinxing Han, Weidong Geng | NeurIPS | [Paper](https://proceedings.neurips.cc/paper_files/paper/2025/hash/10ba36411c4651fca95a1822fc83863d-Abstract-Conference.html) |

## Image Super-Resolution

| Year | Paper | Authors | Venue | Resources |
|:---:|---|---|:---:|:---:|
| 2025 | **Spiking Meets Attention: Efficient Remote Sensing Image Super-Resolution with Attention Spiking Neural Networks** (SpikeSR) | Yi Xiao, Qiangqiang Yuan, Kui Jiang, Wenke Huang, Qiang Zhang, Tingting Zheng, Chia-Wen Lin, Liangpei Zhang | NeurIPS | [Paper](https://arxiv.org/abs/2503.04223) · [Code](https://github.com/XY-boy/SpikeSR) |

## Related Event/Spike-guided Restoration

These papers use SNN components together with event or spike-camera inputs. They are listed separately because their primary setting differs from conventional frame-based SNN image restoration.

| Year | Paper | Authors | Venue | Resources |
|:---:|---|---|:---:|:---:|
| 2026 | **Seeing Through Blur: Tackling Defocus in Spike-Based Imaging** | Xiantao Ma, Siwei Dong, Lin Zhu, Lizhi Wang, Hua Huang | CVPR | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Ma_Seeing_Through_Blur_Tackling_Defocus_in_Spike-Based_Imaging_CVPR_2026_paper.html) |
| 2025 | **ClearSight: Human Vision-Inspired Solutions for Event-Based Motion Deblurring** | Xiaopeng Lin, Yulong Huang, Hongwei Ren, Zunchang Liu, Hongxiang Huang, Yue Zhou, Haotian Fu, Bojun Cheng | ICCV | [Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Lin_ClearSight_Human_Vision-Inspired_Solutions_for_Event-Based_Motion_Deblurring_ICCV_2025_paper.html) |

## Contributing

Pull requests are welcome. Please add a paper to the most relevant task section and provide:

- the exact paper title and author list;
- the official venue and publication year;
- a paper or proceedings link;
- the official code link, when available.

Please use primary sources such as official proceedings, arXiv, or the authors' repository. If a submission has not been formally accepted, label it as **arXiv** rather than a conference paper.

## License

This curated list is released under the [MIT License](LICENSE).

If you find this repository useful, please consider giving it a star.
