# AGN Host Galaxy Properties in the Local Universe

This project examines the host galaxy properties of Active Galactic Nuclei in the local universe using data from the Sloan Digital Sky Survey. This is to analyze whether AGN preferentially reside in certain kinds of galaxies, and what that tells us about the relationship between black hole activity and star formation. The analysis reproduces and extends the work of Kauffmann et al. 2003 using a substantially larger dataset from SDSS Data Release 8.

## Data

The analysis uses the SDSS MPA-JHU Value Added Catalog, available at https://www.sdss4.org/dr17/spectro/galaxy_mpajhu/. 
Three catalog files are needed: 
1. galSpecInfo
2. galSpecExtra
3. galSpecLine

These are not included in the repository due to their size and should be downloaded from the link above and placed in a folder called data.

## How To Run

Open the notebook called Final Analysis in Jupyter and run all cells from top to bottom. The seven figures will be generated and saved automatically to the figures folder.

## Figures

1. BPT.pdf — BPT diagram identifying AGN from emission line ratios
2. Mass histogram.pdf — Stellar mass distributions of AGN hosts and the full sample with KS test
3. sSFR histogram.pdf — sSFR distributions of AGN hosts and the full sample with KS test
4. sSFR vs Mass.pdf — AGN hosts overlaid on the full galaxy population in sSFR vs stellar mass space
5. AGN fraction.pdf — AGN prevalence as a function of stellar mass
6. AGN Host vs All Galaxies.pdf — Median SFR of AGN hosts compared to all galaxies across stellar mass bins
7. AGN Host vs Star-forming-only Galaxies.pdf — Median SFR of AGN hosts compared to star forming galaxies only

## Dependencies

Python 3, astropy, pandas, numpy, matplotlib, scipy

## Reference

Kauffmann, G., Heckman, T. M., Tremonti, C., et al. 2003, MNRAS, 346, 1055

Written as part of an undergraduate astrophysics research project at UCLA.
