# Awesome Visual Autoregressive Modeling

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![GitHub stars](https://img.shields.io/github/stars/XIANGLONGYAN/Awesome-Visual-Autoregressive-Modeling?style=social)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)
![Paper Count](https://img.shields.io/badge/papers-60+-blue)
![Last Updated](https://img.shields.io/badge/last%20updated-2026.03-orange)

A curated collection of papers on **Visual Autoregressive (VAR) modeling**, covering the *next-scale prediction* paradigm for autoregressive visual generation. Papers are organized both **by venue/year** and **by research topic**.

> **What is VAR?**
> Visual AutoRegressive modeling ([VAR, NeurIPS 2024](https://arxiv.org/abs/2404.02905)) reformulates image generation as **next-scale prediction** rather than next-token prediction. A multi-scale token-map sequence (coarse → fine) is generated autoregressively, enabling GPT-like scaling laws for image synthesis. This repository tracks the growing ecosystem of work built on or inspired by this paradigm.

---

## Table of Contents

- [Papers by Venue](#papers-by-venue)
  - [Conference Papers](#conference-papers)
    - [2026](#2026)
    - [2025](#2025)
    - [2024](#2024)
  - [arXiv Preprints](#arxiv-preprints)
- [Papers by Topic](#papers-by-topic)
  - [Image Generation](#image-generation)
  - [Image Restoration & Super-Resolution](#image-restoration--super-resolution)
  - [Efficiency & Acceleration](#efficiency--acceleration)
  - [Quantization & Compression](#quantization--compression)
  - [Controllable & Guided Generation](#controllable--guided-generation)
  - [Video, 3D & Multi-modal](#video-3d--multi-modal)
  - [Dense Prediction (Depth, Segmentation)](#dense-prediction-depth-segmentation)
  - [Safety & Watermarking](#safety--watermarking)
  - [Theory & Analysis](#theory--analysis)
- [Contributing](#contributing)
- [Star History](#star-history)

---

## Papers by Venue

### Conference Papers

#### 2026

| Venue | Paper | Code |
|-------|-------|------|
| ICLR 2026 | [SkipVAR: Accelerating Visual Autoregressive Modeling via Adaptive Frequency-Aware Skipping](https://arxiv.org/abs/2506.08908) `efficiency` | [![GitHub stars](https://img.shields.io/github/stars/fakerone-li/SkipVAR?style=social)](https://github.com/fakerone-li/SkipVAR) |
| ICLR 2026 | [MVAR: Visual Autoregressive Modeling with Scale and Spatial Markovian Conditioning](https://arxiv.org/abs/2505.12742) `generation` | [![GitHub stars](https://img.shields.io/github/stars/LabShuHangGU/MVAR?style=social)](https://github.com/LabShuHangGU/MVAR) |
| ICLR 2026 | [Visual Autoregressive Modeling for Instruction-Guided Image Editing](https://arxiv.org/abs/2508.15772) `editing` | [![GitHub stars](https://img.shields.io/github/stars/HiDream-ai/VAREdit?style=social)](https://github.com/HiDream-ai/VAREdit) |
| ICLR 2026 | [Closing the Safety Gap: Surgical Concept Erasure in Visual Autoregressive Models](https://arxiv.org/abs/2509.22400) `safety` | — |
| ICLR 2026 | [ToProVAR: Efficient Visual Autoregressive Modeling via Tri-Dimensional Entropy-Aware Semantic Analysis and Sparsity Optimization](https://openreview.net/forum?id=s1djcQx3Ak) `efficiency` | — |
| ICLR 2026 | [Autoregressive Visual Decoding from EEG Signals](https://openreview.net/forum?id=TKjfzuVLX4) `multimodal` | — |
| ICLR 2026 | [Shift-and-Sum Quantization for Visual Autoregressive Models](https://openreview.net/forum?id=DAZvMAlZRp) `quantization` | — |
| ICLR 2026 | [SSG: Scaled Spatial Guidance for Multi-Scale Visual Autoregressive Generation](https://www.arxiv.org/abs/2602.05534) `generation` | [![GitHub stars](https://img.shields.io/github/stars/Youngwoo-git/SSG?style=social)](https://github.com/Youngwoo-git/SSG) |
| ICLR 2026 | [PTQ4ARVG: Post-Training Quantization for AutoRegressive Visual Generation Models](https://arxiv.org/abs/2409.17020) `quantization` | [![GitHub stars](https://img.shields.io/github/stars/gugu511yy/PTQ4RIS?style=social)](https://github.com/gugu511yy/PTQ4RIS) |
| ICLR 2026 | [RestoreVAR: Visual Autoregressive Generation for All-in-One Image Restoration](https://arxiv.org/abs/2505.18047) `restoration` | — |
| ICLR 2026 | [Your VAR Model is Secretly an Efficient and Explainable Generative Classifier](https://arxiv.org/abs/2510.12060) `theory` | — |
| ICLR 2026 | [VARestorer: One-Step VAR Distillation for Real-World Image Super-Resolution](https://openreview.net/forum?id=T2Oihh7zN8) `restoration` | — |
| AAAI 2026 | [AMS-KV: Adaptive KV Caching in Multi-Scale Visual Autoregressive Transformers](https://arxiv.org/abs/2511.16047) `efficiency` | — |

#### 2025

| Venue | Paper | Code |
|-------|-------|------|
| CVPR 2025 | [Navigating Image Restoration with VAR's Distribution Alignment Prior (VARFormer)](https://arxiv.org/abs/2412.21063) `restoration` | [![GitHub stars](https://img.shields.io/github/stars/siywang541/Varformer?style=social)](https://github.com/siywang541/Varformer) |
| CVPR 2025 | [Scalable Autoregressive Monocular Depth Estimation](https://arxiv.org/abs/2411.11361) `depth` | — |
| CVPR 2025 | [Infinity ∞: Scaling Bitwise AutoRegressive Modeling for High-Resolution Image Synthesis](https://arxiv.org/abs/2412.04431) `generation` | [![GitHub stars](https://img.shields.io/github/stars/FoundationVision/Infinity?style=social)](https://github.com/FoundationVision/Infinity) |
| CVPR 2025 | [Collaborative Decoding Makes Visual Auto-Regressive Modeling Efficient (CoDe)](https://arxiv.org/abs/2411.17787) `efficiency` | [![GitHub stars](https://img.shields.io/github/stars/czg1225/CoDe?style=social)](https://github.com/czg1225/CoDe) |
| ICLR 2025 | [HART: Efficient Visual Generation with Hybrid Autoregressive Transformer](https://arxiv.org/abs/2410.10812) `generation` `efficiency` | [![GitHub stars](https://img.shields.io/github/stars/mit-han-lab/hart?style=social)](https://github.com/mit-han-lab/hart) |
| ICML 2025 | [Continuous Visual Autoregressive Generation via Score Maximization (EAR)](https://arxiv.org/abs/2505.07812) `generation` | [![GitHub stars](https://img.shields.io/github/stars/shaochenze/EAR?style=social)](https://github.com/shaochenze/EAR) |
| ICML 2025 | [Visual Autoregressive Modeling for Image Super-Resolution (VARSR)](https://arxiv.org/abs/2501.18993) `restoration` | [![GitHub stars](https://img.shields.io/github/stars/quyp2000/VARSR?style=social)](https://github.com/quyp2000/VARSR) |
| ICML 2025 | [Fundamental Limits of Visual Autoregressive Transformers: Universal Approximation Abilities](https://arxiv.org/abs/2502.06167) `theory` | — |
| ICML 2025 | [FlowAR: Scale-wise Autoregressive Image Generation Meets Flow Matching](https://arxiv.org/abs/2412.15205) `generation` | [![GitHub stars](https://img.shields.io/github/stars/OliverRensu/FlowAR?style=social)](https://github.com/OliverRensu/FlowAR) |
| ICCV 2025 | [Frequency-Aware Autoregressive Modeling for Efficient High-Resolution Image Synthesis (SparseVAR)](https://arxiv.org/abs/2507.20454) `efficiency` | [![GitHub stars](https://img.shields.io/github/stars/Caesarhhh/SparseVAR?style=social)](https://github.com/Caesarhhh/SparseVAR) |
| ICCV 2025 | [Neighboring Autoregressive Modeling for Efficient Visual Generation (NAR)](https://arxiv.org/abs/2503.10696) `efficiency` | [![GitHub stars](https://img.shields.io/github/stars/ThisisBillhe/NAR?style=social)](https://github.com/ThisisBillhe/NAR) |
| ICCV 2025 | [CSD-VAR: Content-Style Decomposition in Visual Autoregressive Models](https://arxiv.org/abs/2507.13984) `generation` | — |
| ICCV 2025 | [FastVAR: Linear Visual Autoregressive Modeling via Cached Token Pruning](https://arxiv.org/abs/2503.23367) `efficiency` | [![GitHub stars](https://img.shields.io/github/stars/csguoh/FastVAR?style=social)](https://github.com/csguoh/FastVAR) |
| ICCV 2025 | [Conditional Visual Autoregressive Modeling for Pathological Image Restoration (CVARPath)](https://openaccess.thecvf.com/content/ICCV2025/papers/Liu_Conditional_Visual_Autoregressive_Modeling_for_Pathological_Image_Restoration_ICCV_2025_paper.pdf) `restoration` | [![GitHub stars](https://img.shields.io/github/stars/ziniBRC/CVARPath?style=social)](https://github.com/ziniBRC/CVARPath) |
| ICCV 2025 | [Training-Free Text-Guided Image Editing with Visual Autoregressive Model (AREdit)](https://arxiv.org/abs/2503.23897) `editing` | [![GitHub stars](https://img.shields.io/github/stars/wyf0912/AREdit?style=social)](https://github.com/wyf0912/AREdit) |
| ICCV 2025 | [CycleVAR: Repurposing Autoregressive Model for Unsupervised One-Step Image Translation](https://arxiv.org/abs/2506.23347) `generation` | [![GitHub stars](https://img.shields.io/github/stars/IamCreateAI/CycleVAR?style=social)](https://github.com/IamCreateAI/CycleVAR) |
| NeurIPS 2025 | [FlexVAR: Flexible Visual Autoregressive Modeling without Residual Prediction](https://arxiv.org/abs/2502.20313) `generation` | [![GitHub stars](https://img.shields.io/github/stars/jiaosiyu1999/FlexVAR?style=social)](https://github.com/jiaosiyu1999/FlexVAR) |
| NeurIPS 2025 | [Seg-VAR: Image Segmentation with Visual Autoregressive Modeling](https://arxiv.org/pdf/2511.12594v1) `segmentation` | [![GitHub stars](https://img.shields.io/github/stars/rkzheng99/Seg-VAR?style=social)](https://github.com/rkzheng99/Seg-VAR) |
| NeurIPS 2025 | [InfinityStar: Unified Spacetime AutoRegressive Modeling for Visual Generation](https://arxiv.org/abs/2511.04675) `video` | [![GitHub stars](https://img.shields.io/github/stars/FoundationVision/InfinityStar?style=social)](https://github.com/FoundationVision/InfinityStar) |
| NeurIPS 2025 | [FreqExit: Enabling Early-Exit Inference for Visual Autoregressive Models via Frequency-Aware Guidance](https://openreview.net/pdf?id=DUlZTgLkeh) `efficiency` | [![GitHub stars](https://img.shields.io/github/stars/NeuraLiying/FreqExit?style=social)](https://github.com/NeuraLiying/FreqExit) |
| NeurIPS 2025 | [Memory-Efficient Visual Autoregressive Modeling with Scale-Aware KV Cache Compression (ScaleKV)](https://arxiv.org/abs/2505.19602) `efficiency` | [![GitHub stars](https://img.shields.io/github/stars/StargazerX0/ScaleKV?style=social)](https://github.com/StargazerX0/ScaleKV) |
| NeurIPS 2025 | [EditInfinity: Image Editing with Binary-Quantized Generative Models](https://arxiv.org/abs/2510.20217) `editing` `quantization` | [![GitHub stars](https://img.shields.io/github/stars/yx-chen-ust/EditInfinity?style=social)](https://github.com/yx-chen-ust/EditInfinity) |
| NeurIPS 2025 Workshop | [LiteVAR: Compressing Visual Autoregressive Modelling with Efficient Attention and Quantization](https://arxiv.org/abs/2411.17178) `efficiency` `quantization` | — |
| TII 2025 | [VarAD: Lightweight High-Resolution Image Anomaly Detection via Visual Autoregressive Modeling](https://arxiv.org/abs/2412.17263) `detection` | [![GitHub stars](https://img.shields.io/github/stars/caoyunkang/VarAD?style=social)](https://github.com/caoyunkang/VarAD) |

#### 2024

| Venue | Paper | Code |
|-------|-------|------|
| NeurIPS 2024 | [Visual Autoregressive Modeling: Scalable Image Generation via Next-Scale Prediction](https://arxiv.org/abs/2404.02905) ⭐ *Foundational Work* `generation` | [![GitHub stars](https://img.shields.io/github/stars/FoundationVision/VAR?style=social)](https://github.com/FoundationVision/VAR) |

---

### arXiv Preprints

> Papers sorted roughly by recency. Papers that have been accepted to a venue are listed only under that venue above.

| Date | Paper | Code |
|------|-------|------|
| 2602 | [SparVAR: Exploring Sparsity in Visual AutoRegressive Modeling for Training-Free Acceleration](https://arxiv.org/abs/2602.04361) `efficiency` | [![GitHub stars](https://img.shields.io/github/stars/CAS-CLab/SparVAR?style=social)](https://github.com/CAS-CLab/SparVAR) |
| 2601 | [VAR RL Done Right: Tackling Asynchronous Policy Conflicts in Visual Autoregressive Generation](https://arxiv.org/abs/2601.02256) `generation` | [![GitHub stars](https://img.shields.io/github/stars/ByteVisionLab/NextFlow?style=social)](https://github.com/ByteVisionLab/NextFlow) |
| 2601 | [NextFlow: Unified Sequential Modeling Activates Multimodal Understanding and Generation](https://arxiv.org/abs/2601.02204) `multimodal` | [![GitHub stars](https://img.shields.io/github/stars/ByteVisionLab/NextFlow?style=social)](https://github.com/ByteVisionLab/NextFlow) |
| 2510 | [Visual Autoregressive Models Beat Diffusion Models on Inference Time Scaling](https://arxiv.org/abs/2510.16751) `theory` | — |
| 2510 | [Dynamic Mixture-of-Experts for Visual Autoregressive Model](https://arxiv.org/abs/2510.08629) `efficiency` | — |
| 2510 | [SoftCFG: Uncertainty-guided Stable Guidance for Visual Autoregressive Model](https://arxiv.org/abs/2510.00996) `generation` | — |
| 2509 | [Scale-Wise VAR is Secretly Discrete Diffusion](https://arxiv.org/abs/2509.22636) `theory` | — |
| 2509 | [Not All Tokens are Guided Equal: Improving Guidance in Visual Autoregressive Models](https://arxiv.org/abs/2509.23876) `generation` | — |
| 2509 | [Safe-VAR: Safe Visual Autoregressive Model for Text-to-Image Generative Watermarking](https://arxiv.org/abs/2503.11324) `safety` | — |
| 2507 | [TTS-VAR: A Test-Time Scaling Framework for Visual Auto-Regressive Generation](https://arxiv.org/abs/2507.18537) `efficiency` | [![GitHub stars](https://img.shields.io/github/stars/ali-vilab/TTS-VAR?style=social)](https://github.com/ali-vilab/TTS-VAR) |
| 2503 | [Visual Autoregressive Transformers Must Use Memory](https://arxiv.org/abs/2503.14881) `theory` | — |
| 2502 | [Generative Autoregressive Transformers for Model-Agnostic Federated MRI Reconstruction](https://arxiv.org/abs/2502.04521) `medical` | — |
| 2501 | [VARGPT: Unified Understanding and Generation in a Visual Autoregressive Multimodal Large Language Model](https://arxiv.org/abs/2501.12327) `multimodal` | — |
| 2501 | [Circuit Complexity Bounds for Visual Autoregressive Model](https://arxiv.org/abs/2501.04299) `theory` | — |
| 2512 | [Designing Scale-Wise Transformers for Text-to-Image Synthesis](https://arxiv.org/abs/2412.01819) `generation` | — |
| 2512 | [StageVAR: Stage-Aware Acceleration for Visual Autoregressive Models](https://arxiv.org/abs/2512.16483) `efficiency` | [![GitHub stars](https://img.shields.io/github/stars/sen-mao/StageVAR?style=social)](https://github.com/sen-mao/StageVAR) |
| 2512 | [LSRS: Latent Scale Rejection Sampling for Visual Autoregressive Modeling](https://arxiv.org/abs/2512.03796) `generation` | [![GitHub stars](https://img.shields.io/github/stars/dt-3t/LSRS?style=social)](https://github.com/dt-3t/LSRS) |
| 2511 | [FVAR: Visual Autoregressive Modeling via Next Focus Prediction](https://arxiv.org/abs/2511.18838) `generation` | — |
| 2511 | [Progressive Supernet Training for Efficient Visual Autoregressive Modeling (VARiant)](https://arxiv.org/abs/2511.16546) `efficiency` | [![GitHub stars](https://img.shields.io/github/stars/Nola-chen/VARiant?style=social)](https://github.com/Nola-chen/VARiant) |
| 2411 | [SAR3D: Autoregressive 3D Object Generation and Understanding via Multi-scale 3D VQVAE](https://arxiv.org/abs/2411.16856) `3d` | — |
| 2410 | [CAR: Controllable Autoregressive Modeling for Visual Generation](https://arxiv.org/abs/2410.04671) `controllable` | [![GitHub stars](https://img.shields.io/github/stars/MiracleDance/CAR?style=social)](https://github.com/MiracleDance/CAR) |
| 2409 | [DepthART: Monocular Depth Estimation as Autoregressive Refinement Task](https://arxiv.org/abs/2409.15010) `depth` | — |
| 2409 | [G3PT: Unleash the power of Autoregressive Modeling in 3D Generation via Cross-scale Querying Transformer](https://arxiv.org/abs/2409.06322) `3d` | — |
| 2408 | [VAR-CLIP: Text-to-Image Generator with Visual Auto-Regressive Modeling](https://arxiv.org/abs/2408.01181) `generation` `controllable` | [![GitHub stars](https://img.shields.io/github/stars/daixiangzi/VAR-CLIP?style=social)](https://github.com/daixiangzi/VAR-CLIP) |
| 2406 | [ControlVAR: Exploring Controllable Visual Autoregressive Modeling](https://arxiv.org/abs/2406.09750) `controllable` | [![GitHub stars](https://img.shields.io/github/stars/lxa9867/ControlVAR?style=social)](https://github.com/lxa9867/ControlVAR) |
| 2406 | [STAR: Scale-wise Text-to-image generation via Auto-Regressive representations](https://arxiv.org/abs/2406.10797) `generation` `controllable` | [![GitHub stars](https://img.shields.io/github/stars/Davinci-XLab/STAR-T2I?style=social)](https://github.com/Davinci-XLab/STAR-T2I) |
| — | [MVP: Multi-scale Visual Prompt for Visual AutoRegressive Generation](https://openreview.net/forum?id=ARlWghTilp) `generation` | — |

---

## Papers by Topic

> Each paper links back to its primary listing above. Topics are not mutually exclusive.

### Image Generation

Core VAR-based image generation methods.

- [VAR](https://arxiv.org/abs/2404.02905) ⭐ NeurIPS 2024 — Foundational next-scale prediction framework
- [Infinity ∞](https://arxiv.org/abs/2412.04431) CVPR 2025 — Bitwise AR for high-resolution synthesis
- [HART](https://arxiv.org/abs/2410.10812) ICLR 2025 — Hybrid AR transformer
- [FlowAR](https://arxiv.org/abs/2412.15205) ICML 2025 — Scale-wise AR meets flow matching
- [EAR](https://arxiv.org/abs/2505.07812) ICML 2025 — Continuous generation via score maximization
- [FlexVAR](https://arxiv.org/abs/2502.20313) NeurIPS 2025 — Without residual prediction
- [MVAR](https://arxiv.org/abs/2505.12742) ICLR 2026 — Markovian scale & spatial conditioning
- [SSG](https://www.arxiv.org/abs/2602.05534) ICLR 2026 — Scaled spatial guidance
- [CSD-VAR](https://arxiv.org/abs/2507.13984) ICCV 2025 — Content-style decomposition
- [CycleVAR](https://arxiv.org/abs/2506.23347) ICCV 2025 — Unsupervised image translation
- [FVAR](https://arxiv.org/abs/2511.18838) arXiv — Next focus prediction
- [LSRS](https://arxiv.org/abs/2512.03796) arXiv — Latent scale rejection sampling
- [STAR](https://arxiv.org/abs/2406.10797) arXiv — Scale-wise text-to-image
- [VAR-CLIP](https://arxiv.org/abs/2408.01181) arXiv — Text-to-image with CLIP
- [Designing Scale-Wise Transformers](https://arxiv.org/abs/2412.01819) arXiv — Architecture study
- [MVP](https://openreview.net/forum?id=ARlWghTilp) arXiv — Multi-scale visual prompts

### Image Restoration & Super-Resolution

- [VARFormer](https://arxiv.org/abs/2412.21063) CVPR 2025 — Distribution alignment prior for restoration
- [VARSR](https://arxiv.org/abs/2501.18993) ICML 2025 — Image super-resolution
- [CVARPath](https://openaccess.thecvf.com/content/ICCV2025/papers/Liu_Conditional_Visual_Autoregressive_Modeling_for_Pathological_Image_Restoration_ICCV_2025_paper.pdf) ICCV 2025 — Pathological image restoration
- [RestoreVAR](https://arxiv.org/abs/2505.18047) ICLR 2026 — All-in-one image restoration
- [VARestorer](https://openreview.net/forum?id=T2Oihh7zN8) ICLR 2026 — One-step distillation for super-resolution
- [Federated MRI Reconstruction](https://arxiv.org/abs/2502.04521) arXiv — Medical imaging

### Efficiency & Acceleration

Token pruning, caching, early-exit, and sparsity approaches.

- [CoDe](https://arxiv.org/abs/2411.17787) CVPR 2025 — Collaborative decoding
- [HART](https://arxiv.org/abs/2410.10812) ICLR 2025 — Hybrid AR with efficient design
- [FastVAR](https://arxiv.org/abs/2503.23367) ICCV 2025 — Cached token pruning
- [NAR](https://arxiv.org/abs/2503.10696) ICCV 2025 — Neighboring AR modeling
- [SparseVAR](https://arxiv.org/abs/2507.20454) ICCV 2025 — Frequency-aware sparse generation
- [FreqExit](https://openreview.net/pdf?id=DUlZTgLkeh) NeurIPS 2025 — Early-exit inference
- [ScaleKV](https://arxiv.org/abs/2505.19602) NeurIPS 2025 — KV cache compression
- [LiteVAR](https://arxiv.org/abs/2411.17178) NeurIPS 2025 Workshop — Efficient attention + quantization
- [SkipVAR](https://arxiv.org/abs/2506.08908) ICLR 2026 — Adaptive frequency-aware skipping
- [ToProVAR](https://openreview.net/forum?id=s1djcQx3Ak) ICLR 2026 — Entropy-aware sparsity
- [AMS-KV](https://arxiv.org/abs/2511.16047) AAAI 2026 — Adaptive KV caching
- [StageVAR](https://arxiv.org/abs/2512.16483) arXiv — Stage-aware acceleration
- [VARiant](https://arxiv.org/abs/2511.16546) arXiv — Progressive supernet training
- [SparVAR](https://arxiv.org/abs/2602.04361) arXiv — Sparsity for training-free acceleration
- [TTS-VAR](https://arxiv.org/abs/2507.18537) arXiv — Test-time scaling
- [Dynamic MoE](https://arxiv.org/abs/2510.08629) arXiv — Mixture-of-experts for VAR

### Quantization & Compression

- [PTQ4ARVG](https://arxiv.org/abs/2409.17020) ICLR 2026 — Post-training quantization
- [Shift-and-Sum Quantization](https://openreview.net/forum?id=DAZvMAlZRp) ICLR 2026 — Hardware-friendly binarization
- [EditInfinity](https://arxiv.org/abs/2510.20217) NeurIPS 2025 — Editing with binary-quantized models
- [LiteVAR](https://arxiv.org/abs/2411.17178) NeurIPS 2025 Workshop — Attention + quantization
- [AMS-KV](https://arxiv.org/abs/2511.16047) AAAI 2026 — Adaptive KV caching

### Controllable & Guided Generation

- [ControlVAR](https://arxiv.org/abs/2406.09750) arXiv — Controllable VAR
- [CAR](https://arxiv.org/abs/2410.04671) arXiv — Controllable AR generation
- [VAREdit](https://arxiv.org/abs/2508.15772) ICLR 2026 — Instruction-guided editing
- [AREdit](https://arxiv.org/abs/2503.23897) ICCV 2025 — Training-free text-guided editing
- [CycleVAR](https://arxiv.org/abs/2506.23347) ICCV 2025 — Image-to-image translation
- [SoftCFG](https://arxiv.org/abs/2510.00996) arXiv — Uncertainty-guided CFG
- [Not All Tokens Equal](https://arxiv.org/abs/2509.23876) arXiv — Improved guidance
- [VAR-CLIP](https://arxiv.org/abs/2408.01181) arXiv — CLIP-conditioned generation
- [STAR](https://arxiv.org/abs/2406.10797) arXiv — Text-to-image generation

### Video, 3D & Multi-modal

- [InfinityStar](https://arxiv.org/abs/2511.04675) NeurIPS 2025 — Unified spacetime AR generation
- [SAR3D](https://arxiv.org/abs/2411.16856) arXiv — 3D object generation
- [G3PT](https://arxiv.org/abs/2409.06322) arXiv — 3D generation via cross-scale querying
- [VARGPT](https://arxiv.org/abs/2501.12327) arXiv — Multimodal understanding + generation
- [NextFlow](https://arxiv.org/abs/2601.02204) arXiv — Unified sequential multimodal modeling
- [EEG Decoding](https://openreview.net/forum?id=TKjfzuVLX4) ICLR 2026 — Visual decoding from brain signals

### Dense Prediction (Depth, Segmentation)

- [Scalable Monocular Depth](https://arxiv.org/abs/2411.11361) CVPR 2025
- [Seg-VAR](https://arxiv.org/pdf/2511.12594v1) NeurIPS 2025 — Image segmentation
- [DepthART](https://arxiv.org/abs/2409.15010) arXiv — Depth estimation as AR refinement
- [VarAD](https://arxiv.org/abs/2412.17263) TII 2025 — Anomaly detection

### Safety & Watermarking

- [Closing the Safety Gap](https://arxiv.org/abs/2509.22400) ICLR 2026 — Concept erasure
- [Safe-VAR](https://arxiv.org/abs/2503.11324) arXiv — Generative watermarking

### Theory & Analysis

- [VAR as Generative Classifier](https://arxiv.org/abs/2510.12060) ICLR 2026 — Implicit classification ability
- [Fundamental Limits](https://arxiv.org/abs/2502.06167) ICML 2025 — Universal approximation theory
- [Visual AR Beats Diffusion on Inference Scaling](https://arxiv.org/abs/2510.16751) arXiv
- [Visual AR Transformers Must Use Memory](https://arxiv.org/abs/2503.14881) arXiv
- [Scale-Wise VAR is Discrete Diffusion](https://arxiv.org/abs/2509.22636) arXiv — Connection to diffusion
- [Circuit Complexity Bounds](https://arxiv.org/abs/2501.04299) arXiv — Theoretical complexity analysis
- [VAR RL Done Right](https://arxiv.org/abs/2601.02256) arXiv — Reinforcement learning for VAR

---

## Contributing

Contributions are welcome! If you know of a paper that should be included:

1. **Fork** this repository
2. Add your paper entry following the existing format:
   ```
   | Venue Year | [Title](link) `topic-tag` | [![GitHub stars](...)](code-link) or — |
   ```
3. Place it under the correct venue/year section and add it to the relevant topic section(s)
4. Submit a **Pull Request** with a brief description

**Topic tags** currently in use:
`generation` `restoration` `efficiency` `quantization` `controllable` `editing` `video` `3d` `multimodal` `depth` `segmentation` `detection` `safety` `theory` `medical`

If you find a mistake (wrong venue, broken link, duplicate), please open an **Issue**.

---

## Star History

<a href="https://star-history.com/#XIANGLONGYAN/Awesome-Visual-Autoregressive-Modeling&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=XIANGLONGYAN/Awesome-Visual-Autoregressive-Modeling&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=XIANGLONGYAN/Awesome-Visual-Autoregressive-Modeling&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=XIANGLONGYAN/Awesome-Visual-Autoregressive-Modeling&type=Date" />
  </picture>
</a>


---

<p align="center">
  <i>If this repository is helpful to your research, please consider giving it a ⭐</i>
</p>
