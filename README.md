# Sequential-Prediction-of-Parkinson-s-Cognitive-Progression-via-Statistical-and-DL-Approaches
This project aims to compare and evaluate statistical, machine learning (ML), and deep learning (DL) models for forecasting the progression of cognitive impairment in Parkinson’s Disease (PD) using longitudinal clinical data from the Parkinson’s Progression Markers Initiative (PPMI).

📌 Project Overview
Cognitive decline in PD varies significantly across individuals, progressing from Normal Cognition (NC) to Mild Cognitive Impairment (MCI) and Dementia. Accurately predicting these transitions enables better care planning and targeted interventions.

This work implements and compares the following models:

Statistical: Inhomogeneous Continuous-Time Markov Models

Machine Learning: Logistic Regression with time-series features

Deep Learning:

Long Short-Term Memory (LSTM)

Temporal Fusion Transformer (TFT)

Ensemble model combining all three approaches

🗂️ Dataset
The data is sourced from the Parkinson’s Progression Markers Initiative (PPMI), a multicenter longitudinal study with detailed annual clinical assessments.
Key features used include:

Montreal Cognitive Assessment (MoCA)

UPDRS score

Demographics (age, sex, education)

Medical history (e.g., diabetes)

PD-related metrics (e.g., years since diagnosis)

📈 Modeling Approach
Structured clinical data into multivariate time-series format.

Framed the problem as a multi-class classification task (NC, MCI, Dementia).

Used Inverse Probability Weighted F1 Score (IPW-F1) to address extreme class imbalance (ratio ~ 50:8:1).

Ensemble method was implemented by weighted fusion of prediction probabilities
