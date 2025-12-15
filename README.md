# 📉 Simple Linear Regression: Manual and Scikit-learn Implementation

This project contains a Jupyter Notebook that implements **Simple Linear Regression**, a fundamental statistical and machine learning technique for modeling the relationship between a single independent variable and a continuous dependent variable. The notebook provides two methods of implementation: manual calculation from scratch and efficient implementation using Scikit-learn.

---

## 🎯 Project Goals

The objective is to demonstrate the core mechanics of Simple Linear Regression:

1.  **Data Creation & Visualization:** Define a small, synthetic dataset and visualize the linear relationship using a scatter plot.
2.  **Manual Calculation:** Calculate the regression line parameters (slope $m$ and y-intercept $b$) using the ordinary least squares (OLS) formulas from scratch.
3.  **Scikit-learn Implementation:** Apply the `LinearRegression` class from Scikit-learn to the same data.
4.  **Prediction:** Use both the manual and Scikit-learn models to make predictions and verify results.

## 🗃️ Dataset Used

The notebook uses a small, **synthetic Pandas DataFrame** created within the script. The features include:
* **`cgpa`:** The independent variable (X).
* **`pkg`:** The dependent variable (Y), representing an assumed package or salary amount.

## ⚙️ Technology Stack and Dependencies

The project relies on standard Python libraries for data science:

| Library | Role |
| :--- | :--- |
| **`pandas` & `numpy`** | Data structuring, manipulation, and vectorized mathematical operations. |
| **`matplotlib.pyplot`** | Used for visualizing the scatter plot and the fitted regression line. |
| **`scikit-learn`** | Used to implement the `LinearRegression` model for comparison. |

### Installation
```bash
pip install pandas numpy matplotlib scikit-learn

```bash
pip install pandas numpy matplotlib scikit-learn
