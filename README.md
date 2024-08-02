# Mining Mastodon for Silent Users - CS483 Course Project

## Project Overview

This project explores user behavior on Mastodon, with a focus on identifying and understanding silent users across different Mastodon servers. Our team collected and analyzed data from four Mastodon instances, applying data mining techniques to categorize users and uncover behavior patterns.

## Data Collection

We gathered data from the following Mastodon servers:
- mastodon.social
- mstdn.social
- mas.to
- techhub.social

The data collection period spanned from April 2nd to April 5th, 2023. The collected data is stored in these files:
- user_data_1.txt (mastodon.social)
- user_data_2.txt (mstdn.social)
- user_data_3.txt (mas.to)
- user_data_4.txt (techhub.social)

## Methodology

Our approach involved several key steps:

1. Data Collection: Utilized Mastodon.py, a Python wrapper for the Mastodon API
1. Data Preprocessing: Performed cleaning and transformation of the raw data
1. Data Analysis: Developed metrics such as "toot per time" and "engagement ratio"
1. Feature Selection: Reduced dimensions to two principal features
1. Data Mining / Training: Applied CURE and Bisecting K-means clustering algorithms
1. Evaluation: Employed Silhouette and Calinski-Harabasz scores to assess clustering effectiveness

## Key Findings

Our analysis revealed that approximately 96% of users in our dataset could be classified as silent users. The Bisecting K-means algorithm with k=2 clusters proved most effective in distinguishing between silent and active users.

## Project Code

The project code is available in a Google Colab notebook:
[Mining Mastodon for Silent Users - Colab Notebook](https://colab.research.google.com/drive/1pRRov64Iz4HndiwGIH5H8cs-nSeOt805)

Note: The data collection loop in the code has been commented out as rerunning is unnecessary with the saved data files.

## Future Work

We've identified several avenues for future research:
- Enhance the feature set to gain deeper insights into user behavior
- Evaluate additional clustering models for potential improvements
- Extend our metrics to generalize across other social media platforms

## Team Members

This project was conducted by:
- Chan Lee
- Sang Nguyen
- Nancy Pitta
- Sidney Mei

## Acknowledgments

We extend our gratitude to Dr. Lu Cheng for providing valuable guidance throughout the course of this project.