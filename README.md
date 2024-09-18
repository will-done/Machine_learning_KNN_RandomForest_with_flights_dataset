# Machine Learning Project: Flight Data Analysis

This repository contains a machine learning project focused on the analysis of flight data, employing both supervised and unsupervised learning methods.

*Project Overview*
This project analyzes flight data from the Kaggle dataset using two key machine learning techniques:

Supervised Learning: A Random Forest Regressor model is trained to predict flight delays.
Unsupervised Learning: A KMeans Clustering algorithm is applied to identify patterns and group similar flights.
The main goal is to perform a detailed exploratory analysis of the dataset, build predictive models, and evaluate their performance.

*Key Features*
* Data Analysis (EDA): Perform exploratory data analysis to understand the structure and characteristics of the dataset.
* Data Preprocessing: Handle missing values, encode categorical variables, and scale numerical data.
* Model Building: Select and train both supervised and unsupervised models.
* Hyperparameter Tuning: Optimize model performance using techniques like GridSearchCV.
* Model Evaluation: Evaluate the models using metrics like classification reports, confusion matrices, and visualizations.

*Algorithms Used*
* Supervised Learning: Random Forest Regressor
* Unsupervised Learning: KMeans Clustering
* Additional Techniques: Principal Component Analysis (PCA) for dimensionality reduction

*Steps Involved*
1. Exploratory Data Analysis (EDA): Understand key statistics and visual trends in the data.
2. Data Preprocessing: Prepare the dataset by handling missing values and performing necessary transformations.
3. Model Selection: Choose appropriate models for both supervised and unsupervised learning tasks.
4. Model Training & Hyperparameter Tuning: Train the models and fine-tune their performance.
5. Model Evaluation: Assess the models' performance using various evaluation metrics and interpret the results.

*Dataset*
The dataset used for this project comes from [Kaggle's Flights Dataset](https://www.kaggle.com/datasets/mahoora00135/flights). It contains data related to flight schedules, delays, and various flight attributes.

**Results**
The models have been trained and evaluated on the flight dataset, with the Random Forest Regressor showing promising results for delay prediction. KMeans clustering successfully identified distinct clusters within the data.

*Future Work*
* Enhance the models by adding more features.
* Experiment with additional algorithms like Gradient Boosting or Neural Networks.
* Perform further optimization on hyperparameters to improve performance.
