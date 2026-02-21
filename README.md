# Insurance Fraud Detection using Machine Learning

## Overview

This project focuses on detecting fraudulent insurance claims using machine learning algorithms. Insurance fraud is a major issue that causes financial losses to insurance companies. The goal of this project is to build and compare different machine learning models to classify whether an insurance claim is fraudulent or not.

The project includes data preprocessing, model training, evaluation, and performance comparison using graphs and metrics.

---

## Dataset

The dataset used in this project is:

dataset/insurance_fraud.csv

The dataset contains insurance claim records including:

- Customer information
- Policy details
- Incident information
- Claim amount
- Fraud reported status

Target variable:

fraud_reported

This variable indicates whether the claim is fraudulent.

---

## Project Structure

```
insurance-fraud-detection

dataset/
    insurance_fraud.csv

results/
    graphs and output files

Data_Mining.ipynb

README.md
```

---

## Algorithms Used

The following machine learning algorithms were implemented and compared:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Neural Network

Each model was trained using the training dataset and tested using the testing dataset.

---

## Model Evaluation

The models were evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC Curve

Performance comparison graphs were generated and saved in the results folder.

---

## Results

Based on the model evaluation:

- Random Forest achieved the best performance in detecting fraudulent claims.
- Neural Network also showed strong performance.
- Logistic Regression provided stable and consistent results.
- Decision Tree performed well but showed slight overfitting.
- SVM showed moderate performance.

ROC curve analysis confirmed that ensemble models performed better compared to other algorithms.

All result graphs and outputs are available in the results folder.

---

## Visualizations

The project includes:

- Training vs Testing Accuracy Comparison
- Metrics Comparison Graph
- ROC Curve

These graphs help compare the performance of different machine learning models.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- TensorFlow / Keras
- Jupyter Notebook

---

## How to Run

Step 1: Clone the repository

git clone https://github.com/yourusername/insurance-fraud-detection.git

Step 2: Open Jupyter Notebook

jupyter notebook

Step 3: Open the file

Data_Mining.ipynb

Step 4: Run all cells

---

## Conclusion

This project demonstrates how machine learning can be used to detect fraudulent insurance claims effectively. Random Forest and Neural Network provided the best performance.

This system can help insurance companies detect fraud faster and reduce financial losses.

---

## Author

Yaswanth Podapati

MS Computer Science
