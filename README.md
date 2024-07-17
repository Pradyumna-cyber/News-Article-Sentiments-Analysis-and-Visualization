# News-Article-Sentiments-Analysis-and-Visualization


Certainly! Here's a README description for your GitHub repository based on the provided code:

---

# News Sentiment Analysis with Word Clouds

This Python script fetches top news headlines from India using the NewsAPI, performs sentiment analysis on the news article descriptions, and visualizes the sentiment distribution using word clouds and bar plots.

## Features

- **News API Integration**: Uses the NewsAPI to fetch top headlines from India.
- **Sentiment Analysis**: Utilizes TextBlob for sentiment analysis on each news article description.
- **Word Cloud Visualization**: Generates word clouds to visualize the most frequent words in positive, negative, and neutral sentiment categories.
- **Sentiment Distribution**: Displays a bar plot and a pie chart to show the distribution of positive, negative, and neutral sentiments among the fetched articles.

## Requirements

- Python 3.x
- Libraries: requests, nltk, textblob, wordcloud, matplotlib, pandas, seaborn

## Usage

1. Install the required libraries:
   ```bash
   pip install requests nltk textblob wordcloud matplotlib pandas seaborn
   ```

2. Obtain a NewsAPI key from [NewsAPI](https://newsapi.org/) and replace `'b9b9147260b4494d87034abfd17aa25a'` with your API key in the script.

3. Run the script:
   ```bash
   python news_sentiment_analysis.py
   ```

4. View the generated visualizations for sentiment analysis results.

## Screenshots

- Word Cloud for All Descriptions
- Positive Sentiment Word Cloud
- Negative Sentiment Word Cloud
- Neutral Sentiment Word Cloud
- Sentiment Distribution Bar Plot
- Sentiment Distribution Pie Chart

## Example Output

```
Total results found: 37
1. NDTV.com: India, Business, Bollywood, Cricket, Video and Breaking News
    Sentiment: Neutral
    Article Polarity: 0.0
...
```

