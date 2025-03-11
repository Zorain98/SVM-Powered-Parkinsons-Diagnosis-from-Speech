# SVM-Powered-Parkinsons-Diagnosis-from-Speech

## Overview  
This repository contains a machine learning-based predictive system for detecting Parkinson's disease using vocal biomarkers. The model is trained on the **Oxford Parkinson's Disease Detection Dataset**, leveraging **Support Vector Classifier (SVC)** to classify individuals as healthy or affected by Parkinson's disease.  

## Dataset  
The dataset comprises **195 voice recordings** from **31 individuals**, 23 of whom have Parkinson's disease. Each recording is characterized by **22 biomedical voice measurements**, capturing variations in fundamental frequency, amplitude, noise-to-tonal ratios, and nonlinear dynamics.  

**Key Features:**  
- **Fundamental Frequency (Fo, Fhi, Flo)**: Measures of vocal frequency variations.  
- **Jitter & Shimmer**: Measures of frequency and amplitude perturbations.  
- **NHR & HNR**: Noise-to-harmonic ratio features.  
- **Nonlinear Measures**: Complexity and fractal scaling features like RPDE, DFA, D2, and PPE.  
- **Health Status (`status`)**: The target variable (1 = Parkinson's, 0 = Healthy).  

## Model & Methodology  
- **Algorithm**: **Support Vector Machine (SVM)** with optimized hyperparameters.  
- **Feature Scaling**: Standardization for optimal model performance.  
- **Evaluation Metrics**: Accuracy.  
- **Cross-validation**: To ensure generalizability.  

## Predictive System  
A user-friendly predictive system has been built, allowing users to input biomedical voice parameters and receive an instant prediction on whether the patient has Parkinson’s disease.  

## References  
- **Dataset Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Parkinsons)  
- **Research Paper**:  
  Max A. Little, Patrick E. McSharry, Eric J. Hunter, Lorraine O. Ramig (2008),  
  _"Suitability of Dysphonia Measurements for Telemonitoring of Parkinson's Disease"_,  
  IEEE Transactions on Biomedical Engineering.  

## Contributing  
Contributions are welcome! Feel free to submit pull requests or open issues for improvements.  
