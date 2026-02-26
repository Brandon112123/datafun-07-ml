# datafun-07-ml

Author: Brandon Deshaun Smith  
Northwest Missouri State University  
Master of Science in Data Analytics  
Year: 2026  

---

## Project Overview

This project introduces core machine learning concepts through the application of simple linear regression. The objective is to analyze historical temperature data and forecast future trends using both statistical and machine learning approaches.

The dataset used in this project contains New York City’s average January high temperatures from 1895 to 2018.

The project is divided into four major parts:

1. **Part 1 – Chart a Straight Line**  
   Demonstrates a basic linear relationship using the Fahrenheit-to-Celsius conversion formula.

2. **Part 2 – Predict Using SciPy**  
   Applies simple linear regression using SciPy’s `linregress()` function to calculate slope and intercept and generate predictions.

3. **Part 3 – Predict Using scikit-learn**  
   Reimplements linear regression using scikit-learn’s `LinearRegression` estimator, including:
   - Train/test split
   - Model fitting
   - Prediction
   - Visualization

4. **Part 4 – Insights and Comparison**  
   Compares statistical and machine learning implementations and reflects on model structure and workflow.

---

## Dataset

The dataset contains:
- `Date` (Year)
- `Temperature` (Average January high temperature in Fahrenheit)
- `Anomaly` (Deviation from long-term average)

Source: NOAA Climate at a Glance

---

## Tools & Technologies

- Python
- JupyterLab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- SciPy
- scikit-learn
- PyArrow

---

## Key Concepts Demonstrated

- Time Series Data
- Simple Linear Regression
- Ordinary Least Squares (OLS)
- Train/Test Split
- Model Evaluation
- Data Visualization
- Regression Line Interpretation

---

## How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/datafun-07-ml.git
cd datafun-07-ml