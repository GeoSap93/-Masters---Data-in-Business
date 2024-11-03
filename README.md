# Music App User Satisfaction Analysis #
This project investigates how various musical features influence user satisfaction in music applications, using data sourced from Spotify's track characteristics. The analysis was divided into three major assignments, each contributing insights toward a deeper understanding of user preferences in the music streaming industry.

# Project Overview #
The music streaming industry often faces the challenge of providing highly personalized recommendations that align with user preferences. Despite advancements in recommendation algorithms, music apps still struggle with balancing popular tracks with individual user tastes. This project explores potential improvements through data-driven insights from Spotify's world music dataset, analyzing how characteristics such as danceability, energy, and tempo influence track popularity. The goal is to enhance the personalization experience and, consequently, user satisfaction in music apps.

# Assignment Summaries #
## Assignment 1: Problem Identification & Exploratory Data Analysis (EDA) ##
Objective: To identify a real-world issue in music app recommendations and explore the available dataset to address this problem.
Problem Definition: Many music apps recommend songs based primarily on popularity rather than nuanced preferences like danceability, loudness, or instrumentalness, limiting the user experience.
Database Selection: We utilized the "Spotify World Music Tracks" dataset from Kaggle, which includes key musical attributes such as danceability, energy, loudness, and more.
EDA Findings: Initial analyses revealed weak correlations between popularity and some track characteristics. Notably:
Higher valence (positive mood) and danceability generally correspond with higher popularity.
Tracks with more spoken content (speechiness) tend to be less popular.
Challenges Identified: The dataset showed limited diversity, with a concentration of tracks from the 2000s, which may skew trends.

## Assignment 2: Detailed EDA & Statistical Testing ##
Expanded Analysis: We delved further into univariate and bivariate analyses, examining how attributes correlate with each other and with track popularity.
Correlation and Regression: Regression analysis revealed that danceability and valence positively impact popularity, while speechiness has a significant negative effect.
Statistical Testing: Tests like the t-test and chi-square test were conducted to validate findings, ensuring statistical reliability.
Conclusions: Popularity seems influenced by attributes like danceability and mood (valence), while other attributes like energy and tempo have a weaker correlation with popularity.

## Assignment 3: Data Visualization and Storytelling ##
Visual Storytelling Tools: Data narratives were crafted using Tableau, Data Wrapper, and Plotly to visually represent findings.
Visual Insights:
Scatterplots highlighted weak correlations between popularity and attributes like loudness and energy.
Pie Charts showed that most popular tracks are in major keys, suggesting a preference for upbeat music.
Stacked Bar Charts illustrated the prevalence of tracks with moderate levels of speechiness, instrumentalness, and valence across varying popularity levels.
Key Insight: Tracks high in danceability and positive valence are generally favored, suggesting that recommendation algorithms should incorporate these preferences to enhance user satisfaction.

## Individual Report: Machine Learning in Social Media ##
In addition to the group assignments, an individual report on Machine Learning (ML) in Social Media provided insights into the application and challenges of ML in platforms like TikTok, Facebook, and Twitter. This report addresses:

Challenges: Data quality, model interpretability, and data privacy are major concerns in social media ML.
Opportunities: ML enables personalized content, increased user engagement, and real-time content moderation.
Recommendations: Emphasis on data quality, interpretability, and balancing automation with human oversight to optimize ML applications in social media.

# Conclusion & Recommendations #
Our analyses underscore the need for music apps to prioritize track characteristics beyond popularity, incorporating attributes like danceability, valence, and mood into recommendation algorithms. Key recommendations include:
Algorithm Diversification: Expand recommendation metrics to focus on user-specific attributes, enhancing personalization.
Data Diversity: Use a broader, more diverse dataset for improved insights into current trends and user preferences.
Feature Prioritization: Focus on attributes such as danceability and valence, which align closely with user preferences for popular tracks.
By implementing these recommendations, music streaming platforms can improve user engagement and satisfaction, ultimately benefiting both users and stakeholders in the competitive music app market.

