# CA-Final
# Health & Lifestyle Weight Prediction

This repository contains a Colab notebook that builds a linear regression model to predict 
an individual’s weight (kg) from height (cm), age (years), and weekly exercise frequency. 

## Reflection

I approached this problem by:
1. **Loading & Cleaning**  
   - Downloaded the “Health and Lifestyle” dataset from Kaggle via `kagglehub`.  
   - Standardized column names and encoded textual exercise-frequency labels into numeric midpoints.

2. **Modeling**  
   - Performed an 80/20 train/test split (`random_state=42`).  
   - Trained `LinearRegression` and interpreted coefficients for height, age, and exercise.

3. **Evaluation**  
   - Computed Test MSE = 209.89 (RMSE ≈ 14.49 kg), indicating large average error relative to typical adult weights.
