# Radar-Signal-Processing-Learning
This repository contains my study notes and Python notebooks based on  "Fundamentals of Radar Signal Processing " by Mark A. Richards. (2nd Ed.)

## Structure

-`Chapter_1_Basics/` – sampling complex sinusoids, complex envelope, FFT fundamentals  
-`Chapter_2_Pulse_Echo_Models/`  
-`Notes/` – brief concept summaries and references
## Status

Learning in public. I add a new notebook after each concept I study.
##  Chapter 1 - Basics

**Notebook:** [Sampling a Complex Sinusoid](Chapter_1_Basics/1%29%20Sampling%20a%20Complex%20Sinusoid.ipynb)

**Overview:**  
This notebook shows what a complex sinusoidal signal really means and how it’s represented digitally.
**Key takeaway:**  
This simple complex sinusoid is much more than a math expression, it’s the foundation of radar signals.
The way its phase and frequency behave later helps us detect motion, measure Doppler shifts, and estimate target range.

---
**Notebook:**  [FFT of a Stationary Target](Chapter_1_Basics/2_1%29%20FFT_Stationary_Target.ipynb)

**Overview:** 
This notebook demonstrates how the Fast Fourier Transform (FFT) reveals the frequency content of a sampled radar signal.
It shows that a stationary target produces a single, sharp spectral spike at its tone frequency, corresponding to a constant echo with no Doppler shift.

---
**Notebook:**  [FFT of a Moving Target](Chapter_1_Basics/2_2%29%20FFT_Moving_Target.ipynb)

**Overview:**
This notebook demonstrates how a moving radar target produces a Doppler frequency shift in its returned signal.
By comparing stationary and moving echoes using the Fast Fourier Transform (FFT), it shows how motion shifts the spectral peak by the Doppler frequency.

---
**Notebook:** [FFT_Noise_and_Targets](Chapter_1_Basics/2_3%29%20FFT_Noise_and_Targets.ipynb)

**Overview:**  
This notebook demonstrates how **Additive White Gaussian Noise (AWGN)** affects radar signals and how **Signal-to-Noise Ratio (SNR)** determines the visibility of a target in the frequency domain.  

---
