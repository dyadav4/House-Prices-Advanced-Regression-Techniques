# House Prices: Advanced Regression Techniques

**Kaggle Competition**: Predicting house sale prices using advanced regression techniques and feature engineering. Includes Tableau dashboard for interactive data visualization.

## Overview

This project tackles the classic Kaggle competition for predicting house prices in Ames, Iowa. Using 79 explanatory variables describing residential homes, the model predicts the final sale price through advanced regression techniques and comprehensive feature engineering.

## Dataset

- **Source**: Kaggle - House Prices: Advanced Regression Techniques
- **Features**: 79 variables including:
  - Physical attributes (lot size, bedrooms, bathrooms)
  - Location factors (neighborhood, zoning)
  - Quality ratings (overall quality, condition)
  - Year built, remodeling dates
  - Garage, basement, and other amenities
- **Target**: SalePrice (continuous variable)
- **Size**: ~1,400 training examples

## Approach

### Data Preprocessing:
- **Missing Value Imputation** - Handle NaN values strategically
- **Feature Engineering** - Create new meaningful features
- **Outlier Detection** - Identify and handle extreme values
- **Feature Scaling** - Normalize numerical features

### Modeling Techniques:
- **Linear Regression** - Baseline model
- **Ridge Regression** - L2 regularization
- **Lasso Regression** - L1 regularization with feature selection
- **ElasticNet** - Combined L1/L2 regularization
- **Gradient Boosting** - XGBoost, LightGBM
- **Ensemble Methods** - Model stacking and blending

## Technologies Used

- **Language**: Python
- **ML Libraries**: Scikit-learn, XGBoost, LightGBM
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, **Tableau**
- **Environment**: Jupyter Notebook

## Interactive Dashboard

**Tableau Workbook**: `Sprint 2 - dashboard Final Sprint.twb`

Interactive visualization dashboard featuring:
- Price distribution analysis
- Feature correlation heatmaps
- Neighborhood price comparisons
- Quality vs. Price relationships
- Temporal trends (year built impact)

## Project Structure

```
House-Prices-Advanced-Regression-Techniques/
├── House_Prices_Advanced_Regression_Techniques.ipynb  # Main analysis
├── Sprint 2 - dashboard Final Sprint.twb              # Tableau dashboard
└── README.md
```

## Installation

1. Clone the repository
```bash
git clone https://github.com/dyadav4/House-Prices-Advanced-Regression-Techniques.git
cd House-Prices-Advanced-Regression-Techniques
```

2. Install dependencies
```bash
pip install pandas numpy scikit-learn xgboost lightgbm matplotlib seaborn jupyter
```

3. Run the notebook
```bash
jupyter notebook House_Prices_Advanced_Regression_Techniques.ipynb
```

4. Open Tableau dashboard (requires Tableau Desktop)

## Key Features Engineered

- Total square footage (above ground + basement)
- Age of house at time of sale
- Remodeling indicator
- Quality-to-price ratios
- Interaction features
- Polynomial features for non-linear relationships

## Evaluation Metric

- **RMSE** (Root Mean Squared Error) - Kaggle competition metric
- **R² Score** - Model fit quality
- **MAE** (Mean Absolute Error) - Average prediction error

## Results

[Add your Kaggle scores here]
- Public Leaderboard RMSE: [X]
- Private Leaderboard RMSE: [X]
- R² Score: [X]

## Key Learnings

- Advanced feature engineering techniques
- Handling missing data in real estate datasets
- Regularization to prevent overfitting
- Ensemble methods for improved predictions
- Data visualization with Tableau
- Kaggle competition workflow

## Future Improvements

- Deep learning approaches (Neural Networks)
- More sophisticated feature interactions
- Geo spatial analysis
- External data integration (economic indicators)
- AutoML techniques

## Competition

- **Platform**: Kaggle
- **Challenge**: House Prices - Advanced Regression Techniques
- **Link**: https://www.kaggle.com/c/house-prices-advanced-regression-techniques

## Contact

- GitHub: [@dyadav4](https://github.com/dyadav4)
