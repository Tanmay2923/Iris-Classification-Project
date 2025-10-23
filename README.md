# Iris-Classification-Project
####  *A foundational classification project. It uses Logistic Regression on the Iris dataset to predict flower species (Setosa, Versicolor, Virginica) based on measurements. Focuses on data preparation, model training, and evaluation using the Accuracy Score and Confusion Matrix.*

## Overview
A foundational machine learning project focused on classification. This repository trains a **Logistic Regression** model using the renowned **Iris dataset** to predict the species of Iris flowers. It serves as an excellent introduction to handling structured data, applying a linear classification model, and rigorously evaluating its performance.

## Goal
The primary goal is to build and evaluate a robust, high-accuracy classification model capable of distinguishing between the three Iris species: Setosa, Versicolor, and Virginica, based solely on their physical measurements.

## Methodology
The project follows a standard machine learning pipeline:
1. **Data Loading**: The Iris dataset is loaded directly from `scikit-learn`.
2. **Data Splitting**: The dataset is divided into training and testing sets (standard 70/30 split) to ensure unbiased evaluation.
3. **Preprocessing**: `StandardScaler` is applied to normalize the features, ensuring the Logistic Regression model converges efficiently and performs optimally.
4. **Model Training**: A **Logistic Regression** model is fitted to the scaled training data.
5. **Prediction & Evaluation**: The model generates predictions on the test set, and its performance is quantified using classification metrics.

## Features
- **Classification**: Predicts the species of Iris flower (Setosa, Versicolor, or Virginica).
- **Logistic Regression**: Implements the model for multi-class classification.
- **Feature Scaling**: Uses `StandardScaler` to normalize input features.
- **Model Evaluation**: Reports key metrics: Accuracy Score, Confusion Matrix, and Classification Report.

## Results and Metrics
The model's performance is measured using the following standard classification metrics:
- **Accuracy Score**: The overall proportion of correct predictions made by the model.
- **Confusion Matrix**: A table summarizing the number of correct and incorrect predictions for each class.
- **Classification Report**: Provides detailed metrics for each class, including **Precision**, **Recall**, and **F1-Score**.

## Tech Stack
| Tool | Purpose |
|------|---------|
|**Python**|Primary programming language for model development.|
|**`scikit-learn`**|Used for **Logistic Regression**, model training, and performance metrics.|
|**`pandas`**|Essential for data loading and feature handling.|
|**`numpy`**|Core library for high-performance array operations.|

## Prerequisites
- **Python 3.x** environment.

- Required Python packages (listed in **Installation**).

## Installation
**Clone the repository and install the dependencies:**
1. #### Clone the repository ####
```bash
git clone https://github.com/Tanmay2923/Iris-Classification-Project.git
```

2. #### Install necessary Python libraries ####
```bash
pip install pandas numpy scikit-learn
```

## Running the Application
The project is executed as a single Jupyter/Colab notebook.
1. Open the file `Iris Classification Project` in Google Colab or a local Jupyter Notebook environment.
2. Run all cells sequentially to load the data, train the model, and display the final performance metrics.
