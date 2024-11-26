# Breast Cancer Prediction Using Machine Learning

This repository contains a project that predicts breast cancer cases as **malignant** or **benign** using the **Breast Cancer Wisconsin dataset** from `sklearn`. Three machine learning models are implemented: **Logistic Regression**, **Support Vector Machine (SVM)**, and **Decision Tree Classifier**.

## Features
- **Preprocessing**: Standardization of features using `StandardScaler`.
- **Model Training**: Implementation of Logistic Regression, SVM, and Decision Tree Classifier.
- **Evaluation**: Metrics include accuracy, precision, recall, F1-score, confusion matrix, and ROC curve.
- **Visualizations**: Includes class distribution, ROC curves, and confusion matrices.

## Results
- **Logistic Regression**: Accuracy = 97.37%  
- **SVM**: Accuracy = 98.25%  
- **Decision Tree Classifier**: Accuracy = 93.86%

## How to Run
1. Clone the repository.
2. Install required libraries:
   ```bash
   pip install numpy pandas matplotlib scikit-learn
   ```
3. Run the script to train models and view evaluation metrics.

## Visualizations
- Class distribution of target labels.
- Confusion matrices for each model.
- Receiver Operating Characteristic (ROC) curve for Logistic Regression.

## License
Open for educational purposes.
