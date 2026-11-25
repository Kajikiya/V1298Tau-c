
# V1298 Tau c – Supplementary Material

Supplementary figures for the paper:

**Activity-constrained Hα Indication of Atmospheric Escape from a Young Super-Earth Progenitor**

Kajikiya et al. (2026)

## Corner Plots

This repository provides corner plots showing the posterior distributions of the model parameters used in the Gaussian-process (GP) analysis of stellar rotational modulation and the hierarchical Bayesian regression of the atmospheric mass-loss scaling relation.

### Gaussian-Process Models

- [corner_gp_photometry.pdf](corner_gp_photometry.pdf): GP model fitted to the R-band light curve.
- [corner_mdgp_out_of_transit.pdf](corner_mdgp_out_of_transit.pdf): Multidimensional GP model jointly fitted to the R-band and Hα equivalent-width light curves using out-of-transit Hα observations.
- [corner_mdgp_all_nights.pdf](corner_mdgp_all_nights.pdf): Multidimensional GP model including the transit-night observations.
- [corner_mdgp_excluding_dec02.pdf](corner_mdgp_excluding_dec02.pdf): Multidimensional GP model excluding the Hα observations obtained on 2024 December 2.

### Bayesian Regression

- [corner_bayesian_regression.pdf](corner_bayesian_regression.pdf): Hierarchical Bayesian errors-in-variables regression of the scaling relation between the atmospheric mass-loss rate and $F_{\mathrm{XUV}}/\rho_p$, accounting for asymmetric measurement uncertainties in both variables and intrinsic scatter.
