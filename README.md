End-to-end Instagram engagement analysis and regression modeling project using Python, EDA, feature engineering, and model comparison.

# What the project does
It goes through a full small analytics workflow:
- loads an Instagram dataset from Kaggle
- checks structure and missing values
- performs EDA on likes, comments, caption length, and engagement
- creates new features: caption_length, hashtag_count, engagement_score = likes + 2 * comments
- visualizes relationships such as: likes distribution, comments distribution, caption length distribution, likes vs caption length, correlation matrix, top/bottom 20 posts by likes
- builds regression models to predict engagement: Linear Regression, Random Forest Regressor, Random Forest with log-transformed target
- compares models with MAE and R²
- exports the processed dataset

# Main idea
The goal is to understand what content-related factors may influence engagement and to test whether simple post attributes can predict performance.

<img width="1341" height="767" alt="image" src="https://github.com/user-attachments/assets/f328359b-25a7-4be8-b56e-8e6921383af1" />
