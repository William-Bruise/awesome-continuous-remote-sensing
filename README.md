# Awesome Continuous Remote Sensing

A curated list of papers on **continuous representations for remote sensing and Earth observation**. The collection covers continuous modeling along spatial, spectral, temporal, geometric, viewing, and physical coordinates, including INR/function representations, tensor functions, neural operators, NeRF/implicit surfaces, and Gaussian Splatting.

The guiding view is that remote-sensing measurements are discrete, heterogeneous observations of underlying continuous or coupled Earth fields. This repository focuses on methods that explicitly model that continuity or provide important foundations, boundary cases, and sensing-aware context.

**Current collection:** 127 papers (119 Core + 8 Context) · 48 entries with verified project/code links · literature audit updated through **2026-09-26**.

> **Link policy:** `Paper` points to the publisher/DOI/project page recorded in the literature ledger. `Code` is shown only when an author/project code link was verified in the ledger; absence of a code link does **not** prove that no implementation exists.

## Contents

- [Surveys & Reviews](#surveys-reviews) (2)
- [Foundations — INR, Functional & Tensor Representations](#foundations-inr-functional-tensor-representations) (32)
- [Foundations — Neural Operators & Function Learning](#foundations-neural-operators-function-learning) (3)
- [Foundations — Continuous 3D Scene Representations](#foundations-continuous-3d-scene-representations) (8)
- [Spatial Continuous Modeling & Arbitrary-Scale Reconstruction](#spatial-continuous-modeling-arbitrary-scale-reconstruction) (5)
- [Spectral & Spatial-Spectral Continuous Modeling](#spectral-spatial-spectral-continuous-modeling) (23)
- [Temporal & Spatiotemporal Continuous EO](#temporal-spatiotemporal-continuous-eo) (4)
- [Continuous Physical & Geophysical Fields](#continuous-physical-geophysical-fields) (15)
- [NeRF, Implicit Surfaces & Continuous 3D Geometry](#nerf-implicit-surfaces-continuous-3d-geometry) (14)
- [Gaussian Splatting & Explicit Continuous 3D Fields](#gaussian-splatting-explicit-continuous-3d-fields) (19)
- [Continuous Geospatial Feature Fields](#continuous-geospatial-feature-fields) (1)
- [Sensor Modeling, Registration & Boundary Cases](#sensor-modeling-registration-boundary-cases) (1)

## Papers

### Surveys & Reviews

- **2017 · IEEE GRSM** — Hyperspectral and Multispectral Data Fusion: A Comparative Review of the Recent Literature — [Paper](https://ieeexplore.ieee.org/)
- **2015 · IEEE GRSM** — Hyperspectral Pansharpening: A Review — [Paper](https://ieeexplore.ieee.org/)

### Foundations — INR, Functional & Tensor Representations

- **2026 · IEEE TPAMI** — Learning Continuous Spatiotemporal Implicit Neural Fields for Unsupervised Video Denoising — [Paper](https://doi.org/10.1109/TPAMI.2026.3680159)
- **2025 · ICML** — Inductive Gradient Adjustment for Spectral Bias in Implicit Neural Representations — [Paper](https://proceedings.mlr.press/)
- **2025 · ICLR** — KAN: Kolmogorov-Arnold Networks — [Paper](https://openreview.net/forum?id=Ozo7qJ5vZi) · [Code](https://github.com/KindXiaoming/pykan)
- **2025 · ICLR** — PIN: Prolate Spheroidal Wave Function-Based Implicit Neural Representations — [Paper](https://openreview.net/forum?id=9lOnKSUjZq)
- **2025 · CVPR** — Preconditioners for the Stochastic Training of Neural Fields — [Paper](https://openaccess.thecvf.com/)
- **2025 · IEEE TPAMI** — Revisiting Nonlocal Self-Similarity from Continuous Representation — [Paper](https://pubmed.ncbi.nlm.nih.gov/39298302/)
- **2024 · IEEE TPAMI** — Disorder-Invariant Implicit Neural Representation — [Paper](https://doi.org/10.1109/TPAMI.2024.3366408)
- **2024 · CVPR** — DS-NeRV: Implicit Neural Video Representation with Decomposed Static and Dynamic Codes — [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Yan_DS-NeRV_Implicit_Neural_Video_Representation_with_Decomposed_Static_and_Dynamic_Codes_CVPR_2024_paper.html)
- **2024 · CVPR** — FINER: Flexible Spectral Bias Tuning in Implicit Neural Representation by Variable-Periodic Activation Functions — [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Liu_FINER_Flexible_Spectral_Bias_Tuning_in_Implicit_Neural_Representation_by_CVPR_2024_paper.html) · [Code](https://github.com/liuzhen0212/FINER)
- **2024 · ICLR** — Functional Bayesian Tucker Decomposition for Continuous-Indexed Tensor Data — [Paper](https://openreview.net/forum?id=9J7dnjcDKR)
- **2024 · ICLR** — Implicit Neural Representations and the Algebra of Complex Wavelets — [Paper](https://openreview.net/forum?id=Dbf1sXXMmb)
- **2024 · CVPR** — Improved Implicit Neural Representation with Fourier Reparameterized Training — [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Shi_Improved_Implicit_Neural_Representation_with_Fourier_Reparameterized_Training_CVPR_2024_paper.html)
- **2024 · NeurIPS** — Learning Transferable Features for Implicit Neural Representations — [Paper](https://proceedings.neurips.cc/)
- **2024 · IEEE TPAMI** — Low-Rank Tensor Function Representation for Multi-Dimensional Data Recovery — [Paper](https://doi.org/10.1109/TPAMI.2023.3346024)
- **2024 · NeurIPS** — Neural Experts: Mixture of Experts for Implicit Neural Representations — [Paper](https://proceedings.neurips.cc/)
- **2024 · CVPR** — Neural Fields as Distributions: Signal Processing Beyond Euclidean Space — [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Rebain_Neural_Fields_as_Distributions_Signal_Processing_Beyond_Euclidean_Space_CVPR_2024_paper.html)
- **2024 · ICML** — Nonparametric Teaching of Implicit Neural Representations — [Paper](https://proceedings.mlr.press/)
- **2024 · ECCV** — Superpixel-Informed Implicit Neural Representation for Multi-Dimensional Data — [Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/5711_ECCV_2024_paper.php)
- **2023 · CVPR** — WIRE: Wavelet Implicit Neural Representations — [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Saragadam_WIRE_Wavelet_Implicit_Neural_Representations_CVPR_2023_paper.html) · [Code](https://github.com/vishwa91/wire)
- **2022 · CVPR** — A Structured Dictionary Perspective on Implicit Neural Representations — [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Yuce_A_Structured_Dictionary_Perspective_on_Implicit_Neural_Representations_CVPR_2022_paper.html)
- **2022 · ICLR** — CoordX: Accelerating Implicit Neural Representation with a Split MLP Architecture — [Paper](https://openreview.net/forum?id=mX0s1L6pQ0)
- **2022 · CVPR** — Direct Voxel Grid Optimization: Super-Fast Convergence for Radiance Fields Reconstruction — [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Sun_Direct_Voxel_Grid_Optimization_Super-Fast_Convergence_for_Radiance_Fields_Reconstruction_CVPR_2022_paper.html) · [Code](https://github.com/sunset1995/DirectVoxGO)
- **2022 · ACM TOG / SIGGRAPH** — Instant Neural Graphics Primitives with a Multiresolution Hash Encoding — [Paper](https://doi.org/10.1145/3528223.3530127) · [Code](https://github.com/NVlabs/instant-ngp)
- **2022 · ECCV** — MINER: Multiscale Implicit Neural Representation — [Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/118_ECCV_2022_paper.php)
- **2022 · NeurIPS** — Signal Processing for Implicit Neural Representations — [Paper](https://proceedings.neurips.cc/)
- **2022 · ECCV** — Transformers as Meta-Learners for Implicit Neural Representations — [Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/2012_ECCV_2022_paper.php)
- **2021 · CVPR** — Learning Continuous Image Representation with Local Implicit Image Function — [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Chen_Learning_Continuous_Image_Representation_With_Local_Implicit_Image_Function_CVPR_2021_paper.html) · [Code](https://github.com/yinboc/liif)
- **2021 · CVPR** — Learning Initializations for Optimizing Coordinate-Based Neural Representations — [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Tancik_Learned_Initializations_for_Optimizing_Coordinate-Based_Neural_Representations_CVPR_2021_paper.html)
- **2021 · ICLR** — Multiplicative Filter Networks — [Paper](https://openreview.net/forum?id=OmtmcPkkhT)
- **2021 · NeurIPS** — NeRV: Neural Representations for Videos — [Paper](https://proceedings.neurips.cc/paper/2021/hash/7f6ffaa6bb0b408017b62254211691b5-Abstract.html)
- **2020 · NeurIPS** — Fourier Features Let Networks Learn High Frequency Functions in Low Dimensional Domains — [Paper](https://proceedings.neurips.cc/paper/2020/hash/55053683268957697aa39fba6f231c68-Abstract.html) · [Code](https://github.com/tancik/fourier-feature-networks)
- **2020 · NeurIPS** — Implicit Neural Representations with Periodic Activation Functions — [Paper](https://proceedings.neurips.cc/paper/2020/hash/53c04118df112c13a8c34b38343b9c10-Abstract.html) · [Code](https://github.com/vsitzmann/siren)

### Foundations — Neural Operators & Function Learning

- **2024 · ICML** — Implicit Representations via Operator Learning — [Paper](https://proceedings.mlr.press/v235/pal24a.html)
- **2021 · Nature Machine Intelligence** — DeepONet: Learning nonlinear operators for identifying differential equations based on the universal approximation theorem of operators — [Paper](https://www.nature.com/articles/s42256-021-00302-5) · [Code](https://github.com/lululxvi/deeponet)
- **2021 · ICLR** — Fourier Neural Operator for Parametric Partial Differential Equations — [Paper](https://openreview.net/forum?id=c8P9NQVtmnO) · [Code](https://github.com/neuraloperator/neuraloperator)

### Foundations — Continuous 3D Scene Representations

- **2026 · CVPR** — Gaussian Splatting-based Low-Rank Tensor Representation for Multi-Dimensional Image Recovery — [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Zeng_Gaussian_Splatting-based_Low-Rank_Tensor_Representation_for_Multi-Dimensional_Image_Recovery_CVPR_2026_paper.html)
- **2023 · ACM TOG / SIGGRAPH** — 3D Gaussian Splatting for Real-Time Radiance Field Rendering — [Paper](https://doi.org/10.1145/3592433) · [Code](https://github.com/graphdeco-inria/gaussian-splatting)
- **2022 · CVPR** — Plenoxels: Radiance Fields without Neural Networks — [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Fridovich-Keil_Plenoxels_Radiance_Fields_Without_Neural_Networks_CVPR_2022_paper.html) · [Code](https://github.com/sxyu/svox2)
- **2022 · ECCV** — Tensorial Radiance Fields — [Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3156_ECCV_2022_paper.php) · [Code](https://github.com/apchenstu/TensoRF)
- **2021 · ICCV** — PlenOctrees for Real-time Rendering of Neural Radiance Fields — [Paper](https://openaccess.thecvf.com/content/ICCV2021/html/Yu_PlenOctrees_for_Real-Time_Rendering_of_Neural_Radiance_Fields_ICCV_2021_paper.html) · [Code](https://github.com/sxyu/plenoctree)
- **2020 · ECCV** — NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis — [Paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/1473_ECCV_2020_paper.php) · [Code](https://github.com/bmild/nerf)
- **2019 · CVPR** — DeepSDF: Learning Continuous Signed Distance Functions for Shape Representation — [Paper](https://openaccess.thecvf.com/content_CVPR_2019/html/Park_DeepSDF_Learning_Continuous_Signed_Distance_Functions_for_Shape_Representation_CVPR_2019_paper.html)
- **2019 · CVPR** — Occupancy Networks: Learning 3D Reconstruction in Function Space — [Paper](https://openaccess.thecvf.com/content_CVPR_2019/html/Mescheder_Occupancy_Networks_Learning_3D_Reconstruction_in_Function_Space_CVPR_2019_paper.html)

### Spatial Continuous Modeling & Arbitrary-Scale Reconstruction

- **2025 · IEEE TGRS** — Latent Diffusion, Implicit Amplification: Efficient Continuous-Scale Super-Resolution for Remote Sensing Images — [Paper](https://doi.org/10.1109/TGRS.2025.3571290) · [Code](https://github.com/MoooJianG/LDCSR)
- **2024 · ISPRS JPRS** — A Continuous Digital Elevation Representation Model for DEM Super-Resolution — [Paper](https://www.sciencedirect.com/science/article/pii/S0924271624000017)
- **2023 · IEEE TGRS** — Continuous Remote Sensing Image Super-Resolution Based on Context Interaction in Implicit Function Space — [Paper](https://arxiv.org/abs/2302.08046) · [Code](https://github.com/KyanChen/FunSR)
- **2023 · IEEE TGRS** — Learning Dynamic Scale Awareness and Global Implicit Functions for Continuous-Scale Super-Resolution of Remote Sensing Images — [Paper](https://ieeexplore.ieee.org/document/10026827/) · [Code](https://github.com/hanlinwu/SADN)
- **2023 · IEEE TGRS** — Lightweight Stepless Super-Resolution of Remote Sensing Images via Saliency-Aware Dynamic Routing Strategy — [Paper](https://doi.org/10.1109/TGRS.2023.3236624) · [Code](https://github.com/hanlinwu/SalDRN)

### Spectral & Spatial-Spectral Continuous Modeling

- **2026 · ISPRS JPRS** — DCMArb: Decoupled-Collaborative Mamba for Arbitrary-scale Hyperspectral Super-resolution — [Paper](https://doi.org/10.1016/j.isprsjprs.2026.06.009) · [Code](https://github.com/wangswhu/DCMArb)
- **2025 · Information Fusion** — A spatial-frequency dual-domain implicit guidance method for hyperspectral and multispectral remote sensing image fusion based on Kolmogorov–Arnold Network — [Paper](https://doi.org/10.1016/j.inffus.2025.103261) · [Code](https://github.com/chunyuzhu/SFIGNet)
- **2025 · IEEE TGRS** — Continuous Tensor Representation for Hyperspectral Anomaly Detection — [Paper](https://doi.org/10.1109/TGRS.2025.3593391) · [Code](https://github.com/Weihao-Wu/CBAR)
- **2025 · IEEE TGRS** — Mamba Collaborative Implicit Neural Representation for Hyperspectral and Multispectral Remote Sensing Image Fusion — [Paper](https://doi.org/10.1109/TGRS.2025.3537638) · [Code](https://github.com/chunyuzhu/MCIFNet)
- **2025 · IEEE TGRS** — Meta-Collaborative Learning for Arbitrarily Scaled Hyperspectral Image Super-Resolution — [Paper](https://doi.org/10.1109/TGRS.2025.3544253) · [Code](https://github.com/ShuangWu-XDU/MCArb_HSI_SR)
- **2025 · AAAI** — OTIAS: OcTree Implicit Adaptive Sampling for Multispectral and Hyperspectral Image Fusion — [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/32275) · [Code](https://github.com/shangqideng/OTIAS)
- **2024 · Int. J. Applied Earth Observation and Geoinformation** — An Implicit Transformer-based Fusion Method for Hyperspectral and Multispectral Remote Sensing Image — [Paper](https://doi.org/10.1016/j.jag.2024.103955)
- **2024 · IEEE TGRS** — Arbitrary-Scale Hyperspectral Image Super-Resolution From a Fusion Perspective With Spatial Priors — [Paper](https://doi.org/10.1109/TGRS.2024.3481041)
- **2024 · NeurIPS** — Fourier-Enhanced Implicit Neural Fusion Network for Multispectral and Hyperspectral Image Fusion — [Paper](https://mlanthology.org/neurips/2024/liang2024neurips-fourierenhanced/) · [Code](https://github.com/294coder/Efficient-MIF)
- **2024 · IEEE Transactions on Computational Imaging** — INF³: Implicit Neural Feature Fusion Function for Multispectral and Hyperspectral Image Fusion — [Paper](https://doi.org/10.1109/TCI.2024.3488569)
- **2024 · IEEE TGRS** — Nonnegative Matrix Functional Factorization for Hyperspectral Unmixing With Nonuniform Spectral Sampling — [Paper](https://doi.org/10.1109/TGRS.2023.3347414)
- **2024 · AAAI** — Progressive High-Frequency Reconstruction for Pan-Sharpening with Implicit Neural Representation — [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/28214)
- **2024 · IEEE TCSVT** — Spectral-Wise Implicit Neural Representation for Hyperspectral Image Reconstruction — [Paper](https://doi.org/10.1109/TCSVT.2023.3318366)
- **2023 · Int. J. Applied Earth Observation and Geoinformation** — An adaptive multi-perceptual implicit sampling for hyperspectral and multispectral remote sensing image fusion — [Paper](https://doi.org/10.1016/j.jag.2023.103560) · [Code](https://github.com/chunyuzhu/AMGSGAN)
- **2023 · IEEE TGRS** — Implicit Neural Representation Learning for Hyperspectral Image Super-Resolution — [Paper](https://github.com/kaviezhang/INR-HSISR) · [Code](https://github.com/kaviezhang/INR-HSISR)
- **2023 · IEEE TGRS** — QIS-GAN: A Lightweight Adversarial Network With Quadtree Implicit Sampling for Multispectral and Hyperspectral Image Fusion — [Paper](https://doi.org/10.1109/TGRS.2023.3332176) · [Code](https://github.com/chunyuzhu/QIS-GAN)
- **2023 · IEEE TGRS** — SS-INR: Spatial-Spectral Implicit Neural Representation Network for Hyperspectral and Multispectral Image Fusion — [Paper](https://github.com/wxy11-27/SS-INR) · [Code](https://github.com/wxy11-27/SS-INR)
- **2021 · IEEE TGRS** — Unsupervised and Unregistered Hyperspectral Image Super-Resolution With Mutual Dirichlet-Net — [Paper](https://ieeexplore.ieee.org/)
- **2020 · IEEE TIP** — Super-Resolution for Hyperspectral and Multispectral Image Fusion Accounting for Seasonal Spectral Variability — [Paper](https://ieeexplore.ieee.org/document/8768351)
- **2019 · IEEE TGRS** — An Integrated Approach to Registration and Fusion of Hyperspectral and Multispectral Images — [Paper](https://ieeexplore.ieee.org/)
- **2019 · ICCV** — Deep Blind Hyperspectral Image Fusion — [Paper](https://openaccess.thecvf.com/content_ICCV_2019/html/Wang_Deep_Blind_Hyperspectral_Image_Fusion_ICCV_2019_paper.html)
- **2015 · IEEE TGRS** — Hyperspectral and Multispectral Image Fusion Based on a Sparse Representation — [Paper](https://arxiv.org/abs/1409.5729)
- **2015 · IEEE TGRS** — HySure: A Convex Formulation for Hyperspectral Image Superresolution via Subspace-Based Regularization — [Paper](https://arxiv.org/abs/1411.4005) · [Code](https://github.com/alfaiate/HySure)

### Temporal & Spatiotemporal Continuous EO

- **2026 · CVPR EarthVision Workshop** — Location Is All You Need: Continuous Spatiotemporal Neural Representations of Earth Observation Data — [Paper](https://arxiv.org/abs/2604.07092) · [Code](https://github.com/mojganmadadi/LIANet/tree/v1.0.1) · `Context`
- **2026 · IEEE TGRS** — Neural Operator-Based Continuous Tensor Representation for Thick Cloud Removal in Multiresolution Remote Sensing Images — [Paper](https://eurekamag.com/research/110/713/110713554.php)
- **2025 · IEEE TGRS** — A Unified Sentinel-2 Imagery Thick Cloud Removal and Rescaling Framework From a Continuous Perspective — [Paper](https://doi.org/10.1109/TGRS.2025.3609321)
- **2025 · ISPRS JPRS** — Streamlined Multilayer Perceptron for Contaminated Time Series Reconstruction: A Case Study in Coastal Zones of Southern China — [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0924271625000401)

### Continuous Physical & Geophysical Fields

- **2026 · Geoscientific Model Development** — A continuous implicit neural representation framework with gradient regularization for sea surface height reconstruction from satellite altimetry — [Paper](https://doi.org/10.5194/gmd-19-7349-2026) · [Code](https://doi.org/10.5281/zenodo.21232682) · `Context`
- **2026 · IEEE TGRS** — A Generalized Eikonal Solver Using Operator Learning — [Paper](https://doi.org/10.1109/TGRS.2026.3674885)
- **2026 · IEEE TGRS** — Adaptive Neural Operator for Arbitrary-Scale Asteroid Remote Sensing Image Super-Resolution With Unsupervised and Supervised Learning — [Paper](https://doi.org/10.1109/TGRS.2026.3699589)
- **2026 · IEEE TGRS** — Height-Aware Fourier Neural Operator for Near-Space Short-Term Wind Field Prediction: A Systematic Neural Operator Benchmark — [Paper](https://doi.org/10.1109/TGRS.2026.3724650)
- **2026 · Nature Communications** — Microseismic monitoring with the quake neural operator — [Paper](https://doi.org/10.1038/s41467-026-73965-6) · [Code](https://zenodo.org/records/20072888)
- **2026 · IEEE TGRS** — Rapid 2-D Magnetotelluric Forward Modeling via Automatic Differentiation Fourier Neural Operator With Gradient Supervision — [Paper](https://doi.org/10.1109/TGRS.2026.3701700)
- **2026 · IEEE TGRS** — Seamless Daily XCO2 Mapping Across China with Transformer and Geo Implicit Neural Representation — [Paper](https://eurekamag.com/research/110/669/110669089.php)
- **2026 · IEEE TGRS** — Spatiotemporal Implicit Neural Representation for Ionospheric Tomography With Multi-LEO Occultation Data — [Paper](https://www.mindat.org/reference.php?id=19514502)
- **2026 · ICLR** — Unveiling the Mechanism of Continuous Representation Full-Waveform Inversion: A Wave-Based Neural Tangent Kernel Framework — [Paper](https://openreview.net/)
- **2025 · IEEE TGRS** — A Feature Enhanced Autoencoder Integrated With Fourier Neural Operator for Intelligent Elastic Wavefield Modeling — [Paper](https://doi.org/10.1109/TGRS.2025.3542082)
- **2025 · Scientific Reports** — Implicit neural representation for potential field geophysics — [Paper](https://doi.org/10.1038/s41598-024-83979-z) · `Context`
- **2025 · IEEE TGRS** — Microseismic Source Localization Using Fourier Neural Operator With Application to Field Data From Utah FORGE — [Paper](https://doi.org/10.1109/TGRS.2025.3533635)
- **2024 · IEEE TGRS** — 5-D Seismic Data Interpolation by Continuous Representation — [Paper](https://ieeexplore.ieee.org/document/10604902/)
- **2023 · IEEE TGRS** — Rapid Seismic Waveform Modeling and Inversion With Neural Operators — [Paper](https://doi.org/10.1109/TGRS.2023.3264210)
- **2023 · IEEE TGRS** — Solving Seismic Wave Equations on Variable Velocity Models With Fourier Neural Operator — [Paper](https://ieeexplore.ieee.org/)

### NeRF, Implicit Surfaces & Continuous 3D Geometry

- **2026 · IEEE TGRS** — Depth and Geometry Regularization for Neural Implicit Reconstruction From Few-View Satellite Images — [Paper](https://doi.org/10.1109/TGRS.2026.3699879) · [Code](https://github.com/Ljy0109/DGR-NeRF)
- **2025 · ISPRS JPRS** — Accurate and complete neural implicit surface reconstruction in street scenes using images and LiDAR point clouds — [Paper](https://doi.org/10.1016/j.isprsjprs.2024.12.012) · [Code](https://github.com/SCH1001/StreetRecon)
- **2025 · ISPRS JPRS** — Cross-sensor adaptive semantic segmentation for mobile laser scanning point clouds based on continuous potential scene surface reconstruction — [Paper](https://doi.org/10.1016/j.isprsjprs.2025.07.021) · [Code](https://github.com/PCsFJNU/CrossSensorAdaptiveSemanticSeg)
- **2025 · Remote Sensing of Environment** — NeRF-LAI: A Hybrid Method Combining Neural Radiance Field and Gap-Fraction Theory for Deriving Effective Leaf Area Index of Corn and Soybean Using Multi-Angle UAV Images — [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0034425725002482)
- **2025 · IEEE TGRS** — RDS-NeRF: Residual and Depth Supervision Neural Radiance Field for Multiscene 3-D Reconstruction of Satellite Images — [Paper](https://doi.org/10.1109/TGRS.2025.3636144)
- **2025 · arXiv** — Sat-DN: Implicit Surface Reconstruction from Multi-View Satellite Images with Depth and Normal Supervision — [Paper](https://arxiv.org/abs/2502.08352) · [Code](https://github.com/costune/SatDN) · `Context`
- **2025 · WACV CV4EO Workshop** — Semantic Neural Radiance Fields for Multi-Date Satellite Data — [Paper](https://openaccess.thecvf.com/content/WACV2025W/CV4EO/html/Wagner_Semantic_Neural_Radiance_Fields_for_Multi-Date_Satellite_Data_WACVW_2025_paper.html) · [Code](https://github.com/wagnva/semantic-nerf-for-satellite-data) · `Context`
- **2024 · IEEE TGRS** — FVMD-ISRe: 3-D Reconstruction From Few-View Multidate Satellite Images Based on the Implicit Surface Representation of Neural Radiance Fields — [Paper](https://doi.org/10.1109/TGRS.2024.3399786) · [Code](https://github.com/HEU-super-generalized-remote-sensing/FVMD-ISRe)
- **2024 · ISPRS JPRS** — LiDeNeRF: Neural Radiance Field Reconstruction with Depth Prior Provided by LiDAR Point Cloud — [Paper](https://www.sciencedirect.com/science/article/pii/S0924271624000261)
- **2024 · ISPRS JPRS** — PriNeRF: Prior Constrained Neural Radiance Field for Robust Novel View Synthesis of Urban Scenes with Fewer Views — [Paper](https://www.sciencedirect.com/science/article/pii/S092427162400282X) · [Code](https://github.com/Dongber/PriNeRF)
- **2024 · IEEE TGRS** — rpcPRF: Generalizable MPI Neural Radiance Field for Satellite Camera With Single and Sparse Views — [Paper](https://ieeexplore.ieee.org/document/10480403/)
- **2024 · IEEE TGRS** — SatensoRF: Fast Satellite Tensorial Radiance Field for Multidate Satellite Imagery of Large Size — [Paper](https://doi.org/10.1109/TGRS.2024.3382632)
- **2023 · CVPR EarthVision Workshop** — Multi-Date Earth Observation NeRF: The Detail Is in the Shadows — [Paper](https://github.com/rogermm14/eonerf) · [Code](https://github.com/rogermm14/eonerf) · `Context`
- **2022 · CVPR EarthVision Workshop** — Sat-NeRF: Learning Multi-View Satellite Photogrammetry With Transient Objects and Shadow Modeling Using RPC Cameras — [Paper](https://centreborelli.github.io/satnerf/) · [Code](https://github.com/centreborelli/satnerf) · `Context`

### Gaussian Splatting & Explicit Continuous 3D Fields

- **2026 · ISPRS JPRS** — A Differentiable Method for Novel View SAR Image Generation via 3D Gaussian Splatting — [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0924271625004204)
- **2026 · CVPR** — AeroGS: Scale-Aware Gaussian Splatting for Pose-Free Dynamic UAV Scene Reconstruction — [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Li_AeroGS_Scale-Aware_Gaussian_Splatting_for_Pose-Free_Dynamic_UAV_Scene_Reconstruction_CVPR_2026_paper.html)
- **2026 · ISPRS JPRS** — ARSGaussian: 3D Gaussian Splatting with LiDAR for aerial remote sensing novel view synthesis — [Paper](https://doi.org/10.1016/j.isprsjprs.2025.10.022) · [Code](https://github.com/WenjuanZhang-aircas/ARSGaussian)
- **2026 · IEEE TGRS** — Efficient Incremental Large-Scale Orthophoto Generation via 3-D Gaussian Splatting SLAM — [Paper](https://doi.org/10.1109/TGRS.2026.3710516)
- **2026 · ISPRS Annals** — EOGS++: Earth Observation Gaussian Splatting with Internal Camera Refinement and Direct Panchromatic Rendering — [Paper](https://doi.org/10.5194/isprs-annals-XI-2-2026-217-2026) · [Code](https://gardiens.github.io/EOGS2/) · `Context`
- **2026 · ISPRS JPRS** — GaussianCraft: Fine-grained 3D Gaussians for efficient large-scene surface reconstruction — [Paper](https://doi.org/10.1016/j.isprsjprs.2026.03.020)
- **2026 · ISPRS JPRS** — GeoGS: Geometric Prior-Guided Gaussian Splatting for Robust Urban Reconstruction from Sparse Views — [Paper](https://www.sciencedirect.com/science/article/pii/S0924271626003588)
- **2026 · IEEE TGRS** — GU-GS: Gaussian Splatting-Based Geometry Refinement and Uncertainty-Aware Learning Method for DSM Generation From Satellite Imagery — [Paper](https://doi.org/10.1109/TGRS.2026.3671346) · [Code](https://github.com/thessshy/GU-GS)
- **2026 · Computer Graphics Forum** — Multi-Spectral Gaussian Splatting with Neural Color Representation — [Paper](https://doi.org/10.1111/cgf.70337) · [Code](https://github.com/j-gruen/MS-Splatting)
- **2026 · ISPRS JPRS** — SA-GS: Season-Aware Affine 3D Gaussian Splatting for Satellite Image Rendering — [Paper](https://www.sciencedirect.com/science/article/pii/S0924271626001905)
- **2026 · IEEE TGRS** — Satellite-GS: Enhanced 2D Gaussian Splatting for Robust Satellite Reconstruction — [Paper](https://doi.org/10.1109/TGRS.2026.3675851)
- **2026 · IEEE TGRS** — Splatting SA: Direct Rendering of Synthetic Aperture Imagery — [Paper](https://doi.org/10.1109/TGRS.2026.3653637)
- **2026 · IEEE TGRS** — Tortho–SatGS: A 3-D Gaussian Splatting-Based Method for True Orthophoto Generation From Multiview Satellite Imagery — [Paper](https://doi.org/10.1109/TGRS.2026.3707311)
- **2026 · CVPR** — Urban-GS: A Unified 3D Gaussian Splatting Framework for Compact and High-Fidelity Aerial-to-Street Reconstruction — [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Wang_Urban-GS_A_Unified_3D_Gaussian_Splatting_Framework_for_Compact_and_CVPR_2026_paper.html)
- **2025 · CVPR** — Gaussian Splatting for Efficient Satellite Image Photogrammetry — [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Aira_Gaussian_Splatting_for_Efficient_Satellite_Image_Photogrammetry_CVPR_2025_paper.html) · [Code](https://mezzelfo.github.io/EOGS/)
- **2025 · CVPR** — Horizon-GS: Unified 3D Gaussian Splatting for Large-Scale Aerial-to-Ground Scenes — [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Jiang_Horizon-GS_Unified_3D_Gaussian_Splatting_for_Large-Scale_Aerial-to-Ground_Scenes_CVPR_2025_paper.html)
- **2025 · IEEE TGRS** — SAR-GS: Gaussian Splatting-Based SAR Image Rendering and Target Reconstruction — [Paper](https://doi.org/10.1109/TGRS.2025.3639636)
- **2025 · ISPRS JPRS** — SpectralGaussians: Semantic, Spectral 3D Gaussian Splatting for Multi-Spectral Scene Representation, Visualization and Analysis — [Paper](https://www.sciencedirect.com/science/article/pii/S0924271625002345)
- **2025 · ISPRS JPRS** — ULSR-GS: Urban Large-Scale Surface Reconstruction Gaussian Splatting with Multi-View Geometric Consistency — [Paper](https://www.sciencedirect.com/science/article/pii/S092427162500396X)

### Continuous Geospatial Feature Fields

- **2026 · ISPRS JPRS** — GAIR: Location-Aware Self-Supervised Contrastive Pre-Training with Geo-Aligned Implicit Representations — [Paper](https://www.sciencedirect.com/science/article/pii/S092427162600208X)

### Sensor Modeling, Registration & Boundary Cases

- **2026 · IEEE TGRS** — Performance and Efficiency of Climate In Situ Data Reconstruction: Why Optimized IDW Outperforms Kriging and Implicit Neural Representation — [Paper](https://zh.mindat.org/reference.php?id=20210547)

## Contributing

Pull requests are welcome. Please keep each entry minimal: **title, paper/project webpage, and official code link when available**. New papers should fit the scope of continuous remote sensing or provide a clearly relevant foundation/boundary case.

A machine-readable version of the collection is available in [`data/papers.csv`](data/papers.csv).

## Acknowledgment

This list is maintained as a community resource for research on continuous remote sensing and continuous Earth representations.