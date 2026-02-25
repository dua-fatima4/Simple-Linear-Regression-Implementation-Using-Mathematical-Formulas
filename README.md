📈 Simple Linear Regression from Scratch

📌 Project Overview

This project implements Simple Linear Regression from scratch using Python without relying on sklearn's built-in LinearRegression model.

The model predicts student placement Package based on CGPA using mathematical formula derivation.

📁 Dataset

Dataset: placements.csv

Features:

CGPA (Independent Variable)

Target:

Package (Dependent Variable)

The dataset contains student academic performance and corresponding placement packages.

🧠 Algorithm Implementation

The model is implemented manually using the mathematical formulas:

Slope (m):

m = Σ[(xi − x̄)(yi − ȳ)] / Σ[(xi − x̄)²]

Intercept (b):

b = ȳ − m(x̄)

Prediction equation:

y = mx + b

The model calculates slope and intercept using loops and basic NumPy operations.

⚙️ Technologies Used

Python

NumPy

Pandas

Matplotlib

Scikit-learn (only for train-test split)

📊 Visualization

The regression line is plotted against training data using Matplotlib.

Scatter Plot → Actual data points

Red Line → Regression line (Predicted values)

The graph demonstrates a positive linear relationship between CGPA and Package.

📈 Results

Model Parameters:

Slope (m): 0.5579

Intercept (b): -0.8961

The model successfully captures the positive relationship between CGPA and placement package.

Higher CGPA generally leads to higher placement package.
