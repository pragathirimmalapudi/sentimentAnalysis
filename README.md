
# Sentiment Analysis Project

## Overview
This project performs sentiment analysis on a dataset of product reviews using two different approaches: VADER (Valence Aware Dictionary and sEntiment Reasoner) and RoBERTa (a robustly optimized BERT approach). The goal is to compare the performance and results of these two models in understanding the sentiment expressed in the reviews.

## Dataset
The dataset used for this project can be found on Kaggle:
- https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews
The dataset contains product reviews with the following columns:
- `Id`: Unique identifier for each review.
- `ProductId`: Unique identifier for each product.
- `UserId`: Unique identifier for each user.
- `ProfileName`: Name of the user.
- `HelpfulnessNumerator`: Number of users who found the review helpful.
- `HelpfulnessDenominator`: Number of users who rated the review.
- `Score`: Rating given by the user (1 to 5 stars).
- `Time`: Timestamp of the review.
- `Summary`: Summary of the review.
- `Text`: Full text of the review.

## Requirements
- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- nltk
- tqdm
- transformers
- scipy

## Steps

### 1. Data Preprocessing
- Load the dataset.
- Perform basic data cleaning such as removing null values and duplicates.
- Visualize the distribution of review scores.

### 2. Sentiment Analysis with VADER
- Use VADER to calculate sentiment scores (negative, neutral, positive, and compound) for each review.
- Merge the VADER results with the original dataset.
- Visualize the sentiment scores.

### 3. Sentiment Analysis with RoBERTa
- Use RoBERTa to tokenize the review text and calculate sentiment scores.
- Merge the RoBERTa results with the original dataset.
- Visualize the sentiment scores.

### 4. Comparison and Analysis
- Compare the sentiment scores from VADER and RoBERTa.
- Analyze discrepancies between the models.
- Visualize and interpret the results.

## Conclusion
This project demonstrates the use of two different sentiment analysis techniques—VADER and RoBERTa—on a dataset of product reviews. By comparing the results from both models, we gain insights into their strengths and limitations, providing a comprehensive understanding of sentiment analysis in natural language processing.



