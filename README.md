

# Linear Regression on 1000 Companies Dataset

## Project Overview

This project demonstrates the implementation of a multiple linear regression model using Python to predict company profits based on factors such as R&D Spend, Administration, Marketing Spend, and State. The dataset used for this project consists of 1000 companies and their respective expenses in different departments along with the profit they generated.

## Key Features

- **Data Preprocessing**: Handled categorical variables using Label Encoding and OneHotEncoding.
- **Model Training**: Built a multiple linear regression model using the scikit-learn library.
- **Evaluation Metrics**: Evaluated the model using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²).

## Dataset

The dataset contains the following columns:

- `R&D Spend`: Amount spent on research and development.
- `Administration`: Expenses related to the administration department.
- `Marketing Spend`: Amount allocated for marketing.
- `State`: State in which the company operates (New York, California, Florida).
- `Profit`: The profit made by the company.

## Steps to Reproduce

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/1000-companies.git
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset and place it in the root directory.


   ```

## Model Performance

- **Mean Absolute Error**: 2300.22
- **Mean Squared Error**: 192,148,061.82
- **Root Mean Squared Error**: 13,861.75
- **R-squared (R²)**: 0.9113

## Libraries Used

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`

## Conclusion

The linear regression model provides a good fit to the dataset, with an R² score of 0.911, which suggests that approximately 91% of the variance in the profits can be explained by the model.

## Future Work

- Experiment with different models like Random Forest or Gradient Boosting to improve accuracy.
- Optimize the feature engineering process to include more derived features.

---
