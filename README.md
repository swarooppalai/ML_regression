# Readme for Economic Index Analysis

## Overview

This repository contains Python scripts for analyzing economic indices and building linear regression models. The analysis focuses on understanding the relationships between different economic indicators and predicting the economic index's behavior.

## Files

1. `economic_index.csv`: This CSV file contains the dataset with economic indicators, including interest rates, unemployment rates, and an economic index.

2. `linear_regression_analysis.ipynb`: This Jupyter Notebook provides a step-by-step walkthrough of the analysis. It includes data exploration, visualization, data cleaning, model training, and evaluation.

## Libraries Used

- **pandas**: Used for data manipulation and analysis.
- **matplotlib**: Employed for creating visualizations.
- **numpy**: Utilized for numerical operations.
- **seaborn**: Used for enhanced data visualization.
- **scikit-learn**: Employed for machine learning tasks, such as data splitting, standardization, linear regression modeling, and performance evaluation.
- **statsmodels**: Utilized for more detailed statistical analysis, including Ordinary Least Squares (OLS) linear regression.

## How to Use

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/economic-index-analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd economic-index-analysis
   ```

3. Ensure you have the required libraries installed:

   ```bash
   pip install -r requirements.txt
   ```

4. Open and run the `linear_regression_analysis.ipynb` Jupyter Notebook to execute the analysis steps.

## Analysis Steps

1. **Data Loading**: The economic data is loaded from the `economic_index.csv` file using the `pandas` library.

2. **Data Cleaning**: Unwanted columns (e.g., "Unnamed: 0", "year", "month") are dropped, and missing values are checked and handled.

3. **Exploratory Data Analysis (EDA)**: Visualizations, such as pair plots and correlation matrices, are created to understand the relationships between variables.

4. **Linear Regression Modeling**: The data is split into training and testing sets. Features are standardized using the `StandardScaler`. A linear regression model is trained on the training data and evaluated on the test data.

5. **Cross-Validation**: Cross-validation is performed to assess the model's generalization performance.

6. **Performance Metrics**: Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), R-squared, and adjusted R-squared are calculated to evaluate the model's performance.

7. **Statistical Analysis (Optional)**: The `statsmodels` library is used to perform a more detailed statistical analysis, including the Ordinary Least Squares (OLS) linear regression.

8. **Visualization of Results**: Various plots, such as scatter plots and residual plots, are generated to visualize the model's predictions and residuals.


Feel free to contribute or provide feedback!

---

*This readme serves as a guide for understanding and utilizing the economic index analysis scripts. For any questions or concerns, please contact the contributors.*
