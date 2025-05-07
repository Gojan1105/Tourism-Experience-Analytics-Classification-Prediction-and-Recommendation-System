# Tourism Experience Analytics: Classification, Prediction, and Recommendation System

## NAAN MUDHALVAN  
**Course Name**: Data Analytics in Process Industries  
**1105 - Gojan School of Business and Technology**  
**Project Title**: Tourism Experience Analytics: Classification, Prediction, and Recommendation System.

---

### Submitted By:
- **Kayalvizhi S** - 110523237013
- **Mahalakshmi S** - 110523237014
- **Monika S** - 110523237015
- **Niranjani T** - 110523237016
- **Pavithra B** - 110523237017

---

## Overview
This project aims to enhance tourism experiences by providing personalized recommendations, predicting user satisfaction, and classifying potential user behavior. By leveraging data from user preferences, travel patterns, and attraction features, the system focuses on three primary objectives: regression, classification, and recommendation.

### Skills Acquired
- **Data Cleaning and Preprocessing**
- **Exploratory Data Analysis (EDA)**
- **Data Visualization**
- **SQL**
- **Streamlit**
- **Machine Learning (Regression, Classification, & Recommendation)**

## Problem Statement
Tourism agencies and travel platforms aim to enhance user experiences by leveraging data to provide personalized recommendations, predict user satisfaction, and classify potential user behavior. This project involves analyzing user preferences, travel patterns, and attraction features to achieve three primary objectives: 
- **Regression:** Predicting user ratings for attractions.
- **Classification:** Predicting user visit modes (Business, Family, etc.).
- **Recommendation:** Personalized attraction suggestions based on user history and preferences.

## Business Use Cases
- **Personalized Recommendations:** Suggest attractions based on users' past visits and preferences.
- **Tourism Analytics:** Provide insights into popular attractions and regions.
- **Customer Segmentation:** Classify users based on their travel behavior for targeted promotions.
- **Increasing Customer Retention:** Improve customer loyalty through personalized recommendations.

## Project Objectives

### 1. **Regression:** Predicting Attraction Ratings
- **Aim:** Develop a regression model to predict the rating a user might give to a tourist attraction.
- **Inputs:** User demographics, visit details, attraction attributes.
- **Target:** Predicted rating (1-5 scale).

### 2. **Classification:** User Visit Mode Prediction
- **Aim:** Create a classification model to predict the mode of visit (e.g., business, family, friends) based on user and attraction data.
- **Inputs:** User demographics, attraction characteristics, historical visit data.
- **Target:** Visit mode (Business, Family, Couples, Friends).

### 3. **Recommendation:** Personalized Attraction Suggestions
- **Aim:** Develop a recommendation system to suggest attractions based on user history and preferences.
- **Approach:** 
  - **Collaborative Filtering:** Recommend based on similar user preferences.
  - **Content-Based Filtering:** Suggest attractions based on user interests and visited attractions.

## Dataset
This project uses a Tourism Dataset with the following key components:

1. **Transaction Data**: Information on user visits to attractions, ratings, and visit details.
2. **User Data**: Geographical information of users (continent, country, city).
3. **City Data**: Information about cities where attractions are located.
4. **Attraction Type Data**: Categorization of attractions (beach, museum, park, etc.).
5. **Visit Mode Data**: Information about user visit modes (business, family, etc.).

## Approach

### 1. **Data Cleaning and Preprocessing**
- Handle missing values and outliers.
- Standardize categorical variables and date formats.
- Perform feature engineering (e.g., aggregating user ratings).

### 2. **Exploratory Data Analysis (EDA)**
- Visualize user distribution across continents, countries, and regions.
- Explore attraction types and popularity based on user ratings.
- Analyze correlations between visit modes and demographics.

### 3. **Model Training**
- **Regression Task:** Predict ratings using regression models.
- **Classification Task:** Predict visit modes using classification algorithms (e.g., Random Forest, LightGBM).
- **Recommendation Task:** Use collaborative and content-based filtering techniques.

### 4. **Model Evaluation**
- **Classification Model:** Evaluate using accuracy, precision, recall, F1-score.
- **Regression Model:** Evaluate using R2, MSE.
- **Recommendation System:** Evaluate using metrics like MAP or RMSE.

### 5. **Deployment**
- Build a **Streamlit** application to input user details and provide:
  - Predicted visit mode.
  - Personalized attraction recommendations.
  - Visualizations of popular attractions and regions.

## Project Deliverables
- **Cleaned Dataset:** Final preprocessed dataset for analysis.
- **Source Code:** Python scripts for data cleaning, analysis, model building, and visualization.
- **Streamlit Application:** A web app for classification and recommendation.
- **Documentation:** A report with key findings, insights, and model evaluation.

## How to Run the Project

### Requirements:
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, streamlit, xgboost, lightgbm, etc.

### Installation:
1. Clone this repository:
   ```bash
   git clone https://github.com/SETHU0010/Tourism-Experience-Analytics.git
