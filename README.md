# Audio Signal Processing Lab

## Overview
This repository contains a signal processing lab focused on analyzing, modifying, and filtering an audio signal using Python. The lab demonstrates how to read an audio file, visualize its waveform and spectral density, add noise, and apply a Butterworth low-pass filter to remove unwanted frequencies.

## Objectives
- Import and analyze an audio signal.
- Visualize the waveform and power spectral density (PSD).
- Introduce white noise into the signal.
- Apply a Butterworth low-pass filter to remove noise.
- Compare original, noisy, and filtered signals.

## Requirements
To run the lab, install the required dependencies using:
```bash
pip install pydub numpy matplotlib scipy
```

## Usage
Run the script in a Jupyter Notebook or Google Colab. Upload your `.wav` file when prompted and follow the steps interactively.

## Results
- The original and noisy signals are compared both in the time and frequency domains.
- The Butterworth low-pass filter successfully reduces high-frequency noise while preserving important speech components.
