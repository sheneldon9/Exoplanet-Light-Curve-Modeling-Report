# WASP-135b Light-Curve Modelling Report

This repository showcases my final written report for the project based course **AST325 (Observational Astronomy)** taken at the **University of Toronto Mississauga**.

### **Synopsis:**

A popular way to detect possible exoplanets is to observe the drop in a star's brightness when said exoplanet passes it, called the _Transit Method_. Using ground based observations, we can try to predict plausible parameters (orbital period, semi-major axis, etc.) of the exoplanet.

Alongside the guidance of my professor and help of my classmates, we attempted to develop a comprehensive Python pipeline for transiting exoplanet data reduction, image alignment, photometry and transit modelling:
- **Data Reduction & Processing:** Built workflow for calibration (dark subtraction, flat fielding) and differential photometry on raw telescope frames.
- **Modelling & Inference:** Used `batman`, Maximum Likelihood Estimation and MCMC sampling to fit theoretical transit light-curves and recover planetary parameters (successfully matching literature values for transit depth and duration).
- **Validation & Analysis:** Propagated errors for comparison against AAVSO reference datasets, and identified baseline quality and completeness of the observational data as primary constraints for planetary characterization.

Although this pipeline was only tested on the _WASP-135b_ dataset, it should theoretically work for any reasonably complete exoplanet dataset.

## Report
📄 The full research paper is available as a PDF in this repository: [`Final_Written_Report.pdf`](./WASP-135b_Transit_Report.pdf)
