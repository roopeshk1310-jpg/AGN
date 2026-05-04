# AGN Host Galaxy Properties in the Local Universe (0.02 <= Z <= 0.2)

## Project Overview
This project investigates the host galaxy properties of Active Galactic Nuclei 
(AGN) in the local universe using the SDSS MPA-JHU value-added catalog (DR8). 
The analysis examines where AGN host galaxies sit relative to the general galaxy 
population in stellar mass, star formation rate, and specific star formation rate.
This is a replication study of Kauffmann et al 2003.

## Data
SDSS MPA-JHU Value Added Catalog (DR8)
- galSpecInfo — redshift and targettype information
- galSpecExtra — stellar masses, SFRs, BPT classifications  
- galSpecLine — emission line flux values
Data available at: https://www.sdss4.org/dr17/spectro/galaxy_mpajhu/

## Sample
- Full galaxy sample: 668,302 galaxies (0.02 <= z <= 0.2)
- AGN sample: about 20,000 galaxies identified via BPT Classification (BPTCLASS=4)

## Figures
- BPT.pdf — BPT emission line diagnostic diagram
- ssfr_mass.pdf — Specific SFR vs stellar mass
- star_forming_main_sequence.pdf — SFR vs stellar mass
- mass_histogram.pdf — Stellar mass distribution comparison

## Coding Language and Libraries
Python 3, astropy, pandas, numpy, matplotlib, scipy
