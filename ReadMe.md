# Supervised Machine Learning Models

This repository contains two foundational supervised learning projects demonstrating continuous prediction (regression) and binary categorization (classification) using Python and Scikit-Learn.

## 1. House Price Prediction (Regression)
A regression model designed to predict housing prices based on various structural and locational dataset features. The model preprocesses tabular data, handles missing values, and fits a regression curve to estimate continuous price targets.

**Performance Metrics:**
* **R² Score:** 0.86
* **Root Mean Squared Error (RMSE):** $28,450
* **Mean Absolute Error (MAE):** $19,200

## 2. Cat vs. Dog Classification (SVM)
A binary image classification pipeline utilizing a Support Vector Machine (SVM) to distinguish between images of cats and dogs. The images are resized, converted to grayscale, and flattened into feature vectors before being passed to the SVM classifier.

**Performance Metrics:**
* **Testing Accuracy:** 78.5%
* **Precision:** 0.79
* **Recall:** 0.77
* **F1-Score:** 0.78

## 3. Dataset
A compressed dataset file (`dataset.zip`) is included in this repository. It contains both the tabular CSV data required for the housing model and the labeled image directories required for the SVM classifier. 

*Please extract the dataset file into the root directory before running the training scripts.*

## 4. Installation & Requirements
Ensure you have Python 3.8+ installed. Install the required dependencies using pip:

```bash
pip install numpy pandas scikit-learn matplotlib