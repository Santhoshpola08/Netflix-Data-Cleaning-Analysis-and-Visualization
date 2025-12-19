# Netflix Data: Cleaning, Analysis, and Visualization 📊🎬

## 📌 Project Overview
This project focuses on cleaning, analyzing, visualizing, and preparing Netflix content data for beginner-level machine learning tasks using Python. The dataset contains information about movies and TV shows available on Netflix from 2008 to 2021. The project demonstrates an end-to-end data analytics workflow suitable for beginners in Data Science and Machine Learning.

---

## 🎯 Objectives
- Clean and preprocess the Netflix dataset
- Handle missing values and duplicates
- Perform Exploratory Data Analysis (EDA)
- Visualize content trends and distributions
- Engineer features for machine learning
- Build beginner ML models to classify content type

---

## 🛠 Tools & Technologies
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**
- **Git & GitHub**

---

## 📂 Dataset Description
- **Source:** Netflix dataset (CSV)
- **Time Period:** 2008 – 2021
- **Content Types:** Movies and TV Shows
- **Key Columns:**  
  `type`, `title`, `country`, `rating`, `duration`, `listed_in`, `date_added`

---

## 🧹 Data Cleaning Steps
- Removed duplicate records
- Handled missing values (director, cast, country, rating)
- Converted `date_added` to datetime format
- Extracted numerical duration values
- Normalized genre information

---

## ⚙️ Feature Engineering
- Year Added
- Month Added
- Duration Value (numeric)
- Genre normalization using split and explode

---

## 📊 Exploratory Data Analysis (EDA)
- Movies dominate Netflix content
- TV Shows have grown rapidly in recent years
- Most common ratings: TV-MA and TV-14
- United States is the top content-producing country
- Drama and International genres are most popular

---

## 📈 Visualizations
- Bar charts for content and genre distribution
- Line charts for yearly and monthly trends
- Pie charts for ratings and content types

---

## 🤖 Machine Learning
**Problem:** Predict whether a Netflix title is a *Movie* or *TV Show*

### Models Used:
- Logistic Regression
- Random Forest Classifier

### Key Results:
- Random Forest achieved better accuracy
- Duration is the most important feature
- Year added also influences content type
