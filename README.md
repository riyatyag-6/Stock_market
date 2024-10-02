# Stock Price Prediction

## Overview
This project aims to predict **Amazon stock prices** using historical financial market data. The dataset includes features such as **Natural Gas Price**, **Crude Oil Price**, **Bitcoin Price**, and **Gold Price**. The model was built using **Linear Regression** after thorough data preprocessing and feature selection.

## Project Structure
- **Data Preprocessing:** Handling missing values, scaling numerical data, and encoding categorical features.
- **Feature Selection:** Key features such as **Crude Oil Price**, **Natural Gas Price**, and **Gold Price** were selected for the model based on domain knowledge.
- **Modeling:** A **Linear Regression** model was used to predict **Amazon_Price**, with performance evaluation through visualizing feature importance via regression coefficients.

## Challenges
- **Data Complexity:** The dataset contained many features, making it difficult to select the most relevant ones.
- **Missing Data:** Missing values in certain columns (e.g., volume data) were handled via imputation.
- **Feature Correlation:** High correlation between certain market prices posed a challenge for feature selection and model performance.

## Solutions
- **Preprocessing:** Handled missing data using imputation and scaled the features to ensure proper model training.
- **Feature Engineering:** Selected important features and transformed categorical data using one-hot encoding.
- **Model Selection:** Applied **Linear Regression** to identify key predictors and analyzed their influence on Amazon stock prices through model coefficients.

## Roadblocks
- **Multicollinearity:** High correlation between some features like commodity prices required careful handling to avoid multicollinearity issues.
- **Overfitting:** The risk of overfitting was mitigated using regularization techniques and cross-validation.

## Conclusion
This project demonstrates the effective use of **Linear Regression** in predicting Amazon stock prices by leveraging market indicators. Future enhancements could include using advanced models like **Random Forest** or **XGBoost** to capture more complex patterns.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/amazon-stock-price-prediction.git
