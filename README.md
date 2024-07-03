# Capstone Project: Propensity Model for Prescribing Behavior

**Author:** James Peebles
**Date:** July 2024

This repository contains the final capstone project for predicting the propensity of healthcare providers to prescribe medications. The project leverages an artificial neural network (ANN) to analyze various features related to provider characteristics and prescribing patterns. The goal is to develop a high-accuracy predictive model that can offer valuable insights for healthcare providers and policymakers.

## Repository Contents

- **Data Overview**: Detailed description and exploration of the dataset used.
- **Data Preprocessing**: Steps for encoding, splitting, and scaling the data.
- **Model Training**: Architecture of the ANN, training process, and hyperparameter tuning.
- **Model Evaluation**: Performance evaluation using metrics such as accuracy, precision, recall, and F1-score.
- **Feature Importance and Interpretation**: Analysis of key features influencing the model's predictions.
- **Conclusions and Recommendations**: Insights drawn from the model and suggestions for future work.

## Data Overview

The dataset used in this project includes various features related to healthcare providers and their prescribing patterns. Key attributes are:

- **Prescriber ID**: Unique identifier for each prescriber.
- **Prescriber Name**: Name of the prescriber.
- **Region**: Geographic region of the prescriber.
- **Prescriber Specialty**: Area of specialization of the prescriber.
- **Payment Type**: Type of payment (e.g., commercial, managed Medicaid).
- **Payer Plan Lives**: Number of lives covered by the payer plan.
- **TRx**: Total number of prescriptions.
- **NRx**: Number of new prescriptions.
- **NQty**: Quantity of new prescriptions.
- **TQty**: Total quantity of prescriptions.
- **TRx6Mos**: Total number of prescriptions in the last six months.
- **Probability**: Predicted probability of prescribing.
- **Prediction**: Binary prediction of prescribing behavior.

## Key Features

- **Python Implementation**: All code is implemented in Python, utilizing popular libraries such as NumPy, Pandas, Scikit-learn, and TensorFlow.
- **Jupyter Notebook**: The project is documented and executed in a Jupyter Notebook for easy understanding and reproducibility.
- **Detailed Analysis**: Comprehensive exploratory data analysis and feature importance interpretation.
- **Real-World Application**: Practical recommendations for deploying the model in healthcare settings.

## Results

The project successfully develops an ANN model with high accuracy in predicting prescribing behaviors. Key features influencing the model's predictions are identified, providing valuable insights for understanding provider prescribing patterns.

### Conclusions

#### Model Performance:
- The ANN model achieved an accuracy of approximately 72.89%, indicating a reasonable performance in predicting the propensity of providers to prescribe medications.
- The confusion matrix shows that the model correctly predicted 114 positive cases and 7 negative cases, with 34 false positives and 11 false negatives.

#### Key Features:
The most influential features in predicting prescribing behaviors include:
- **Prescriber Specialty**: The area of specialization of the prescriber significantly impacts the likelihood of prescribing.
- **Region**: Geographic location also plays a crucial role, indicating regional differences in prescribing patterns.
- **Payment Type**: The type of payment (e.g., commercial, managed Medicaid) influences prescribing behavior.
- **Payer Plan Lives**: The number of lives covered by the payer plan.
- **TRx6Mos**: The total number of prescriptions in the last six months.

### Recommendations

#### Model Refinement:
- Further tuning of hyperparameters and exploring different neural network architectures could enhance the model’s performance.
- Incorporating additional features such as detailed patient demographics and clinical outcomes may improve accuracy.

#### Data Collection and Quality:
- Continuous data collection is essential to keep the model updated with the latest prescribing trends and behaviors.
- Improving data quality by addressing missing values, ensuring accurate data entry, and reducing noise in the dataset will benefit model performance.

#### Implementation and Usage:
- Deploy the model in real-world settings to assist healthcare providers and policymakers in making informed decisions about prescribing practices.
- Training and support for users will be crucial for effective interpretation and utilization of the model’s predictions.

#### Future Research:
- Investigate the integration of other machine learning models (e.g., ensemble methods) to potentially boost performance.
- Explore the ethical implications and ensure compliance with privacy and regulatory standards in healthcare to build trust and acceptance among users.

By following these recommendations, the utility of the model can be enhanced, providing valuable insights to healthcare providers and ultimately leading to better patient outcomes and optimized prescribing practices.
