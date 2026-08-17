# Data Unboxed : Analytics X Machine Learning

This repository contains comprehensive masterclasses covering the complete data science pipeline, from Data Analytics and Visualization (DAV) to Machine Learning (ML).

## 📊 Data Analytics & Visualization (DAV)

**Notebook:** `DAV_Masterclass.ipynb`
**Dataset:** Telecom Customer Churn (`CustomerChurn.csv`)

This section focuses on understanding and analyzing data to answer critical business questions, such as: *A telecom company is losing customers. Can data tell us who is leaving and why?*

**Key Topics Covered:**
- **Data Collection & Loading:** Importing data using pandas and understanding data shapes and structures.
- **Data Cleaning & Preprocessing:** Handling missing values, correcting data types (e.g., converting text to numeric), and preparing the dataset for analysis.
- **Exploratory Data Analysis (EDA) & Visualization:** Using Matplotlib and Seaborn to uncover hidden patterns and trends in customer behavior.
- **Bridge to Machine Learning:** Structuring and organizing cleaned data to be fed into predictive models.

## 🤖 Machine Learning (Titanic Survival Prediction)

**Notebook:** `titanic.ipynb`

This section demonstrates the fundamental workflow of building and evaluating a Machine Learning model. We focus on a binary classification problem: predicting passenger survival on the Titanic.

**Key Topics Covered:**
- **Data Preprocessing & Feature Engineering:** Handling missing values (imputation with median/mode), dropping redundant columns, and one-hot encoding categorical variables (e.g., Sex, Embarked).
- **Train-Test Split:** Splitting the dataset into training (80%) and testing (20%) sets to ensure model generalization and avoid overfitting.
- **Model Training:** Implementing and training a Logistic Regression model for binary classification.
- **Predictions & Evaluation:** Using the trained model to make predictions on unseen data and evaluating its performance using critical metrics:
  - Accuracy Score
  - Classification Report (Precision, Recall, F1-Score, Support)
  - Confusion Matrix (Visualized using Heatmaps)

## 🚀 Getting Started

1. Clone this repository to your local machine.
2. Ensure you have Python installed along with Jupyter Notebook.
3. Install the required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
4. Launch Jupyter Notebook and open the `.ipynb` files to begin!
