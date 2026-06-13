# House Price Prediction using Machine Learning

## Project Overview

This project applies machine learning techniques to predict residential property prices using the Ames Housing dataset. The objective is to identify the key factors influencing house prices and build predictive models that can accurately estimate property values.

## Dataset

The dataset contains 1,460 residential property records with 81 features describing various aspects of each house, including:

- Property size and area
- Overall quality rating
- Number of rooms
- Garage capacity
- Basement characteristics
- Construction year
- Sale price (target variable)

**Target Variable:**
- SalePrice

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Joblib
- Jupyter Notebook

## Exploratory Data Analysis (EDA)

The analysis included:

- Dataset structure inspection
- Missing value analysis and handling
- Correlation analysis
- Feature importance investigation
- Data visualization

### Key Findings

- OverallQual showed the strongest relationship with house prices.
- Larger living areas generally resulted in higher sale prices.
- Garage capacity and garage area significantly influenced property value.
- Newer properties tended to have higher prices.

## Machine Learning Models

### Linear Regression

**Performance Metrics**

- MAE: 21,494.77
- RMSE: 34,330.19
- R² Score: 0.8463

### Random Forest Regressor

**Performance Metrics**

- MAE: 17,520.62
- RMSE: 28,474.39
- R² Score: 0.8943

## Model Comparison

| Model | MAE | RMSE | R² Score |
|---------|---------|---------|---------|
| Linear Regression | 21,494.77 | 34,330.19 | 0.8463 |
| Random Forest Regressor | 17,520.62 | 28,474.39 | 0.8943 |

### Best Model

The Random Forest Regressor achieved the best performance with:

- Lower prediction error
- Lower RMSE
- Higher R² score

The model explains approximately **89.4%** of the variation in house prices.

## Feature Importance

The most influential features identified by the Random Forest model were:

1. OverallQual
2. GrLivArea
3. TotalBsmtSF
4. 2ndFlrSF
5. 1stFlrSF
6. BsmtFinSF1
7. LotArea
8. GarageArea
9. GarageCars
10. YearBuilt

## Project Structure

```text
House-Price-Prediction/
│
├── data/
├── notebooks/
├── images/
├── models/
│   └── random_forest_house_price.pkl
├── requirements.txt
├── README.md
└── .gitignore
```

## Future Improvements

- Hyperparameter tuning using GridSearchCV
- XGBoost and Gradient Boosting models
- Cross-validation
- Streamlit deployment
- Real-time house price prediction application

## Author

**Ruchitha Sampath Weerasekara**

🎓 MSc Data Science, University of East Anglia

💻 Aspiring Data Scientist | Machine Learning Enthusiast

