# Cosmic-Ray Data Analysis  
In this mini project we are using various statistical methods like curve fit and MCMC to  analyze the cosmic ray data.


In this project we are analysing cosmic ray data from Cosmic Ray Database at http://lpsc.in2p3.fr/crdb/. 


All the data is recorded from many experiments that measure the flux of Galactic cosmic rays at the top of the atmosphere as a function of energy. For the data selection I have selected H as the element, ‘EKN (kinetic energy per nucleon)’ as the energy axis, and 1 GeV as the energy cutoff. Data is downloaded in the format of (.tar.gz) file after extracting the data in a specific folder where we can see 1 to 144 data exp file which contains the cosmic ray data and in data exps file contains experiment names by which data is generated.


Initially, I attempted to fit a power law to the data, resulting in a poor fit. Subsequently, I performed an MCMC analysis to estimate the uncertainties in the model parameters. This analysis considered both the data and any prior information available on the parameters, providing more reliable estimates of the parameters along with their associated uncertainties. 
