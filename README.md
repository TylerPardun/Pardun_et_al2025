# Left-Moving-Supercell-Dissipation

This repository contains all the information needed to replicate the series of simulations used in Pardun et al. (2025). Each simulation was conducted using version 21.1 of Cloud Model 1 (CM1), maintained by Dr. George Bryan (https://www2.mmm.ucar.edu/people/bryan/cm1/).

The "input_sounding" is a text file that is the base state used to initiate the left-moving supercell. This is a modified version of the observed 15 June 2019 23:19 UTC sounding launched in the field. The text file are formatted to use as the "input_sounding" file to be imported directly by CM1. 

The "namelist.input" is the namelist file used for each simulation. This is standard across all simulations conducted.

The BSS files used to update the base state in each simulation inlcudes the thermodynamic and kinematic profiles in "thermo_replace" and "wind_replace", respectively. 

The "toy.input" file shows the configuration for tendencey nudging used to initiated convection within the modeled domain (Flournoy and Rasmussen 2023)

Please contact Tyler Pardun if you have any questions, comments, conundrums, or other inquiries. (tyler.pardun@noaa.gov)
