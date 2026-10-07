# Curation Policy

This repository is the **strict remote-sensing bibliography** for continuous remote sensing. It is not a general neural-field reading list.

## Inclusion test

A paper is included only if **both** conditions hold:

1. **Direct sensing relevance.** The paper studies Earth observation, remote sensing, photogrammetry/geospatial sensing, atmospheric/ocean/ionospheric sensing, or geophysical sensing/inversion.
2. **Continuity is central.** At least one of the following is part of the method itself, not just background terminology:
   - coordinate/function/field representation over continuous space, wavelength, time, view, or physical parameters;
   - genuine arbitrary/continuous-scale or off-grid querying;
   - continuous tensor/function factorization;
   - neural operator learning between physical fields/functions, with grid/discretization/location flexibility as a core property;
   - remote-sensing NeRF / radiance field / implicit surface;
   - remote-sensing Gaussian field / Gaussian splatting as the scene or signal representation.

## Explicit exclusions

The main list intentionally excludes:

- generic SIREN, Fourier Features, LIIF, NeRF, FNO, 3DGS, DeepSDF, etc. **when the paper itself has no direct remote-sensing/geoscience application**;
- ordinary remote-sensing CNN/Transformer/Mamba methods that output only a fixed discrete grid and do not make continuity part of the model;
- classical fusion/registration/interpolation baselines and broad task surveys whose main contribution is not continuous representation;
- papers using the word “continuous” in an unrelated sense;
- planetary/space-object reconstruction when it is outside the Earth-observation/geoscience scope.

## Borderline rule

For a borderline paper, ask: **if the continuous representation/operator were removed, would the paper still be essentially the same remote-sensing method?** If yes, exclude it.

## Evidence levels

- **Core** — peer-reviewed and directly in scope.
- **Extended** — directly in scope but in a specialized/adjacent venue or mainly a methodological bridge.
- **Emerging** — workshop/preprint work directly in scope.

## Audit trail

The current list was re-audited on **2026-10-07** from the previous 127-paper working ledger plus a second targeted search/citation-chasing pass. Generic foundations and non-continuous remote-sensing baselines were removed from the public list, while direct continuous remote-sensing papers missing from the old ledger were added.

The list is intentionally conservative: **omission is preferable to including a paper whose relevance to continuous remote sensing cannot be defended clearly.**
