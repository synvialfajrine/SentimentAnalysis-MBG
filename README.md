# Project Overview: Sentiment Analysis of 'Makan Bergizi Gratis' Program

This project analyzes public opinion about the 'Makan Bergizi Gratis' program, a free nutritious meal initiative provided by the Indonesian government. By leveraging sentiment analysis on X (formerly Twitter), the project aims to:

- Examine public sentiment trends (positive, negative, or neutral).
- Identify common concerns or praises in feedback.
- Provide actionable insights for the program's improvement.

The sentiment analysis model was built using Python, the X API for tweet collection, and Naive Bayes for sentiment classification. The training dataset was sourced from [this Indonesian sentiment dataset](https://github.com/rizalespe/Dataset-Sentimen-Analisis-Bahasa-Indonesia).

---

## Project Steps

### 1. Data Collection
- Used the X API to gather tweets mentioning keywords and hashtags related to the 'Makan Bergizi Gratis' program.
- Stored the tweets in a structured CSV file for further processing.

### 2. Data Preprocessing
- Removed irrelevant content such as URLs, mentions, hashtags, and special characters.
- Normalized text to lowercase and removed stopwords (custom stopword list used for Indonesian).
- Prepared a cleaned dataset of tweets for analysis.

### 3. Model Development
- Trained a sentiment analysis model using the Naive Bayes algorithm.
- Utilized an existing labeled dataset of Indonesian text for model training: [Dataset Sentimen Analisis Bahasa Indonesia](https://github.com/rizalespe/Dataset-Sentimen-Analisis-Bahasa-Indonesia).

### 4. Sentiment Classification
- Applied the trained model to classify tweets into three categories: positive, negative, or neutral.
- Stored the classification results in a CSV file, along with tweet text and sentiment labels.

### 5. Data Visualization and Insights
- Generated bar charts and pie charts to visualize sentiment distribution.
- Calculated percentages and total counts for positive, negative, and neutral tweets.
- Summarized the key findings to identify the general sentiment trend and frequent themes in public opinion.

---

## Data Source
- The training dataset for the sentiment analysis model was obtained from [this GitHub repository](https://github.com/rizalespe/Dataset-Sentimen-Analisis-Bahasa-Indonesia).
- Tweets were collected in real-time using the X API and filtered by keywords related to the program.

