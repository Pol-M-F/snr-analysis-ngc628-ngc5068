# Supernova Remnant Analysis in NGC 628 and NGC 5068

This repository contains the code and data for the identification and characterization of supernova remnants (SNRs) in the nearby galaxies NGC 628 and NGC 5068 using both optical and X-ray data.

## Description

This project utilizes multiwavelength imaging to identify SNR candidates and characterize their physical properties:

* **Optical Analysis**: Photometric measurements on narrowband images (e.g., Hα, [S II], [O III]) using predefined region files.  
* **X-ray Analysis**: Source detection using CIAO's `wavdetect` in four energy bands, followed by source matching and flux extraction.  
* **Post-Processing**: Line ratio diagnostics, electron density and luminosity estimations, shock velocity modeling, and comparison to theoretical models.

## Getting Started

### Requirements

* Python 3.8+  
* Libraries: `numpy`, `astropy`, `matplotlib`, `pandas`, `photutils`, `extinction`, `scipy`, `pyneb`, `emcee`  
* Jupyter Notebook environment installed (e.g., via `notebook` or `jupyterlab` package)  
* CIAO (Chandra Interactive Analysis of Observations) must be installed separately: [https://cxc.harvard.edu/ciao/](https://cxc.harvard.edu/ciao/)

### Usage

```bash
git clone https://github.com/Pol-M-F/snr-analysis-ngc628-ngc5068.git
cd snr-analysis-ngc628-ngc5068
jupyter notebook NGC628/code_optical_NGC628.ipynb
```
Follow the notebooks step-by-step for both optical and X-ray analyses.

## Output Files

* .csv files contain tabulated results from both optical and X-ray studies.
* .png figures show diagnostic plots including densities, luminosities, and shock velocity estimates.
* .txt files provide supplemental ratio data and shock model comparison values.

### Access to FITS Slices

Flux and error maps (.fits) used for the emission line analysis can be downloaded here:

🔗 [Download slices (OneDrive link)](https://ubarcelona-my.sharepoint.com/:f:/g/personal/pmustefe25_alumnes_ub_edu/EvY9tVPmbWNJjhDqGP1HX5EBp9FjSONy6RbFsRBvYkL11w?e=17LSkA)

## Citation

If you use this repository or any of its content in your work, please cite it using the following GitHub link:

> [https://github.com/Pol-M-F/snr-analysis-ngc628-ngc5068](https://github.com/Pol-M-F/snr-analysis-ngc628-ngc5068)

## Note

This code is shared for academic and collaborative purposes. Please contact the author if you intend to reuse or redistribute any part of it.
