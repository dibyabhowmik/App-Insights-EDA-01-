Project Overview:
This project analyzes Google Play Store app data to understand app popularity, ratings, user engagement, app characteristics, pricing, and update patterns. The analysis was used to identify trends that can help understand what contributes to app adoption and user engagement.

Objectives:
Understand the overall app market and category distribution.
Analyze ratings, reviews, and installs.
Compare free and paid apps.
Study the relationship between app size, price, ratings, and installs.
Identify highly installed and highly reviewed apps.
Analyze app update patterns over time.

Tools Used:
Python
Pandas & NumPy
Matplotlib & Seaborn
Kaggle Code
Kaggle Dataset

Process:
The dataset was first checked for missing values, duplicates, incorrect data types, and inconsistent formats. Reviews, installs, prices, app sizes, and dates were converted into usable formats. Duplicate records were removed and missing ratings were kept as missing instead of assigning artificial values.

After cleaning, I performed descriptive analysis, correlation analysis, grouping, binning, and visualizations to study ratings, installs, reviews, categories, genres, pricing, app size, and update activity. Since the dataset does not contain actual review text, rating-based analysis was used instead of true sentiment analysis.

Key Insights:
Free apps make up the majority of the Play Store dataset.
The average app rating is around 4.19, showing generally positive ratings.
Everyone is the most common content-rating category.
Apps such as Subway Surfers, Hangouts, Google Photos, Google News, and Google Drive have very high install numbers.
Higher installs do not automatically mean higher ratings.
App size does not show a simple relationship with popularity.
Paid apps are much less common than free apps, and higher prices do not clearly result in better ratings.
App updates are heavily concentrated around 2018 in this dataset.
Overall, app success depends on multiple factors such as user satisfaction, category, popularity, product characteristics, and market demand.
