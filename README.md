# Regression
## Objective
This project applies regression techniques to the California Housing dataset to predict median house prices. The goal is to compare multiple regression models and evaluate their performance.

## Dataset
- The dataset is obtained using `fetch_california_housing` from `sklearn.datasets`.
- It contains various features describing houses in California and their median prices.

## Implementation Steps
1. **Loading and Preprocessing**
   - Load dataset into a Pandas DataFrame.
   - Check and handle missing values (if any).
   - Perform feature scaling using `StandardScaler`.
   
2. **Regression Models**
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
   - Gradient Boosting Regressor
   - Support Vector Regressor (SVR)

3. **Model Evaluation**
   - Metrics used:
     - Mean Squared Error (MSE)
     - Mean Absolute Error (MAE)
     - R² Score
   - Compare performance and determine the best and worst models.

## Results
The performance of each model is evaluated, and the best and worst models are identified based on R² Score.

## Repository Structure
- `regression.ipynb` - Jupyter Notebook containing the implementation.
-. `README.md` - This file describing the project.


## Dependencies
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

