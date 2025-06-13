This project analyzes customer review text to determine overall sentiment (positive, neutral, negative). Using Python and natural language processing (NLP), it cleans text data, scores sentiment using VADER, and visualizes key patterns in customer feedback. The goal is to help businesses understand customer satisfaction and take action based on feedback trends.

🧾 Dataset Overview
The dataset includes thousands of product reviews from Amazon, with the following key fields:

Text – written customer review

Score – star rating (1 to 5)

(Optional) Time, ProductId, UserId

📁 Data Source: Amazon Fine Food Reviews (Kaggle)

🛠️ Tools & Libraries Used
Python

pandas, numpy – data handling

re, sklearn – text preprocessing

vaderSentiment – sentiment scoring

matplotlib, seaborn, wordcloud – visualizations

🧠 Key Steps in the Project
Text Preprocessing

Removed punctuation, special characters

Converted text to lowercase

Removed stopwords using sklearn

Sentiment Scoring

Used VADER to assign polarity scores to reviews:

> 0.05: Positive

< -0.05: Negative

Otherwise: Neutral

Visualization

WordClouds for positive and negative reviews

Histogram of sentiment polarity scores

Countplot of sentiment labels

📊 Key Insights
Most reviews are highly positive, but lower scores often use specific negative words.

Negative reviews are associated with product issues, delivery problems, or service complaints.

WordClouds help visualize the most common words in each sentiment class.

📁 Files Included
sentiment_analysis_reviews.ipynb – Main notebook with code and explanations

(Optional) cleaned_reviews.csv – Final processed dataset

WordCloud visuals as PNG files (optional)

🔗 Project Links
📘 View on Kaggle: https://www.kaggle.com/code/soumyameshram/sentiment-analysis-of-customer-reviews-in-python

📊 More Projects:https://www.kaggle.com/soumyameshram

📈 Business Use Case
This type of sentiment analysis can help companies:

Track brand health over time

Flag negative product trends early

Use feedback to guide improvements

