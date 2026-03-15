# Customer Behavior Analysis and Purchase Prediction using Machine Learning

## Project Overview

This project focuses on analyzing customer behavior on an e-commerce platform and building machine learning models to predict whether a user will make a purchase.

The dataset contains customer interaction events such as product views, cart additions, and purchases. By performing exploratory data analysis, feature engineering, and machine learning modeling, the project identifies patterns in customer activity and predicts purchasing behavior.

This project demonstrates the complete machine learning workflow including data preprocessing, exploratory analysis, dimensionality reduction, supervised learning, and clustering for customer segmentation.

---

## Problem Statement

E-commerce platforms generate large amounts of user interaction data. Understanding this behavior is essential for improving product recommendations, marketing strategies, and sales performance.

The objective of this project is to:

* Analyze customer interaction patterns
* Understand user shopping behavior
* Build machine learning models to predict whether a customer will make a purchase
* Segment customers using clustering techniques

---

## Dataset Description

The dataset represents user interaction with products on an e-commerce platform.

Each row corresponds to a user activity event.

| Column        | Description                           |
| ------------- | ------------------------------------- |
| event_time    | Timestamp of user interaction         |
| event_type    | Type of action (view, cart, purchase) |
| product_id    | Unique product identifier             |
| category_id   | Product category identifier           |
| category_code | Category name                         |
| brand         | Product brand                         |
| price         | Product price                         |
| user_id       | Unique user identifier                |
| user_session  | User browsing session ID              |

---

## Tools and Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* Git & GitHub

---

## Project Workflow

### 1. Data Understanding

* Loaded and explored the dataset
* Analyzed dataset size, structure, and data types
* Identified missing values and unique entities

### 2. Data Preprocessing

* Converted timestamp columns to datetime
* Handled missing values
* Removed duplicates
* Cleaned categorical variables
* Prepared dataset for analysis

### 3. Exploratory Data Analysis (EDA)

* Analyzed distribution of user actions
* Studied price distribution
* Identified popular products and categories
* Examined user activity patterns
* Visualized insights using various charts

### 4. Dimensionality Reduction

* Applied Principal Component Analysis (PCA)
* Reduced feature dimensionality
* Visualized patterns in customer behavior

### 5. Supervised Learning (Purchase Prediction)

Implemented multiple machine learning models to predict purchase behavior.

Models used:

* Logistic Regression
* Support Vector Machine (SVM)
* Random Forest Classifier

Evaluation metrics:

* Accuracy
* Confusion Matrix
* Model comparison

### 6. Clustering (Customer Segmentation)

* Applied K-Means clustering
* Grouped customers based on behavior patterns
* Identified different customer segments

---

## Results

The machine learning models were evaluated based on their prediction accuracy.

Ensemble models such as Random Forest performed well in predicting customer purchases.

The clustering analysis also helped identify different user groups such as:

* Frequent viewers
* Active buyers
* Casual browsers

---

## Project Structure

```
Customer-Behavior-Analysis-and-Purchase-Prediction

data
    ecommerce_data.csv

notebooks
    data_understanding.ipynb
    data_preprocessing.ipynb
    eda.ipynb
    dimensionality_reduction.ipynb
    supervised_learning.ipynb
    clustering.ipynb

images
    event_type_distribution.png
    price_distribution.png
    confusion_matrix.png

models
    purchase_prediction_model.pkl

results
    model_results.csv

requirements.txt
README.md
```

---

## How to Run the Project

1. Clone the repository

```
git clone https://github.com/Dhruvijhanjhri/Customer-Behavior-Analysis-and-Purchase-Prediction-using-Machine-Learning.git
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Open Jupyter Notebook

```
jupyter notebook
```

4. Run notebooks in sequence from data understanding to clustering.

---

## Future Improvements

* Deploy the model using Streamlit or Flask
* Integrate real-time customer data
* Apply deep learning models for prediction
* Build a recommendation system for products


