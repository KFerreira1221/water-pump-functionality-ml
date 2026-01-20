# water-pump-functionality-ml
# Predicting Water Pump Functionality in Tanzania

This project builds a machine learning model to predict the operational
status of water pumps in Tanzania using real-world infrastructure data.

The task is a multiclass classification problem with three outcomes:
functional, functional but needs repair, and non-functional.

## Problem Motivation
Access to clean water is critical for public health and economic stability.
Predicting pump failures can help governments and NGOs prioritize inspections
and maintenance efforts.

## Dataset
- Source: Tanzania Ministry of Water (via Kaggle)
- ~59,000 water pumps
- Mix of numeric and high-cardinality categorical features
- Real-world missing and noisy data

## Approach
- Exploratory Data Analysis (EDA)
- Feature engineering and data cleaning
- Model comparison:
  - Logistic Regression (baseline)
  - Random Forest
  - Gradient Boosting
- Evaluation using accuracy and class-level metrics

## Results
- Tree-based models outperform linear models
- Improved identification of non-functional pumps
- Final model achieves approximately XX% accuracy

## Tools
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## Notes
This project demonstrates an end-to-end machine learning workflow on
real-world data and is intended as a decision-support tool.
