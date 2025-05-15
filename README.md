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
1.The dataset had over 500,000 Amazon product reviews with various attributes like score, text, summary, and timestamp.
2.Most of the reviews were positive (scores 4 and 5), showing overall customer satisfaction.
3.Null values were minimal and were handled with imputation or removal of unnecessary columns.
4.After cleaning the text data, we observed frequent words like "great", "love", and "product", especially in positive reviews.
5.Score 3 was treated as neutral and excluded from sentiment analysis to avoid ambiguity.
6.Sentiment labeling helped classify reviews into Positive and Negative categories.
7.WordCloud and bar graphs helped visualize common words and score distribution clearly.
8.Monthly review trends showed periods of high review activity.
9.This analysis gives useful insights into customer opinions, product popularity, and areas for improvement.

## Technologies Used
- Python (pandas, numpy, matplotlib, seaborn, sklearn, wordcloud)
- Jupyter Notebook / Google Colab

## Author
Riddhi Parmar  
[GitHub](https://github.com/riddhiparmar2810) | [LinkedIn]([your-linkedin-profile-link](https://www.linkedin.com/in/riddhi-parmar-920b43251/))
