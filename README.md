# Credit Card Fraud Detection Using Machine Learning

A machine learning project that detects fraudulent credit card transactions using classification algorithms. The project uses the real Credit Card Fraud Detection dataset from Kaggle and compares multiple machine learning models to identify suspicious transactions.

## 📌 Project Overview

Credit card fraud detection is a binary classification problem in which transactions are classified as either legitimate or fraudulent.

The dataset is highly imbalanced, with fraudulent transactions representing a very small percentage of all transactions. Therefore, the project evaluates models using multiple metrics rather than relying solely on accuracy.

### Objectives
- Analyze credit card transaction data.
- Perform exploratory data analysis (EDA).
- Preprocess the dataset for machine learning.
- Train and compare multiple classification algorithms.
- Evaluate model performance using appropriate metrics.
- Identify the best-performing model based on F1-score.

## 📊 Dataset

**Dataset:** Credit Card Fraud Detection

**Source:** [Kaggle – Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

The dataset contains:
- 284,807 transactions
- 492 fraudulent transactions
- 30 input features and 1 target variable

### Features
- `Time`: Seconds elapsed between the transaction and the first transaction in the dataset.
- `Amount`: Transaction amount.
- `V1`–`V28`: Anonymized features obtained using Principal Component Analysis (PCA).
- `Class`: Target variable.

| Class | Description |
|---|---|
| 0 | Legitimate transaction |
| 1 | Fraudulent transaction |

## 🤖 Machine Learning Algorithms

The following classification algorithms are implemented:

1. Logistic Regression
2. Decision Tree Classifier
3. K-Nearest Neighbors (KNN)
4. Gaussian Naive Bayes
5. Support Vector Machine (SVM)

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- KaggleHub

## 📈 Evaluation Metrics

The models are evaluated using:

- **Accuracy:** Overall proportion of correctly classified transactions.
- **Precision:** Proportion of predicted fraudulent transactions that are actually fraudulent.
- **Recall:** Proportion of actual fraudulent transactions correctly identified.
- **F1-score:** Harmonic mean of precision and recall.
- **ROC-AUC:** Measures the model's ability to distinguish between classes.
- **PR-AUC:** Evaluates the precision-recall trade-off, especially useful for imbalanced datasets.
- **Confusion Matrix:** Visualizes correct and incorrect classifications.

The best model is selected based on its F1-score.

🔍 Project Workflow

1. Dataset acquisition using KaggleHub.

2. Data loading and inspection.

3. Exploratory Data Analysis.

4. Data preprocessing and feature scaling.

5. Train-test split using stratification.

6. Training five classification models.

7. Model comparison using evaluation metrics.

8. Confusion matrix analysis.

9. ROC and Precision-Recall curve visualization.

10. Example fraud prediction.

🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV.

- Experiment with SMOTE and undersampling techniques.

- Optimize classification thresholds.

- Explore ensemble learning techniques.

- Develop a web application for real-time fraud detection.
