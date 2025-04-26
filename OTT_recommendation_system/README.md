# OTT Recommendation System 🎬📈

A machine learning project to build a personalized recommendation system for OTT platforms. This project helps users discover content based on genres, duration, release date, and viewer ratings.

## 📌 Project Overview
With the growth of OTT platforms, personalized recommendations are vital for user retention. This system analyzes metadata to predict ratings and recommend similar content using collaborative filtering and regression techniques.

![image](https://github.com/user-attachments/assets/a38f607b-a547-46d7-af9b-94b7df5f2c8c)

## 📊 Dataset
- **Source**: [Kaggle - OTT Recommendation Dataset](https://www.kaggle.com/datasets/ossingh6/ott-recommendation-sonyrise)
- **Records**: ~48,645 entries
- **Features**: Genre, Duration, Release Date, Language, Ratings, etc.

## 🔧 Tech Stack
- Python 🐍
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Surprise Library (for SVD)

## ⚙️ Key Components
- Data Cleaning: Handled missing values and duplicates
- Exploratory Data Analysis: Histograms, box plots, scatter plots, and correlation heatmaps
- Feature Engineering: Encoding categorical features, handling outliers
- Algorithms Implemented:
  - Linear Regression (predict ratings)
  - SVD (collaborative filtering for recommendations)
  - PCA (dimensionality reduction)
- Evaluation Metrics: RMSE, R² Score
- Visualizations: Rating distributions, content trends, recommendation outputs

## 📈 Sample Visuals
- Histogram of duration and ratings
- Scatter plot of rating vs duration
- SVD-based top-N recommendations

## ✅ Final Outcome
A content-based + collaborative filtering recommendation system that improves user engagement by suggesting relevant shows/movies.

## 📁 Project Structure
