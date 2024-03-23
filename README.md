# Income Prediction Model

## Project Overview

This project aims to predict whether an individual earns more than $50,000 per year based on demographic and employment-related features. Using a well-known dataset from kaggle.com (https://www.kaggle.com/datasets/wenruliu/adult-income-dataset), the analysis delves into exploratory data analysis, data preprocessing, model building, and evaluation to develop a predictive model.

## Dataset

The dataset used in this project is the Adult Income dataset, which contains information about individuals from a 1994 Census database. It includes attributes like age, work class, education, occupation, and income.

## Files

- `Income_prediction.ipynb`: Jupyter notebook containing the analysis and modeling.
- `adult.csv`: The dataset used for this project.

## Methodology

The project follows these steps:

1. Exploratory Data Analysis (EDA)
2. Data Preprocessing
3. Model Building
   - Logistic Regression (Baseline)
   - Random Forest (Baseline)
   - Random Forest with Hyperparameter Tuning and Cross-Validation (Final Model)
4. Model Evaluation and Selection

## Results

The final model, a Random Forest classifier with hyperparameter tuning and cross-validation, proved to be the best performing model. It achieved an 86.70% accuracy on the test set and a cross-validation mean score of 86.09%, indicating no significant overfitting.

## Usage

To run the Jupyter notebook, ensure that you have the following prerequisites installed:

- Python 3.8+
- Jupyter Notebook
- Libraries: pandas, numpy, scikit-learn, seaborn, matplotlib

## Contact

Your Name - [parinya.ssai@gmail.com]

Project Link: [https://github.com/teampa/income_prediction.git]
