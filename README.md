# amazon-review-sentiment-analysis

### Introduction
Sentiment Analysis has become an important part of understanding customer, marketing, product improvement etc., Amazon is one of the biggest E-commerce platform where millions of transaction or purchases occur. Having hold on quality of each and every product is not an easy task. The sentiment analysis of product reviews can help us understand how each product is percieved by the customer. This can also help us formulate a marketing/sales strategy like increasing the visibility of products which have more positive reviews, giving a product report to the vendors for product improvement, creating sector wise reports etc.,

### Purpose
Our purpose is to create a tool that can categorize a review as 'positive' or 'negative' using the book reviews and ratings of amazon.

### Language & Methods
Python - Pandas, Numpy, Scikit Learn, Seaborn, Matplotlib

### Data 
Source : UCSanDiego library/repo Curated by Julian McAuley
[[ Link ]](http://jmcauley.ucsd.edu/data/amazon/)

### Methodology
- Creating classes
- Classification / Sentiment Analysis
  * Logistic Regression
  * K Nearest Neighbour
  * Support vector machine
  * Decision Tree
- Balancing data using Undersampling technique
- Visualizing the balanced and unbalanced model results using precision-recall curve and ROC curve

### Model Evaluation
- Unbalanced Best Model : F1 score of positive is 0.93 and Negative is 0.5
- Balanced Best Model: F1 Score of positive is 0.86 and Negative is 0.6
- Best AUC score is obtained for SVM which is 0.872

