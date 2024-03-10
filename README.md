# Amazon-Review-Sentiment-Analysis
## Problem statement: 
Business owners often struggle to grasp the genuine sentiment of customers regarding their products. They may not have the time to delve into the complete feedback beyond average ratings, missing valuable insights. Additionally, nuances in language and varying expressions make it challenging to accurately interpret customer feedback at scale. This project aims to develop a sentiment analysis model that can overcome these challenges, providing businesses with trending actionable insights to enhance customer satisfaction and loyalty.

## Proposed methodology: 
Our methodology involves downloading a dataset of customer reviews and extracting both the review text and the corresponding rating. After preprocessing the text and assigning sentiment labels based on star ratings, we will convert the text into numerical features using word embeddings and/or TF-IDF vectorization. We will then split the data into training and testing sets, train a model, and evaluate its performance in predicting sentiments. We will also use the numerical features and word embeddings to perform exploratory analysis, identifying key terms or concepts associated with high and low reviews.

## Dataset(s): 
- https://www.kaggle.com/datasets/datafiniti/consumer-reviews-of-amazon-products/data?select=Datafiniti_Amazon_Consumer_Reviews_of_Amazon_Products_May19.csv
