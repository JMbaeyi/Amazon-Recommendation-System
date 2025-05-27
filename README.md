# 🛒 Amazon Product Recommender System

This project builds a recommendation engine using Amazon product reviews data. It suggests items to users based on their previous interactions and preferences using collaborative filtering techniques.

## 📌 Project Overview

Recommender systems are essential in e-commerce platforms to improve user experience and boost sales. This project focuses on building a user-based and item-based collaborative filtering model to recommend products from Amazon reviews.

## 🔍 Dataset

- **Source**: [Amazon Product Reviews dataset](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews) (or a subset)
- **Contents**: UserID, ProductID, Rating, Review Text
- **Use Case**: Predict products a user is likely to be interested in based on past behavior

## ⚙️ Techniques Used

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Popularity-based Recommendation
- User-based Collaborative Filtering
- Item-based Collaborative Filtering
- Cosine Similarity for nearest neighbors

## 📊 Evaluation Metrics

- Precision@k
- Recall@k
- Root Mean Squared Error (RMSE) for rating predictions
- Sparsity and Coverage

## 🛠 How to Run

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
