# CART Regression: B.Tech Student Academic Performance Prediction

## Student Details
- **Name:** KUNAPULI BALA SRI SARVANI
- **Student ID:** 2300030957

## Project Overview
This assignment implements a Classification and Regression Tree (CART) for predicting B.Tech students' final semester scores using Python.

The project demonstrates how a Decision Tree Regressor identifies the best feature-based splits by minimizing Mean Squared Error (MSE).

## Dataset Description
- **Dataset:** Synthetic B.Tech Student Academic Performance Dataset
- **Number of Records:** 1,500
- **Target Variable:** `Final_Semester_Score`
- **Target Range:** 0–100

### Features
- Attendance Percentage
- Study Hours Per Week
- Assignment Average
- Internal Marks
- Previous Semester GPA
- Sleep Hours
- Coding Hours Per Week
- Project Score

*Note: The dataset is synthetically generated for educational and demonstration purposes.*

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Implementation
1. Dataset generation and exploration
2. Exploratory Data Analysis (EDA)
3. Data preprocessing and feature selection
4. Train-test splitting
5. Manual Parent MSE and best binary split calculation
6. CART Regression using DecisionTreeRegressor
7. Tree visualization
8. Pre-pruning and post-pruning
9. Model evaluation using MAE, RMSE and R²
10. Actual vs. predicted analysis and feature importance

## Model Results

| Model | Test RMSE | Test R² |
|---|---:|---:|
| Mean Baseline | 10.413 | -0.013 |
| Full CART | 7.698 | 0.446 |
| Pre-pruned CART | 6.369 | 0.621 |
| Post-pruned CART | 6.713 | 0.579 |

The pre-pruned CART model achieved the best test performance among the evaluated models.

## How to Run
1. Clone or download this repository.
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open the `.ipynb` notebook using Jupyter Notebook or VS Code.
4. Run all cells sequentially.

## Conclusion
This assignment demonstrates CART Regression, manual split calculations, tree visualization, pruning techniques and model evaluation on a synthetic student academic performance dataset.
