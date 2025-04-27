# House Prices - Advanced Regression Techniques

## Project Overview

This project predicts housing prices based on a variety of property features using supervised learning regression techniques. It was created as part of a final project for a machine learning course, demonstrating EDA, feature engineering, model building, hyperparameter tuning, and model evaluation.

Dataset: [Kaggle House Prices Competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)

## Project Structure

* house-pricing.ipynb: Full Jupyter Notebook including:

  * Problem Description

  * Exploratory Data Analysis (EDA)

  * Data Cleaning and Feature Engineering

  * Feature Selection

  * Model Training and Comparison (Linear Regression, Random Forest, XGBoost)

  * Hyperparameter Tuning

  * Performance Evaluation and Visualization

  * Discussion and Conclusions

* house_prices_presentation.pptx: Final project presentation.

## Methodology

### Exploratory Data Analysis

* Analyzed distributions, missing values, and correlations.

* Log-transformed skewed numerical features.

* Imputed missing values using domain knowledge and statistical techniques.

### Feature Engineering

* One-hot encoding of categorical variables.

* Standard scaling of numerical features.

* Feature selection using Lasso regression to reduce dimensionality.

### Models Used

* Linear Regression: As a baseline.

* Ridge Regressor: Attempt to address potential multicollinearity.

* Random Forest Regressor: To capture non-linear relationships.

### Hyperparameter Tuning

* Performed using GridSearchCV with 5-Fold Cross-Validation for Random Forest and XGBoost.

### Evaluation Metrics

* Root Mean Squared Error (RMSE)

* R² Score

### Results

* Best Model: Random Forest

* Performance:

  * Lowest RMSE: 0.141

  * Highest R² score on validation data: 0.9

### Key Influential Features:

* OverallQual

* GrLivArea

* GarageCars

* TotalBsmtSF

## How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/house-prices-regression.git
cd house-prices-regression
```

2. Install required packages:

```
pip install -r requirements.txt
```

3. Run the Jupyter notebook:

## Deliverables

* **Jupyter Notebook**: Full code, visualizations, and analysis.

* **Video Presentation**: Project highlights and demo (linked in the GitHub repository).

* **GitHub Repository**: Organized and documented.

