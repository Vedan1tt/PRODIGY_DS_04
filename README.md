# Twitter Sentiment Analysis

## Overview

This project performs **Sentiment Analysis on Twitter data** to identify public opinions and emotions expressed in tweets. The analysis categorizes tweets into sentiment classes such as **Positive**, **Negative**, **Neutral**, and **Irrelevant**.

The project includes:

* Data cleaning and preprocessing
* Sentiment distribution analysis
* Brand-wise sentiment analysis
* Word cloud generation
* Data visualization using charts

---

## Project Structure

```text
task4/
│
├── twitter_training.csv
├── twitter_validation.csv
├── sentiment_analysis.py
│
├── chart1_sentiment_distribution.png
├── chart2_sentiment_by_brand.png
├── chart3_sentiment_pie.png
├── chart4_positive_wordcloud.png
└── chart5_negative_wordcloud.png
```

---

## Dataset Description

The dataset contains tweets related to various brands, products, and services.

### Main Columns

* Tweet ID
* Brand / Company
* Sentiment Label
* Tweet Text

### Sentiment Categories

* Positive
* Negative
* Neutral
* Irrelevant

---

## Technologies Used

* Python 3.x
* Pandas
* Matplotlib
* WordCloud
* NumPy

---

## Project Workflow

### 1. Data Loading

The Twitter dataset is loaded using Pandas.

### 2. Data Cleaning

* Remove missing values
* Handle duplicate records
* Prepare text data for analysis

### 3. Sentiment Analysis

The dataset is analyzed based on predefined sentiment labels.

### 4. Visualization

Various charts are generated to understand sentiment trends and brand perception.

---

## Generated Visualizations

### 1. Sentiment Distribution

**File:** `chart1_sentiment_distribution.png`

Displays the number of tweets in each sentiment category.

---

### 2. Brand-wise Sentiment Analysis

**File:** `chart2_sentiment_by_brand.png`

Shows sentiment distribution across different brands or companies.

---

### 3. Sentiment Pie Chart

**File:** `chart3_sentiment_pie.png`

Illustrates the proportion of:

* Positive Tweets
* Negative Tweets
* Neutral Tweets
* Irrelevant Tweets

---

### 4. Positive Word Cloud

**File:** `chart4_positive_wordcloud.png`

Highlights the most frequently used words in positive tweets.

---

### 5. Negative Word Cloud

**File:** `chart5_negative_wordcloud.png`

Highlights the most frequently used words in negative tweets.

---

## Installation

Install the required libraries:

```bash
pip install pandas matplotlib numpy wordcloud
```

---

## Running the Project

Execute the Python script:

```bash
python sentiment_analysis.py
```

The script will:

1. Load the Twitter dataset.
2. Perform sentiment analysis.
3. Generate charts and word clouds.
4. Save visualization outputs as image files.

---

## Key Insights

The project helps identify:

* Overall public sentiment trends.
* Brands receiving positive or negative feedback.
* Common words associated with positive opinions.
* Common words associated with negative opinions.
* Customer perception patterns from social media data.

---

## Learning Outcomes

Through this project, you will learn:

* Text data analysis basics
* Sentiment classification concepts
* Data cleaning and preprocessing
* Word cloud generation
* Data visualization techniques
* Exploratory Data Analysis (EDA) for text datasets

---

## Applications

This type of sentiment analysis can be used for:

* Brand monitoring
* Customer feedback analysis
* Product review analysis
* Social media analytics
* Marketing campaign evaluation

---

## Author

** Vedant Mule **
Bachelor of Computer Application Student
Aspiring Data Science Enthusiast

---

## Future Enhancements

* Apply NLP preprocessing techniques (stemming, lemmatization).
* Use machine learning models for sentiment prediction.
* Implement deep learning approaches such as LSTM or BERT.
* Build a real-time Twitter sentiment dashboard.
* Deploy the project using Flask, Streamlit, or Power BI.
