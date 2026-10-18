 # # Multiple Linear Regression Analysis of Medical Insurance Costs

##  Project Overview

This project applies **Multiple Linear Regression (MLR)** to analyze and predict individual medical insurance charges based on demographic and lifestyle-related factors.

Using Python, the project explores how variables such as age, body mass index (BMI), number of children, smoking status, and sex relate to medical insurance costs. Statistical analysis and data visualization are used to understand the dataset and evaluate the regression model.

##  Project Objectives

- Analyze the medical insurance dataset using descriptive statistics.
- Explore the relationship between personal characteristics and insurance charges.
- Perform data preprocessing and categorical variable encoding.
- Build a Multiple Linear Regression model using Ordinary Least Squares (OLS).
- Evaluate the model using statistical measures and diagnostic tests.
- Identify factors associated with differences in medical insurance costs.
- Predict estimated insurance charges for a sample individual.

##  Dataset

- **Dataset:** Medical Cost Personal Dataset
- **Source:** [Kaggle – Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- **File required:** `insurance.csv`

### Variables Used

| Variable | Description |
|---|---|
| `age` | Age of the individual |
| `bmi` | Body Mass Index |
| `children` | Number of children or dependants |
| `smoker` | Smoking status |
| `sex` | Sex of the individual |
| `charges` | Individual medical insurance charges in USD |

The `charges` variable is the dependent variable, while age, BMI, children, smoking status, and sex are used as independent variables. Categorical variables are encoded into numerical values for regression analysis.

##  Technologies Used

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Statsmodels** – Regression modelling and statistical analysis
- **SciPy** – Statistical tests
- **Jupyter Notebook** – Development environment

##  Project Workflow

1. **Data Loading and Inspection** — Load the dataset and inspect its structure, data types, and missing values.
2. **Data Preprocessing** — Encode categorical variables and select the predictors and target variable.
3. **Descriptive Statistics** — Examine the distribution and summary statistics of the variables.
4. **Exploratory Data Analysis (EDA)** — Use histograms, scatter plots, boxplots, and correlation analysis to explore the data.
5. **Regression Modelling** — Build a Multiple Linear Regression model using Ordinary Least Squares (OLS).
6. **Model Evaluation** — Evaluate the model using R-squared, adjusted R-squared, the F-statistic, p-values, AIC, BIC, and RMSE.
7. **Diagnostic Analysis** — Examine residual plots, a Q-Q plot, and Variance Inflation Factor (VIF) to assess model assumptions and multicollinearity.
8. **Sample Prediction** — Estimate medical insurance charges for an example individual using the fitted model.

## 📈 Key Analysis

This project includes:

- Correlation analysis between predictors and medical insurance charges.
- Statistical significance testing for individual regression coefficients.
- Analysis of the overall regression model using an F-test and ANOVA.
- Residual diagnostics to examine model fit and potential assumption violations.
- Multicollinearity assessment using VIF.
- A sample prediction of medical insurance charges.

The actual statistical findings and model performance can be obtained by running the notebook.


