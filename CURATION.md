# Curation Policy

This repository is intended to support a scholarly review of **Continuous Remote Sensing**. Inclusion is conservative: it is better to omit a borderline paper than to inflate the bibliography with loosely related or weak-venue work.

## Gate A — scientific relevance

A paper must directly study remote sensing, Earth observation, photogrammetry/geospatial sensing, atmospheric/ocean/ionospheric sensing, or geophysical sensing/inversion, and continuity must be central to the method.

At least one of the following must be a substantive modeling mechanism:

- continuous coordinate/function/field representation over space, wavelength, time, view, or physical parameters;
- genuine arbitrary/continuous-scale or off-grid querying;
- continuous tensor/function factorization;
- neural-operator mapping between fields/functions where function-space/discretization behavior is part of the method;
- remote-sensing NeRF / radiance field / implicit surface;
- remote-sensing Gaussian field / Gaussian splatting as the represented scene or signal.

Generic SIREN, LIIF, NeRF, FNO, 3DGS, DeepSDF, etc. are **not** included merely as foundations. Likewise, ordinary fixed-grid remote-sensing CNN/Transformer/Mamba papers are excluded when continuity is not methodological.

## Gate B — venue quality

### Journals
A journal paper must satisfy **at least one** of:
- CAS (中科院) major-category **1区 or 2区**; or
- **JCR Q1** in at least one indexed category.

If publicly checkable evidence is ambiguous, the paper is held outside the main list until verified.

### Conferences
A conference paper must be from a **CCF-A** conference and must be a **Full/Regular main-conference paper**.

The 2026 CCF rules explicitly exclude Short papers, Demo papers, Technical Briefs, Summaries, Findings, and co-located Workshops from the recommended-conference scope:
https://www.ccf.org.cn/Academic_Evaluation/By_category/2026-03-31/870181.shtml

Accordingly, a paper can be technically important yet still remain outside this repository's main list if it is workshop-only, Findings-only, preprint-only, or from a non-CCF-A conference.

## Borderline test

Ask two questions:

1. If the continuous representation/operator were removed, would the paper still be essentially the same method? If **yes**, exclude it.
2. Does the final peer-reviewed venue pass Gate B? If **no** or **unverified**, exclude it from the main list.

## Audit trail

- `data/papers.csv` contains the current **core bibliography** and per-paper venue-quality evidence.
- `data/paper_level_audit.csv` records the paper-level scientific-scope audit: the continuous variable, representation family, **what is continuous**, **why the paper belongs to Continuous Remote Sensing**, PASS/FAIL decision, and evidence source.
- `data/context_negative_evidence.csv` preserves useful counter-evidence that does not pass the direct remote-sensing/EO scope gate and is therefore **not counted** in the core bibliography.
- `data/venue_quality_audit.csv` records the venue-level decision.
- `data/excluded_by_quality.csv` preserves relevant papers removed only because of venue quality.
- `data/excluded_from_ledger_v2.csv` preserves earlier relevance/scope exclusions.

These thresholds are **repository curation rules**, not a blanket judgment on the scientific merit of excluded papers.

## Paper-level continuity test

For every candidate, the audit must identify a concrete continuous object or variable (for example spatial coordinate, wavelength, time, view, scale, physical field, implicit surface, Gaussian scene field, or an explicitly function-space/discretization-aware operator). Naming an architecture such as FNO, PINN, NeRF, INR, or 3DGS is not sufficient evidence by itself.

A `PASS` requires that removing the continuous representation/operator would materially change the proposed remote-sensing/geospatial/geophysical method. A `FAIL` is kept in the audit trail when continuity is only nominal, the neural operator is merely a fixed-grid backbone, 3DGS is not the represented sensing scene/signal, or the data/task itself falls outside the direct sensing scope.
