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
1. The dataset contains over 500,000 Amazon product reviews with various attributes including score, review text, summary, and timestamp.
2. Most of the reviews were labeled as positive (scores 4 and 5), showing overall customer satisfaction.
3. Null values were minimal and handled by imputation or dropping irrelevant columns.
4. After text cleaning, commonly used positive words included “great”, “love”, and “product”.
5. Score 3 (neutral) reviews were excluded from final sentiment classification to avoid ambiguity.
6. Sentiment labeling helped in distinguishing between positive and negative feedback effectively.
7. WordClouds and bar plots provided useful visual insights into review content and score distribution.
8. Time-based trend analysis showed periods with high review activity.
9. The overall analysis offers valuable insights into customer opinions, frequently used words, product popularity, and improvement areas.

## Technologies Used
- Python (pandas, numpy, matplotlib, seaborn, sklearn, wordcloud)
- Jupyter Notebook / Google Colab

## Author
Riddhi Parmar  
[GitHub](https://github.com/riddhiparmar2810) | [LinkedIn](https://www.linkedin.com/in/riddhi-parmar-920b43251/)
