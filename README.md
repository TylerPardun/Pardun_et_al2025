# Pardun_et_al2024

This repository contains all the information needed to replicate the series of simulations used in Pardun et al. (2024). Each simulation was conducted using version 21.1 of Cloud Model 1 (CM1), maintained by Dr. George Bryan (https://www2.mmm.ucar.edu/people/bryan/cm1/).

The "input_sounding" is a text file found in /cm1r21.1/run/bss_sounding_files/ that is the base state used to initiate the left-moving supercell. This is a modified version of the observed 15 June 2019 23:19 UTC sounding launched in the field. The text file are formatted to use as the "input_sounding" file to be imported directly by CM1. 

The "namelist.input" is found in /cm1r21.1/run/ and is the namelist file used for each simulation. This is standard across all simulations conducted.

The BSS files used to update the base state in each simulation is found in /cm1r21.1/bss_sounding_files/ inlcuding the thermodynamic and kinematic profiles. These are linearly interpolated from the initial profile to the final profile and used for each simulation conducted.
