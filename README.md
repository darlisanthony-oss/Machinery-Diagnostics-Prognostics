# Machinery Diagnostics & Stochastic Prognostics

## Overview

This project investigates condition monitoring, fault diagnosis and Remaining Useful Life (RUL) estimation for rotating machinery using vibration-signal analysis and stochastic modelling in MATLAB.

The study combines time-domain statistics, frequency-domain analysis, bearing-fault diagnostics and prognostic modelling within a single workflow.

The project was completed as part of the undergraduate course **Diagnostics and Prognostics of Machinery** at the University of Patras.

---

## Experimental and Data Context

The analysis is based on vibration measurements from rotating mechanical systems.

The workflow includes:

- vibration-signal acquisition and preprocessing
- comparison of healthy and faulty operating conditions
- bearing-fault analysis
- frequency-domain diagnostics
- automated fault identification
- degradation monitoring
- Remaining Useful Life estimation

---

## Signal Processing

The vibration signals are first examined in the time domain using statistical descriptors such as:

- Mean
- Variance
- Skewness
- Kurtosis
- RMS
- Peak-to-Peak
- Crest Factor

Autocovariance is also used to investigate temporal dependence and dynamic behaviour.

---

## Frequency-Domain Analysis

The project applies several spectral-analysis techniques:

- Fast Fourier Transform (FFT)
- Power Spectrum
- Welch Power Spectral Density
- Spectrograms

These methods are used to identify dominant frequencies, harmonics and changes in spectral content associated with operating conditions and potential faults.

---

## Filtering

A digital Chebyshev Type II low-pass filter is designed and applied to the vibration signals.

The filtering study examines:

- frequency-response behaviour
- attenuation of high-frequency components
- effect on statistical signal features
- preservation of diagnostically relevant low-frequency content

---

## Bearing Fault Diagnostics

The study includes theoretical calculation of characteristic bearing frequencies such as:

- BPFO
- BPFI
- BSF
- FTF

These frequencies are compared with measured spectral features to identify possible bearing defects.

Additional diagnostic tools include:

- FFT comparison
- Welch PSD
- spectrogram analysis
- envelope analysis
- threshold-based feature comparison

---

## Automated Fault Diagnosis

A MATLAB-based diagnostic workflow is developed to classify signals according to deviations from healthy reference behaviour.

The automated procedure uses combinations of:

- statistical features
- characteristic fault frequencies
- spectral indicators
- diagnostic thresholds

---

## Prognostics and Remaining Useful Life

The project extends beyond fault detection to degradation prediction and RUL estimation.

The prognostic analysis includes:

- tracking statistical degradation indicators
- selecting suitable health indicators
- prediction-based extrapolation
- Remaining Useful Life estimation
- stochastic degradation modelling

---

## Wiener-Process Prognostics

A Wiener-process-based model is used to represent stochastic degradation.

This allows uncertainty in the degradation trajectory to be incorporated into RUL estimation rather than relying only on deterministic extrapolation.

The prognostic section therefore introduces a probabilistic approach to machinery health prediction.

---

## Key Concepts

- Condition monitoring
- Vibration analysis
- Signal processing
- FFT
- Power Spectral Density
- Welch method
- Spectrograms
- Digital filtering
- Bearing fault frequencies
- Envelope analysis
- Automated diagnostics
- Remaining Useful Life
- Stochastic degradation modelling
- Wiener process

---

## Tools

- MATLAB
- Signal Processing
- Statistical Analysis
- Frequency-Domain Analysis
- Stochastic Modelling

---

## Planned Repository Content

The cleaned repository will include:

- MATLAB source code
- representative vibration signals
- FFT and PSD plots
- spectrograms
- filtering results
- bearing-diagnostic results
- envelope-analysis figures
- RUL prediction plots
- Wiener-process prognostic results
- the original academic report

---

## Academic Context

**Course:** Diagnostics and Prognostics of Machinery  
**Institution:** University of Patras  
**Department:** Mechanical Engineering and Aeronautics  
**Project type:** Team undergraduate coursework project

The project was completed in collaboration with another student.

My individual contributions will be documented explicitly in the final repository version.

> Source code, selected figures and the original report will be added during repository cleanup.
