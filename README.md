# Multiscale HRV Analysis using DMA and CNN

This project implements a multiscale heart rate variability (HRV) analysis
framework using Detrended Moving Average (DMA) curves and a 1D Convolutional
Neural Network (CNN).

## Dataset
- MIT-BIH Normal Sinus Rhythm Database
- BIDMC Congestive Heart Failure Database
(Data obtained from PhysioNet)

## Methodology
- ECG → RR interval extraction
- HRV preprocessing and cleaning
- DMA feature extraction (200 scales)
- CNN-based classification

## Tools
- Python
- NumPy, SciPy
- TensorFlow / Keras
- wfdb

## Author
Surbhi Tiwari
Samreet kaur