# Digital Communication Modelling in Simulink

## Description
This project focuses on simulating digital communication systems using Simulink. Implemented modulation schemes include Binary Phase Shift Keying (BPSK), Quadrature Phase Shift Keying (QPSK), and 16 Quadrature Amplitude Modulation (16 QAM). Each modulation scheme is simulated to analyze its performance in terms of Bit Error Rate (BER) against Signal-to-Noise Ratio (SNR). The simulations include the usage of AWGN (Additive White Gaussian Noise) channel to represent realistic channel conditions.

## Modulation Schemes

### BPSK (Binary Phase Shift Keying)
#### Key Features:
- BPSK modulates binary data onto a carrier signal by shifting its phase.
- Simple to implement and robust against channel impairments.
- Suitable for low-complexity applications.

#### Scatter Plot
![BPSK Scatter Plot](https://github.com/ayazmunis/Digital-Communication-Simulink/assets/99540621/cff0f8a2-5596-48a2-af86-cb2614c9d457)


#### BER vs SNR Curve
![BPSK BER vs SNR Curve](https://github.com/ayazmunis/Digital-Communication-Simulink/assets/99540621/57e416f2-83f0-4908-8f76-be08c302a391)


### QPSK (Quadrature Phase Shift Keying)
#### Key Features:
- QPSK modulates data using four phase shifts of the carrier signal.
- More bandwidth-efficient compared to BPSK.
- Robust against phase noise and multipath fading.

#### Scatter Plot
![QPSK Scatter Plot](https://github.com/ayazmunis/Digital-Communication-Simulink/assets/99540621/887e106b-959c-42c8-8953-d6b6e9ec3459)
)

#### BER vs SNR Curve
![QPSK BER vs SNR Curve](https://github.com/ayazmunis/Digital-Communication-Simulink/assets/99540621/c87a7bbc-59b9-4333-93f7-279ced212369)


### 16 QAM (16 Quadrature Amplitude Modulation)
#### Key Features:
- 16 QAM modulates data by varying both amplitude and phase of the carrier signal.
- Higher spectral efficiency compared to BPSK and QPSK.
- More susceptible to noise and channel distortions.

#### Scatter Plot
![16 QAM Scatter Plot](https://github.com/ayazmunis/Digital-Communication-Simulink/assets/99540621/95047c2d-5bcd-4230-8d5b-582134cd6cbf)


#### BER vs SNR Curve
![16 QAM BER vs SNR Curve](https://github.com/ayazmunis/Digital-Communication-Simulink/assets/99540621/13189eeb-5927-4e31-a585-1d77d458145d)


