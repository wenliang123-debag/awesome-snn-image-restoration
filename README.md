<h1 align="center">Awesome SNN-based Image Restoration</h1>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="MIT License"></a>
</p>

<p align="center">
  <strong>A curated collection of spiking neural network papers, benchmarks, and toolboxes for image restoration.</strong><br>
  Focused on energy-efficient methods for <strong>denoising</strong>, <strong>deraining</strong>, <strong>dehazing</strong>, <strong>low-light enhancement</strong>, <strong>super-resolution</strong>, and <strong>general restoration</strong>.
</p>

<p align="center">
  <a href="#general--all-in-one-restoration">General Restoration</a> ·
  <a href="#image-denoising">Denoising</a> ·
  <a href="#image-deraining">Deraining</a> ·
  <a href="#image-dehazing">Dehazing</a> ·
  <a href="#low-light-image-enhancement">Low-Light</a> ·
  <a href="#image-super-resolution">Super-Resolution</a> ·
  <a href="#benchmarks--datasets">Benchmarks</a> ·
  <a href="#toolboxes--platforms">Toolboxes</a> ·
  <a href="#contributing">Contributing</a>
</p>

---

## 👋 Introduction

**Awesome-SNN-IR** collects research on **Spiking Neural Networks (SNNs) for Image Restoration (IR)**, especially methods that use sparse, event-driven computation to reduce the energy and computational cost of pixel-level restoration.

The list focuses on SNN and hybrid SNN–ANN models that directly solve image restoration tasks. Event-camera and spike-camera reconstruction are outside the scope of this repository.

## 🧭 SNN Restoration Areas

