# E-commerce Analysis Research Based on Linear Regression

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.7%2B-blue" alt="Python">
  <img src="https://img.shields.io/badge/Scikit--learn-Linear%20Regression-orange" alt="Scikit-learn">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
</p>

A comprehensive machine learning project that analyzes e-commerce customer behavior and builds predictive models to forecast yearly spending based on customer engagement metrics.

## 📊 Project Overview

This project implements multiple linear regression models to predict customer yearly spending based on various behavioral metrics. The analysis includes exploratory data analysis, model training, and evaluation of different regularization techniques.

## 🎯 Business Problem

E-commerce companies need to understand which customer behaviors most significantly impact revenue. By predicting yearly spending based on engagement metrics, businesses can optimize their platform and marketing strategies to maximize customer value.

## 📁 Dataset

The dataset contains information about 500 e-commerce customers with the following features:

- **Customer Information**:
  - `Email`: Customer email address
  - `Address`: Customer physical address
  - `Avatar`: Customer avatar/theme

- **Behavioral Metrics**:
  - `Avg. Session Length`: Average session duration (minutes)
  - `Time on App`: Time spent on mobile app (minutes)
  - `Time on Website`: Time spent on website (minutes)
  - `Length of Membership`: Customer membership duration (years)

- **Target Variable**:
  - `Yearly Amount Spent`: Total yearly spending ($)

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.7+
- Jupyter Notebook


### Required Libraries

```bash
# Core Data Science Libraries
      pandas numpy matplotlib seaborn

# Machine Learning
      scikit-learn scipy

# Jupyter Environment
      jupyter ipykernel

# Optional for advanced analysis
      statsmodels plotly
