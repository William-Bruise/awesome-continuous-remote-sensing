# White-Paper Alignment and Classification Decisions

Reference proposal: **Continuous Remote Sensing: From Discrete Observations to Continuous Earth Fields** (IEEE Geoscience and Remote Sensing Magazine review white paper, October 2026).

The three principal review sections are **not** model architecture families; they ask *what is represented*, *how disparate measurements are reconciled*, and *what physical quantities and processes may be inferred*.

| White paper theme | Necessary central mechanism | Typical examples | Explicit boundary |
| --- | --- | --- | --- |
| **I. Representation of Continuous Geophysical Fields** | A continuous observation response/field or queryable scene in spatial, spectral, temporal or 3-D coordinates | Single-sensor INR super-resolution, continuous HSI or DEM fields, radiance/surface/GS scenes | A latent feature enhancement alone is not a proven geophysical field representation |
| **II. Harmonization of Heterogeneous Remote-Sensing Measurements** | Continuous coordinates, observation operators, or scene representations unify different measurement modalities/resolutions/times/views | HSI–MSI/RGB, PAN–MS, optical–SAR, LiDAR+camera, multisensor/multitemporal reconstruction | Generic feature concatenation or spatial attention without a continuous mechanism is excluded |
| **III. Physical Inference from Continuous Geophysical Fields** | Governing equations, physical inverse/forward models, functional operators or parameter retrieval use continuous Earth fields | Wave/EM/PINN, subsurface inversion, ionospheric operator maps, biophysical LAI retrieval | FNO/DeepONet terminology alone does not prove a physics-informed loss or constraints |

## Key cross-theme adjudications

- **PINO for Pansharpening (NeurIPS 2025): II (primary), III (secondary).** The task fuses PAN with multi-band images via a physically formulated spectral-response model and field/operator mechanisms. Physics-informed title alone should not move a fusion paper out of harmonization.
- **Sentinel-2 multiresolution thick-cloud removal / neural-operator continuous tensor cloud removal: II (primary), I (secondary).** Heterogeneous resolution and temporally separated observations are crucial to the task; reconstruction and representation mechanisms overlap.
- **DCMArb / arbitrary-scale hyperspectral single-sensor SR: I.** Arbitrary output resolution alone does not turn an individual-sensor image problem into *multimodal* harmonization.
- **NeRF-LAI: III (primary), I (secondary).** 3D radiance representation is instrumental for physically meaningful vegetation-leaf-area inference.
- **5-D seismic interpolation: I.** Missing-sample interpolation is not by itself physical inverse inference; geophysical acoustic/wave-equation inversion and forward modeling belong to III.
- **Satellite–street imagery, LiDAR–optical 3-D reconstruction, and optical–SAR GSIS/GFIS: II.** A shared continuous space mediates different observation configurations.
- **SIGGRAPH 2023 original 3DGS:** important general foundation, **not** a remote-sensing paper and not counted in the core.

## Editorial changes from the previous bibliography

- Replaces seven architecture/modality-oriented sections with exactly three scientific objective-oriented sections.
- Replaces `CAS 1/2 OR JCR Q1` with **JCR Q1 only** for journals. Previously included *Geophysical Journal International* and *IEEE Transactions on Computational Imaging* records moved to the quality-exclusion archive because they were not verified as 2025 JCR Q1.
- Removes *NeRI* from the core on a stricter definition of geophysical-field representation, while keeping its citation/reason in the scope-exclusion table.
- Adds an optical–SAR implicit fusion TGRS paper and the LiDAR–optical *MFGaussian* digital-earth journal paper with explicit evidence. Empty/unreleased official code pages are not advertised as implementations.
- Preserves the full historical audit fields, prior exclusions and negative evidence. Primary/secondary theme assignments and evidence are available in CSV for later manual correction.

## Open coverage gaps

The corpus remains an **audited starting set rather than an exhaustive census**. Optical–SAR and multi-physics/multivariable coupling are notably underrepresented compared with single-sensor continuous SR and seismic inversion. Future additions should prioritize their connection to a *continuous* Earth field and verify conference main-track / **JCR Q1** status before inclusion.
