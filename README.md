# 📱 Google Play Store App Insight Analysis

[![Python](https://img.shields.io/badge/Python-3.10-blue.svg)]()
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)]()
[![Kaggle](https://img.shields.io/badge/Kaggle-Notebook-blue?logo=kaggle)](https://www.kaggle.com/code/aarzukashyap/eda-project-3-app-insight-analysis)

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on Google Play Store application data to identify trends in ratings, installs, reviews, categories, and user engagement.
📌 Project Overview

This project performs an Exploratory Data Analysis (EDA) on the Google Play Store dataset to uncover patterns, trends, and insights that influence app performance in the Android marketplace.

The analysis focuses on understanding how factors such as app category, ratings, reviews, installs, app size, pricing, and content ratings affect user engagement and app success.

Using Python and data visualization techniques, this project transforms raw app store data into actionable business insights that can support app developers, product managers, and business stakeholders in making data-driven decisions.

🎯 Business Objective

The objective of this project is to analyze Google Play Store application data and answer the following business questions:

Which app categories are the most popular?
Which categories generate the highest user engagement?
What factors influence app ratings?
How do installs relate to ratings and reviews?
What are the characteristics of successful applications?
Do free apps perform better than paid apps?
Which app categories present growth opportunities?
📂 Dataset Information
Dataset Source

Google Play Store Dataset

Dataset Features
Feature	Description
App	Application Name
Category	App Category
Rating	User Rating
Reviews	Number of Reviews
Size	Application Size
Installs	Total Installs
Type	Free or Paid
Price	App Price
Content Rating	Target Audience
Genres	App Genre
Last Updated	Last Update Date
Current Version	Current Version
Android Version	Required Android Version
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Kaggle Notebook

Data Cleaning Process

Before analysis, several preprocessing steps were performed:

Missing Value Handling
Identified null values
Removed or imputed missing records
Data Type Conversion

Converted:

Reviews → Integer
Installs → Numeric
Price → Numeric
Rating → Float
Duplicate Removal
Removed duplicate applications
Data Standardization
Cleaned install counts
Removed special characters
Standardized category names
Outlier Treatment
Inspected extreme values
Validated rating distributions

Exploratory Data Analysis
1. App Category Analysis
Objective

Identify categories with the highest number of applications.

Insights
Family apps dominate the Play Store.
Game and Tools categories have strong representation.
Several niche categories have low competition.
Visualization
Category Distribution Bar Chart

2. Rating Analysis
Objective

Understand rating behavior across applications.

Insights
Most apps receive ratings between 4.0 and 4.5.
Highly rated apps are concentrated in specific categories.
Rating distribution is positively skewed.
Visualization
Rating Histogram
Rating Box Plot

3. Install Analysis
Objective

Identify factors influencing app installs.

Insights
Higher review counts generally correspond to higher installs.
Top-performing apps attract significantly more downloads.
Popular categories dominate install volumes.
Visualization
Install Distribution
Category-wise Install Analysis

4. Review Analysis
Objective

Measure user engagement through review activity.

Insights
Reviews are strongly correlated with installs.
Apps with active user engagement tend to maintain higher ratings.
Visualization
Scatter Plot: Reviews vs Installs

5. Free vs Paid App Analysis
Objective

Compare performance of free and paid applications.

Insights
Free apps account for the majority of downloads.
Paid apps generally represent a smaller market segment.
User adoption is significantly higher for free applications.
Visualization
Pie Chart: Free vs Paid Apps
Install Comparison

6. Content Rating Analysis
Objective

Analyze target audience distribution.

Insights
Most apps target the "Everyone" category.
Teen and Mature audiences represent smaller segments.
Content ratings influence category performance.
Visualization
Content Rating Distribution Chart

7. Correlation Analysis
Objective

Identify relationships among key variables.

Variables Examined
Rating
Reviews
Installs
Price
Size
Insights
Reviews and installs show strong positive correlation.
Price shows weak correlation with installs.
Ratings exhibit moderate influence on installs.
Visualization

 Key Findings
Finding 1

Apps with higher review counts generally achieve higher install numbers.

Finding 2

Free applications dominate the marketplace and attract the majority of users.

Finding 3

Family, Games, and Tools categories are among the most competitive and popular segments.

Finding 4

Most successful apps maintain ratings above 4.0.

Finding 5

User engagement metrics such as reviews provide strong indicators of app success.

Finding 6

Category selection significantly impacts app visibility and adoption.

Business Recommendations
For App Developers
Focus on user engagement strategies to increase reviews.
Maintain application quality to sustain ratings above 4.0.
Prioritize user experience and performance optimization.
For Product Managers
Monitor category competition before launching new applications.
Analyze successful competitors within target categories.
Use ratings and review trends to guide product improvements.
For Business Stakeholders
Invest in categories demonstrating strong install growth.
Utilize customer feedback for feature prioritization.
Track engagement metrics alongside download volumes.

Visualizations Included
Category Distribution
Rating Distribution
Install Analysis
Reviews vs Installs Scatter Plot
Free vs Paid Comparison
Content Rating Distribution
Correlation Heatmap

Project Outcome

This project demonstrates how Exploratory Data Analysis can be used to uncover meaningful business insights from app marketplace data.

The analysis helps identify the characteristics of successful applications and provides recommendations that can improve app performance, user satisfaction, and business growth.



Author

Aarzu Bharti

MBA (Business Analytics) | ECBA Certified

Aspiring Data Analyst | Business Analyst

Skills Demonstrated
Exploratory Data Analysis (EDA)
Data Cleaning
Data Visualization
Statistical Analysis
Business Insights Generation
Python Programming
Pandas
NumPy
Matplotlib
Seaborn
Connect With Me
LinkedIn: [Add LinkedIn URL]
GitHub: [Add GitHub URL]