- **[General & All-in-One Restoration](#general--all-in-one-restoration)**: unified models for multiple degradations and stereo restoration.
- **[Image Denoising](#image-denoising)**: Gaussian and real-image noise removal with spike-based computation.
- **[Image Deraining](#image-deraining)**: efficient single-image rain streak removal.
- **[Image Dehazing](#image-dehazing)**: natural and underwater image dehazing with directly trained SNNs.
- **[Low-Light Image Enhancement](#low-light-image-enhancement)**: illumination enhancement using SNN and Retinex-inspired models.
- **[Image Super-Resolution](#image-super-resolution)**: high-resolution reconstruction with spiking attention.

---

## General & All-in-One Restoration

> SNN methods for **multi-degradation, all-in-one, and stereo image restoration**.

| Title & Authors | Intro | Useful Links |
|---|---|---|
| [Spiking Pyramid Wavelet Transformation for High-efficient and Low-energy Image Restoration](https://doi.org/10.1016/j.patcog.2026.114297) <br> Chen Zhao *et al.* <br> > Pattern Recognition'26 | <a href="https://arxiv.org/abs/2606.18644"><img src="https://arxiv.org/html/2606.18644v1/x2.png" width="960" alt="SPWM architecture" /></a> | [Journal](https://doi.org/10.1016/j.patcog.2026.114297) · [arXiv](https://arxiv.org/abs/2606.18644) · [PDF](https://arxiv.org/pdf/2606.18644) · [HTML](https://arxiv.org/html/2606.18644) |
| [SpikingIR: A Novel Converted Spiking Neural Network for Efficient Image Restoration](https://ojs.aaai.org/index.php/AAAI/article/view/37769) <br> Yang Ouyang *et al.* <br> > AAAI'26 | -- | [AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/37769) · [DOI](https://doi.org/10.1609/aaai.v40i10.37769) · [PDF](https://ojs.aaai.org/index.php/AAAI/article/download/37769/41731) |
| [SNNSIR: A Simple Spiking Neural Network for Stereo Image Restoration](https://arxiv.org/abs/2508.12271) <br> Ronghua Xu *et al.* <br> > Preprint'25 | <a href="https://arxiv.org/abs/2508.12271"><img src="https://arxiv.org/html/2508.12271v1/x3.png" width="960" alt="SNNSIR architecture" /></a> | [arXiv](https://arxiv.org/abs/2508.12271) · [PDF](https://arxiv.org/pdf/2508.12271) · [HTML](https://arxiv.org/html/2508.12271) |
| [Bridge the Gap between SNN and ANN for Image Restoration](https://arxiv.org/abs/2504.01755) <br> Xin Su *et al.* <br> > Preprint'25 | <a href="https://arxiv.org/abs/2504.01755"><img src="https://arxiv.org/html/2504.01755v1/x2.png" width="960" alt="SpikerIR framework" /></a> | [arXiv](https://arxiv.org/abs/2504.01755) · [PDF](https://arxiv.org/pdf/2504.01755) · [HTML](https://arxiv.org/html/2504.01755) |

---

## Image Denoising

> Spike-based methods for **efficient image denoising**.

| Title & Authors | Intro | Useful Links |
|---|---|---|
| [SPIDEN: Deep Spiking Neural Networks for Efficient Image Denoising](https://doi.org/10.3389/fnins.2023.1224457) <br> Andrea Castagnetti *et al.* <br> > Frontiers in Neuroscience'23 | -- | [Journal](https://doi.org/10.3389/fnins.2023.1224457) · [arXiv](https://arxiv.org/abs/2305.11898) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/37638316/) |
| [VTSNN: A Virtual Temporal Spiking Neural Network](https://doi.org/10.3389/fnins.2023.1091097) <br> Xue-Rui Qiu *et al.* <br> > Frontiers in Neuroscience'23 | <a href="https://github.com/bollossom/VTSNN"><img src="https://github.com/bollossom/VTSNN/raw/main/Figure2.jpg" width="960" alt="VTSNN framework" /></a> | [Journal](https://doi.org/10.3389/fnins.2023.1091097) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/37287800/) · [GitHub](https://github.com/bollossom/VTSNN) |
| [Probabilistic Inference of Binary Markov Random Fields in Spiking Neural Networks through Mean-Field Approximation](https://doi.org/10.1016/j.neunet.2020.03.003) <br> Y. Zheng *et al.* <br> > Neural Networks'20 | -- | [Journal](https://doi.org/10.1016/j.neunet.2020.03.003) · [Accepted Version](https://eprints.whiterose.ac.uk/id/eprint/176163/) |

---

## Image Deraining

> SNN methods for **single-image rain streak removal**.

| Title & Authors | Intro | Useful Links |
|---|---|---|
| [SpikeRain: Towards Energy-Efficient Single Image Deraining with Spiking Neural Networks](https://openaccess.thecvf.com/content/WACV2026/html/Islam_SpikeRain_Towards_Energy-Efficient_Single_Image_Deraining_with_Spiking_Neural_Networks_WACV_2026_paper.html) <br> Md Tanvir Islam *et al.* <br> > WACV'26 | <a href="https://github.com/tanvirnwu/SpikeRain_WACV_2025"><img src="https://github.com/tanvirnwu/SpikeRain_WACV_2025/raw/main/assets/figures/SpikeRain.jpg" width="960" alt="SpikeRain architecture" /></a> | [CVF](https://openaccess.thecvf.com/content/WACV2026/html/Islam_SpikeRain_Towards_Energy-Efficient_Single_Image_Deraining_with_Spiking_Neural_Networks_WACV_2026_paper.html) · [PDF](https://openaccess.thecvf.com/content/WACV2026/papers/Islam_SpikeRain_Towards_Energy-Efficient_Single_Image_Deraining_with_Spiking_Neural_Networks_WACV_2026_paper.pdf) · [GitHub](https://github.com/tanvirnwu/SpikeRain_WACV_2025) |
| [Exploring the Potentials of Spiking Neural Networks for Image Deraining](https://arxiv.org/abs/2512.02258) (VLIF) <br> Shuang Chen *et al.* <br> > Preprint'25 | -- | [arXiv](https://arxiv.org/abs/2512.02258) · [PDF](https://arxiv.org/pdf/2512.02258) · [GitHub](https://github.com/ChrisChen1023/VLIF) |
| [Learning a Spiking Neural Network for Efficient Image Deraining](https://www.ijcai.org/proceedings/2024/139) <br> Tianyu Song *et al.* <br> > IJCAI'24 | <a href="https://github.com/MingTian99/ESDNet"><img src="https://github.com/MingTian99/ESDNet/raw/master/arch.png" width="960" alt="ESDNet architecture" /></a> | [IJCAI](https://www.ijcai.org/proceedings/2024/139) · [PDF](https://www.ijcai.org/proceedings/2024/0139.pdf) · [GitHub](https://github.com/MingTian99/ESDNet) |

---

## Image Dehazing

> Directly trained SNN methods for **natural and underwater image dehazing**.

| Title & Authors | Intro | Useful Links |
|---|---|---|
| [Spiking Transformer with Learnable Threshold Mechanism for Underwater Image Dehazing to Aid Vision-Based Navigation](https://doi.org/10.1088/2634-4386/ae41e1) <br> Vidya Sudevan *et al.* <br> > Neuromorphic Computing and Engineering'26 | -- | [Journal](https://doi.org/10.1088/2634-4386/ae41e1) · [arXiv](https://arxiv.org/abs/2504.11482) · [PDF](https://arxiv.org/pdf/2504.11482) |
| [Retina-Inspired Lightweight Spiking Convolutional Neural Network for Single-Image Dehazing](https://doi.org/10.1109/TNNLS.2024.3460973) (RI-SCNN) <br> Ya Zhang *et al.* <br> > IEEE TNNLS'25 | -- | [DOI](https://doi.org/10.1109/TNNLS.2024.3460973) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/39325611/) |
| [U-Net-Like Spiking Neural Networks for Single Image Dehazing](https://doi.org/10.1109/IJCNN64981.2025.11228727) (DehazeSNN) <br> Huibin Li *et al.* <br> > IJCNN'25 | -- | [DOI](https://doi.org/10.1109/IJCNN64981.2025.11228727) · [arXiv](https://arxiv.org/abs/2512.23950) · [GitHub](https://github.com/HaoranLiu507/DehazeSNN) |

---

## Low-Light Image Enhancement

> SNN methods for **visibility and illumination enhancement in low-light scenes**.

| Title & Authors | Intro | Useful Links |
|---|---|---|
| [Spike-RetinexFormer: Rethinking Low-light Image Enhancement with Spiking Neural Networks](https://proceedings.neurips.cc/paper_files/paper/2025/hash/10ba36411c4651fca95a1822fc83863d-Abstract-Conference.html) <br> Hongzhi Wang *et al.* <br> > NeurIPS'25 | -- | [NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2025/hash/10ba36411c4651fca95a1822fc83863d-Abstract-Conference.html) · [PDF](https://proceedings.neurips.cc/paper_files/paper/2025/file/10ba36411c4651fca95a1822fc83863d-Paper-Conference.pdf) · [BibTeX](https://proceedings.neurips.cc/paper_files/paper/2025/hash/10ba36411c4651fca95a1822fc83863d-Bibtex-Conference.bib) |

---

## Image Super-Resolution

> SNN methods for **high-resolution image reconstruction**.

| Title & Authors | Intro | Useful Links |
|---|---|---|
| [Spiking Meets Attention: Efficient Remote Sensing Image Super-Resolution with Attention Spiking Neural Networks](https://arxiv.org/abs/2503.04223) <br> Yi Xiao *et al.* <br> > NeurIPS'25 | <a href="https://github.com/XY-boy/SpikeSR"><img src="https://github.com/XY-boy/SpikeSR/raw/main/fig/network.png" width="960" alt="SpikeSR architecture" /></a> | [arXiv](https://arxiv.org/abs/2503.04223) · [PDF](https://arxiv.org/pdf/2503.04223) · [HTML](https://arxiv.org/html/2503.04223) · [GitHub](https://github.com/XY-boy/SpikeSR) |

---

## Benchmarks & Datasets

| Resource | Used for | Related Methods |
|---|---|---|
| **BSD68 / Set12 / CIFAR10** | Image denoising and reconstruction | SPIDEN, VTSNN, SpikerIR |
| **Rain12 / Rain200L / Rain200H / Rain1200** | Single-image deraining | ESDNet, VLIF, SpikeRain, SPWM |
| **SOTS / Dense-Haze / RESIDE / UIEB / EUVP** | Natural and underwater image dehazing | RI-SCNN, DehazeSNN, snnTrans-DHZ, SpikingIR, SPWM |
| **Set5 / Urban100** | Image super-resolution | SpikingIR |
| **LOL-v1 / SDSD** | Low-light image enhancement | Spike-RetinexFormer |
| **AID / DOTA / DIOR** | Remote sensing super-resolution | SpikeSR |
| **StereoWaterdrop and stereo restoration sets** | Stereo raindrop removal, deraining, low-light enhancement, and super-resolution | SNNSIR |

---

## Toolboxes & Platforms

### SNN Frameworks

- **[SpikingJelly](https://github.com/fangwei123456/spikingjelly)** — deep-learning framework for SNN simulation and training.
- **[snnTorch](https://github.com/jeshraghian/snntorch)** — PyTorch-based spiking neural network library.
- **[Norse](https://github.com/norse/norse)** — deep-learning library for spiking neural networks.
- **[Lava](https://github.com/lava-nc/lava)** — neuromorphic computing framework from Intel Labs.

### Restoration Codebases

- **[ESDNet](https://github.com/MingTian99/ESDNet)** — efficient SNN-based image deraining.
- **[VLIF](https://github.com/ChrisChen1023/VLIF)** — visual-LIF neurons for image deraining.
- **[SpikeRain](https://github.com/tanvirnwu/SpikeRain_WACV_2025)** — energy-efficient single-image deraining.
- **[SpikeSR](https://github.com/XY-boy/SpikeSR)** — attention-based SNN for remote sensing super-resolution.
- **[DehazeSNN](https://github.com/HaoranLiu507/DehazeSNN)** — U-Net-like SNN for single-image dehazing.
- **[VTSNN](https://github.com/bollossom/VTSNN)** — virtual-temporal SNN for image reconstruction and denoising.

---

## Contributing

- Add papers or resources to the proper section.
- Prefer official proceedings, arXiv, project pages, and author repositories.
- Keep the three-column paper format consistent.
- Label unaccepted submissions as **Preprint**, not as conference papers.
- Only include work that clearly uses SNN computation to solve an image restoration task.

If you find this repository useful, please consider giving it a star ⭐.

## License

This curated list is released under the [MIT License](LICENSE).
