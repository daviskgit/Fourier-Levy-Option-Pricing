# Fourier-Based Option Pricing with Lévy Processes

**Author:** Davis Koebig Griffin

This repository implements Fourier-based option pricing methods for
exponential Lévy models, with a focus on contour deformation and residue
contributions in complex Fourier inversion.

Models studied include:
- Variance Gamma (VG)
- CGMY

## Repository Structure

- `notebooks/`: Research notebooks organized conceptually
- `requirements.txt`: Reproducible environment

## Key Topics

- Characteristic functions and analytic strips
- Pole and branch cut structure
- Carr–Madan Fourier pricing
- FFT-based pricing
- Contour deformation
- Residue contributions
- Calibration and numerical failure modes

## How to Use

1. Install dependencies:
```bash
pip install -r requirements.txt

