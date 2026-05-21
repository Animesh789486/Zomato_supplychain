# Zomato Restaurant Price Prediction using Machine Learning

## Overview
End-to-end Machine Learning project to predict the **cost for two** of restaurants using Zomato dataset. Built multiple regression models with detailed EDA and model comparison.

### Key Highlights
- **Best Model**: Random Forest Regressor with **R² = 0.9086**
- **Other Models**: Linear Regression (R² = 0.578) | Decision Tree (R² = 0.855)
- Achieved significant improvement through proper feature engineering and model tuning.

## Tech Stack
- **Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Models**: Linear Regression, Decision Tree Regressor, Random Forest Regressor

## Project Workflow
1. Data Loading & Cleaning
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing (Encoding + Scaling)
4. Model Building & Training
5. Model Evaluation & Comparison
6. Conclusion

## Results
| Model                  | R² Score    | MSE          |
|------------------------|-------------|--------------|
| Linear Regression      | 0.578       | 81857.88     |
| Decision Tree          | 0.855       | 28069.06     |
| **Random Forest**      | **0.909**   | **17739.49** |

## How to Run
```bash
jupyter notebook Zomato.ipynb
