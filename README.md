# My-Experiments-with-LHC-CERN
This repository contains my various experiments with the OpenData from CERN mainly associated with the Large Hadron Collider. Some of the Experiments include Finding the Measurement of the Z boson mass, Particle Identification, Search for Rare Decays, etc.

## Measuring the Z Boson Mass
I tried to analyse the mass spectrum of particle decaying into muon-antimuon (dimuon) pairs and figured out the mass of Z boson. Of course, the mass of Z boson can be looked up at the PDG, but I thought it would much more fun If I did it myself!

I started my making a histogram of mass distribution, where I tired to fit a mixture of parametrised signal and background distributions into the shape of the histogram.
The parameters of the mixture are the mass of Z boson and other estimations of the significance and uncertainty of the measurement.

Finally I, fit the Gaussian distribution and Flat distribution using scikit-optimise toolkit.

The dataset that I used fot this project was taken from CERN opendata portal http://opendata.cern.ch/record/545
