# OFDM-Based Wireless Communication System Simulation Using Python

## Project Overview

This project simulates a basic OFDM (Orthogonal Frequency Division Multiplexing) wireless communication system using Python.

The system uses QPSK modulation and an AWGN channel to study the effect of noise on wireless communication performance.

## System Flow

Random Bits
↓
QPSK Modulation
↓
IFFT
↓
Cyclic Prefix
↓
AWGN Channel
↓
Remove Cyclic Prefix
↓
FFT
↓
QPSK Demodulation
↓
BER Calculation

## Technologies Used

- Python
- NumPy
- Matplotlib
- Google Colab

## Parameters

- Number of subcarriers: 64
- Number of OFDM symbols: 1000
- Cyclic Prefix length: 16
- Modulation: QPSK
- Channel: AWGN
- SNR range: 0–20 dB

## Results

The simulation evaluates the Bit Error Rate (BER) at different SNR levels.

As SNR increases, the effect of noise decreases and the BER generally decreases.

The QPSK constellation is also observed at different SNR levels to visualize the effect of noise.

## Applications

OFDM is an important technique used in modern wireless communication systems and is relevant to technologies such as LTE and 5G.

## Author

NAMITH T B
