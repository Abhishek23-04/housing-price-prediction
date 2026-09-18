# Housing Price Prediction - ML Project

## Overview
This project predicts house prices using machine learning. The model is trained on the Kaggle "House Prices - Advanced Regression Techniques" dataset.

## Dataset
- **Source**: Kaggle
- **Records**: 1,460 houses
- **Features**: 37 numerical features
- **Target**: SalePrice

## Models Built
1. **Linear Regression** - R² Score: 0.8227 (82.27%)
2. **Random Forest** - R² Score: 0.8877 (88.77%)
3. **Gradient Boosting** - R² Score: 0.8974 (89.74%) ⭐ BEST

## Results
- **Best Model**: Gradient Boosting Regressor
- **R² Score**: 0.8974 (89.74% accuracy)
- **MAE**: ~$18,000
- **RMSE**: ~$24,000

## Key Features Used
- OverallQual, GrLivArea, GarageCars, GarageArea, TotalBsmtSF

## Technologies Used
- Python 3.11
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Open Jupyter: `jupyter notebook`
3. Run `housing-analysis.ipynb`

## Files
- `housing-analysis.ipynb` - Complete analysis and modeling
- `housing_model.pkl` - Trained Gradient Boosting model
- `train.csv` - Training dataset
- `test.csv` - Test dataset

## Author
Abhishek

## License
MIT
