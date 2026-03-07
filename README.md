# Customer Behavior Analysis and Purchase Prediction using Machine Learning

# Project Overview

This project analyzes customer behavior in an e-commerce platform and predicts whether a user is likely to make a purchase based on their browsing and interaction data.

Understanding customer behavior helps businesses:
- Improve product recommendations
- Optimize marketing strategies
- Increase conversion rates
- Enhance customer experience

This project applies machine learning models to analyze user activity and predict purchase behavior using an E-commerce event dataset.

# Dataset

The dataset used in this project contains user interaction events from an e-commerce platform.

Each row represents a customer interaction event.

# Dataset Columns
Column	                        Description
event_time	                   Timestamp of the event
event_type	                   Type of event (view, cart, purchase)
product_id	                   Unique product identifier
category_id	                   Product category ID
category_code	                 Category hierarchy
brand	                         Product brand
price	                         Product price
user_id	                       Unique user identifier
user_session	                 Session ID

The dataset contains millions of interaction records, representing real-world customer behavior patterns.

# Project Objectives
The main objectives of this project are:
1) Analyze customer interaction patterns in e-commerce data
2) Perform exploratory data analysis (EDA)
3) Engineer meaningful features from behavioral data
4) Apply dimensionality reduction techniques
5) Train multiple machine learning models
6) Compare model performance
7) Predict purchase likelihood

# Project Workflow
The project follows a structured machine learning pipeline.

# 1) Data Collection

Load and inspect the e-commerce dataset.

# 2) Data Cleaning

- Handle missing values
- Remove irrelevant features
- Format timestamps
- Convert categorical variables

# 3) Exploratory Data Analysis (EDA)
Analyze patterns such as:
- Most viewed products
- Purchase behavior
- Price distribution
- Event type frequency
- User activity

Visualization libraries used:
- Matplotlib
- Seaborn

# 4) Feature Engineering

New features are created such as:
- User activity count
- Average price viewed
- Session interaction count
- Event type encoding

These features help the model better understand customer behavior.

# 5) Dimensionality Reduction

High-dimensional data is reduced using techniques like:
- PCA (Principal Component Analysis)

This improves model efficiency and reduces noise.

# 6) Machine Learning Models

Multiple classification algorithms are used:
- Logistic Regression
- Random Forest
- Decision Tree
- Support Vector Machine (SVM)
- K-Nearest Neighbors

These models predict whether a user interaction will lead to a purchase.

# 7) Model Evaluation

Models are evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

Performance comparison helps identify the best model.

# Technologies Used

- Programming Language

- Python

- Libraries

- Pandas

- NumPy

- Matplotlib

- Seaborn

- Scikit-learn

# Tools

- Jupyter Notebook

- Git

- GitHub

# Project Structure

Customer-Behavior-Analysis/
│
├── data/
│   └── ecommerce_dataset.csv
│
├── notebooks/
│   └── customer_behavior_analysis.ipynb
│
├── models/
│   └── trained_models.pkl
│
├── results/
│   └── model_performance.png
│
├── README.md
├── requirements.txt
└── .gitignore

# Results

The models were trained and compared based on multiple evaluation metrics.

Key insights:

- User behavior patterns strongly influence purchase probability

- Certain product categories show higher conversion rates

- Machine learning models can effectively predict purchasing behavior

# Future Improvements

Possible improvements for this project include:
- Using deep learning models
- Building a recommendation system
- Real-time purchase prediction
- Deploying the model using a web application
- Using larger datasets

# How to Run the Project

- Clone the repository

git clone https://github.com/Dhruvijhanjhri/Customer-Behavior-Analysis-and-Purchase-Prediction-using-Machine-Learning.git

- Navigate to the project folder

cd Customer-Behavior-Analysis-and-Purchase-Prediction-using-Machine-Learning

- Install dependencies

pip install -r requirements.txt

- Run the notebook

jupyter notebook

# Author
Dhruv Jhanjhri

# License
This project is for educational and research purposes.
