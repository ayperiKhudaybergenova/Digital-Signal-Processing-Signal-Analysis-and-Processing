# Digital Signal Processing: Signal Analysis and Processing

## Project Vision

This project explores the fundamentals of **Digital Signal Processing (DSP)** through Python-based experiments. The main objective is to understand how continuous signals can be sampled, represented, analysed in the frequency domain, and reconstructed using mathematical and computational methods.

The project combines signal-processing theory with practical implementation, data visualisation, and experimentation. It demonstrates technical skills that are relevant to roles in signal processing, software development, audio engineering, and applied data analysis.

## Objectives

- Understand the relationship between continuous-time and discrete-time signals.
- Investigate the effects of different sampling frequencies.
- Approximate periodic signals using Fourier series.
- Analyse signals in the frequency domain using the Fast Fourier Transform (FFT).
- Develop practical Python skills for numerical computation and visualisation.
- Interpret results and explain the behaviour of signals.

## Methods and Techniques

### 1. Signal Generation and Sampling

A sawtooth signal with a frequency of 200 Hz is generated mathematically.

Different sampling frequencies are compared:

- 8 kHz sampling
- 1 kHz sampling

The experiment demonstrates how sampling frequency affects the representation of a continuous signal and illustrates aliasing.

**Techniques:** NumPy, discrete-time sampling, signal visualisation, audio playback.

### 2. Fourier Series Approximation

The sawtooth signal is approximated using a Fourier series.

The approximation is evaluated with different numbers of harmonics:

- N = 1
- N = 2
- N = 3
- N = 5

The results are plotted together with the original signal to observe how the approximation changes as more harmonics are included.

**Techniques:** Fourier series, harmonic analysis, mathematical modelling, Matplotlib.

### 3. Fourier Transform and Frequency Analysis

The sampled signal is analysed using the Fast Fourier Transform (FFT).

The signal is sampled at 8 kHz over a 20 ms window. Its frequency spectrum is then calculated and visualised.

This provides practical experience in examining the frequency components that make up a signal.

**Techniques:** FFT, frequency-domain analysis, NumPy, spectrum visualisation.

## Technical Skills

| Area | Skills and Tools |
|---|---|
| Programming | Python |
| Numerical computation | NumPy |
| Data visualisation | Matplotlib |
| Signal processing | Sampling, aliasing, Fourier series, FFT |
| Mathematical methods | Trigonometric functions, harmonic analysis |
| Analysis | Comparing results, interpreting plots, evaluating signal behaviour |

## Skills Demonstrated to Employers

This project provides evidence of the ability to:

- Translate mathematical concepts into working Python code.
- Use numerical libraries to process and analyse data.
- Visualise technical results and communicate findings.
- Compare different experimental parameters.
- Identify and explain technical effects such as aliasing.
- Work systematically through a technical problem.
- Connect theoretical knowledge with practical implementation.

## Potential Future Improvements

The project can be extended with additional experiments:

- Compare more sampling frequencies and investigate the Nyquist criterion.
- Analyse different periodic signals, such as sine and square waves.
- Compare FFT spectra for signals with different harmonic content.
- Implement digital filters and evaluate their frequency responses.
- Add quantitative comparisons between original and reconstructed signals.
- Organise the code into reusable Python functions and modules.

These extensions would provide further opportunities to demonstrate problem-solving, software design, and practical signal-processing knowledge.

## Repository Structure

```text
digital-signal-processing/
│
├── notebooks/
│   └── digital_signal_processing.ipynb
│
├── images/
│   └── plots/
│
├── src/
│   └── signal_processing.py
│
├── README.md
└── requirements.txt
```

## Technologies

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

## Project Outcome

The project demonstrates the application of mathematical and computational techniques to digital signal processing. It provides practical experience in generating signals, investigating sampling behaviour, approximating signals using Fourier series, and analysing frequency components using FFT.

The work forms a foundation for further development in digital signal processing, audio analysis, communications engineering, and other fields involving numerical data and signal analysis.
