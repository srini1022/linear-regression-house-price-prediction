# Task 3 --- Linear Regression: House Price Prediction

## 📌 Overview

This project implements **Simple Linear Regression** and **Multiple
Linear Regression** to predict house prices using the `Housing.csv`
dataset.

The project was completed as part of the Linear Regression task and
follows the required workflow of data understanding, preprocessing,
exploratory analysis, feature preparation, model training, evaluation,
and visualization.

## 🎯 Objective

-   Understand Simple Linear Regression
-   Understand Multiple Linear Regression
-   Prepare numerical and categorical features
-   Encode categorical variables using Scikit-learn
-   Train regression models
-   Evaluate models using MAE, MSE, and R²
-   Visualize regression results
-   Interpret regression coefficients

## 📂 Project Structure

``` text
linear-regression-house-price-prediction/
│
├── Task_3_Linear_Regression.ipynb
├── Data/
│   └── Housing.csv
└── README.md
```

## 🛠️ Technologies Used

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Scikit-learn
-   Jupyter Notebook

## 📊 Dataset

The project uses a house-price dataset containing numerical and
categorical features such as:

-   Area
-   Bedrooms
-   Bathrooms
-   Stories
-   Parking
-   Main road
-   Guest room
-   Basement
-   Hot water heating
-   Air conditioning
-   Preferred area
-   Furnishing status

**Target variable:** `price`

## 🔄 Project Workflow

1.  Dataset Understanding and Inspection
2.  Data Cleaning and Preprocessing
3.  Exploratory Data Analysis
4.  Bivariate Analysis
5.  Correlation Analysis
6.  Feature Preparation
7.  Train-Test Split
8.  Simple Linear Regression
9.  Simple Linear Regression Evaluation
10. Multiple Linear Regression
11. Multiple Linear Regression Evaluation

## 🤖 Models Implemented

### Simple Linear Regression

`area` is used as the single predictor to estimate house price.

### Multiple Linear Regression

Multiple numerical and encoded categorical features are used together to
predict house price.

Categorical variables are encoded using Scikit-learn's `OneHotEncoder`
with:

-   `drop="first"`
-   `handle_unknown="ignore"`

The encoder is fitted only on the training data to avoid data leakage.

## 📈 Evaluation Metrics

The models are evaluated using:

-   **MAE (Mean Absolute Error)** --- average absolute prediction error.
-   **MSE (Mean Squared Error)** --- average squared prediction error.
-   **R² (R-squared)** --- proportion of variation in the target
    explained by the model.

The performance of Simple and Multiple Linear Regression is compared
using these metrics.

## 📉 Visualizations

The notebook includes:

-   Numerical feature distributions
-   Boxplots
-   Categorical feature distributions
-   Feature vs. price analysis
-   Correlation heatmap
-   Simple Linear Regression line
-   Actual vs. Predicted prices for Multiple Linear Regression

## 🚀 How to Run

### 1. Clone the repository

``` bash
git clone <your-github-repository-url>
cd linear-regression-house-price-prediction
```

### 2. Install dependencies

``` bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

### 3. Start Jupyter Notebook

``` bash
jupyter notebook
```

Open:

``` text
Task_3_Linear_Regression.ipynb
```

## 👤 Author

**Srinidhi M D**

B.Tech --- Computer Science and Engineering

## 📄 License

This project is created for educational and internship task submission
purposes.
