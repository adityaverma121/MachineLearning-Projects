# 📊 Machine Learning Mini Projects

This repository contains two machine learning projects:  
1. **Housing Price Prediction** – a regression model to predict house prices.  
2. **Movie Recommendation System** – a collaborative filtering-based recommender.  

---

## 🏠 Housing Price Prediction

Built a regression model to predict house prices based on multiple property features.  

- **Tech Stack**: Python, Pandas, NumPy, Matplotlib, Scikit-learn  
- **Dataset**: "Housing.csv" (included in this repo)  
- **Process**:  
  - Data preprocessing (encoding categorical variables, scaling features)  
  - Exploratory Data Analysis (correlation heatmap, feature impact)  
  - Model training & evaluation  
- **Model Used**: Linear Regression  
- **Results**:  
  - R² Score ≈ 0.64  
  - MAE ≈ 9.25 Lakhs INR  
  - Visualized actual vs predicted house prices  

---

## 🎬 Movie Recommendation System

Implemented a collaborative filtering-based recommender to suggest movies based on user ratings.  

- **Tech Stack**: Python, Pandas, NumPy, Matplotlib, Scikit-learn  
- **Dataset**: "ratings.csv" and "movies.csv" (included in this repo)   
- **Process**:  
  - Data cleaning & preprocessing  
  - Pivot table creation for user-movie ratings  
  - Rating distribution analysis  
  - Similarity calculation using Pearson correlation  
- **Approach**: Found movies similar to a given movie based on user rating patterns  
- **Results**:  
  - Example → Input: *“Braveheart (1995)”*  
  - Output: Top 5 correlated movies returned as recommendations  

---
