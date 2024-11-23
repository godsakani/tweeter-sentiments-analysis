# Twitter Sentiment Analysis

## Description

This project performs sentiment analysis on tweets related to a specific search term. It uses the TextBlob library to determine the sentiment of each tweet as positive, negative, or neutral. The analysis provides insights into public opinion and sentiment towards the chosen topic.

## Installation

1.  **Set up a virtual environment (venv):**

    ```bash
    python3 -m venv <your_env_name>

    To activate the environment use:
    
    <vertual environment name>\Scripts\activate
    ````

2.  **Install necessary packages in virtual environment:**

    ```bash
    pip install tweepy

    pip install textblob

    pip install matplotlib
    
    ````
3.  **Set up Twitter API credentials:**

    - Create a Twitter developer account and obtain API keys and tokens.
    - Replace the placeholder values for `consumer_key`, `consumer_secret`, `access_token`, `access_token_secret`, and `bearer_token` in the code with your actual credentials.

## Usage

1.  **Define search term and number of tweets:**
    - Modify the `search_term` variable to specify the topic you want to analyze.
    - Adjust the `no_of_tweets` variable to control the number of tweets to retrieve.

2.  **Run the code:**
    - Execute the code in a Google Colab environment or Jupyter Notebook.

## Results

- The code prints the sentiment of each tweet (positive, negative, or neutral).

#### Sentiment Analysis of Tweets about 'Coronavirus'

This pie chart presents the results of a sentiment analysis performed on tweets about "Coronavirus."  The analysis categorized tweets into three sentiment categories:

* **Neutral:** 70% of the analyzed tweets were classified as neutral.
* **Positive:** 20% of the tweets expressed a positive sentiment.
* **Negative:** 10% of the tweets exhibited a negative sentiment.

![Sentiment Analysis Pie Chart](/analysis_plot/output.png)  

The chart clearly shows that the majority of tweets about Coronavirus during the period of analysis were neutral in tone.  Positive and negative sentiments were present but represented smaller portions of the overall conversation.

#### Significance

- This project helps to understand public opinion and sentiment towards a specific topic on Twitter.
- It can be used to track changes in sentiment over time.
- The insights gained from sentiment analysis can be valuable for market research, brand monitoring, and social media analytics.