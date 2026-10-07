# Awesome Continuous Remote Sensing

A rigorously curated list of **continuous-representation methods that are actually applied to remote sensing, Earth observation, photogrammetry/geospatial sensing, or geophysical sensing**.

> **Scope rule:** a paper is listed only when continuity is methodologically central **and** the paper directly studies a remote-sensing / EO / geoscience-sensing problem. Generic SIREN/LIIF/NeRF/FNO/3DGS papers, ordinary fixed-grid remote-sensing models, broad task surveys, and historical baselines are intentionally excluded. See [CURATION.md](CURATION.md).

**Current strict collection:** 100 papers · 83 Core · 10 Extended · 7 Emerging · 42 entries with verified code/project links · re-audited **2026-10-07**.

## What counts as “continuous” here?

A paper qualifies when it models or queries a remote-sensing/Earth quantity as a function or field over continuous coordinates/variables (space, wavelength, time, view, physical parameters), supports genuinely arbitrary/continuous scale or sampling, learns mappings between continuous fields/functions (neural operators), or represents geospatial scenes with continuous implicit/explicit primitives such as NeRF/SDF/Gaussian fields.

## Contents

- [Spatial & Terrain Continuous Fields](#spatial-terrain) (15)
- [Satellite Video & Spatiotemporal EO](#spatiotemporal-eo) (8)
- [Spectral & Spatial–Spectral Continuous Fields](#spectral-spatial-spectral) (18)
- [Continuous Physical & Geophysical Fields](#physical-geophysical) (23)
- [NeRF, Radiance & Implicit Surface Fields](#nerf-implicit) (16)
- [Gaussian Splatting & Explicit Continuous Primitives](#gaussian-splatting) (18)
- [Continuous Geospatial & Cross-Sensor Feature Fields](#geospatial-feature) (1)
- [Critical / Negative Evidence](#critical-negative) (1)

---

<a id="spatial-terrain"></a>
## Spatial & Terrain Continuous Fields

Arbitrary/continuous-scale image and terrain representations with space or scale treated continuously.

- **Flow-Based Gaussian Splatting for Continuous-Scale Remote Sensing Image Super-Resolution** — *arXiv, 2026*. [Paper](https://arxiv.org/abs/2605.22147) `[Emerging]`
- **OFTNet: Omni-Feature and Texture-Aware Enhancement Learning Network for Continuous Remote Sensing Image Super-Resolution** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3686838)
- **Structure-Aware Coarse-to-Fine Upsampling Network for Arbitrary-Scale Super-Resolution of Remote Sensing Images** — *Engineering Applications of Artificial Intelligence, 2026*. [Paper](https://doi.org/10.1016/j.engappai.2025.113046) `[Extended]`
- **TADSR: Texture-Aware Dynamic Gaussian Splatting for Continuous-Scale Remote Sensing Image Super-Resolution** — *Optics & Laser Technology, 2026*. [Paper](https://doi.org/10.1016/j.optlastec.2026.115812) `[Extended]`
- **Binary Lightweight Neural Networks for Arbitrary Scale Super-Resolution of Remote Sensing Images** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3529696)
- **Domain-Aware Implicit Network for Arbitrary-Scale Remote Sensing Image Super-Resolution** — *Advanced Intelligent Discovery, 2025*. [Paper](https://doi.org/10.1002/aidi.202400021) `[Extended]`
- **Latent Diffusion, Implicit Amplification: Efficient Continuous-Scale Super-Resolution for Remote Sensing Images** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3571290) · [Code/Project](https://github.com/MoooJianG/LDCSR)
- **A Continuous Digital Elevation Representation Model for DEM Super-Resolution** — *ISPRS JPRS, 2024*. [Paper](https://www.sciencedirect.com/science/article/pii/S0924271624000017)
- **ImplicitTerrain: a Continuous Surface Model for Terrain Data Analysis** — *CVPR INRV Workshop, 2024*. [Paper](https://openaccess.thecvf.com/content/CVPR2024W/INRV/html/Feng_ImplicitTerrain_a_Continuous_Surface_Model_for_Terrain_Data_Analysis_CVPRW_2024_paper.html) · [Code/Project](https://github.com/Fengyee/implicit-terrain) `[Emerging]`
- **MWLN: Multilevel Wavelet Learning Network for Continuous-Scale Remote-Sensing Image Super-Resolution** — *IEEE GRSL, 2024*. [Paper](https://doi.org/10.1109/LGRS.2023.3339517) `[Extended]`
- **Continuous Remote Sensing Image Super-Resolution Based on Context Interaction in Implicit Function Space** — *IEEE TGRS, 2023*. [Paper](https://arxiv.org/abs/2302.08046) · [Code/Project](https://github.com/KyanChen/FunSR)
- **Learning Dynamic Scale Awareness and Global Implicit Functions for Continuous-Scale Super-Resolution of Remote Sensing Images** — *IEEE TGRS, 2023*. [Paper](https://ieeexplore.ieee.org/document/10026827/) · [Code/Project](https://github.com/hanlinwu/SADN)
- **Lightweight Stepless Super-Resolution of Remote Sensing Images via Saliency-Aware Dynamic Routing Strategy** — *IEEE TGRS, 2023*. [Paper](https://doi.org/10.1109/TGRS.2023.3236624) · [Code/Project](https://github.com/hanlinwu/SalDRN)
- **Hierarchical Feature Aggregation and Self-Learning Network for Remote Sensing Image Continuous-Scale Super-Resolution** — *IEEE GRSL, 2022*. [Paper](https://doi.org/10.1109/LGRS.2021.3122985) `[Extended]`
- **A Unified Network for Arbitrary Scale Super-Resolution of Video Satellite Images** — *IEEE TGRS, 2021*. [Paper](https://doi.org/10.1109/TGRS.2020.3038653)

<a id="spatiotemporal-eo"></a>
## Satellite Video & Spatiotemporal EO

Continuous temporal, spatiotemporal, multi-resolution, and satellite-video Earth-observation representations.

- **Location Is All You Need: Continuous Spatiotemporal Neural Representations of Earth Observation Data** — *CVPR EarthVision Workshop, 2026*. [Paper](https://arxiv.org/abs/2604.07092) · [Code/Project](https://github.com/mojganmadadi/LIANet/tree/v1.0.1) `[Emerging]`
- **Neural Operator-Based Continuous Tensor Representation for Thick Cloud Removal in Multiresolution Remote Sensing Images** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3731463)
- **Satellite Video Continuous Space-Time Super-Resolution via Mask-Based Temporal-Aware Warping and Cross-Level Frequency Integration** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3666370)
- **Seamless Daily XCO2 Mapping Across China with Transformer and Geo Implicit Neural Representation** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3732466) · [Code/Project](https://github.com/luojhello/oco_mapping)
- **A Unified Sentinel-2 Imagery Thick Cloud Removal and Rescaling Framework From a Continuous Perspective** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3609321)
- **Hazy Low-Quality Satellite Video Restoration Via Learning Optimal Joint Degradation Patterns and Continuous-Scale Super-Resolution Reconstruction** — *CVPR, 2025*. [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Ni_Hazy_Low-Quality_Satellite_Video_Restoration_Via_Learning_Optimal_Joint_Degradation_CVPR_2025_paper.html)
- **Streamlined Multilayer Perceptron for Contaminated Time Series Reconstruction: A Case Study in Coastal Zones of Southern China** — *ISPRS JPRS, 2025*. [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0924271625000401)
- **Deformable Convolution Alignment and Dynamic Scale-Aware Network for Continuous-Scale Satellite Video Super-Resolution** — *IEEE TGRS, 2024*. [Paper](https://doi.org/10.1109/TGRS.2024.3366550) · [Code/Project](https://github.com/chongningni/CSVSR)

<a id="spectral-spatial-spectral"></a>
## Spectral & Spatial–Spectral Continuous Fields

Methods that make wavelength and/or spatial–spectral coordinates part of the continuous representation or querying mechanism.

- **DCMArb: Decoupled-Collaborative Mamba for Arbitrary-scale Hyperspectral Super-resolution** — *ISPRS JPRS, 2026*. [Paper](https://doi.org/10.1016/j.isprsjprs.2026.06.009) · [Code/Project](https://github.com/wangswhu/DCMArb)
- **MGINR-WGAN: A Multiscale Guided Implicit Neural Representation Wasserstein GAN for Hyperspectral and Multispectral Image Fusion** — *IEEE JSTARS, 2026*. [Paper](https://doi.org/10.1109/JSTARS.2026.3697374) · [Code/Project](https://github.com/zhangyanxa/MGINR-WGAN) `[Extended]`
- **A spatial-frequency dual-domain implicit guidance method for hyperspectral and multispectral remote sensing image fusion based on Kolmogorov–Arnold Network** — *Information Fusion, 2025*. [Paper](https://doi.org/10.1016/j.inffus.2025.103261) · [Code/Project](https://github.com/chunyuzhu/SFIGNet)
- **Continuous Tensor Representation for Hyperspectral Anomaly Detection** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3593391) · [Code/Project](https://github.com/Weihao-Wu/CBAR)
- **Mamba Collaborative Implicit Neural Representation for Hyperspectral and Multispectral Remote Sensing Image Fusion** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3537638) · [Code/Project](https://github.com/chunyuzhu/MCIFNet)
- **Meta-Collaborative Learning for Arbitrarily Scaled Hyperspectral Image Super-Resolution** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3544253) · [Code/Project](https://github.com/ShuangWu-XDU/MCArb_HSI_SR)
- **OTIAS: OcTree Implicit Adaptive Sampling for Multispectral and Hyperspectral Image Fusion** — *AAAI, 2025*. [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/32275) · [Code/Project](https://github.com/shangqideng/OTIAS)
- **An Implicit Transformer-based Fusion Method for Hyperspectral and Multispectral Remote Sensing Image** — *Int. J. Applied Earth Observation and Geoinformation, 2024*. [Paper](https://doi.org/10.1016/j.jag.2024.103955)
- **Arbitrary-Scale Hyperspectral Image Super-Resolution From a Fusion Perspective With Spatial Priors** — *IEEE TGRS, 2024*. [Paper](https://doi.org/10.1109/TGRS.2024.3481041)
- **Fourier-Enhanced Implicit Neural Fusion Network for Multispectral and Hyperspectral Image Fusion** — *NeurIPS, 2024*. [Paper](https://mlanthology.org/neurips/2024/liang2024neurips-fourierenhanced/) · [Code/Project](https://github.com/294coder/Efficient-MIF)
- **INF³: Implicit Neural Feature Fusion Function for Multispectral and Hyperspectral Image Fusion** — *IEEE Transactions on Computational Imaging, 2024*. [Paper](https://doi.org/10.1109/TCI.2024.3488569)
- **Nonnegative Matrix Functional Factorization for Hyperspectral Unmixing With Nonuniform Spectral Sampling** — *IEEE TGRS, 2024*. [Paper](https://doi.org/10.1109/TGRS.2023.3347414)
- **Progressive High-Frequency Reconstruction for Pan-Sharpening with Implicit Neural Representation** — *AAAI, 2024*. [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/28214)
- **Spectral-Wise Implicit Neural Representation for Hyperspectral Image Reconstruction** — *IEEE TCSVT, 2024*. [Paper](https://doi.org/10.1109/TCSVT.2023.3318366)
- **An adaptive multi-perceptual implicit sampling for hyperspectral and multispectral remote sensing image fusion** — *Int. J. Applied Earth Observation and Geoinformation, 2023*. [Paper](https://doi.org/10.1016/j.jag.2023.103560) · [Code/Project](https://github.com/chunyuzhu/AMGSGAN)
- **Implicit Neural Representation Learning for Hyperspectral Image Super-Resolution** — *IEEE TGRS, 2023*. [Paper](https://doi.org/10.1109/TGRS.2022.3230204) · [Code/Project](https://github.com/kaviezhang/INR-HSISR)
- **QIS-GAN: A Lightweight Adversarial Network With Quadtree Implicit Sampling for Multispectral and Hyperspectral Image Fusion** — *IEEE TGRS, 2023*. [Paper](https://doi.org/10.1109/TGRS.2023.3332176) · [Code/Project](https://github.com/chunyuzhu/QIS-GAN)
- **SS-INR: Spatial-Spectral Implicit Neural Representation Network for Hyperspectral and Multispectral Image Fusion** — *IEEE TGRS, 2023*. [Paper](https://doi.org/10.1109/TGRS.2023.3317413) · [Code/Project](https://github.com/wxy11-27/SS-INR)

<a id="physical-geophysical"></a>
## Continuous Physical & Geophysical Fields

Coordinate fields and neural operators for geophysical, atmospheric, ionospheric, oceanic, seismic, EM, and related physical sensing problems.

- **A continuous implicit neural representation framework with gradient regularization for sea surface height reconstruction from satellite altimetry** — *Geoscientific Model Development, 2026*. [Paper](https://doi.org/10.5194/gmd-19-7349-2026) · [Code/Project](https://doi.org/10.5281/zenodo.21232682) `[Extended]`
- **A Generalized Eikonal Solver Using Operator Learning** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3674885)
- **EFKAN: A KAN-Integrated Neural Operator for Efficient Magnetotelluric Forward Modeling** — *Computers & Geosciences, 2026*. [Paper](https://doi.org/10.1016/j.cageo.2025.106052) · [Code/Project](https://github.com/linfengyu77/EFKAN)
- **Height-Aware Fourier Neural Operator for Near-Space Short-Term Wind Field Prediction: A Systematic Neural Operator Benchmark** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3724650)
- **Implicit Neural Representation for Elastic Full-Waveform Inversion** — *Geophysical Prospecting, 2026*. [Paper](https://doi.org/10.1111/1365-2478.70168)
- **Implicit Neural Representations for 3D Gravity Inversion** — *Computers & Geosciences, 2026*. [Paper](https://doi.org/10.1016/j.cageo.2025.106082)
- **Microseismic monitoring with the quake neural operator** — *Nature Communications, 2026*. [Paper](https://doi.org/10.1038/s41467-026-73965-6) · [Code/Project](https://zenodo.org/records/20072888)
- **Rapid 2-D Magnetotelluric Forward Modeling via Automatic Differentiation Fourier Neural Operator With Gradient Supervision** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3701700)
- **Reversible Deep Operator Network for Grid-Independent, Multi-Scale Magnetotelluric Inversion and Uncertainty Quantification** — *JGR: Solid Earth, 2026*. [Paper](https://doi.org/10.1029/2025JB033046)
- **Spatiotemporal Implicit Neural Representation for Ionospheric Tomography With Multi-LEO Occultation Data** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3667515)
- **Unveiling the Mechanism of Continuous Representation Full-Waveform Inversion: A Wave-Based Neural Tangent Kernel Framework** — *ICLR, 2026*. [Paper](https://proceedings.iclr.cc/paper_files/paper/2026/hash/c89f09849eb5af489abb122394ff0f0b-Abstract-Conference.html)
- **A Feature Enhanced Autoencoder Integrated With Fourier Neural Operator for Intelligent Elastic Wavefield Modeling** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3542082)
- **Implicit neural representation for potential field geophysics** — *Scientific Reports, 2025*. [Paper](https://doi.org/10.1038/s41598-024-83979-z) `[Extended]`
- **Implicit Neural Representations for Unsupervised Seismic Data Interpolation From Single Gather** — *Geophysical Prospecting, 2025*. [Paper](https://doi.org/10.1111/1365-2478.70110)
- **Microseismic Source Localization Using Fourier Neural Operator With Application to Field Data From Utah FORGE** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3533635)
- **5-D Seismic Data Interpolation by Continuous Representation** — *IEEE TGRS, 2024*. [Paper](https://ieeexplore.ieee.org/document/10604902/)
- **Fully Convolutional Network-Enhanced DeepONet-Based Surrogate of Predicting the Travel-Time Fields** — *IEEE TGRS, 2024*. [Paper](https://doi.org/10.1109/TGRS.2024.3401196) · [Code/Project](https://github.com/ismyif/fc-deeponet)
- **Global 4-D Ionospheric STEC Prediction Based on DeepONet for GNSS Rays** — *IEEE TGRS, 2024*. [Paper](https://doi.org/10.1109/TGRS.2024.3422150)
- **Seismic Traveltime Simulation for Variable Velocity Models Using Physics-Informed Fourier Neural Operator** — *IEEE TGRS, 2024*. [Paper](https://doi.org/10.1109/TGRS.2024.3457949)
- **Transfer Learning Fourier Neural Operator for Solving Parametric Frequency-Domain Wave Equations** — *IEEE TGRS, 2024*. [Paper](https://doi.org/10.1109/TGRS.2024.3440199)
- **Rapid Seismic Waveform Modeling and Inversion With Neural Operators** — *IEEE TGRS, 2023*. [Paper](https://doi.org/10.1109/TGRS.2023.3264210)
- **Solving Seismic Wave Equations on Variable Velocity Models With Fourier Neural Operator** — *IEEE TGRS, 2023*. [Paper](https://doi.org/10.1109/TGRS.2023.3333663)
- **Rapid Surrogate Modeling of Electromagnetic Data in Frequency Domain Using Neural Operator** — *IEEE TGRS, 2022*. [Paper](https://doi.org/10.1109/TGRS.2022.3222507)

<a id="nerf-implicit"></a>
## NeRF, Radiance & Implicit Surface Fields

Remote-sensing/photogrammetric NeRF, radiance-field, SDF/implicit-surface, and related continuous scene representations.

- **Depth and Geometry Regularization for Neural Implicit Reconstruction From Few-View Satellite Images** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3699879) · [Code/Project](https://github.com/Ljy0109/DGR-NeRF)
- **Accurate and complete neural implicit surface reconstruction in street scenes using images and LiDAR point clouds** — *ISPRS JPRS, 2025*. [Paper](https://doi.org/10.1016/j.isprsjprs.2024.12.012) · [Code/Project](https://github.com/SCH1001/StreetRecon)
- **Cross-sensor adaptive semantic segmentation for mobile laser scanning point clouds based on continuous potential scene surface reconstruction** — *ISPRS JPRS, 2025*. [Paper](https://doi.org/10.1016/j.isprsjprs.2025.07.021) · [Code/Project](https://github.com/PCsFJNU/CrossSensorAdaptiveSemanticSeg)
- **NeRF-LAI: A Hybrid Method Combining Neural Radiance Field and Gap-Fraction Theory for Deriving Effective Leaf Area Index of Corn and Soybean Using Multi-Angle UAV Images** — *Remote Sensing of Environment, 2025*. [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0034425725002482)
- **RDS-NeRF: Residual and Depth Supervision Neural Radiance Field for Multiscene 3-D Reconstruction of Satellite Images** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3636144)
- **Sat-DN: Implicit Surface Reconstruction from Multi-View Satellite Images with Depth and Normal Supervision** — *arXiv, 2025*. [Paper](https://arxiv.org/abs/2502.08352) · [Code/Project](https://github.com/costune/SatDN) `[Emerging]`
- **Semantic Neural Radiance Fields for Multi-Date Satellite Data** — *WACV CV4EO Workshop, 2025*. [Paper](https://openaccess.thecvf.com/content/WACV2025W/CV4EO/html/Wagner_Semantic_Neural_Radiance_Fields_for_Multi-Date_Satellite_Data_WACVW_2025_paper.html) · [Code/Project](https://github.com/wagnva/semantic-nerf-for-satellite-data) `[Emerging]`
- **FVMD-ISRe: 3-D Reconstruction From Few-View Multidate Satellite Images Based on the Implicit Surface Representation of Neural Radiance Fields** — *IEEE TGRS, 2024*. [Paper](https://doi.org/10.1109/TGRS.2024.3399786) · [Code/Project](https://github.com/HEU-super-generalized-remote-sensing/FVMD-ISRe)
- **Implicit Neural Representation for Change Detection** — *WACV, 2024*. [Paper](https://openaccess.thecvf.com/content/WACV2024/html/Naylor_Implicit_Neural_Representation_for_Change_Detection_WACV_2024_paper.html) · [Code/Project](https://github.com/PeterJackNaylor/NN-4-change-detection)
- **LiDeNeRF: Neural Radiance Field Reconstruction with Depth Prior Provided by LiDAR Point Cloud** — *ISPRS JPRS, 2024*. [Paper](https://www.sciencedirect.com/science/article/pii/S0924271624000261)
- **PriNeRF: Prior Constrained Neural Radiance Field for Robust Novel View Synthesis of Urban Scenes with Fewer Views** — *ISPRS JPRS, 2024*. [Paper](https://www.sciencedirect.com/science/article/pii/S092427162400282X) · [Code/Project](https://github.com/Dongber/PriNeRF)
- **rpcPRF: Generalizable MPI Neural Radiance Field for Satellite Camera With Single and Sparse Views** — *IEEE TGRS, 2024*. [Paper](https://ieeexplore.ieee.org/document/10480403/)
- **SatensoRF: Fast Satellite Tensorial Radiance Field for Multidate Satellite Imagery of Large Size** — *IEEE TGRS, 2024*. [Paper](https://doi.org/10.1109/TGRS.2024.3382632)
- **UAV-ENeRF: Text-Driven UAV Scene Editing With Neural Radiance Fields** — *IEEE TGRS, 2024*. [Paper](https://doi.org/10.1109/TGRS.2024.3379649)
- **Multi-Date Earth Observation NeRF: The Detail Is in the Shadows** — *CVPR EarthVision Workshop, 2023*. [Paper](https://openaccess.thecvf.com/content/CVPR2023W/EarthVision/html/Mari_Multi-Date_Earth_Observation_NeRF_The_Detail_Is_in_the_Shadows_CVPRW_2023_paper.html) · [Code/Project](https://github.com/rogermm14/eonerf) `[Emerging]`
- **Sat-NeRF: Learning Multi-View Satellite Photogrammetry With Transient Objects and Shadow Modeling Using RPC Cameras** — *CVPR EarthVision Workshop, 2022*. [Paper](https://centreborelli.github.io/satnerf/) · [Code/Project](https://github.com/centreborelli/satnerf) `[Emerging]`

<a id="gaussian-splatting"></a>
## Gaussian Splatting & Explicit Continuous Primitives

Earth-observation, aerial, urban, multispectral, and SAR methods whose scene/signal representation is based on continuous Gaussian primitives.

- **A Differentiable Method for Novel View SAR Image Generation via 3D Gaussian Splatting** — *ISPRS JPRS, 2026*. [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0924271625004204)
- **AeroGS: Scale-Aware Gaussian Splatting for Pose-Free Dynamic UAV Scene Reconstruction** — *CVPR, 2026*. [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Li_AeroGS_Scale-Aware_Gaussian_Splatting_for_Pose-Free_Dynamic_UAV_Scene_Reconstruction_CVPR_2026_paper.html)
- **ARSGaussian: 3D Gaussian Splatting with LiDAR for aerial remote sensing novel view synthesis** — *ISPRS JPRS, 2026*. [Paper](https://doi.org/10.1016/j.isprsjprs.2025.10.022) · [Code/Project](https://github.com/WenjuanZhang-aircas/ARSGaussian)
- **Efficient Incremental Large-Scale Orthophoto Generation via 3-D Gaussian Splatting SLAM** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3710516)
- **EOGS++: Earth Observation Gaussian Splatting with Internal Camera Refinement and Direct Panchromatic Rendering** — *ISPRS Annals, 2026*. [Paper](https://doi.org/10.5194/isprs-annals-XI-2-2026-217-2026) · [Code/Project](https://gardiens.github.io/EOGS2/) `[Extended]`
- **GaussianCraft: Fine-grained 3D Gaussians for efficient large-scene surface reconstruction** — *ISPRS JPRS, 2026*. [Paper](https://doi.org/10.1016/j.isprsjprs.2026.03.020)
- **GeoGS: Geometric Prior-Guided Gaussian Splatting for Robust Urban Reconstruction from Sparse Views** — *ISPRS JPRS, 2026*. [Paper](https://www.sciencedirect.com/science/article/pii/S0924271626003588)
- **GU-GS: Gaussian Splatting-Based Geometry Refinement and Uncertainty-Aware Learning Method for DSM Generation From Satellite Imagery** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3671346) · [Code/Project](https://github.com/thessshy/GU-GS)
- **LDI-3DGS: Structurally Robust 3-D Gaussian Splatting Driven by UAV-Borne LiDAR Depth and Intensity Priors** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3727449)
- **Multi-Spectral Gaussian Splatting with Neural Color Representation** — *Computer Graphics Forum, 2026*. [Paper](https://doi.org/10.1111/cgf.70337) · [Code/Project](https://github.com/j-gruen/MS-Splatting) `[Extended]`
- **SA-GS: Season-Aware Affine 3D Gaussian Splatting for Satellite Image Rendering** — *ISPRS JPRS, 2026*. [Paper](https://www.sciencedirect.com/science/article/pii/S0924271626001905) · [Code/Project](https://github.com/CosyXu/SA-GS)
- **Tortho–SatGS: A 3-D Gaussian Splatting-Based Method for True Orthophoto Generation From Multiview Satellite Imagery** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3707311)
- **Urban-GS: A Unified 3D Gaussian Splatting Framework for Compact and High-Fidelity Aerial-to-Street Reconstruction** — *CVPR, 2026*. [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Wang_Urban-GS_A_Unified_3D_Gaussian_Splatting_Framework_for_Compact_and_CVPR_2026_paper.html) · [Code/Project](https://github.com/wangm-buaa/Urban-GS)
- **Gaussian Splatting for Efficient Satellite Image Photogrammetry** — *CVPR, 2025*. [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Aira_Gaussian_Splatting_for_Efficient_Satellite_Image_Photogrammetry_CVPR_2025_paper.html) · [Code/Project](https://mezzelfo.github.io/EOGS/)
- **Horizon-GS: Unified 3D Gaussian Splatting for Large-Scale Aerial-to-Ground Scenes** — *CVPR, 2025*. [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Jiang_Horizon-GS_Unified_3D_Gaussian_Splatting_for_Large-Scale_Aerial-to-Ground_Scenes_CVPR_2025_paper.html)
- **SAR-GS: Gaussian Splatting-Based SAR Image Rendering and Target Reconstruction** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3639636)
- **SpectralGaussians: Semantic, Spectral 3D Gaussian Splatting for Multi-Spectral Scene Representation, Visualization and Analysis** — *ISPRS JPRS, 2025*. [Paper](https://www.sciencedirect.com/science/article/pii/S0924271625002345)
- **ULSR-GS: Urban Large-Scale Surface Reconstruction Gaussian Splatting with Multi-View Geometric Consistency** — *ISPRS JPRS, 2025*. [Paper](https://www.sciencedirect.com/science/article/pii/S092427162500396X) · [Code/Project](https://ulsrgs.github.io)

<a id="geospatial-feature"></a>
## Continuous Geospatial & Cross-Sensor Feature Fields

Continuous latent/geospatial feature representations for location, scale, or cross-sensor alignment.

- **GAIR: Location-Aware Self-Supervised Contrastive Pre-Training with Geo-Aligned Implicit Representations** — *ISPRS JPRS, 2026*. [Paper](https://www.sciencedirect.com/science/article/pii/S092427162600208X)

<a id="critical-negative"></a>
## Critical / Negative Evidence

Direct evidence clarifying when a learned continuous representation is unnecessary or inferior to classical alternatives.

- **Performance and Efficiency of Climate In Situ Data Reconstruction: Why Optimized IDW Outperforms Kriging and Implicit Neural Representation** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3701545)

---

## Curation policy

- **Core**: peer-reviewed, directly in scope, and strong evidence for a continuous-remote-sensing branch.
- **Extended**: directly in scope but in a specialized/adjacent venue or mainly a methodological bridge.
- **Emerging**: workshop/preprint work directly in scope and useful for tracking a fast-moving branch.
- A missing `Code/Project` link means only that an official implementation was not verified in this audit.
- Generic foundations are deliberately kept out of the public bibliography even if the eventual review cites them for background.
- The previous 127-paper working ledger was **not** copied blindly: removals and reasons are recorded in [data/excluded_from_ledger_v2.csv](data/excluded_from_ledger_v2.csv).

## Contributing

Please read [CURATION.md](CURATION.md) and [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.
