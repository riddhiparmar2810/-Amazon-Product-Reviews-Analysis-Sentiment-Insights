# Amazon Product Reviews Analysis & Sentiment Insights

## Overview
This project analyzes Amazon product reviews to extract meaningful insights through data exploration and sentiment classification. The goal is to understand customer opinions and sentiment trends from review texts.

## Dataset
- Dataset contains Amazon product reviews with fields like ProductId, Score, Summary, Text, and Time.
- Data cleaning involved handling missing values, text preprocessing, and filtering.

## Steps Performed
1. **Data Loading and Cleaning**: Removed unnecessary columns, handled missing values.
2. **Exploratory Data Analysis (EDA)**:  
   - Distribution of review scores  
   - Most reviewed products  
   - WordClouds for positive and negative reviews  
   - Time-based trend analysis
3. **Text Preprocessing**:  
   - Lowercasing, punctuation removal, removing numbers and extra spaces.
4. **Sentiment Labeling**: Reviews labeled as Positive (4,5), Neutral (3), Negative (1,2).
5. **Model Training (Optional)**: Logistic Regression trained on review texts to classify sentiment.
6. **Evaluation and Visualization**: Accuracy score, classification report, and various plots.

## Results & Conclusion
- Majority of reviews are positive.
- Logistic Regression model shows decent accuracy for sentiment classification.
- WordClouds highlight common words in positive and negative sentiments.

## Technologies Used
- Python (pandas, numpy, matplotlib, seaborn, sklearn, wordcloud)
- Jupyter Notebook / Google Colab

## Author
Riddhi Parmar  
[GitHub](https://github.com/riddhiparmar2810) | [LinkedIn]([your-linkedin-profile-link](https://www.linkedin.com/in/riddhi-parmar-920b43251/))
