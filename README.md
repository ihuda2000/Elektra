# Elektra: Harmful Brain Activity Classification

## Overview
Elektra is a software application that utilizes open-source machine learning and deep learning packages to classify EEG (electroencephalogram) signals. The system is designed to detect and categorize harmful brain activities such as seizures, LRDA, GRDA, LPD, and GPD.  

The goal of Elektra is to support neurologists with faster and more accurate diagnoses by reducing cognitive workload, improving real-time analysis, and enhancing clinical usability.

---

## Problem Statement
Manual EEG analysis is:
- Slow, error-prone, and difficult to scale  
- Often leads to delayed detection of seizures and poor patient outcomes  

Current solutions lack noise handling, real-time capability, and clinical usability.  

Elektra addresses these limitations by providing:
- Automated EEG signal classification  
- High model accuracy (~95% in harmful event detection)  
- A user-friendly interface for raw EEG data analysis  

---

## Features
- **Signal Preprocessing**: Cleans and prepares raw EEG signals  
- **Multiple ML/DL Models**: Supports Random Forest, CNN, and other classifiers  
- **Visualization Tools**: Time-domain and frequency-domain analysis  
- **Inference Engine**: Classifies harmful vs. non-harmful brain activity in real time  
- **Adaptable**: Extendable to EEG tasks like sleep stage monitoring or mental state prediction  

---

## Results
- Achieved ~95% model accuracy in harmful event detection  
- Successfully classified and distinguished between different harmful EEG patterns  
- Demonstrated ability to analyze new EEG datasets via the interface  

---

## Community Benefit
Currently, classification of EEG signals is performed manually by medical professionals, which is time-consuming and prone to error. By applying machine learning and deep learning techniques:
- Harmful brain activities can be detected instantly and reliably  
- Cognitive workload for neurologists is reduced  
- Patients benefit from faster interventions and improved outcomes  

---

## Project Structure
- data/ # EEG datasets (large files excluded via .gitignore)
- logs/ # Training and evaluation logs
- ml/ # ML/DL models and utilities
- cnn.py # Convolutional Neural Network implementation
- main.py # Entry point for running the application
- predictor.py # Inference and prediction logic
- preprocessor.py # EEG preprocessing utilities
- tf.py # TensorFlow-based modules
- visualizer.py # Signal and spectrogram visualization
- .gitignore # Ignore rules
- README.md # Project documentation
- requirements.txt # Python dependencies
