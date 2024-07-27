# Car Price Prediction Using Machine Learning

This project aims to predict car prices in the US market using machine learning techniques. A car manufacturing company in China plans to enter the US market and compete with existing companies. To achieve this, they need to understand the factors influencing car prices in the US, as these might differ from the factors in China.

## Objectives

The project has the following objectives:
1. To identify significant variables for car price prediction.
2. To understand how well these variables describe the price of a car.
3. To build a predictive model that accurately predicts car prices in the US.

## Steps

### Step 1: Reading and Understanding the Data

First, we need to import the necessary libraries for data analysis, visualization, and machine learning:

- **Data Analysis and Visualization**: Numpy, Pandas, Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn

```python
# Importing necessary libraries
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error
