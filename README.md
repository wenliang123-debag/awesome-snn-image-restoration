<h1 align="center">Awesome SNN-based Image Restoration</h1>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="MIT License"></a>
</p>

Papers, datasets, and tools for image restoration with spiking or hybrid SNN–ANN models. Event- and spike-camera reconstruction are out of scope.

[General Restoration](#general--all-in-one-restoration) · [Denoising](#image-denoising) · [Deraining](#image-deraining) · [Dehazing](#image-dehazing) · [Low-Light](#low-light-image-enhancement) · [Super-Resolution](#image-super-resolution) · [Benchmarks](#benchmarks--datasets) · [Toolboxes](#toolboxes--platforms) · [Contributing](#contributing)

**21 papers** · [Paper notes and figures](docs/paper-notes.md) · [October verification record](docs/verification-2026-10-25.md)

Preprint and submission labels do not indicate acceptance. A dash in the Code column means no code link is listed.

Energy results depend on time steps, architecture, hardware, and measurement or estimation protocol. Do not compare values across incompatible setups.

## General & All-in-One Restoration

| Paper | Venue | Link | Code |
|---|---|---|---|
| Spiking Pyramid Wavelet Transformation for High-efficient and Low-energy Image Restoration<br>Chen Zhao *et al.* | Pattern Recognition 2026 | [Journal](https://doi.org/10.1016/j.patcog.2026.114297) · [arXiv](https://arxiv.org/abs/2606.18644) · [PDF](https://arxiv.org/pdf/2606.18644) · [HTML](https://arxiv.org/html/2606.18644) | — |
| SpikingIR: A Novel Converted Spiking Neural Network for Efficient Image Restoration<br>Yang Ouyang *et al.* | AAAI 2026 | [AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/37769) · [DOI](https://doi.org/10.1609/aaai.v40i10.37769) · [PDF](https://ojs.aaai.org/index.php/AAAI/article/download/37769/41731) | — |
| SNNSIR: A fully Spiking Neural Network for Stereo Image Restoration<br>Ronghua Xu *et al.* | Pattern Recognition 2026 | [arXiv](https://arxiv.org/abs/2508.12271) · [PDF](https://arxiv.org/pdf/2508.12271) · [HTML](https://arxiv.org/html/2508.12271) · [Journal](https://doi.org/10.1016/j.patcog.2026.114546) | [Code](https://github.com/tukumax/SNNSIR) |
| SpikeRestormer: Towards Energy-Efficient All-in-One Image Restoration via Unified Event Reasoning<br>Shengkai Hu *et al.* | Preprint 2026 | [arXiv](https://arxiv.org/abs/2608.02290) · [PDF](https://arxiv.org/pdf/2608.02290) | — |
| Bridge the Gap between SNN and ANN for Image Restoration<br>Xin Su *et al.* | Preprint 2025 | [arXiv](https://arxiv.org/abs/2504.01755) · [PDF](https://arxiv.org/pdf/2504.01755) · [HTML](https://arxiv.org/html/2504.01755) | — |

## Image Denoising

| Paper | Venue | Link | Code |
|---|---|---|---|
| Layer-Wise Spike Modulation for Structure-Aware Image Denoising with Spiking Neural Networks<br>Eunbin Kim and Onseok Lee | Applied Sciences 2026 | [Journal](https://www.mdpi.com/2076-3417/16/20/10391) | [Code](https://github.com/EBiinii/SNN-denoising) |
| SPIDEN: Deep Spiking Neural Networks for Efficient Image Denoising<br>Andrea Castagnetti *et al.* | Frontiers in Neuroscience 2023 | [Journal](https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2023.1224457/full) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/37638316/) | — |
| VTSNN: A Virtual Temporal Spiking Neural Network<br>Xue-Rui Qiu *et al.* | Frontiers in Neuroscience 2023 | [Journal](https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2023.1091097/full) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/37287800/) | [Code](https://github.com/bollossom/VTSNN) |
| Probabilistic Inference of Binary Markov Random Fields in Spiking Neural Networks through Mean-Field Approximation<br>Y. Zheng *et al.* | Neural Networks 2020 | [Journal](https://doi.org/10.1016/j.neunet.2020.03.003) · [Accepted Version](https://eprints.whiterose.ac.uk/id/eprint/176163/) | — |

## Image Deraining

| Paper | Venue | Link | Code |
|---|---|---|---|
| SpikeRain: Towards Energy-Efficient Single Image Deraining with Spiking Neural Networks<br>Md Tanvir Islam *et al.* | WACV 2026 | [CVF](https://openaccess.thecvf.com/content/WACV2026/html/Islam_SpikeRain_Towards_Energy-Efficient_Single_Image_Deraining_with_Spiking_Neural_Networks_WACV_2026_paper.html) · [PDF](https://openaccess.thecvf.com/content/WACV2026/papers/Islam_SpikeRain_Towards_Energy-Efficient_Single_Image_Deraining_with_Spiking_Neural_Networks_WACV_2026_paper.pdf) | [Code](https://github.com/tanvirnwu/SpikeRain_WACV_2025) |
| Exploring the Potentials of Spiking Neural Networks for Image Deraining (VLIF)<br>Shuang Chen *et al.* | AAAI 2026 | [arXiv](https://arxiv.org/abs/2512.02258) · [PDF](https://arxiv.org/pdf/2512.02258) · [AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/37295) | [Code](https://github.com/ChrisChen1023/VLIF) |
| Learning a Spiking Neural Network for Efficient Image Deraining<br>Tianyu Song *et al.* | IJCAI 2024 | [IJCAI](https://www.ijcai.org/proceedings/2024/139) · [PDF](https://www.ijcai.org/proceedings/2024/0139.pdf) | [Code](https://github.com/MingTian99/ESDNet) |

## Image Dehazing

| Paper | Venue | Link | Code |
|---|---|---|---|
| ReBo-SNN: Boosted spiking neural network with retina mechanism for efficient haze removal<br>Ya Zhang *et al.* | Neural Networks 2027 | [Journal](https://doi.org/10.1016/j.neunet.2026.109428) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/42546443/) | — |
| Spiking Transformer with Learnable Threshold Mechanism for Underwater Image Dehazing to Aid Vision-Based Navigation<br>Vidya Sudevan *et al.* | Neuromorphic Computing and Engineering 2026 | [Journal](https://doi.org/10.1088/2634-4386/ae41e1) · [arXiv](https://arxiv.org/abs/2504.11482) · [PDF](https://arxiv.org/pdf/2504.11482) | [Code](https://github.com/vidya-rejul/snnTrans-DHZ) |
| EM-SNN: Efficiently Modulated Spiking Neural Network for Remote Sensing Image Dehazing<br>Jie Shao *et al.* | Preprint 2026 | [arXiv](https://arxiv.org/abs/2610.09275) · [PDF](https://arxiv.org/pdf/2610.09275) | — |
| Learning a density-guided adaptive spiking network for remote sensing image dehazing (DASNet)<br>Baowen Wu *et al.* | Scientific Reports 2026 (early version) | [Journal](https://www.nature.com/articles/s41598-026-80033-y) · [PDF](https://www.nature.com/articles/s41598-026-80033-y_reference.pdf) | — |
| Retina-Inspired Lightweight Spiking Convolutional Neural Network for Single-Image Dehazing (RI-SCNN)<br>Ya Zhang *et al.* | IEEE TNNLS 2025 | [DOI](https://doi.org/10.1109/TNNLS.2024.3460973) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/39325611/) | — |
| U-Net-Like Spiking Neural Networks for Single Image Dehazing (DehazeSNN)<br>Huibin Li *et al.* | IJCNN 2025 | [DOI](https://doi.org/10.1109/IJCNN64981.2025.11228727) · [arXiv](https://arxiv.org/abs/2512.23950) | [Code](https://github.com/HaoranLiu507/DehazeSNN) |

## Low-Light Image Enhancement

| Paper | Venue | Link | Code |
|---|---|---|---|
| A Dual-Domain Synergistic Network with Frequency-Guided Neuromorphic Adaptation for low-light fundus image enhancement (DDSN)<br>Lvchen Cao *et al.* | Knowledge-Based Systems 2026 | [Journal](https://doi.org/10.1016/j.knosys.2026.116809) | [Code](https://github.com/Turing2022/DDSN) |
| Spike-RetinexFormer: Rethinking Low-light Image Enhancement with Spiking Neural Networks<br>Hongzhi Wang *et al.* | NeurIPS 2025 | [NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2025/hash/10ba36411c4651fca95a1822fc83863d-Abstract-Conference.html) · [PDF](https://proceedings.neurips.cc/paper_files/paper/2025/file/10ba36411c4651fca95a1822fc83863d-Paper-Conference.pdf) · [BibTeX](https://proceedings.neurips.cc/paper_files/paper/2025/hash/10ba36411c4651fca95a1822fc83863d-Bibtex-Conference.bib) | — |

## Image Super-Resolution

| Paper | Venue | Link | Code |
|---|---|---|---|
| Spiking Meets Attention: Efficient Remote Sensing Image Super-Resolution with Attention Spiking Neural Networks<br>Yi Xiao *et al.* | NeurIPS 2025 | [arXiv](https://arxiv.org/abs/2503.04223) · [PDF](https://arxiv.org/pdf/2503.04223) · [HTML](https://arxiv.org/html/2503.04223) · [NeurIPS](https://papers.nips.cc/paper_files/paper/2025/hash/5e3f2028c5a78fbfb6e1754b7cfb6153-Abstract-Conference.html) | [Code](https://github.com/XY-boy/SpikeSR) |

## Benchmarks & Datasets

Dataset entries link to original releases, primary papers, or clearly labeled author-maintained evaluation copies. Match each paper's split, preprocessing and degradation settings before comparing results. AID, DOTA and DIOR are source imagery used to construct SR evaluations; they are not originally paired SR datasets. SOTS is a subset of RESIDE.

| Resource | Task / source entry | Notes |
|---|---|---|
| BSD68 / Set12 / CIFAR-10 | [BSD68 / Set12 evaluation copies from DnCNN authors](https://github.com/cszn/DnCNN/tree/master/testsets) · [CIFAR-10 original release](https://www.cs.toronto.edu/~kriz/cifar.html) | Denoising / reconstruction; [Berkeley source dataset](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/bsds/) |
| Rain12 / Rain200L / Rain200H / Rain1200 | [Rain12 primary paper](https://openaccess.thecvf.com/content_cvpr_2016/html/Li_Rain_Streak_Removal_CVPR_2016_paper.html) · [Rain200 primary paper](https://openaccess.thecvf.com/content_cvpr_2017/html/Yang_Deep_Joint_Rain_CVPR_2017_paper.html) · [Rain1200 author release](https://github.com/hezhangsprinter/DID-MDN) | Single-image deraining; use each paper's specified train/test variant |
| SOTS / RESIDE / Dense-Haze | [RESIDE and SOTS](https://sites.google.com/view/reside-dehaze-datasets) · [Dense-Haze official release](https://data.vision.ee.ethz.ch/cvl/ntire19//dense-haze/) | Synthetic and real haze; RESIDE's original page points to its Standard/β versions |
| UIEB / EUVP | [UIEB official page](https://li-chongyi.github.io/proj_benchmark.html) · [EUVP official page](https://irvlab.cs.umn.edu/resources/euvp-dataset) | Underwater enhancement/dehazing; paired and unpaired subsets differ |
| Set5 / Urban100 | [SwinIR authors' evaluation-data instructions](https://github.com/JingyunLiang/SwinIR) | Author-provided evaluation copies, not original dataset ownership |
| LOL-v1 / SDSD | [LOL author release](https://github.com/weichen582/RetinexNet) · [SDSD author release](https://github.com/JIA-Lab-research/SDSD) | Low-light enhancement; SDSD is video data, so record frame sampling |
| AID / DOTA / DIOR | [AID official page](https://captain-whu.github.io/AID/) · [DOTA official page](https://captain-whu.github.io/DOTA/) · [SpikeSR evaluation instructions](https://github.com/XY-boy/SpikeSR) | Remote-sensing SR; DIOR evaluation entry is provided through SpikeSR |
| StereoWaterdrop and stereo restoration sets | [SNNSIR experimental protocol and original references](https://arxiv.org/html/2508.12271v1) | Paper/protocol entry; a verified standalone dataset release is still needed |

Dataset and paper licenses are set by their original authors. This list does not relicense them.

---

## Toolboxes & Platforms

### SNN Frameworks

- **[SpikingJelly](https://github.com/fangwei123456/spikingjelly)** — deep-learning framework for SNN simulation and training.
- **[snnTorch](https://github.com/jeshraghian/snntorch)** — PyTorch-based spiking neural network library.
- **[Norse](https://github.com/norse/norse)** — deep-learning library for spiking neural networks.
- **[Lava](https://github.com/lava-nc/lava)** — neuromorphic computing framework; the linked repository is archived (checked 2026-10-25).

### Restoration Codebases

- **[ESDNet](https://github.com/MingTian99/ESDNet)** — efficient SNN-based image deraining.
- **[VLIF](https://github.com/ChrisChen1023/VLIF)** — visual-LIF neurons for image deraining.
- **[SpikeRain](https://github.com/tanvirnwu/SpikeRain_WACV_2025)** — energy-efficient single-image deraining.
- **[SpikeSR](https://github.com/XY-boy/SpikeSR)** — attention-based SNN for remote sensing super-resolution.
- **[snnTrans-DHZ](https://github.com/vidya-rejul/snnTrans-DHZ)** — spiking-transformer underwater image dehazing.
- **[DehazeSNN](https://github.com/HaoranLiu507/DehazeSNN)** — U-Net-like SNN for single-image dehazing.
- **[VTSNN](https://github.com/bollossom/VTSNN)** — virtual-temporal SNN for image reconstruction and denoising.

---

## Contributing

Follow the [manual contribution guide](CONTRIBUTING.md). Check primary sources, preserve the paper-table format, and label unaccepted manuscripts as **Preprint**. Include the source URL, checked date and reason for inclusion in a focused PR. See the [October verification record](docs/verification-2026-10-25.md) for known access limits.

This repository currently has no CI or scheduled maintenance. Run and report local checks for each change; historical workflow results are not current validation.

## License

This curated list is released under the [MIT License](LICENSE).

The MIT license applies to this repository's list; linked papers, figures, software and datasets retain their own terms.
