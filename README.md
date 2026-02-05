# EEG Motor Imagery Preprocessing

A clean and reproducible preprocessing pipeline for EEG motor imagery data, designed to convert raw EEG recordings into analysis-ready signals for machine learning, BCI systems, and neuroengineering research.

## Overview

EEG motor imagery signals are highly sensitive to noise, artifacts, and session variability. This project applies standard biomedical signal-processing techniques to improve signal quality and ensure reliable downstream analysis.

## Pipeline

- Load and organize raw EEG data  
- Channel selection and re-referencing  
- Band-pass filtering for motor imagery frequency bands  
- Artifact and noise reduction  
- Normalization and segmentation  
- Output ready for feature extraction and model training  

## Files

- `Gamma_EEG_motor_imagery_Pre_processing.ipynb` – complete preprocessing workflow with explanations and visual validation

## Requirements

Python 3.8+, NumPy, SciPy, Matplotlib, MNE, Jupyter Notebook

pip install numpy scipy matplotlib mne jupyter

## Usage
git clone https://github.com/your-username/eeg-motor-imagery-preprocessing.git
cd eeg-motor-imagery-preprocessing
jupyter notebook Gamma_EEG_motor_imagery_Pre_processing.ipynb

## Applications

Motor imagery classification, EEG feature extraction, brain–computer interfaces, biomedical signal analysis

