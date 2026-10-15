# Advanced Machine Learning (AML)

A collection of Jupyter notebooks working through core topics in machine learning and statistics, from the maths behind least squares to model evaluation. Notebooks are numbered by date in their file names, so they read in the order they were written.

## Contents

| # | Notebook | Topic |
|---|----------|-------|
| 1 | `AML_Least_Squares_Slope_Intercept_2026-07-09.ipynb` | Deriving and computing the slope and intercept of a best-fit line using least squares |
| 2 | `AML_Python_Basics_and_Linear_Regression_2026-07-30.ipynb` | Python fundamentals and a first look at linear regression |
| 3 | `AML_Simple_Linear_Regression_sklearn_2026-08-06.ipynb` | Simple linear regression with scikit-learn |
| 4 | `AML_Linear_Regression_Gradient_Descent_2026-08-20.ipynb` | Linear regression trained with gradient descent |
| 5 | `AML_Logistic_Regression_Gradient_Descent_2026-08-20.ipynb` | Logistic regression trained with gradient descent |
| 6 | `AML_Logistic_Regression_Empty_Stub_2026-08-20.ipynb` | Empty logistic regression template (stub) to fill in |
| 7 | `AML_ANOVA_OneWay_TwoWay_2026-09-10.ipynb` | One-way and two-way ANOVA |
| 8 | `AML_Feature_Selection_InfoGain_GainRatio_ChiSquare_2026-09-17.ipynb` | Feature selection using Information Gain, Gain Ratio and Chi-Square |
| 9 | `AML_Model_Evaluation_ROC_PR_Learning_Curve_2026-10-01.ipynb` | Model evaluation with ROC curves, Precision-Recall curves and learning curves |

## Topics Covered

- **Regression:** least squares, simple linear regression, gradient descent optimisation
- **Classification:** logistic regression with gradient descent
- **Statistics:** one-way and two-way ANOVA
- **Feature selection:** Information Gain, Gain Ratio, Chi-Square
- **Model evaluation:** ROC, Precision-Recall, learning curves

## Getting Started

### Prerequisites

- Python 3.9 or newer
- Jupyter Notebook or JupyterLab

### Installation

```bash
git clone https://github.com/siddharth9508kumar/ADVANCED-MACHINE-LEARNING.git
cd ADVANCED-MACHINE-LEARNING
pip install numpy pandas matplotlib scikit-learn scipy statsmodels jupyter
```

Libraries listed above are the usual toolkit for these topics; install any others a notebook asks for.

### Running

```bash
jupyter notebook
```

Open any `.ipynb` file and run the cells from top to bottom.

## Repository Structure

```
ADVANCED-MACHINE-LEARNING/
├── AML_Least_Squares_Slope_Intercept_2026-07-09.ipynb
├── AML_Python_Basics_and_Linear_Regression_2026-07-30.ipynb
├── AML_Simple_Linear_Regression_sklearn_2026-08-06.ipynb
├── AML_Linear_Regression_Gradient_Descent_2026-08-20.ipynb
├── AML_Logistic_Regression_Gradient_Descent_2026-08-20.ipynb
├── AML_Logistic_Regression_Empty_Stub_2026-08-20.ipynb
├── AML_ANOVA_OneWay_TwoWay_2026-09-10.ipynb
├── AML_Feature_Selection_InfoGain_GainRatio_ChiSquare_2026-09-17.ipynb
└── AML_Model_Evaluation_ROC_PR_Learning_Curve_2026-10-01.ipynb
```

## Suggested Learning Path

1. Start with least squares and Python basics to build intuition for fitting a line.
2. Move to scikit-learn and gradient descent to see the same idea done with libraries and from scratch.
3. Extend to logistic regression for classification.
4. Use ANOVA and feature selection to understand which variables matter.
5. Finish with model evaluation to judge how well a model actually performs.

## Author

**Siddharth Kumar** — [@siddharth9508kumar](https://github.com/siddharth9508kumar)
