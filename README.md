# skills4future_fc
# Crop Yield Prediction using Machine Learning
An end-to-end Data Science case study developed during the **Skills4Future Foundation** program. This project implements a predictive modeling pipeline using Python to estimate crop yields in India based on historical agricultural data.

## 🚀 Project Overview
This repository contains a complete workflow for analyzing, preprocessing, and building a predictive model for agricultural yields. The project walks through essential machine learning stages, from raw data loading to evaluation and visualization.

## 📊 Core Concepts & Workflow Covered
1. **Data Loading:** Importing and inspecting the agricultural dataset (`crop_yield_prediction_india_2.csv`) using pandas.
2. **Categorical Encoding:** Utilizing scikit-learn, LabelEncoder to convert object or string columns into numerical formats suitable for machine learning models.
3. **Feature Selection:** Separating the independent features from the target variable.
4. **Data Splitting:** Splitting data into Training and Testing subsets with a reproducible random state using `train_test_split`.
5. **Model Training:** Initializing and training a Linear Regression algorithm using sklearn.linear_model.
6. **Prediction:** Making performance inferences on unseen testing data.
7. **Visualization:** Creating a "Predicted vs Actual" scatter plot evaluation using `matplotlib`.

## 🛠️ Tech Stack & Tools Used
* **Language:** Python
* **Data Manipulation:** pandas , numpy
* **Machine Learning:** scikit-learn
* **Data Visualization:** matplotlib, seaborn

## 📁 Repository Structure
* CASE_STUDY.ipynb — The primary Jupyter Notebook containing the full data science pipeline.
* Day1-4.ipynb — Daily progression and practice work from the foundation class.
* README.md — Project documentation.

## 📈 Key Visualizations
The model evaluates its performance by plotting a comparison of **Predicted Yield vs Actual Yield**, allowing visual validation of the Linear Regression model's trend fitting.
