# Customer-Reviews-Analysis-Unsupervised-ML

**Project Overview**

This project focuses on analyzing customer reviews into three categories: Negative, Positive, or Neutral using unsupervised machine learning techniques. By leveraging sentiment analysis and clustering methods, we aim to uncover patterns in customer feedback and provide meaningful insights for businesses to improve their products and services.

**Objectives**

Classify customer reviews as Positive, Negative, or Neutral.

Perform sentiment analysis using VADER.

Visualize frequently used words in reviews.

Evaluate clustering performance using Silhouette Score.

**Dataset**

The dataset consists of customer reviews collected from various sources. The dataset includes:

Review ID

Customer ID

Product ID

Review text

Rating

Purchase category

Purchase amount

**Methodology**

Data Preprocessing:

Cleaning the customer review column using Regular Expressions.

Applying Word Lemmatization to standardize text.

Removing stop words, punctuation, and special characters.

Sentiment Analysis:

Using VADER (Valence Aware Dictionary and sEntiment Reasoner) to classify reviews as Positive, Negative, or Neutral.

Text Visualization:

Generating Word Cloud to show the frequency of words in the cleaned review column.

Clustering Evaluation:

Computing Silhouette Score to measure the quality of clustering and sentiment classification.

**Tools & Technologies**

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, NLTK, VADER, Matplotlib, Seaborn, WordCloud

**Expected Outcomes**

Accurate classification of reviews into Positive, Negative, or Neutral categories.

Insights into common themes in customer feedback.

Improved understanding of customer sentiment trends.

Enhanced business decision-making based on sentiment patterns.

**Future Improvements**

Implementing deep learning-based sentiment analysis models (e.g., BERT, RoBERTa).

Expanding the dataset to include multilingual reviews.

Enhancing visualization with interactive dashboards.

**Conclusion**

This project demonstrates the effectiveness of unsupervised machine learning in sentiment analysis. By cleaning and analyzing customer reviews, applying VADER for sentiment classification, and validating results with clustering techniques, businesses can make data-driven decisions to improve customer satisfaction and product offerings.
