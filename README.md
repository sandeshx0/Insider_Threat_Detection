# Insider Threat Detection Using Machine Learning

## Project Overview

This project demonstrates a machine learning approach to identifying potentially suspicious employee activity using behavioral features.

The current version uses synthetic employee activity data to demonstrate the complete machine learning workflow. Integration and evaluation using the CERT Insider Threat dataset remain future work.

## Objectives

- Generate and analyze employee activity features.
- Train a Random Forest classification model.
- Evaluate predictions using precision, recall, F1-score, ROC-AUC, and a confusion matrix.
- Explore feature importance.
- Predict whether a new activity record matches suspicious patterns.

## Technologies Used

- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib
- Google Colab
- GitHub

## Project Workflow

1. Generate synthetic employee activity data.
2. Separate features and target labels.
3. Split data into training and testing sets.
4. Train a Random Forest classifier.
5. Evaluate model performance.
6. Visualize the confusion matrix and feature importance.
7. Run a sample prediction and save model artifacts.

## Repository Contents

- `Insider_Threat_Detection.ipynb`: Notebook containing the model development workflow.
- `synthetic_employee_activity.csv`: Demonstration dataset, if included.
- `evaluation_metrics.json`: Evaluation results, if included.

## How to Run

1. Open the notebook in Google Colab.
2. Run the cells from top to bottom.
3. Review the evaluation metrics and visualizations.

## Dataset Disclaimer

The current implementation uses synthetic data. Its results do not establish real-world insider threat detection performance. The model must be evaluated on appropriately labeled real-world or benchmark data before drawing practical conclusions.

## Future Improvements

- Integrate the CERT Insider Threat dataset.
- Engineer features from authentication, file, device, and email activity logs.
- Evaluate class imbalance and false-positive rates.
- Compare multiple machine learning algorithms.
- Develop a dashboard for reviewing suspicious activity.

## Project Status

Prototype in progress.
