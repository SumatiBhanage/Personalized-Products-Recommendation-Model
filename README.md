# Personalized-Products-Recommendation-Model

## Description
  This project builds a smart recommendation system for an e-commerce website. It uses data from user actions like what they view, add to their cart, and purchase to suggest products they might like.
  By analyzing user interactions, we create an interaction matrix and use a method called Alternating Least Squares (ALS)  which is an approach to Collaborative Filtering to recommend products that each user is most likely to be interested in, that is Personalized Product Suggestions. 

## Objective
The objectives of the project work are as -
- To Enhance User Experience.
- To Increase Sales and Revenue.
- To Improve Customer Retention and Loyalty.
- To understand User Preferences and Trends.

## Architecture
![Architecture](Architecture.png)

## Methodology:
1. Raw Data:
o The process begins with raw, unprocessed data. This could be anything from user interactions on a website (clicks, purchases, ratings) to sensor data from IoT devices.

3. Transformation & Actions (Using PySpark):
o The raw data undergoes transformation using PySpark, a powerful tool for large-scale data processing.
o This step involves cleaning, aggregating, and structuring the data to make it suitable for analysis.

5. Exploratory Data Analysis (EDA):
o The upper path in the workflow leads to EDA. Here, data scientists explore the cleaned data to uncover patterns, correlations, and potential insights.
o Techniques like data visualization, statistical summaries, and feature engineering are used.

7. Clean & Modified Data:
o The cleaned and modified data (resulting from EDA) moves forward. It’s now in a more usable format for subsequent steps.

9. Recommendation (Alternating Least Squares - ALS):
o The lower path focuses on recommendation. ALS is an algorithm commonly used for collaborative filtering in recommendation systems.
o ALS predicts missing entries in a user-item interaction matrix, enabling personalized recommendations.

6. MySQL Database:
o The processed data is stored in a MySQL database. This step ensures persistence and efficient retrieval for future use.

8. Visualization (Using Tableau):
o Finally, the workflow culminates in visualization. Tableau, a popular data visualization tool, is employed to create interactive dashboards.
o These dashboards allow users to explore insights, trends, and recommendations visually.

This workflow takes raw data, transforms it, analyzes it, generates recommendations, stores it in a database, and presents visual insights.

## Cleaning & Transformation 

![Raw Data](Visualization/OriginalData.png)
![Cleaning](Visualization/CleaningData.png)
![Process & Transformation](Visualization/ProcessedData.png)

