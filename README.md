# 📊 Sales Prediction Using Machine Learning

This project demonstrates how to predict sales based on advertising expenditures using various machine learning models. By employing different techniques and tuning hyperparameters, the relationship between advertising spend and sales performance is analyzed to improve predictive accuracy.

## 📖 Project Overview

The following machine learning models are implemented and evaluated in this project:
- **Linear Regression**: A basic approach to predict sales using advertising data.
- **Lasso Regression**: Enhances prediction by adding L1 regularization, reducing overfitting.
- **Grid Search with Cross-Validation**: Used to fine-tune hyperparameters for optimal model performance.

## 📊 Dataset

The dataset consists of advertising expenditures across different media platforms (TV, radio, and newspaper) and their corresponding sales figures. The data is provided in the `Advertising.csv` file.

## 🚀 Installation

To run this project on your local environment:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-repo/SalesPrediction.git
   cd SalesPrediction
   ```

2. **Install the necessary dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## 🛠️ Usage Instructions

1. **Launch the Jupyter Notebook**:
   ```bash
   jupyter notebook SalesPrediction.ipynb
   ```

2. **Execute the cells** to train, validate, and test the models.

## 🧩 Models Implemented

- **Linear Regression**: Models a linear relationship between advertising spend and sales.
- **Lasso Regression**: Incorporates L1 regularization to eliminate irrelevant features, reducing model complexity.

## ⚙️ Hyperparameter Tuning

- **GridSearchCV** is applied to optimize the model’s hyperparameters. The key parameters fine-tuned include:
  - `alpha` (regularization strength for Lasso Regression)
  - `fit_intercept`
  - `max_iter` (maximum iterations for convergence)

## 📈 Model Performance

The models' performance is evaluated using the R-squared metric. The Lasso model, after hyperparameter tuning, achieved an R-squared score of **0.92**, indicating a strong correlation between the features and sales.

### Results:
- **Linear Regression R² Score**: 0.89
- **Lasso Regression R² Score**: 0.92 (after tuning)

## 🧪 Libraries Used

- **`scikit-learn`**: For implementing machine learning algorithms and cross-validation techniques.
- **`pandas`**: For data manipulation and analysis.
- **`numpy`**: For numerical operations.

## 🔍 Conclusion

This project showcases how advertising expenditures impact sales and demonstrates the effectiveness of machine learning models in sales prediction. Future enhancements may include:
- Experimenting with Ridge Regression for comparison.
- Applying feature engineering techniques to enhance model accuracy.

