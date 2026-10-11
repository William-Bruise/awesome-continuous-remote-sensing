# Awesome Continuous Remote Sensing

A white-paper-aligned, evidence-audited collection of research on **continuous representation of Earth/geophysical fields**, **harmonization of heterogeneous remote-sensing measurements**, and **physical inference from continuous geophysical fields**.

> **Strict inclusion gates (updated 2026-10-11).** Direct remote-sensing/geophysical application; an explicitly identifiable continuous quantity/field/operator must be central; journals must be **JCR Q1 in at least one subject category** (not merely CAS Q1/Q2), or conferences must be **full/regular main-track** papers at the accepted top venues. Generic INR/FNO/NeRF/3DGS foundations, workshops and unverified/preprint-only papers are **not** counted in the core collection.

**Current core: 104 papers (91 journal, 13 top-conference) · 41 linked official implementations/projects · thematic audit updated 2026-10-11.**

## Review taxonomy (IEEE GRSM white-paper structure)

| Theme | Scientific question | Core papers |
| --- | --- | ---: |
| [I. Representation of Continuous Geophysical Fields](#representation) | What is the continuous geophysical field, and how is it represented? | 46 |
| [II. Harmonization of Heterogeneous Remote-Sensing Measurements](#harmonization) | How do continuous models reconcile distinct remote-sensing measurements and sampling operators? | 29 |
| [III. Physical Inference from Continuous Geophysical Fields](#physical-inference) | How can field representations support physical constraints, inverse inference and field-to-field mappings? | 29 |

Each entry is assigned **one primary theme** by its *scientific objective* (rather than its architecture), and optionally a secondary cross-theme tag. See [WHITEPAPER_ALIGNMENT.md](WHITEPAPER_ALIGNMENT.md) for borderline decisions and [CURATION.md](CURATION.md) for the journal/conference and scientific gates.

## Contents

1. [Representation of Continuous Geophysical Fields](#representation) — **46 papers**
2. [Harmonization of Heterogeneous Remote-Sensing Measurements](#harmonization) — **29 papers**
3. [Physical Inference from Continuous Geophysical Fields](#physical-inference) — **29 papers**

### Data and audit trail

- [Canonical core bibliography (CSV)](data/papers.csv), including one primary theme, subtopic, optional secondary theme, continuous variable, paper link and available official code.
- [Paper-level scientific audit](data/paper_level_audit.csv): *what is continuous*, *why it belongs*, evidence level, theme attribution and explicit inclusion/exclusion decision.
- [Venue-quality audit](data/venue_quality_audit.csv); [venue exclusions](data/excluded_by_quality.csv); [scope exclusions for this review](data/excluded_from_three_theme_review.csv).
- [Historic exclusions](data/excluded_from_ledger_v2.csv) and [context / negative evidence](data/context_negative_evidence.csv) are preserved separately, **not counted** as included core articles.

---

<a id="representation"></a>
## 1. Representation of Continuous Geophysical Fields

How geophysical quantities are represented as continuous functions, fields, tensors, radiance/surface fields, or Gaussian primitives over space, wavelength, time, height, view, or physical coordinates. A single-sensor arbitrary-scale reconstruction primarily belongs here.

### Spatial, terrain and thermal fields (13)

- **[OFTNet: Omni-Feature and Texture-Aware Enhancement Learning Network for Continuous Remote Sensing Image Super-Resolution](https://doi.org/10.1109/TGRS.2026.3686838)** — *IEEE TGRS, 2026* · `JCR Q1`
  - **What is continuous?** spatial scale / output resolution. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[Structure-Aware Coarse-to-Fine Upsampling Network for Arbitrary-Scale Super-Resolution of Remote Sensing Images](https://doi.org/10.1016/j.engappai.2025.113046)** — *Engineering Applications of Artificial Intelligence, 2026* · `JCR Q1`
  - **What is continuous?** 2-D query coordinates + scale. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[TADSR: Texture-Aware Dynamic Gaussian Splatting for Continuous-Scale Remote Sensing Image Super-Resolution](https://doi.org/10.1016/j.optlastec.2026.115812)** — *Optics & Laser Technology, 2026* · `JCR Q1`
  - **What is continuous?** 2-D spatial coordinates + output scale. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[AnyTSR++: Prompt-Oriented Any-Scale Thermal Super-Resolution for Unmanned Aerial Vehicle](https://doi.org/10.1109/TGRS.2025.3630597)** — *IEEE TGRS, 2025* · [Code/Project](https://github.com/vision4robotics/AnyTSRpp) · `JCR Q1`
  - **What is continuous?** horizontal/vertical spatial scale + coordinate offsets. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[Binary Lightweight Neural Networks for Arbitrary Scale Super-Resolution of Remote Sensing Images](https://doi.org/10.1109/TGRS.2025.3529696)** — *IEEE TGRS, 2025* · `JCR Q1`
  - **What is continuous?** spatial scale. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[Latent Diffusion, Implicit Amplification: Efficient Continuous-Scale Super-Resolution for Remote Sensing Images](https://doi.org/10.1109/TGRS.2025.3571290)** — *IEEE TGRS, 2025* · [Code/Project](https://github.com/MoooJianG/LDCSR) · `JCR Q1`
  - **What is continuous?** spatial scale. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[A Continuous Digital Elevation Representation Model for DEM Super-Resolution](https://www.sciencedirect.com/science/article/pii/S0924271624000017)** — *ISPRS JPRS, 2024* · `JCR Q1`
  - **What is continuous?** 2-D geographic position (x,y) -> elevation z. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[MWLN: Multilevel Wavelet Learning Network for Continuous-Scale Remote-Sensing Image Super-Resolution](https://doi.org/10.1109/LGRS.2023.3339517)** — *IEEE GRSL, 2024* · `JCR Q1`
  - **What is continuous?** spatial scale. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[Continuous Remote Sensing Image Super-Resolution Based on Context Interaction in Implicit Function Space](https://arxiv.org/abs/2302.08046)** — *IEEE TGRS, 2023* · [Code/Project](https://github.com/KyanChen/FunSR) · `JCR Q1`
  - **What is continuous?** 2-D output coordinates + scale. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[Learning Dynamic Scale Awareness and Global Implicit Functions for Continuous-Scale Super-Resolution of Remote Sensing Images](https://ieeexplore.ieee.org/document/10026827/)** — *IEEE TGRS, 2023* · [Code/Project](https://github.com/hanlinwu/SADN) · `JCR Q1`
  - **What is continuous?** 2-D arbitrary coordinates + spatial scale. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[Lightweight Stepless Super-Resolution of Remote Sensing Images via Saliency-Aware Dynamic Routing Strategy](https://doi.org/10.1109/TGRS.2023.3236624)** — *IEEE TGRS, 2023* · [Code/Project](https://github.com/hanlinwu/SalDRN) · `JCR Q1`
  - **What is continuous?** spatial scale / output coordinates. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[Hierarchical Feature Aggregation and Self-Learning Network for Remote Sensing Image Continuous-Scale Super-Resolution](https://doi.org/10.1109/LGRS.2021.3122985)** — *IEEE GRSL, 2022* · `JCR Q1`
  - **What is continuous?** spatial scale. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[A Unified Network for Arbitrary Scale Super-Resolution of Video Satellite Images](https://doi.org/10.1109/TGRS.2020.3038653)** — *IEEE TGRS, 2021* · `JCR Q1`
  - **What is continuous?** spatial magnification scale. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.

### Spectral and hyperspectral fields (6)

- **[DCMArb: Decoupled-Collaborative Mamba for Arbitrary-scale Hyperspectral Super-resolution](https://doi.org/10.1016/j.isprsjprs.2026.06.009)** — *ISPRS JPRS, 2026* · [Code/Project](https://github.com/wangswhu/DCMArb) · `JCR Q1`
  - **What is continuous?** continuous spatial scale. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[Continuous Tensor Representation for Hyperspectral Anomaly Detection](https://doi.org/10.1109/TGRS.2025.3593391)** — *IEEE TGRS, 2025* · [Code/Project](https://github.com/Weihao-Wu/CBAR) · `JCR Q1`
  - **What is continuous?** 3-D spatial-spectral coordinates -> background tensor value. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[Meta-Collaborative Learning for Arbitrarily Scaled Hyperspectral Image Super-Resolution](https://doi.org/10.1109/TGRS.2025.3544253)** — *IEEE TGRS, 2025* · [Code/Project](https://github.com/ShuangWu-XDU/MCArb_HSI_SR) · `JCR Q1`
  - **What is continuous?** spatial magnification scale. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[Nonnegative Matrix Functional Factorization for Hyperspectral Unmixing With Nonuniform Spectral Sampling](https://doi.org/10.1109/TGRS.2023.3347414)** — *IEEE TGRS, 2024* · `JCR Q1`
  - **What is continuous?** wavelength lambda -> endmember spectra. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[Spectral-Wise Implicit Neural Representation for Hyperspectral Image Reconstruction](https://doi.org/10.1109/TCSVT.2023.3318366)** — *IEEE TCSVT, 2024* · `JCR Q1`
  - **What is continuous?** spectral coordinate / number of wavelength bands. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[Implicit Neural Representation Learning for Hyperspectral Image Super-Resolution](https://doi.org/10.1109/TGRS.2022.3230204)** — *IEEE TGRS, 2023* · [Code/Project](https://github.com/kaviezhang/INR-HSISR) · `JCR Q1`
  - **What is continuous?** 2-D spatial coordinates -> spectral radiance vector. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.

### Continuous-scale satellite and UAV video (4)

- **[Satellite Video Continuous Space-Time Super-Resolution via Mask-Based Temporal-Aware Warping and Cross-Level Frequency Integration](https://doi.org/10.1109/TGRS.2026.3666370)** — *IEEE TGRS, 2026* · `JCR Q1`
  - **What is continuous?** continuous spatial scale + temporal frame position. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[TAIS-Net: Time adaptive implicit sampling diffusion model for arbitrary-scale UAV video super-resolution](https://doi.org/10.1016/j.isprsjprs.2026.04.060)** — *ISPRS JPRS, 2026* · [Code/Project](https://github.com/cyber-lwk/TAIS-Net) · `JCR Q1`
  - **What is continuous?** spatial query scale/coordinates conditioned by temporal video information. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[Hazy Low-Quality Satellite Video Restoration Via Learning Optimal Joint Degradation Patterns and Continuous-Scale Super-Resolution Reconstruction](https://openaccess.thecvf.com/content/CVPR2025/html/Ni_Hazy_Low-Quality_Satellite_Video_Restoration_Via_Learning_Optimal_Joint_Degradation_CVPR_2025_paper.html)** — *CVPR, 2025* · `Top-conference Full/Regular`
  - **What is continuous?** spatial magnification scale. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[Deformable Convolution Alignment and Dynamic Scale-Aware Network for Continuous-Scale Satellite Video Super-Resolution](https://doi.org/10.1109/TGRS.2024.3366550)** — *IEEE TGRS, 2024* · [Code/Project](https://github.com/chongningni/CSVSR) · `JCR Q1`
  - **What is continuous?** spatial magnification scale. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.

### Spatiotemporal geophysical fields (2)

- **[Seamless Daily XCO2 Mapping Across China with Transformer and Geo Implicit Neural Representation](https://doi.org/10.1109/TGRS.2026.3732466)** — *IEEE TGRS, 2026* · [Code/Project](https://github.com/luojhello/oco_mapping) · `JCR Q1`
  - **What is continuous?** geographic coordinates + time -> XCO2. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[Streamlined Multilayer Perceptron for Contaminated Time Series Reconstruction: A Case Study in Coastal Zones of Southern China](https://www.sciencedirect.com/science/article/abs/pii/S0924271625000401)** — *ISPRS JPRS, 2025* · `JCR Q1`
  - **What is continuous?** time -> multispectral Landsat signal. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.

### Geophysical field representation and interpolation (2)

- **[A continuous implicit neural representation framework with gradient regularization for sea surface height reconstruction from satellite altimetry](https://doi.org/10.5194/gmd-19-7349-2026)** — *Geoscientific Model Development, 2026* · [Code/Project](https://doi.org/10.5281/zenodo.21232682) · `JCR Q1`
  - **What is continuous?** longitude/latitude (or horizontal space) + time -> SSH. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[5-D Seismic Data Interpolation by Continuous Representation](https://ieeexplore.ieee.org/document/10604902/)** — *IEEE TGRS, 2024* · `JCR Q1`
  - **What is continuous?** 5-D acquisition coordinates -> seismic amplitude. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.

### Radiance fields and implicit 3D geometry (7)

- **[Depth and Geometry Regularization for Neural Implicit Reconstruction From Few-View Satellite Images](https://doi.org/10.1109/TGRS.2026.3699879)** — *IEEE TGRS, 2026* · [Code/Project](https://github.com/Ljy0109/DGR-NeRF) · `JCR Q1`
  - **What is continuous?** 3-D position -> signed-distance/geometry field + view-dependent radiance. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[RDS-NeRF: Residual and Depth Supervision Neural Radiance Field for Multiscene 3-D Reconstruction of Satellite Images](https://doi.org/10.1109/TGRS.2025.3636144)** — *IEEE TGRS, 2025* · `JCR Q1`
  - **What is continuous?** 3-D position + viewing direction -> density/radiance. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[FVMD-ISRe: 3-D Reconstruction From Few-View Multidate Satellite Images Based on the Implicit Surface Representation of Neural Radiance Fields](https://doi.org/10.1109/TGRS.2024.3399786)** — *IEEE TGRS, 2024* · [Code/Project](https://github.com/HEU-super-generalized-remote-sensing/FVMD-ISRe) · `JCR Q1`
  - **What is continuous?** 3-D coordinates -> implicit satellite surface + radiance. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[PriNeRF: Prior Constrained Neural Radiance Field for Robust Novel View Synthesis of Urban Scenes with Fewer Views](https://www.sciencedirect.com/science/article/pii/S092427162400282X)** — *ISPRS JPRS, 2024* · [Code/Project](https://github.com/Dongber/PriNeRF) · `JCR Q1`
  - **What is continuous?** 3-D position + viewing direction -> urban radiance/density. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[rpcPRF: Generalizable MPI Neural Radiance Field for Satellite Camera With Single and Sparse Views](https://ieeexplore.ieee.org/document/10480403/)** — *IEEE TGRS, 2024* · `JCR Q1`
  - **What is continuous?** continuous altitude coordinate + satellite RPC geometry. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[SatensoRF: Fast Satellite Tensorial Radiance Field for Multidate Satellite Imagery of Large Size](https://doi.org/10.1109/TGRS.2024.3382632)** — *IEEE TGRS, 2024* · `JCR Q1` · *Cross-theme: Harmonization of Heterogeneous Remote-Sensing Measurements*
  - **What is continuous?** 3-D position + view/date-dependent appearance -> density/reflectance/ambient fields. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[UAV-ENeRF: Text-Driven UAV Scene Editing With Neural Radiance Fields](https://doi.org/10.1109/TGRS.2024.3379649)** — *IEEE TGRS, 2024* · `JCR Q1`
  - **What is continuous?** 3-D position + viewing direction -> UAV scene radiance/density. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.

### Gaussian and scattering scene fields (12)

- **[A Differentiable Method for Novel View SAR Image Generation via 3D Gaussian Splatting](https://www.sciencedirect.com/science/article/abs/pii/S0924271625004204)** — *ISPRS JPRS, 2026* · `JCR Q1`
  - **What is continuous?** 3-D position + viewing direction -> SAR scattering/radiance contribution. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[AeroGS: Scale-Aware Gaussian Splatting for Pose-Free Dynamic UAV Scene Reconstruction](https://openaccess.thecvf.com/content/CVPR2026/html/Li_AeroGS_Scale-Aware_Gaussian_Splatting_for_Pose-Free_Dynamic_UAV_Scene_Reconstruction_CVPR_2026_paper.html)** — *CVPR, 2026* · `Top-conference Full/Regular`
  - **What is continuous?** 3-D space + time + view. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[Efficient Incremental Large-Scale Orthophoto Generation via 3-D Gaussian Splatting SLAM](https://doi.org/10.1109/TGRS.2026.3710516)** — *IEEE TGRS, 2026* · `JCR Q1`
  - **What is continuous?** 3-D mapped scene + camera view -> orthophoto. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[GaussianCraft: Fine-grained 3D Gaussians for efficient large-scene surface reconstruction](https://doi.org/10.1016/j.isprsjprs.2026.03.020)** — *ISPRS JPRS, 2026* · `JCR Q1`
  - **What is continuous?** 3-D position/covariance -> scene surface and appearance. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[GeoGS: Geometric Prior-Guided Gaussian Splatting for Robust Urban Reconstruction from Sparse Views](https://www.sciencedirect.com/science/article/pii/S0924271626003588)** — *ISPRS JPRS, 2026* · `JCR Q1`
  - **What is continuous?** 3-D georeferenced position + view. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[GU-GS: Gaussian Splatting-Based Geometry Refinement and Uncertainty-Aware Learning Method for DSM Generation From Satellite Imagery](https://doi.org/10.1109/TGRS.2026.3671346)** — *IEEE TGRS, 2026* · [Code/Project](https://github.com/thessshy/GU-GS) · `JCR Q1`
  - **What is continuous?** 3-D position/covariance/opacity -> satellite scene geometry. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[SA-GS: Season-Aware Affine 3D Gaussian Splatting for Satellite Image Rendering](https://www.sciencedirect.com/science/article/pii/S0924271626001905)** — *ISPRS JPRS, 2026* · [Code/Project](https://github.com/CosyXu/SA-GS) · `JCR Q1`
  - **What is continuous?** 3-D position + affine satellite view + season. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[Tortho–SatGS: A 3-D Gaussian Splatting-Based Method for True Orthophoto Generation From Multiview Satellite Imagery](https://doi.org/10.1109/TGRS.2026.3707311)** — *IEEE TGRS, 2026* · `JCR Q1`
  - **What is continuous?** 3-D scene position + satellite view -> orthorectified appearance. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[Gaussian Splatting for Efficient Satellite Image Photogrammetry](https://openaccess.thecvf.com/content/CVPR2025/html/Aira_Gaussian_Splatting_for_Efficient_Satellite_Image_Photogrammetry_CVPR_2025_paper.html)** — *CVPR, 2025* · [Code/Project](https://mezzelfo.github.io/EOGS/) · `Top-conference Full/Regular`
  - **What is continuous?** 3-D Earth-surface geometry + view-dependent appearance. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[SAR-GS: Gaussian Splatting-Based SAR Image Rendering and Target Reconstruction](https://doi.org/10.1109/TGRS.2025.3639636)** — *IEEE TGRS, 2025* · `JCR Q1`
  - **What is continuous?** 3-D position + SAR observation geometry -> scattering intensity. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[SpectralGaussians: Semantic, Spectral 3D Gaussian Splatting for Multi-Spectral Scene Representation, Visualization and Analysis](https://www.sciencedirect.com/science/article/pii/S0924271625002345)** — *ISPRS JPRS, 2025* · `JCR Q1`
  - **What is continuous?** 3-D position + viewing direction + spectral band. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.
- **[ULSR-GS: Urban Large-Scale Surface Reconstruction Gaussian Splatting with Multi-View Geometric Consistency](https://www.sciencedirect.com/science/article/pii/S092427162500396X)** — *ISPRS JPRS, 2025* · [Code/Project](https://ulsrgs.github.io) · `JCR Q1`
  - **What is continuous?** 3-D position/covariance -> urban surface. **Why this theme?** Continuous representation or arbitrary-coordinate reconstruction is the primary contribution.


<a id="harmonization"></a>
## 2. Harmonization of Heterogeneous Remote-Sensing Measurements

How heterogeneous observations are related through continuous spatial/spectral/temporal coordinates and sensor-aware mappings: HSI–MSI, PAN–MS, optical–SAR, LiDAR–imagery, cross-view/platform and multiresolution/multitemporal data. Merely concatenating modalities is not sufficient.

### Hyperspectral–multispectral/RGB fusion (14)

- **[Arbitrary-Scale Fusion Operator for High-Resolution Hyperspectral Imaging](https://doi.org/10.1109/TMM.2026.3655472)** — *IEEE Transactions on Multimedia, 2026* · `JCR Q1`
  - **What is continuous?** spatial scale; HSI/MSI treated as degraded spectral functions. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[Arbitrary-scale spatial-spectral fusion using kernel integral and progressive resampling](https://doi.org/10.1016/j.inffus.2026.104143)** — *Information Fusion, 2026* · [Code/Project](https://github.com/weili419/SFNO) · `JCR Q1`
  - **What is continuous?** spatial scale + image-function domain. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[MGINR-WGAN: A Multiscale Guided Implicit Neural Representation Wasserstein GAN for Hyperspectral and Multispectral Image Fusion](https://doi.org/10.1109/JSTARS.2026.3697374)** — *IEEE JSTARS, 2026* · [Code/Project](https://github.com/zhangyanxa/MGINR-WGAN) · `JCR Q1`
  - **What is continuous?** 2-D spatial query coordinates -> hyperspectral vector. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[Solving Spatial-Spectral Fusion with Latent Spectral Operators](https://proceedings.mlr.press/v306/li26en.html)** — *ICML, 2026* · [Code/Project](https://github.com/weili419/LSO) · `Top-conference Full/Regular`
  - **What is continuous?** spectral functions / frequency basis; spatial scale transfer. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[A spatial-frequency dual-domain implicit guidance method for hyperspectral and multispectral remote sensing image fusion based on Kolmogorov–Arnold Network](https://doi.org/10.1016/j.inffus.2025.103261)** — *Information Fusion, 2025* · [Code/Project](https://github.com/chunyuzhu/SFIGNet) · `JCR Q1`
  - **What is continuous?** 2-D spatial coordinates / implicit feature sampling. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[Arbitrary-scale Fusion Neural Operator](https://doi.org/10.1145/3746027.3755312)** — *ACM MM, 2025* · `Top-conference Full/Regular`
  - **What is continuous?** spatial scale + image-function domain. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[Mamba Collaborative Implicit Neural Representation for Hyperspectral and Multispectral Remote Sensing Image Fusion](https://doi.org/10.1109/TGRS.2025.3537638)** — *IEEE TGRS, 2025* · [Code/Project](https://github.com/chunyuzhu/MCIFNet) · `JCR Q1`
  - **What is continuous?** spatial query coordinates / continuous feature mapping. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[OTIAS: OcTree Implicit Adaptive Sampling for Multispectral and Hyperspectral Image Fusion](https://ojs.aaai.org/index.php/AAAI/article/view/32275)** — *AAAI, 2025* · [Code/Project](https://github.com/shangqideng/OTIAS) · `Top-conference Full/Regular`
  - **What is continuous?** 3-D spatial-spectral coordinate tree. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[An Implicit Transformer-based Fusion Method for Hyperspectral and Multispectral Remote Sensing Image](https://doi.org/10.1016/j.jag.2024.103955)** — *Int. J. Applied Earth Observation and Geoinformation, 2024* · `JCR Q1`
  - **What is continuous?** spatial and spectral point coordinates / feature positions. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[Arbitrary-Scale Hyperspectral Image Super-Resolution From a Fusion Perspective With Spatial Priors](https://doi.org/10.1109/TGRS.2024.3481041)** — *IEEE TGRS, 2024* · `JCR Q1`
  - **What is continuous?** 2-D spatial coordinates + spatial scale. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[Fourier-Enhanced Implicit Neural Fusion Network for Multispectral and Hyperspectral Image Fusion](https://mlanthology.org/neurips/2024/liang2024neurips-fourierenhanced/)** — *NeurIPS, 2024* · [Code/Project](https://github.com/294coder/Efficient-MIF) · `Top-conference Full/Regular`
  - **What is continuous?** spatial coordinates / implicit feature function. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[An adaptive multi-perceptual implicit sampling for hyperspectral and multispectral remote sensing image fusion](https://doi.org/10.1016/j.jag.2023.103560)** — *Int. J. Applied Earth Observation and Geoinformation, 2023* · [Code/Project](https://github.com/chunyuzhu/AMGSGAN) · `JCR Q1`
  - **What is continuous?** 2-D spatial query positions. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[QIS-GAN: A Lightweight Adversarial Network With Quadtree Implicit Sampling for Multispectral and Hyperspectral Image Fusion](https://doi.org/10.1109/TGRS.2023.3332176)** — *IEEE TGRS, 2023* · [Code/Project](https://github.com/chunyuzhu/QIS-GAN) · `JCR Q1`
  - **What is continuous?** 2-D spatial coordinates. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[SS-INR: Spatial-Spectral Implicit Neural Representation Network for Hyperspectral and Multispectral Image Fusion](https://doi.org/10.1109/TGRS.2023.3317413)** — *IEEE TGRS, 2023* · [Code/Project](https://github.com/wxy11-27/SS-INR) · `JCR Q1`
  - **What is continuous?** spatial coordinates + spatial-spectral latent features -> HRHSI spectrum. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.

### Panchromatic–multispectral fusion (3)

- **[Spatial-Spectral Residuals Informed Diffusion Neural Operator for Pan-sharpening](https://openaccess.thecvf.com/content/CVPR2026/html/Huang_Spatial-Spectral_Residuals_Informed_Diffusion_Neural_Operator_for_Pan-sharpening_CVPR_2026_paper.html)** — *CVPR, 2026* · `Top-conference Full/Regular`
  - **What is continuous?** spatial-spectral image functions. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[Physics-informed Neural Operator for Pansharpening](https://proceedings.neurips.cc/paper_files/paper/2025/hash/89af8e4eb696738f2c9e589522968a09-Abstract-Conference.html)** — *NeurIPS, 2025* · [Code/Project](https://github.com/ez4lionky/PINO) · `Top-conference Full/Regular` · *Cross-theme: Physical Inference from Continuous Geophysical Fields*
  - **What is continuous?** spatial coordinates (x,y) + wavelength lambda -> radiance. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[Progressive High-Frequency Reconstruction for Pan-Sharpening with Implicit Neural Representation](https://ojs.aaai.org/index.php/AAAI/article/view/28214)** — *AAAI, 2024* · `Top-conference Full/Regular`
  - **What is continuous?** spatial-spectral coordinates / continuous feature position. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.

### Optical–SAR continuous fusion (1)

- **[Multimodal-Interactive GCN-Guided Space–Frequency Implicit Fusion Network for Semantic Segmentation of Optical and SAR Images](https://doi.org/10.1109/TGRS.2026.3691414)** — *IEEE TGRS, 2026* · `JCR Q1`
  - **What is continuous?** 2-D spatial coordinates and Fourier-domain feature sampling. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.

### LiDAR–optical continuous scene fusion (5)

- **[ARSGaussian: 3D Gaussian Splatting with LiDAR for aerial remote sensing novel view synthesis](https://doi.org/10.1016/j.isprsjprs.2025.10.022)** — *ISPRS JPRS, 2026* · [Code/Project](https://github.com/WenjuanZhang-aircas/ARSGaussian) · `JCR Q1`
  - **What is continuous?** 3-D position + viewing direction. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[LDI-3DGS: Structurally Robust 3-D Gaussian Splatting Driven by UAV-Borne LiDAR Depth and Intensity Priors](https://doi.org/10.1109/TGRS.2026.3727449)** — *IEEE TGRS, 2026* · `JCR Q1`
  - **What is continuous?** 3-D position + radiance/intensity. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[Accurate and complete neural implicit surface reconstruction in street scenes using images and LiDAR point clouds](https://doi.org/10.1016/j.isprsjprs.2024.12.012)** — *ISPRS JPRS, 2025* · [Code/Project](https://github.com/SCH1001/StreetRecon) · `JCR Q1`
  - **What is continuous?** 3-D coordinates -> signed distance/surface. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[MFGaussian: multi-modal data fusion based 3D Gaussian splatting for accurate and robust scene representation](https://doi.org/10.1080/17538947.2025.2478584)** — *International Journal of Digital Earth, 2025* · `JCR Q1` · *Cross-theme: Representation of Continuous Geophysical Fields*
  - **What is continuous?** 3-D location and continuous view direction; multi-sensor laser-scanned geometry and camera appearance. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[LiDeNeRF: Neural Radiance Field Reconstruction with Depth Prior Provided by LiDAR Point Cloud](https://www.sciencedirect.com/science/article/pii/S0924271624000261)** — *ISPRS JPRS, 2024* · `JCR Q1`
  - **What is continuous?** 3-D position + viewing direction -> scene density/radiance. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.

### Cross-platform sensing and geo-alignment (4)

- **[GAIR: Location-Aware Self-Supervised Contrastive Pre-Training with Geo-Aligned Implicit Representations](https://www.sciencedirect.com/science/article/pii/S092427162600208X)** — *ISPRS JPRS, 2026* · [Code/Project](https://github.com/zpl99/GAIR) · `JCR Q1`
  - **What is continuous?** geographic/spatial coordinates -> continuous latent feature field. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[Urban-GS: A Unified 3D Gaussian Splatting Framework for Compact and High-Fidelity Aerial-to-Street Reconstruction](https://openaccess.thecvf.com/content/CVPR2026/html/Wang_Urban-GS_A_Unified_3D_Gaussian_Splatting_Framework_for_Compact_and_CVPR_2026_paper.html)** — *CVPR, 2026* · [Code/Project](https://github.com/wangm-buaa/Urban-GS) · `Top-conference Full/Regular`
  - **What is continuous?** 3-D position + viewpoint across aerial/street domains. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[Cross-sensor adaptive semantic segmentation for mobile laser scanning point clouds based on continuous potential scene surface reconstruction](https://doi.org/10.1016/j.isprsjprs.2025.07.021)** — *ISPRS JPRS, 2025* · [Code/Project](https://github.com/PCsFJNU/CrossSensorAdaptiveSemanticSeg) · `JCR Q1`
  - **What is continuous?** 3-D position -> continuous potential scene surface/features. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[Horizon-GS: Unified 3D Gaussian Splatting for Large-Scale Aerial-to-Ground Scenes](https://openaccess.thecvf.com/content/CVPR2025/html/Jiang_Horizon-GS_Unified_3D_Gaussian_Splatting_for_Large-Scale_Aerial-to-Ground_Scenes_CVPR_2025_paper.html)** — *CVPR, 2025* · `Top-conference Full/Regular`
  - **What is continuous?** 3-D position + continuous aerial-to-ground viewpoint. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.

### Multi-temporal and cross-resolution observations (2)

- **[Neural Operator-Based Continuous Tensor Representation for Thick Cloud Removal in Multiresolution Remote Sensing Images](https://doi.org/10.1109/TGRS.2026.3731463)** — *IEEE TGRS, 2026* · `JCR Q1` · *Cross-theme: Representation of Continuous Geophysical Fields*
  - **What is continuous?** continuous spatial-spectral-temporal tensor coordinates across resolutions. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.
- **[A Unified Sentinel-2 Imagery Thick Cloud Removal and Rescaling Framework From a Continuous Perspective](https://doi.org/10.1109/TGRS.2025.3609321)** — *IEEE TGRS, 2025* · `JCR Q1` · *Cross-theme: Representation of Continuous Geophysical Fields*
  - **What is continuous?** 2-D spatial coordinates/resolution -> material abundance maps; time remains discretely indexed. **Why this theme?** The continuous mechanism reconciles heterogeneous observations, modalities, resolutions, times or viewing configurations.


<a id="physical-inference"></a>
## 3. Physical Inference from Continuous Geophysical Fields

How continuous geophysical fields support physics-informed constraints, forward/inverse problems, operator learning, parameter retrieval, biophysical inference, and evolution modeling. A neural-operator architecture alone is not proof of PDE enforcement.

### Seismic wave physics, operators and inversion (19)

- **[A Generalized Eikonal Solver Using Operator Learning](https://doi.org/10.1109/TGRS.2026.3674885)** — *IEEE TGRS, 2026* · `JCR Q1`
  - **What is continuous?** velocity/traveltime input fields + source location -> traveltime field. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Adaptive SIREN-PINN With Principled Initialization: A Frequency-Aware and Singularity-Robust Framework for Solver-Free Acoustic Seismic Wave Modeling](https://doi.org/10.1109/TGRS.2026.3655956)** — *IEEE TGRS, 2026* · `JCR Q1`
  - **What is continuous?** spatial coordinates -> acoustic wavefield. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Enhancing Frequency Response in Implicit Full Waveform Inversion via Fourier Encoding](https://doi.org/10.1109/TGRS.2026.3684378)** — *IEEE TGRS, 2026* · `JCR Q1`
  - **What is continuous?** spatial coordinates -> subsurface velocity/parameter field. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Least-squares-embedded optimization for accelerated convergence of PINNs in high-frequency acoustic wavefield simulations](https://doi.org/10.1016/j.cageo.2026.106162)** — *Computers & Geosciences, 2026* · `JCR Q1`
  - **What is continuous?** 2-D spatial coordinates -> complex scattered wavefield. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[M-SSIM-3DIFWI: 3-D Implicit Full Waveform Inversion Based on the Multiscale Structural Similarity](https://doi.org/10.1109/TGRS.2026.3704938)** — *IEEE TGRS, 2026* · `JCR Q1`
  - **What is continuous?** 3-D spatial coordinates -> velocity field. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Microseismic monitoring with the quake neural operator](https://doi.org/10.1038/s41467-026-73965-6)** — *Nature Communications, 2026* · [Code/Project](https://zenodo.org/records/20072888) · `JCR Q1`
  - **What is continuous?** continuous waveform function over time and station coordinates -> detection/location functions. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Unveiling the Mechanism of Continuous Representation Full-Waveform Inversion: A Wave-Based Neural Tangent Kernel Framework](https://proceedings.iclr.cc/paper_files/paper/2026/hash/c89f09849eb5af489abb122394ff0f0b-Abstract-Conference.html)** — *ICLR, 2026* · `Top-conference Full/Regular`
  - **What is continuous?** spatial coordinates -> subsurface parameter field. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Full-Waveform Inversion With Velocity Model Low-Rank Implicit Neural Representation](https://doi.org/10.1109/TGRS.2025.3594184)** — *IEEE TGRS, 2025* · `JCR Q1`
  - **What is continuous?** 2-D spatial coordinates -> velocity. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Microseismic Source Localization Using Fourier Neural Operator With Application to Field Data From Utah FORGE](https://doi.org/10.1109/TGRS.2025.3533635)** — *IEEE TGRS, 2025* · `JCR Q1`
  - **What is continuous?** seismic waveform/field input across acquisition geometry -> source location. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Physics-Informed Waveform Inversion Using Pretrained Wavefield Neural Operators](https://doi.org/10.1109/TGRS.2025.3624025)** — *IEEE TGRS, 2025* · `JCR Q1`
  - **What is continuous?** velocity field -> seismic wavefield. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Fully Convolutional Network-Enhanced DeepONet-Based Surrogate of Predicting the Travel-Time Fields](https://doi.org/10.1109/TGRS.2024.3401196)** — *IEEE TGRS, 2024* · [Code/Project](https://github.com/ismyif/fc-deeponet) · `JCR Q1`
  - **What is continuous?** velocity/source functions -> traveltime field. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Physics-Informed Robust and Implicit Full Waveform Inversion Without Prior and Low-Frequency Information](https://doi.org/10.1109/TGRS.2024.3416547)** — *IEEE TGRS, 2024* · `JCR Q1`
  - **What is continuous?** spatial coordinates -> subsurface parameter model. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[PINN-Based Seismic Wavefield Simulation With Learnable Multiscale Fourier Feature Mapping and Adaptive Activation Function](https://doi.org/10.1109/LGRS.2024.3485908)** — *IEEE GRSL, 2024* · `JCR Q1`
  - **What is continuous?** spatial coordinates -> Helmholtz wavefield. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Seismic Traveltime Simulation for Variable Velocity Models Using Physics-Informed Fourier Neural Operator](https://doi.org/10.1109/TGRS.2024.3457949)** — *IEEE TGRS, 2024* · `JCR Q1`
  - **What is continuous?** velocity/background-traveltime fields -> perturbation traveltime field. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Transfer Learning Fourier Neural Operator for Solving Parametric Frequency-Domain Wave Equations](https://doi.org/10.1109/TGRS.2024.3440199)** — *IEEE TGRS, 2024* · `JCR Q1`
  - **What is continuous?** parameter/velocity functions + source/frequency -> wavefield function. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Implicit Seismic Full Waveform Inversion With Deep Neural Representation](https://doi.org/10.1029/2022JB025964)** — *JGR: Solid Earth, 2023* · [Code/Project](https://doi.org/10.5281/zenodo.7262564) · `JCR Q1`
  - **What is continuous?** spatial coordinates -> subsurface physical parameters. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Multilayer Perceptron and Bayesian Neural Network-Based Elastic Implicit Full Waveform Inversion](https://doi.org/10.1109/TGRS.2023.3265657)** — *IEEE TGRS, 2023* · `JCR Q1`
  - **What is continuous?** spatial coordinates -> elastic model parameters/distributions. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Rapid Seismic Waveform Modeling and Inversion With Neural Operators](https://doi.org/10.1109/TGRS.2023.3264210)** — *IEEE TGRS, 2023* · `JCR Q1`
  - **What is continuous?** velocity/source functions -> full elastic wavefield. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Solving Seismic Wave Equations on Variable Velocity Models With Fourier Neural Operator](https://doi.org/10.1109/TGRS.2023.3333663)** — *IEEE TGRS, 2023* · `JCR Q1`
  - **What is continuous?** velocity field + source location/frequency -> seismic wavefield. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.

### Electromagnetic and magnetotelluric inference (4)

- **[EFKAN: A KAN-Integrated Neural Operator for Efficient Magnetotelluric Forward Modeling](https://doi.org/10.1016/j.cageo.2025.106052)** — *Computers & Geosciences, 2026* · [Code/Project](https://github.com/linfengyu77/EFKAN) · `JCR Q1`
  - **What is continuous?** survey location + frequency, conditioned on resistivity field -> MT response. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Rapid 2-D Magnetotelluric Forward Modeling via Automatic Differentiation Fourier Neural Operator With Gradient Supervision](https://doi.org/10.1109/TGRS.2026.3701700)** — *IEEE TGRS, 2026* · `JCR Q1`
  - **What is continuous?** grid position + frequency conditioned on resistivity field -> EM response. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Reversible Deep Operator Network for Grid-Independent, Multi-Scale Magnetotelluric Inversion and Uncertainty Quantification](https://doi.org/10.1029/2025JB033046)** — *JGR: Solid Earth, 2026* · `JCR Q1`
  - **What is continuous?** station position + frequency + survey scale; resistivity/response functions. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Rapid Surrogate Modeling of Electromagnetic Data in Frequency Domain Using Neural Operator](https://doi.org/10.1109/TGRS.2022.3222507)** — *IEEE TGRS, 2022* · `JCR Q1`
  - **What is continuous?** site location + frequency conditioned on conductivity/resistivity field -> EM response. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.

### Gravity and potential-field inference (3)

- **[Implicit Neural Representations for 3D Gravity Inversion](https://doi.org/10.1016/j.cageo.2025.106082)** — *Computers & Geosciences, 2026* · `JCR Q1`
  - **What is continuous?** 3-D spatial coordinates -> density. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Three-dimensional inversion of gravity data using implicit neural representations and scientific machine learning](https://doi.org/10.1038/s41598-026-55960-5)** — *Scientific Reports, 2026* · [Code/Project](https://zenodo.org/records/19440024) · `JCR Q1`
  - **What is continuous?** 3-D spatial coordinates -> density. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Implicit neural representation for potential field geophysics](https://doi.org/10.1038/s41598-024-83979-z)** — *Scientific Reports, 2025* · `JCR Q1`
  - **What is continuous?** 3-D coordinates -> magnetic/gravity potential-field value. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.

### Ionospheric and atmospheric inference (2)

- **[Spatiotemporal Implicit Neural Representation for Ionospheric Tomography With Multi-LEO Occultation Data](https://doi.org/10.1109/TGRS.2026.3667515)** — *IEEE TGRS, 2026* · `JCR Q1`
  - **What is continuous?** 3-D space + time -> ionospheric electron-density/prior field. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.
- **[Global 4-D Ionospheric STEC Prediction Based on DeepONet for GNSS Rays](https://doi.org/10.1109/TGRS.2024.3422150)** — *IEEE TGRS, 2024* · `JCR Q1`
  - **What is continuous?** ray geometry (space) + time -> STEC; input STEC function -> output function. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.

### Biophysical parameter inference (1)

- **[NeRF-LAI: A Hybrid Method Combining Neural Radiance Field and Gap-Fraction Theory for Deriving Effective Leaf Area Index of Corn and Soybean Using Multi-Angle UAV Images](https://www.sciencedirect.com/science/article/abs/pii/S0034425725002482)** — *Remote Sensing of Environment, 2025* · `JCR Q1` · *Cross-theme: Representation of Continuous Geophysical Fields*
  - **What is continuous?** 3-D position + viewing direction -> vegetation radiance/density field. **Why this theme?** Geophysical forward/inverse mapping, physical diagnostics or physics-aware field inference is the primary objective.

---

## Curation notes

- **Representation ≠ generic implicit features.** A network with implicit activations or positional encoding is not automatically a continuous geophysical-field model. Queryable fields or well-established continuous sampling/field behavior must be documented.
- **Harmonization ≠ generic multimodal CNN.** Inclusion requires a continuous representation/operator/sampling mechanism that materially contributes to integration of sensing configurations. HSI/MSI and PAN/MS count as heterogeneous modalities/sensor bands; cross-temporal/resolution sampling also fits the white paper.
- **Physical inference ≠ every FNO.** Operators learning maps between physical fields qualify only when their functional/geophysical role is substantiated. PDE-constrained losses, data-driven surrogate forward models and parameter inversion are distinct mechanisms; do not conflate them.
- **JCR Q1 is the journal gate.** CAS Category 2 alone is *not* enough. GJI and IEEE Transactions on Computational Imaging were removed from the core following 2025 JCR Q2 checks, while their references remain archived in the exclusion/audit files.
- **Original 3D Gaussian Splatting (SIGGRAPH 2023, ACM TOG)** is a foundational method, not itself a remote-sensing paper; it is not counted. SIGGRAPH and SIGGRAPH Asia full technical papers are eligible if *directly* relevant.
- **Code links are conservative.** No repository link is shown for papers whose official implementation is merely announced or currently empty. Existing old links are carried forward from the previous audit rather than re-verified one by one in this reorganization.

## Contribution and updates

For new paper proposals, see [CONTRIBUTING.md](CONTRIBUTING.md). This is an evolving curation table, **not a claim of exhaustive coverage** of all eligible publications. Missing or borderline records should be proposed with the publication page, official JCR subject quartile/year, and a concrete description of the continuous variable.
