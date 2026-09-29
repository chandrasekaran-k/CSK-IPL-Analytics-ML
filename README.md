# 🏏 CSK IPL Analytics & Match Prediction

## 📌 Project Overview

An end-to-end IPL analytics and machine learning project focused on analyzing Chennai Super Kings (CSK) performance across IPL seasons.

The project combines Python-based data analysis, feature engineering, machine learning, and Power BI to identify CSK's performance patterns, strengths, weaknesses, and predict match scores.

## 🎯 Objectives

- Analyze CSK's historical IPL performance
- Identify batting, bowling, and match-winning patterns
- Analyze performance across different match phases
- Identify factors behind CSK's wins and losses
- Build machine learning models for IPL score prediction
- Create an interactive Power BI dashboard

## 🔄 Project Workflow

Raw IPL Data  
↓  
Data Cleaning & Preprocessing  
↓  
Exploratory Data Analysis  
↓  
Feature Engineering  
↓  
Machine Learning  
↓  
Score Prediction  
↓  
Power BI Dashboard  
↓  
Business & Performance Insights

## 🧹 Data Processing

The datasets were cleaned and transformed using Python and Pandas.

Key processing steps included:

- Handling missing and inconsistent data
- Standardizing team and player information
- Creating match-level datasets
- Phase-wise analysis
- Powerplay, middle-over and death-over analysis
- Boundary and dot-ball analysis
- Wicket-based features

## ⚙️ Feature Engineering

Created features including:

- Powerplay runs and wickets
- Score after 10 overs
- Boundary indicators
- Dot-ball indicators
- Wicket indicators
- Match and innings-level statistics
- Phase-wise performance features

## 🤖 Machine Learning

Multiple regression models were developed for IPL score prediction:

- Linear Regression
- Random Forest
- XGBoost

### Model Evaluation

Models were evaluated using:

- MAE
- RMSE
- R² Score

The final score prediction model achieved an MAE of approximately **8.40 runs**.

## 📊 Power BI Dashboard

The Power BI dashboard provides interactive analysis of:

- CSK overall performance
- Season-wise performance
- Batting analysis
- Bowling analysis
- Player performance
- Opponent-wise performance
- Venue-wise performance
- Match outcomes
- Phase-wise performance
- ML-based score prediction

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook
- Power BI
- SQL

## 📁 Project Structure

```text
CSK-IPL-Analytics/
│
├── Clean-data/
├── Data/
├── ML-Models/
├── Notebooks/
├── Power_BI/
├── README.md
└── requirements.txt
