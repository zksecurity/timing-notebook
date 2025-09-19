# Kocher's Timing Attack: A Three-Act Tutorial

This repository contains an interactive Jupyter notebook demonstrating Paul Kocher's 1996 timing attack on cryptographic implementations. The tutorial takes you on a journey from theory to practice through three progressive implementations.

## Overview

Paul Kocher's [seminal paper](https://paulkocher.com/doc/TimingAttacks.pdf) showed how microsecond differences in execution time could leak private keys from RSA implementations. This tutorial recreates that journey:

- Part 1: Clean signal demonstration using instruction cost modeling
- Part 2: Real-world challenges with wall-clock timing measurements
- Part 3: Engineering solutions to extract signal from noise

## Educational Purpose

This is a didactic implementation designed to illustrate the principles behind Kocher's attack. It includes simplifications and limitations that make it suitable for learning but not for production cryptanalysis. The focus is on understanding the mathematical foundations and practical challenges of timing side-channel attacks.

## Requirements

- Python 3.x
- Jupyter Notebook
- NumPy
- Matplotlib (for visualizations)

## Usage

```bash
jupyter notebook Kochers-Three-Act-Tutorial.ipynb
```

## Citation

Original paper: Paul C. Kocher. "Timing Attacks on Implementations of Diffie-Hellman, RSA, DSS, and Other Systems." CRYPTO 1996.
