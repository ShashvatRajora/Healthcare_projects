# Disease Prediction ML

## Overview

This repository contains machine learning models for predicting multiple diseases based on health data. The project is implemented in Python, leveraging various machine learning algorithms.

The primary aim of this project is to develop accurate predictive models for diagnosing diseases using machine learning techniques. By leveraging machine learning algorithms, the project aims to assist healthcare professionals in early detection and diagnosis, thereby improving patient outcomes and reducing healthcare costs.

## Programming Languages and Libraries Used

- **Python:** Main programming language used for implementing the machine learning models.

### Libraries

The following Python libraries were used in this project:

- **NumPy:** Used for numerical computing and handling arrays and matrices.
- **Pandas:** Used for data manipulation and analysis.
- **Scikit-learn (sklearn):** Used for implementing machine learning algorithms and model evaluation.
- **Matplotlib:** Used for data visualization.
- **Seaborn:** Used for statistical data visualization.
- **Streamlit:** Used for deploying and sharing the machine learning models as web applications.

## Included Disease Prediction Models

### Diabetes Prediction Model

- **Attributes:**
  1. Pregnancies
  2. Glucose
  3. Blood Pressure
  4. Skin Thickness
  5. Insulin
  6. BMI
  7. Age
  8. Diabetes Pedigree Function

### Heart Disease Prediction Model

- **Attributes:**
  1. Sex
  2. Chest Pain Type (cp)
  3. Resting Blood Pressure (trestbps)
  4. Serum Cholesterol (chol)
  5. Fasting Blood Sugar (fbs)
  6. Resting Electrocardiographic Results (restecg)
  7. Maximum Heart Rate Achieved (thalach)
  8. Exercise-Induced Angina (exang)
  9. ST Depression Induced by Exercise Relative to Rest (oldpeak)
  10. Slope of the Peak Exercise ST Segment (slope)
  11. Number of Major Vessels Colored by Fluoroscopy (ca)
  12. Thalassemia (thal)

### Parkinson's Disease Prediction Model

- **Attributes:**
  1. Name (ASCII subject name and recording number)
  2. Average Vocal Fundamental Frequency (MDVP:Fo(Hz))
  3. Maximum Vocal Fundamental Frequency (MDVP:Fhi(Hz))
  4. Minimum Vocal Fundamental Frequency (MDVP:Flo(Hz))
  5. Several Measures of Variation in Fundamental Frequency (MDVP:Jitter(%), MDVP:Jitter(Abs), MDVP:RAP, MDVP:PPQ, Jitter:DDP)
  6. Several Measures of Variation in Amplitude (MDVP:Shimmer, MDVP:Shimmer(dB), Shimmer:APQ3, Shimmer:APQ5, MDVP:APQ, Shimmer:DDA)
  7. Ratio of Noise to Tonal Components in the Voice (NHR, HNR)
  8. Health Status of the Subject (status) - 1: Parkinson's, 0: Healthy
  9. Two Nonlinear Dynamical Complexity Measures (RPDE, D2)
  10. Signal Fractal Scaling Exponent (DFA)
  11. Three Nonlinear Measures of Fundamental Frequency Variation (spread1, spread2, PPE)

These attributes provide information about various factors related to each disease. The models will use these attributes to predict the likelihood of an individual having the respective disease.


## Future Additions

Additional disease prediction models will be added in the future to provide a comprehensive tool for disease diagnosis and risk assessment.

## Repository Structure

- **diabetes_prediction/:** Contains the diabetes prediction model code and dataset.
- **heart_disease_prediction/:** Contains the heart disease prediction model code and dataset.
- **parkinsons_prediction/:** Contains the Parkinson's disease prediction model code and dataset.
- **.gitignore:** Specifies intentionally untracked files to ignore.


