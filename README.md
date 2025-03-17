Zomato Data Analysis and Machine Learning Project

Project Overview

This project aims to analyze Zomato restaurant data to gain insights into customer preferences, restaurant performance, and pricing patterns. It involves data preprocessing, exploratory data analysis (EDA), and building machine learning models for prediction and clustering.

-> Technologies Used:

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-Learn (Linear Regression, K-Means Clustering)


-> Dataset

The dataset used is "Zomato data.csv," which includes information on restaurant ratings, votes, cost for two people, and online ordering options.


->Project Goals

Identify the types of restaurants most favored by the public.

Analyze the cost preferences of couples.

Determine the correlation between votes, cost, and ratings.

Predict restaurant ratings using Linear Regression.

Perform K-Means Clustering to segment restaurants based on cost and votes.


-> Data Preprocessing

Handling missing values by removing rows with null data.

Converting the 'rate' column to numeric values.

Converting 'approx_cost(for two people)' to numeric after removing commas.

Removing outliers using the Interquartile Range (IQR) method.


-> Exploratory Data Analysis (EDA)

Distribution analysis of restaurant cost.

Correlation heatmap to visualize relationships between numerical features.

Count plots and pivot tables to analyze customer preferences.


-> Machine Learning Models

    -> Linear Regression

       Predicting restaurant ratings based on votes and cost.

       Performance Metrics:

            Mean Squared Error

            R-squared Score

    -> K-Means Clustering

      Clustering restaurants into 3 groups based on cost and votes.

      Visualizing the clusters with scatter plots.

    -> Visualizations

        Correlation Heatmap
        
        Distribution Plot for Cost
        
        Count Plots for Online Order and Restaurant Type
        
        Box Plot for Online Orders vs. Ratings
        
        Heatmap for Online Order Preferences by Restaurant Type


-> Results and Insights

Identified the most popular restaurant types.

Analyzed the preferred price range for couples.

Predicted ratings with a reasonable accuracy.

Segmented restaurants into distinct clusters for targeted marketing.
