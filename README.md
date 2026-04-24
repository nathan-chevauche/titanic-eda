# Titanic - Exploratory Data Analysis

Exploratory Data Analysis (EDA) on the Titanic dataset using Python.

## Objectives
Explore the Titanic dataset to identify the key factors that influenced passenger survival.

## Stack
- **Pandas** — data cleaning and manipulation
- **Matplotlib / Seaborn** — visualizations
- **Jupyter Notebook** — analysis environment

## Project Structure
```
project/
    titanic.ipynb   # main notebook
    train.csv       # dataset (Kaggle)
    README.md
```

## Key Steps
1. **Data loading & exploration** — shape, types, missing values
2. **Data cleaning** — dropped irrelevant columns, imputed missing values
3. **Feature engineering** — family size, is_alone, age buckets
4. **Visualizations** — 6 charts with conclusions

## Main Findings
- Only **38%** of passengers survived
- **Sex** is the strongest predictor — women survived at 74% vs 19% for men
- **Class** matters — 1st class survived at 63% vs 24% for 3rd class
- Traveling with a **small family** (2-4 people) improved survival odds
- **Fare** and **Pclass** are strongly correlated with survival

## Dataset
[Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data) — Kaggle
