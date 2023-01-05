# Technology Classification Dataset
This repository contains the dataset for the paper A. Scalingi, D. Giustiniano, R. Calvo-Palomino, N. Apostolakis, G. Bovet, "A Framework for Spectrum Classification using Crowdsensing Platforms".  Please cite the paper if you plan to use it in your publication.


The dataset contains PSD spectrum measurements collected by 47 ElectroSense Sensors. In this work the sensors are composed of a Raspberry Pi embedded board for computing and communication, and an RTL-SDR as radio front-end. 

For each site, we collect 6 hours of the full spectrum scan, the RTL-SDR sweeps the full spectrum from 24 MHz to 1.7 GHz hopping over the frequencies with chunks of 2MHz of bandwidth. Considering FFT of 256 bins and 10 readings of IQ measurements in the band, the dataset resolution is approximately 10 kHz per bin - the highest that can be provided by RTL-SDR front-ends.

We organize the directories per each site and we publish the spectrum portions already labeled.
