# Radar-Signal-Processing-Learning
This repository contains my study notes and Python notebooks based on  "Fundamentals of Radar Signal Processing " by Mark A. Richards. (2nd Ed.)

## Structure

-`Chapter_1_Basics/` – sampling complex sinusoids, complex envelope, FFT fundamentals  
-`Chapter_2_Pulse_Echo_Models/`  
-`Notes/` – brief concept summaries and references
## Status

Learning in public. I add a new notebook after each concept I study.
##  Chapter 1 — Basics

**Notebook:** [Sampling a Complex Sinusoid](Chapter_1_Basics/1%29%20Sampling%20a%20Complex%20Sinusoid.ipynb)

**Overview:**  
This notebook shows what a complex sinusoidal signal really means and how it’s represented digitally.
**Key takeaway:**  
This simple complex sinusoid is much more than a math expression, it’s the foundation of radar signals.
The way its phase and frequency behave later helps us detect motion, measure Doppler shifts, and estimate target range.

---
**Notebook:** [FFT of a Stationary Target](Chapter_1_Basics/2.1%20FFT_Stationary_Target.ipynb)

**Overview:** 
This notebook demonstrates how the Fast Fourier Transform (FFT) reveals the frequency content of a sampled radar signal.
It shows that a stationary target produces a single, sharp spectral spike at its tone frequency, corresponding to a constant echo with no Doppler shift.
