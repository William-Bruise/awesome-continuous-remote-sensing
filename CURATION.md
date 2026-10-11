# Curation Policy — IEEE GRSM White Paper Alignment

**Revision: 2026-10-11.** This repository curates peer-reviewed work relevant to **Continuous Remote Sensing: From Discrete Observations to Continuous Earth Fields**.

## Scientific scope: two positive gates

1. **Earth/remote-sensing relevance.** The paper must directly address Earth-observation, remote sensing, photogrammetry/geospatial observation, atmospheric/oceanic/ionospheric sensing, or geophysical sensing, reconstruction, forward modeling or inversion.
2. **Continuity is substantive.** Identify the *continuous object* and its role: arbitrary 2-D/3-D coordinates, wavelength, time, altitude, viewing geometry, a spectral/spatiotemporal function, radiance/surface/scattering field, continuous tensor, or a field-to-field operator where the functional domain matters.

A paper must pass **both** gates. Do not treat arbitrary neural activation, generic positional encoding, FNO/PINN/NeRF/3DGS terminology or multimodal feature concatenation as enough on their own.

## Venue gate — strict minimum JCR Q1

- **Journals:** **JCR Q1 in at least one indexed JCR subject category**, according to the verifiable 2025 JCR edition (the latest available as of this update), not CAS quartile, SCImago/SJR Q1, or journal impact-factor magnitude. Record JCR category and the applicable year where possible. If conflicting evidence makes JCR Q1 unverifiable, hold outside the core pending manual verification.
- **Conferences:** Full/Regular **main-conference** papers at the user-defined set: **CVPR, ICCV, ECCV, NeurIPS, ICLR, ICML, AAAI, ACM MM, SIGGRAPH, SIGGRAPH Asia**. SIGGRAPH/Asia technical papers often appear in *ACM Transactions on Graphics*; avoid double counting the conference/journal version. Other CCF-A papers may be considered only after explicit review.
- **Not eligible:** preprint-only, workshops, Findings, short/extended abstracts, posters/demos, unverified conference tracks, journal venues with JCR Q2 or lower, or journals where only CAS Category 1/2 is known.

**Examples of revised journal decisions (2025 JCR):** *Geophysical Journal International*: **Q2**, 35/103 in Geochemistry & Geophysics (Oxford publisher, https://academic.oup.com/gji/pages/about); *IEEE Transactions on Computational Imaging*: **Q2** (https://www.minicod.com/journals/ieee-transactions-on-computational-imaging-7888b16c); *International Journal of Digital Earth*: **Q1** (https://www.juqikan.com/sci/17538947.html). *IEEE GRSL* has Q1 in Geochemistry & Geophysics although Remote Sensing quartile may differ: only a **best-category JCR Q1** threshold is applied consistently.

## Exactly three primary themes

### I. Representation of Continuous Geophysical Fields

**Question:** How can underlying Earth quantities be expressed as queryable continuous functions/fields/tensors or spatial/temporal/spectral/3-D Gaussian/radiance models?

Typical single-modality examples: continuous-scale remote-sensing super-resolution; continuous spectrum/wavelength modeling; digital elevation fields; NeRF/3DGS scene representation; seismic 5-D interpolation (when no governing-law inference is primary).

### II. Harmonization of Heterogeneous Remote-Sensing Measurements

**Question:** How does a continuous representation help reconcile observations from different sensors/modalities, resolutions, times or viewing geometries?

Examples: HSI–MSI/RGB fusion, PAN–MS pansharpening, optical–SAR implicit fusion, LiDAR–image NeRF/3DGS, satellite/street-view alignment, multiresolution or multi-temporal cloud reconstruction.

**Counterexample:** concatenating SAR and optical feature tensors in a discrete CNN is *not* sufficient without a meaningful continuous representational mechanism.

### III. Physical Inference from Continuous Geophysical Fields

**Question:** How are physical laws, field-to-field operators, inversion or geophysical/biophysical parameter inference enabled or constrained by continuous representations?

Examples: wave/EM/ionospheric forward models, PINN PDE residuals, operator surrogates, velocity/resistivity/gravity inversion, radiance-geometry models linked to physically meaningful leaf-area inference.

**Distinguish:** physics-informed constraints (explicit PDE/observation laws), data-driven neural-operator surrogate maps, and physical parameter inversion; they are **not identical**.

## Assignment rule

Give each paper **one primary theme** chosen by the main scientific objective. Add `secondary_theme` for genuine overlaps rather than duplicating the paper count. E.g., *Physics-informed Neural Operator for Pansharpening* primarily harmonizes PAN/MS observations (**II**), secondarily exploits physical/sensor constraints (**III**). *NeRF-LAI* primarily infers vegetation physical parameters (**III**), with NeRF field modeling as a secondary representation (**I**).

## Paper-level evidence and reproducibility

- `data/papers.csv` is the **core** list (one row per included work), with `category` = primary theme and `subtopic` = detailed subject.
- `data/paper_level_audit.csv` archives both included and excluded candidates. Required: `continuity_variable`, `what_is_continuous`, `why_continuous_remote_sensing`, `review_decision`, and `classification_reason`.
- `data/venue_quality_audit.csv` tracks venue evidence; `data/excluded_by_quality.csv` and `data/excluded_from_three_theme_review.csv` preserve negative decisions rather than deleting inconvenient papers.
- Historic `data/excluded_from_ledger_v2.csv` and `data/context_negative_evidence.csv` are retained as audit history, not counted in the core.
- Publication links should point to publisher DOI/proceedings where available. Only link verified **official, materially released** code/project pages. A promised-but-unreleased codebase must keep `code_url` blank. Legacy code links were not exhaustively re-tested during this taxonomy migration.
- Incomplete venue/continuity verification is an uncertainty marker, **not** affirmative evidence of inclusion.

## What is NOT included as core

The original general-purpose INR, NeRF, FNO and *3D Gaussian Splatting for Real-Time Radiance Field Rendering* (SIGGRAPH 2023 / ACM TOG) are methodological background, not direct Earth sensing papers. Specialized continuous models for unrelated medical/consumer imaging, ordinary fixed-grid multisensor fusion, workshop-only manuscripts and task-specific latent features without geophysical field interpretation are also excluded.

The journal thresholds are strict **bibliography-selection rules**, not judgments of technical significance or citation impact.
