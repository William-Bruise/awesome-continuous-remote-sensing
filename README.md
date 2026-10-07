# Awesome Continuous Remote Sensing

A rigorously curated bibliography of **continuous representations that are directly used for remote sensing, Earth observation, photogrammetry/geospatial sensing, or geophysical sensing**.

> **Two hard gates are applied to every item.**  
> **Scientific-scope gate:** continuity must be central to the method, not merely cited as background.  
> **Venue-quality gate:** journal papers must be **CAS (中科院) Category 1/2 OR JCR Q1**; conference papers must be **CCF-A Full/Regular papers**. Preprint-only papers, Workshops, Findings, Short/Demo papers, and non-CCF-A conferences are excluded from the main list.

**Current audited collection:** 111 papers · 97 journal papers · 14 CCF-A conference papers · 41 verified official code/project links · re-audited **2026-10-07**.

The CCF 2026 rules explicitly state that only Full/Regular conference papers count; Short, Demo, Technical Brief, Summary, Findings, and co-located Workshops are outside the recommended-conference scope. See [CURATION.md](CURATION.md) and the audit tables under [data/](data/).

## Contents

- [Spatial & Terrain Continuous Fields](#spatial-terrain-continuous-fields) (13)
- [Satellite Video & Spatiotemporal EO](#satellite-video-spatiotemporal-eo) (8)
- [Spectral & Spatial–Spectral Continuous Fields](#spectral-spatial-spectral-continuous-fields) (25)
- [Continuous Physical & Geophysical Fields](#continuous-physical-geophysical-fields) (35)
- [NeRF, Radiance & Implicit Surface Fields](#nerf-radiance-implicit-surface-fields) (11)
- [Gaussian Splatting & Explicit Continuous Primitives](#gaussian-splatting-explicit-continuous-primitives) (16)
- [Continuous Feature Fields, Detection & GeoAI](#continuous-feature-fields-detection-geoai) (2)
- [Critical / Negative Evidence](#critical-negative-evidence) (1)

---

<a id="spatial-terrain-continuous-fields"></a>
## Spatial & Terrain Continuous Fields

Continuous/arbitrary-scale spatial reconstruction and terrain/thermal fields.

- **OFTNet: Omni-Feature and Texture-Aware Enhancement Learning Network for Continuous Remote Sensing Image Super-Resolution** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3686838) · `CAS 1 / JCR Q1`
- **Structure-Aware Coarse-to-Fine Upsampling Network for Arbitrary-Scale Super-Resolution of Remote Sensing Images** — *Engineering Applications of Artificial Intelligence, 2026*. [Paper](https://doi.org/10.1016/j.engappai.2025.113046) · `CAS 1 / JCR Q1`
- **TADSR: Texture-Aware Dynamic Gaussian Splatting for Continuous-Scale Remote Sensing Image Super-Resolution** — *Optics & Laser Technology, 2026*. [Paper](https://doi.org/10.1016/j.optlastec.2026.115812) · `CAS 2 / JCR Q1`
- **AnyTSR++: Prompt-Oriented Any-Scale Thermal Super-Resolution for Unmanned Aerial Vehicle** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3630597) · [Code/Project](https://github.com/vision4robotics/AnyTSRpp) · `CAS 1 / JCR Q1`
- **Binary Lightweight Neural Networks for Arbitrary Scale Super-Resolution of Remote Sensing Images** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3529696) · `CAS 1 / JCR Q1`
- **Latent Diffusion, Implicit Amplification: Efficient Continuous-Scale Super-Resolution for Remote Sensing Images** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3571290) · [Code/Project](https://github.com/MoooJianG/LDCSR) · `CAS 1 / JCR Q1`
- **A Continuous Digital Elevation Representation Model for DEM Super-Resolution** — *ISPRS JPRS, 2024*. [Paper](https://www.sciencedirect.com/science/article/pii/S0924271624000017) · `CAS 1 / JCR Q1`
- **MWLN: Multilevel Wavelet Learning Network for Continuous-Scale Remote-Sensing Image Super-Resolution** — *IEEE GRSL, 2024*. [Paper](https://doi.org/10.1109/LGRS.2023.3339517) · `JCR Q1 (best category)`
- **Continuous Remote Sensing Image Super-Resolution Based on Context Interaction in Implicit Function Space** — *IEEE TGRS, 2023*. [Paper](https://arxiv.org/abs/2302.08046) · [Code/Project](https://github.com/KyanChen/FunSR) · `CAS 1 / JCR Q1`
- **Learning Dynamic Scale Awareness and Global Implicit Functions for Continuous-Scale Super-Resolution of Remote Sensing Images** — *IEEE TGRS, 2023*. [Paper](https://ieeexplore.ieee.org/document/10026827/) · [Code/Project](https://github.com/hanlinwu/SADN) · `CAS 1 / JCR Q1`
- **Lightweight Stepless Super-Resolution of Remote Sensing Images via Saliency-Aware Dynamic Routing Strategy** — *IEEE TGRS, 2023*. [Paper](https://doi.org/10.1109/TGRS.2023.3236624) · [Code/Project](https://github.com/hanlinwu/SalDRN) · `CAS 1 / JCR Q1`
- **Hierarchical Feature Aggregation and Self-Learning Network for Remote Sensing Image Continuous-Scale Super-Resolution** — *IEEE GRSL, 2022*. [Paper](https://doi.org/10.1109/LGRS.2021.3122985) · `JCR Q1 (best category)`
- **A Unified Network for Arbitrary Scale Super-Resolution of Video Satellite Images** — *IEEE TGRS, 2021*. [Paper](https://doi.org/10.1109/TGRS.2020.3038653) · `CAS 1 / JCR Q1`

<a id="satellite-video-spatiotemporal-eo"></a>
## Satellite Video & Spatiotemporal EO

Continuous time, spatiotemporal reconstruction, cloud/time-series modeling, and satellite/UAV video.

- **Neural Operator-Based Continuous Tensor Representation for Thick Cloud Removal in Multiresolution Remote Sensing Images** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3731463) · `CAS 1 / JCR Q1`
- **Satellite Video Continuous Space-Time Super-Resolution via Mask-Based Temporal-Aware Warping and Cross-Level Frequency Integration** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3666370) · `CAS 1 / JCR Q1`
- **Seamless Daily XCO2 Mapping Across China with Transformer and Geo Implicit Neural Representation** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3732466) · [Code/Project](https://github.com/luojhello/oco_mapping) · `CAS 1 / JCR Q1`
- **TAIS-Net: Time adaptive implicit sampling diffusion model for arbitrary-scale UAV video super-resolution** — *ISPRS JPRS, 2026*. [Paper](https://doi.org/10.1016/j.isprsjprs.2026.04.060) · [Code/Project](https://github.com/cyber-lwk/TAIS-Net) · `CAS 1 / JCR Q1`
- **A Unified Sentinel-2 Imagery Thick Cloud Removal and Rescaling Framework From a Continuous Perspective** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3609321) · `CAS 1 / JCR Q1`
- **Hazy Low-Quality Satellite Video Restoration Via Learning Optimal Joint Degradation Patterns and Continuous-Scale Super-Resolution Reconstruction** — *CVPR, 2025*. [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Ni_Hazy_Low-Quality_Satellite_Video_Restoration_Via_Learning_Optimal_Joint_Degradation_CVPR_2025_paper.html) · `CCF-A Full/Regular`
- **Streamlined Multilayer Perceptron for Contaminated Time Series Reconstruction: A Case Study in Coastal Zones of Southern China** — *ISPRS JPRS, 2025*. [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0924271625000401) · `CAS 1 / JCR Q1`
- **Deformable Convolution Alignment and Dynamic Scale-Aware Network for Continuous-Scale Satellite Video Super-Resolution** — *IEEE TGRS, 2024*. [Paper](https://doi.org/10.1109/TGRS.2024.3366550) · [Code/Project](https://github.com/chongningni/CSVSR) · `CAS 1 / JCR Q1`

<a id="spectral-spatial-spectral-continuous-fields"></a>
## Spectral & Spatial–Spectral Continuous Fields

Continuous wavelength or spatial–spectral function/operator models for HSI/MSI fusion, pansharpening, unmixing, and arbitrary-scale HSI.

- **Arbitrary-Scale Fusion Operator for High-Resolution Hyperspectral Imaging** — *IEEE Transactions on Multimedia, 2026*. [Paper](https://doi.org/10.1109/TMM.2026.3655472) · `CAS 1 / JCR Q1`
- **Arbitrary-scale spatial-spectral fusion using kernel integral and progressive resampling** — *Information Fusion, 2026*. [Paper](https://doi.org/10.1016/j.inffus.2026.104143) · [Code/Project](https://github.com/weili419/SFNO) · `CAS 1 / JCR Q1`
- **DCMArb: Decoupled-Collaborative Mamba for Arbitrary-scale Hyperspectral Super-resolution** — *ISPRS JPRS, 2026*. [Paper](https://doi.org/10.1016/j.isprsjprs.2026.06.009) · [Code/Project](https://github.com/wangswhu/DCMArb) · `CAS 1 / JCR Q1`
- **MGINR-WGAN: A Multiscale Guided Implicit Neural Representation Wasserstein GAN for Hyperspectral and Multispectral Image Fusion** — *IEEE JSTARS, 2026*. [Paper](https://doi.org/10.1109/JSTARS.2026.3697374) · [Code/Project](https://github.com/zhangyanxa/MGINR-WGAN) · `CAS 2 / JCR Q1`
- **NODiff: Neural Operator Diffusion for Multispectral Image Fusion** — *AAAI, 2026*. [Paper](https://doi.org/10.1609/aaai.v40i6.42477) · `CCF-A Full/Regular`
- **Solving Spatial-Spectral Fusion with Latent Spectral Operators** — *ICML, 2026*. [Paper](https://proceedings.mlr.press/v306/li26en.html) · [Code/Project](https://github.com/weili419/LSO) · `CCF-A Full/Regular`
- **Spatial-Spectral Residuals Informed Diffusion Neural Operator for Pan-sharpening** — *CVPR, 2026*. [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Huang_Spatial-Spectral_Residuals_Informed_Diffusion_Neural_Operator_for_Pan-sharpening_CVPR_2026_paper.html) · `CCF-A Full/Regular`
- **A spatial-frequency dual-domain implicit guidance method for hyperspectral and multispectral remote sensing image fusion based on Kolmogorov–Arnold Network** — *Information Fusion, 2025*. [Paper](https://doi.org/10.1016/j.inffus.2025.103261) · [Code/Project](https://github.com/chunyuzhu/SFIGNet) · `CAS 1 / JCR Q1`
- **Arbitrary-scale Fusion Neural Operator** — *ACM MM, 2025*. [Paper](https://doi.org/10.1145/3746027.3755312) · `CCF-A Regular`
- **Continuous Tensor Representation for Hyperspectral Anomaly Detection** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3593391) · [Code/Project](https://github.com/Weihao-Wu/CBAR) · `CAS 1 / JCR Q1`
- **Mamba Collaborative Implicit Neural Representation for Hyperspectral and Multispectral Remote Sensing Image Fusion** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3537638) · [Code/Project](https://github.com/chunyuzhu/MCIFNet) · `CAS 1 / JCR Q1`
- **Meta-Collaborative Learning for Arbitrarily Scaled Hyperspectral Image Super-Resolution** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3544253) · [Code/Project](https://github.com/ShuangWu-XDU/MCArb_HSI_SR) · `CAS 1 / JCR Q1`
- **OTIAS: OcTree Implicit Adaptive Sampling for Multispectral and Hyperspectral Image Fusion** — *AAAI, 2025*. [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/32275) · [Code/Project](https://github.com/shangqideng/OTIAS) · `CCF-A Full/Regular`
- **Physics-informed Neural Operator for Pansharpening** — *NeurIPS, 2025*. [Paper](https://proceedings.neurips.cc/paper_files/paper/2025/hash/89af8e4eb696738f2c9e589522968a09-Abstract-Conference.html) · [Code/Project](https://github.com/ez4lionky/PINO) · `CCF-A Full/Regular`
- **An Implicit Transformer-based Fusion Method for Hyperspectral and Multispectral Remote Sensing Image** — *Int. J. Applied Earth Observation and Geoinformation, 2024*. [Paper](https://doi.org/10.1016/j.jag.2024.103955) · `CAS 1 / JCR Q1`
- **Arbitrary-Scale Hyperspectral Image Super-Resolution From a Fusion Perspective With Spatial Priors** — *IEEE TGRS, 2024*. [Paper](https://doi.org/10.1109/TGRS.2024.3481041) · `CAS 1 / JCR Q1`
- **Fourier-Enhanced Implicit Neural Fusion Network for Multispectral and Hyperspectral Image Fusion** — *NeurIPS, 2024*. [Paper](https://mlanthology.org/neurips/2024/liang2024neurips-fourierenhanced/) · [Code/Project](https://github.com/294coder/Efficient-MIF) · `CCF-A Full/Regular`
- **INF³: Implicit Neural Feature Fusion Function for Multispectral and Hyperspectral Image Fusion** — *IEEE Transactions on Computational Imaging, 2024*. [Paper](https://doi.org/10.1109/TCI.2024.3488569) · `CAS 2`
- **Nonnegative Matrix Functional Factorization for Hyperspectral Unmixing With Nonuniform Spectral Sampling** — *IEEE TGRS, 2024*. [Paper](https://doi.org/10.1109/TGRS.2023.3347414) · `CAS 1 / JCR Q1`
- **Progressive High-Frequency Reconstruction for Pan-Sharpening with Implicit Neural Representation** — *AAAI, 2024*. [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/28214) · `CCF-A Full/Regular`
- **Spectral-Wise Implicit Neural Representation for Hyperspectral Image Reconstruction** — *IEEE TCSVT, 2024*. [Paper](https://doi.org/10.1109/TCSVT.2023.3318366) · `CAS 1 / JCR Q1`
- **An adaptive multi-perceptual implicit sampling for hyperspectral and multispectral remote sensing image fusion** — *Int. J. Applied Earth Observation and Geoinformation, 2023*. [Paper](https://doi.org/10.1016/j.jag.2023.103560) · [Code/Project](https://github.com/chunyuzhu/AMGSGAN) · `CAS 1 / JCR Q1`
- **Implicit Neural Representation Learning for Hyperspectral Image Super-Resolution** — *IEEE TGRS, 2023*. [Paper](https://doi.org/10.1109/TGRS.2022.3230204) · [Code/Project](https://github.com/kaviezhang/INR-HSISR) · `CAS 1 / JCR Q1`
- **QIS-GAN: A Lightweight Adversarial Network With Quadtree Implicit Sampling for Multispectral and Hyperspectral Image Fusion** — *IEEE TGRS, 2023*. [Paper](https://doi.org/10.1109/TGRS.2023.3332176) · [Code/Project](https://github.com/chunyuzhu/QIS-GAN) · `CAS 1 / JCR Q1`
- **SS-INR: Spatial-Spectral Implicit Neural Representation Network for Hyperspectral and Multispectral Image Fusion** — *IEEE TGRS, 2023*. [Paper](https://doi.org/10.1109/TGRS.2023.3317413) · [Code/Project](https://github.com/wxy11-27/SS-INR) · `CAS 1 / JCR Q1`

<a id="continuous-physical-geophysical-fields"></a>
## Continuous Physical & Geophysical Fields

Continuous physical fields, implicit geophysical inversion, PINNs, and neural operators for seismic/EM/atmospheric/ionospheric/oceanic sensing.

- **A continuous implicit neural representation framework with gradient regularization for sea surface height reconstruction from satellite altimetry** — *Geoscientific Model Development, 2026*. [Paper](https://doi.org/10.5194/gmd-19-7349-2026) · [Code/Project](https://doi.org/10.5281/zenodo.21232682) · `CAS 2 / JCR Q1`
- **A Generalized Eikonal Solver Using Operator Learning** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3674885) · `CAS 1 / JCR Q1`
- **Adaptive SIREN-PINN With Principled Initialization: A Frequency-Aware and Singularity-Robust Framework for Solver-Free Acoustic Seismic Wave Modeling** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3655956) · `CAS 1 / JCR Q1`
- **EFKAN: A KAN-Integrated Neural Operator for Efficient Magnetotelluric Forward Modeling** — *Computers & Geosciences, 2026*. [Paper](https://doi.org/10.1016/j.cageo.2025.106052) · [Code/Project](https://github.com/linfengyu77/EFKAN) · `CAS 2 / JCR Q1 (best category)`
- **Enhancing Frequency Response in Implicit Full Waveform Inversion via Fourier Encoding** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3684378) · `CAS 1 / JCR Q1`
- **Height-Aware Fourier Neural Operator for Near-Space Short-Term Wind Field Prediction: A Systematic Neural Operator Benchmark** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3724650) · `CAS 1 / JCR Q1`
- **Implicit full waveform inversion with adaptive Fourier frequency bases learning** — *Geophysical Journal International, 2026*. [Paper](https://doi.org/10.1093/gji/ggaf404) · `CAS 2`
- **Implicit Neural Representations for 3D Gravity Inversion** — *Computers & Geosciences, 2026*. [Paper](https://doi.org/10.1016/j.cageo.2025.106082) · `CAS 2 / JCR Q1 (best category)`
- **Least-squares-embedded optimization for accelerated convergence of PINNs in high-frequency acoustic wavefield simulations** — *Computers & Geosciences, 2026*. [Paper](https://doi.org/10.1016/j.cageo.2026.106162) · `CAS 2 / JCR Q1 (best category)`
- **M-SSIM-3DIFWI: 3-D Implicit Full Waveform Inversion Based on the Multiscale Structural Similarity** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3704938) · `CAS 1 / JCR Q1`
- **Microseismic monitoring with the quake neural operator** — *Nature Communications, 2026*. [Paper](https://doi.org/10.1038/s41467-026-73965-6) · [Code/Project](https://zenodo.org/records/20072888) · `CAS 1 / JCR Q1`
- **Rapid 2-D Magnetotelluric Forward Modeling via Automatic Differentiation Fourier Neural Operator With Gradient Supervision** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3701700) · `CAS 1 / JCR Q1`
- **Reversible Deep Operator Network for Grid-Independent, Multi-Scale Magnetotelluric Inversion and Uncertainty Quantification** — *JGR: Solid Earth, 2026*. [Paper](https://doi.org/10.1029/2025JB033046) · `CAS 2 / JCR Q1`
- **Spatiotemporal Implicit Neural Representation for Ionospheric Tomography With Multi-LEO Occultation Data** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3667515) · `CAS 1 / JCR Q1`
- **Three-dimensional inversion of gravity data using implicit neural representations and scientific machine learning** — *Scientific Reports, 2026*. [Paper](https://doi.org/10.1038/s41598-026-55960-5) · [Code/Project](https://zenodo.org/records/19440024) · `JCR Q1`
- **Unveiling the Mechanism of Continuous Representation Full-Waveform Inversion: A Wave-Based Neural Tangent Kernel Framework** — *ICLR, 2026*. [Paper](https://proceedings.iclr.cc/paper_files/paper/2026/hash/c89f09849eb5af489abb122394ff0f0b-Abstract-Conference.html) · `CCF-A Full/Regular`
- **A Feature Enhanced Autoencoder Integrated With Fourier Neural Operator for Intelligent Elastic Wavefield Modeling** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3542082) · `CAS 1 / JCR Q1`
- **Bayesian seismic inversion with implicit neural representations** — *Geophysical Journal International, 2025*. [Paper](https://doi.org/10.1093/gji/ggaf249) · [Code/Project](https://github.com/DeepWave-KAUST/B-IntraSeismic-pub) · `CAS 2`
- **Full-Waveform Inversion With Velocity Model Low-Rank Implicit Neural Representation** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3594184) · `CAS 1 / JCR Q1`
- **Implicit multiparameter full waveform inversion of multioffset ground penetrating radar data** — *Geophysical Journal International, 2025*. [Paper](https://doi.org/10.1093/gji/ggae420) · `CAS 2`
- **Implicit neural representation for potential field geophysics** — *Scientific Reports, 2025*. [Paper](https://doi.org/10.1038/s41598-024-83979-z) · `JCR Q1`
- **Microseismic Source Localization Using Fourier Neural Operator With Application to Field Data From Utah FORGE** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3533635) · `CAS 1 / JCR Q1`
- **Physics-Informed Waveform Inversion Using Pretrained Wavefield Neural Operators** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3624025) · `CAS 1 / JCR Q1`
- **5-D Seismic Data Interpolation by Continuous Representation** — *IEEE TGRS, 2024*. [Paper](https://ieeexplore.ieee.org/document/10604902/) · `CAS 1 / JCR Q1`
- **Fully Convolutional Network-Enhanced DeepONet-Based Surrogate of Predicting the Travel-Time Fields** — *IEEE TGRS, 2024*. [Paper](https://doi.org/10.1109/TGRS.2024.3401196) · [Code/Project](https://github.com/ismyif/fc-deeponet) · `CAS 1 / JCR Q1`
- **Global 4-D Ionospheric STEC Prediction Based on DeepONet for GNSS Rays** — *IEEE TGRS, 2024*. [Paper](https://doi.org/10.1109/TGRS.2024.3422150) · `CAS 1 / JCR Q1`
- **Physics-Informed Robust and Implicit Full Waveform Inversion Without Prior and Low-Frequency Information** — *IEEE TGRS, 2024*. [Paper](https://doi.org/10.1109/TGRS.2024.3416547) · `CAS 1 / JCR Q1`
- **PINN-Based Seismic Wavefield Simulation With Learnable Multiscale Fourier Feature Mapping and Adaptive Activation Function** — *IEEE GRSL, 2024*. [Paper](https://doi.org/10.1109/LGRS.2024.3485908) · `JCR Q1 (best category)`
- **Seismic Traveltime Simulation for Variable Velocity Models Using Physics-Informed Fourier Neural Operator** — *IEEE TGRS, 2024*. [Paper](https://doi.org/10.1109/TGRS.2024.3457949) · `CAS 1 / JCR Q1`
- **Transfer Learning Fourier Neural Operator for Solving Parametric Frequency-Domain Wave Equations** — *IEEE TGRS, 2024*. [Paper](https://doi.org/10.1109/TGRS.2024.3440199) · `CAS 1 / JCR Q1`
- **Implicit Seismic Full Waveform Inversion With Deep Neural Representation** — *JGR: Solid Earth, 2023*. [Paper](https://doi.org/10.1029/2022JB025964) · [Code/Project](https://doi.org/10.5281/zenodo.7262564) · `CAS 2 / JCR Q1`
- **Multilayer Perceptron and Bayesian Neural Network-Based Elastic Implicit Full Waveform Inversion** — *IEEE TGRS, 2023*. [Paper](https://doi.org/10.1109/TGRS.2023.3265657) · `CAS 1 / JCR Q1`
- **Rapid Seismic Waveform Modeling and Inversion With Neural Operators** — *IEEE TGRS, 2023*. [Paper](https://doi.org/10.1109/TGRS.2023.3264210) · `CAS 1 / JCR Q1`
- **Solving Seismic Wave Equations on Variable Velocity Models With Fourier Neural Operator** — *IEEE TGRS, 2023*. [Paper](https://doi.org/10.1109/TGRS.2023.3333663) · `CAS 1 / JCR Q1`
- **Rapid Surrogate Modeling of Electromagnetic Data in Frequency Domain Using Neural Operator** — *IEEE TGRS, 2022*. [Paper](https://doi.org/10.1109/TGRS.2022.3222507) · `CAS 1 / JCR Q1`

<a id="nerf-radiance-implicit-surface-fields"></a>
## NeRF, Radiance & Implicit Surface Fields

Remote-sensing NeRF, radiance fields, implicit surfaces, and continuous 3-D scene geometry.

- **Depth and Geometry Regularization for Neural Implicit Reconstruction From Few-View Satellite Images** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3699879) · [Code/Project](https://github.com/Ljy0109/DGR-NeRF) · `CAS 1 / JCR Q1`
- **Accurate and complete neural implicit surface reconstruction in street scenes using images and LiDAR point clouds** — *ISPRS JPRS, 2025*. [Paper](https://doi.org/10.1016/j.isprsjprs.2024.12.012) · [Code/Project](https://github.com/SCH1001/StreetRecon) · `CAS 1 / JCR Q1`
- **Cross-sensor adaptive semantic segmentation for mobile laser scanning point clouds based on continuous potential scene surface reconstruction** — *ISPRS JPRS, 2025*. [Paper](https://doi.org/10.1016/j.isprsjprs.2025.07.021) · [Code/Project](https://github.com/PCsFJNU/CrossSensorAdaptiveSemanticSeg) · `CAS 1 / JCR Q1`
- **NeRF-LAI: A Hybrid Method Combining Neural Radiance Field and Gap-Fraction Theory for Deriving Effective Leaf Area Index of Corn and Soybean Using Multi-Angle UAV Images** — *Remote Sensing of Environment, 2025*. [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0034425725002482) · `CAS 1 / JCR Q1`
- **RDS-NeRF: Residual and Depth Supervision Neural Radiance Field for Multiscene 3-D Reconstruction of Satellite Images** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3636144) · `CAS 1 / JCR Q1`
- **FVMD-ISRe: 3-D Reconstruction From Few-View Multidate Satellite Images Based on the Implicit Surface Representation of Neural Radiance Fields** — *IEEE TGRS, 2024*. [Paper](https://doi.org/10.1109/TGRS.2024.3399786) · [Code/Project](https://github.com/HEU-super-generalized-remote-sensing/FVMD-ISRe) · `CAS 1 / JCR Q1`
- **LiDeNeRF: Neural Radiance Field Reconstruction with Depth Prior Provided by LiDAR Point Cloud** — *ISPRS JPRS, 2024*. [Paper](https://www.sciencedirect.com/science/article/pii/S0924271624000261) · `CAS 1 / JCR Q1`
- **PriNeRF: Prior Constrained Neural Radiance Field for Robust Novel View Synthesis of Urban Scenes with Fewer Views** — *ISPRS JPRS, 2024*. [Paper](https://www.sciencedirect.com/science/article/pii/S092427162400282X) · [Code/Project](https://github.com/Dongber/PriNeRF) · `CAS 1 / JCR Q1`
- **rpcPRF: Generalizable MPI Neural Radiance Field for Satellite Camera With Single and Sparse Views** — *IEEE TGRS, 2024*. [Paper](https://ieeexplore.ieee.org/document/10480403/) · `CAS 1 / JCR Q1`
- **SatensoRF: Fast Satellite Tensorial Radiance Field for Multidate Satellite Imagery of Large Size** — *IEEE TGRS, 2024*. [Paper](https://doi.org/10.1109/TGRS.2024.3382632) · `CAS 1 / JCR Q1`
- **UAV-ENeRF: Text-Driven UAV Scene Editing With Neural Radiance Fields** — *IEEE TGRS, 2024*. [Paper](https://doi.org/10.1109/TGRS.2024.3379649) · `CAS 1 / JCR Q1`

<a id="gaussian-splatting-explicit-continuous-primitives"></a>
## Gaussian Splatting & Explicit Continuous Primitives

High-quality EO/aerial/satellite/SAR work using differentiable Gaussian primitives as the continuous scene/signal representation.

- **A Differentiable Method for Novel View SAR Image Generation via 3D Gaussian Splatting** — *ISPRS JPRS, 2026*. [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0924271625004204) · `CAS 1 / JCR Q1`
- **AeroGS: Scale-Aware Gaussian Splatting for Pose-Free Dynamic UAV Scene Reconstruction** — *CVPR, 2026*. [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Li_AeroGS_Scale-Aware_Gaussian_Splatting_for_Pose-Free_Dynamic_UAV_Scene_Reconstruction_CVPR_2026_paper.html) · `CCF-A Full/Regular`
- **ARSGaussian: 3D Gaussian Splatting with LiDAR for aerial remote sensing novel view synthesis** — *ISPRS JPRS, 2026*. [Paper](https://doi.org/10.1016/j.isprsjprs.2025.10.022) · [Code/Project](https://github.com/WenjuanZhang-aircas/ARSGaussian) · `CAS 1 / JCR Q1`
- **Efficient Incremental Large-Scale Orthophoto Generation via 3-D Gaussian Splatting SLAM** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3710516) · `CAS 1 / JCR Q1`
- **GaussianCraft: Fine-grained 3D Gaussians for efficient large-scene surface reconstruction** — *ISPRS JPRS, 2026*. [Paper](https://doi.org/10.1016/j.isprsjprs.2026.03.020) · `CAS 1 / JCR Q1`
- **GeoGS: Geometric Prior-Guided Gaussian Splatting for Robust Urban Reconstruction from Sparse Views** — *ISPRS JPRS, 2026*. [Paper](https://www.sciencedirect.com/science/article/pii/S0924271626003588) · `CAS 1 / JCR Q1`
- **GU-GS: Gaussian Splatting-Based Geometry Refinement and Uncertainty-Aware Learning Method for DSM Generation From Satellite Imagery** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3671346) · [Code/Project](https://github.com/thessshy/GU-GS) · `CAS 1 / JCR Q1`
- **LDI-3DGS: Structurally Robust 3-D Gaussian Splatting Driven by UAV-Borne LiDAR Depth and Intensity Priors** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3727449) · `CAS 1 / JCR Q1`
- **SA-GS: Season-Aware Affine 3D Gaussian Splatting for Satellite Image Rendering** — *ISPRS JPRS, 2026*. [Paper](https://www.sciencedirect.com/science/article/pii/S0924271626001905) · [Code/Project](https://github.com/CosyXu/SA-GS) · `CAS 1 / JCR Q1`
- **Tortho–SatGS: A 3-D Gaussian Splatting-Based Method for True Orthophoto Generation From Multiview Satellite Imagery** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3707311) · `CAS 1 / JCR Q1`
- **Urban-GS: A Unified 3D Gaussian Splatting Framework for Compact and High-Fidelity Aerial-to-Street Reconstruction** — *CVPR, 2026*. [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Wang_Urban-GS_A_Unified_3D_Gaussian_Splatting_Framework_for_Compact_and_CVPR_2026_paper.html) · [Code/Project](https://github.com/wangm-buaa/Urban-GS) · `CCF-A Full/Regular`
- **Gaussian Splatting for Efficient Satellite Image Photogrammetry** — *CVPR, 2025*. [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Aira_Gaussian_Splatting_for_Efficient_Satellite_Image_Photogrammetry_CVPR_2025_paper.html) · [Code/Project](https://mezzelfo.github.io/EOGS/) · `CCF-A Full/Regular`
- **Horizon-GS: Unified 3D Gaussian Splatting for Large-Scale Aerial-to-Ground Scenes** — *CVPR, 2025*. [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Jiang_Horizon-GS_Unified_3D_Gaussian_Splatting_for_Large-Scale_Aerial-to-Ground_Scenes_CVPR_2025_paper.html) · `CCF-A Full/Regular`
- **SAR-GS: Gaussian Splatting-Based SAR Image Rendering and Target Reconstruction** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3639636) · `CAS 1 / JCR Q1`
- **SpectralGaussians: Semantic, Spectral 3D Gaussian Splatting for Multi-Spectral Scene Representation, Visualization and Analysis** — *ISPRS JPRS, 2025*. [Paper](https://www.sciencedirect.com/science/article/pii/S0924271625002345) · `CAS 1 / JCR Q1`
- **ULSR-GS: Urban Large-Scale Surface Reconstruction Gaussian Splatting with Multi-View Geometric Consistency** — *ISPRS JPRS, 2025*. [Paper](https://www.sciencedirect.com/science/article/pii/S092427162500396X) · [Code/Project](https://ulsrgs.github.io) · `CAS 1 / JCR Q1`

<a id="continuous-feature-fields-detection-geoai"></a>
## Continuous Feature Fields, Detection & GeoAI

Continuous latent/geospatial feature fields and remote-sensing detection models whose representation is explicitly continuous.

- **GAIR: Location-Aware Self-Supervised Contrastive Pre-Training with Geo-Aligned Implicit Representations** — *ISPRS JPRS, 2026*. [Paper](https://www.sciencedirect.com/science/article/pii/S092427162600208X) · `CAS 1 / JCR Q1`
- **NeRI: Implicit Neural Representation for Infrared Small Target Detection** — *IEEE TGRS, 2025*. [Paper](https://doi.org/10.1109/TGRS.2025.3633281) · `CAS 1 / JCR Q1`

<a id="critical-negative-evidence"></a>
## Critical / Negative Evidence

High-quality counter-evidence used to delimit when a learned continuous representation is not beneficial.

- **Performance and Efficiency of Climate In Situ Data Reconstruction: Why Optimized IDW Outperforms Kriging and Implicit Neural Representation** — *IEEE TGRS, 2026*. [Paper](https://doi.org/10.1109/TGRS.2026.3701545) · `CAS 1 / JCR Q1`

---

## Curation and audit

This list is deliberately narrower than a general INR / neural-field / neural-operator reading list.

- [CURATION.md](CURATION.md): exact scientific-scope and venue-quality rules.
- [data/papers.csv](data/papers.csv): structured main bibliography with paper/code links and quality evidence.
- [data/venue_quality_audit.csv](data/venue_quality_audit.csv): venue-level PASS/FAIL audit.
- [data/excluded_by_quality.csv](data/excluded_by_quality.csv): papers removed from the previous strict-scope list solely because they fail the venue-quality gate.
- [data/excluded_from_ledger_v2.csv](data/excluded_from_ledger_v2.csv): earlier scope/relevance exclusions.

A missing `Code/Project` link means that an official implementation was not verified; it does **not** mean that no code exists.

## Contributing

Please read [CURATION.md](CURATION.md) before opening a PR. A proposed paper must pass **both** the scientific-scope gate and the venue-quality gate.
