# -Deep-Learning-DeepCSAT-E-Commerce-Customer-Satisfaction-Score-Prediction
# 🛍️ E-Commerce Customer Satisfaction Prediction

This machine learning project focuses on analyzing e-commerce customer data and predicting different levels of customer satisfaction using transactional and behavioral information.

## 🎯 Project Objective

The primary goal of this project is to develop a multi-class classification system capable of identifying customer satisfaction categories and evaluating how effectively different machine learning algorithms perform on the dataset.

## 🧰 Technologies & Libraries

* **Python** – Programming language
* **Pandas & NumPy** – Data cleaning, manipulation, and numerical analysis
* **Scikit-learn** – Model development and evaluation
* **Matplotlib & Seaborn** – Data visualization and graphical analysis
* **Google Colab** – Development and experimentation environment

## 🧠 Machine Learning Algorithms

Two classification algorithms were implemented and compared:

* **Logistic Regression** with balanced class weights
* **Random Forest Classifier** with balanced class weights

Model performance was assessed using a **Classification Report** and **Confusion Matrix**.

## 📈 Project Highlights

* Developed an end-to-end machine learning workflow covering data preprocessing, model building, prediction, and evaluation.
* Addressed class imbalance by applying `class_weight='balanced'` during model training.
* Compared Logistic Regression and Random Forest approaches for multi-class prediction.
* Used a confusion matrix to analyze correct and incorrect predictions for each satisfaction category.
* The Random Forest model achieved better results by learning complex relationships within the customer data.

## 📊 Key Learning & Insight

The project demonstrated how machine learning can be applied to understand and predict customer satisfaction in an e-commerce environment. Using balanced class weights helped improve model performance across less-represented categories. Among the tested approaches, Random Forest provided stronger predictive capabilities by effectively capturing non-linear patterns and interactions within the dataset.
