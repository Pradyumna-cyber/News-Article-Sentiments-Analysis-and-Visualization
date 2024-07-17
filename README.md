# News-Article-Sentiments-Analysis-and-Visualization



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

2. Obtain a NewsAPI key from [NewsAPI](https://newsapi.org/) and replace `'yourapikey[News API]'` with your API key in the script.

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

##Outputs Screenshots
Total results found: 37
1. NDTV.com: India, Business, Bollywood, Cricket, Video and Breaking News
Original: NDTV.com: India, Business, Bollywood, Cricket, Video and Breaking News
Lemmatized: NDTV.com : India , Business , Bollywood , Cricket , Video and Breaking News
    Sentiment: Neutral
    Article Polarity: 0.0

2. This urine collection and filtration system for spacesuits addresses long-standing issues of comfort hygiene and water conservation during spacewalks
Original: This urine collection and filtration system for spacesuits addresses long-standing issues of comfort hygiene and water conservation during spacewalks
Lemmatized: This urine collection and filtration system for spacesuit address long-standing issue of comfort hygiene and water conservation during spacewalks
    Sentiment: Neutral
    Article Polarity: 0.0

3. Budget 2024 Expectations Live Updates: Finance Minister Nirmala Sitharaman is set to present the first comprehensive Union Budget of the Narendra Modi 3.0 administration on July 23, 2024. As India is poised to become the world's third-largest economy in the c…
Original: Budget 2024 Expectations Live Updates: Finance Minister Nirmala Sitharaman is set to present the first comprehensive Union Budget of the Narendra Modi 3.0 administration on July 23, 2024.
Lemmatized: Budget 2024 Expectations Live Updates : Finance Minister Nirmala Sitharaman is set to present the first comprehensive Union Budget of the Narendra Modi 3.0 administration on July 23 , 2024 .
    Sentiment: Positive
Original: As India is poised to become the world's third-largest economy in the c…
Lemmatized: As India is poised to become the world 's third-largest economy in the c…
    Sentiment: Neutral
    Article Polarity: 0.06439393939393939

4. From OnePlus Nord 4 to Realme 13 Pro series, checkout the list of all the smartphones that confirmed to launch in the month of July.
Original: From OnePlus Nord 4 to Realme 13 Pro series, checkout the list of all the smartphones that confirmed to launch in the month of July.
Lemmatized: From OnePlus Nord 4 to Realme 13 Pro series , checkout the list of all the smartphones that confirmed to launch in the month of July .
    Sentiment: Positive
    Article Polarity: 0.4

5. States like New Delhi, Karnataka, Haryana, Punjab, Tamil Nadu, Goa and Kerala are exploring pilot projects regarding the same, a report claimed
Original: States like New Delhi, Karnataka, Haryana, Punjab, Tamil Nadu, Goa and Kerala are exploring pilot projects regarding the same, a report claimed
Lemmatized: States like New Delhi , Karnataka , Haryana , Punjab , Tamil Nadu , Goa and Kerala are exploring pilot project regarding the same , a report claimed
    Sentiment: Positive
    Article Polarity: 0.06818181818181818

6. Benchmark equity indices started the trading session positively. Broader indices also traded in the green. Nifty Realty is the top gainer, and Nifty IT is the top loser.
Original: Benchmark equity indices started the trading session positively.
Lemmatized: Benchmark equity index started the trading session positively .
    Sentiment: Positive
Original: Broader indices also traded in the green.
Lemmatized: Broader index also traded in the green .
    Sentiment: Negative
Original: Nifty Realty is the top gainer, and Nifty IT is the top loser.
Lemmatized: Nifty Realty is the top gainer , and Nifty IT is the top loser .
    Sentiment: Positive
    Article Polarity: 0.17575757575757575

7. None
8. GAMING News: Garena Free Fire MAX in India uses 12-character codes valid for up to 18 hours daily for 500 gamers. Codes provide exclusive items, ensuring fairness.
Original: GAMING News: Garena Free Fire MAX in India uses 12-character codes valid for up to 18 hours daily for 500 gamers.
Lemmatized: GAMING News : Garena Free Fire MAX in India us 12-character code valid for up to 18 hour daily for 500 gamers .
    Sentiment: Positive
Original: Codes provide exclusive items, ensuring fairness.
Lemmatized: Codes provide exclusive item , ensuring fairness .
    Sentiment: Neutral
    Article Polarity: 0.1

9. Six children have died due to suspected Chandipura virus in Gujarat since July 10, with the total number of cases of the infection rising to 12, state Health Minister Rushikesh Patel has said.
Original: Six children have died due to suspected Chandipura virus in Gujarat since July 10, with the total number of cases of the infection rising to 12, state Health Minister Rushikesh Patel has said.
Lemmatized: Six child have died due to suspected Chandipura virus in Gujarat since July 10 , with the total number of case of the infection rising to 12 , state Health Minister Rushikesh Patel ha said .
    Sentiment: Negative
    Article Polarity: -0.0625

10. None
11. Twinkle Khanna and Akshay Kumar twinned in shimmering traditional looks on Day 4 of the Ambani wedding. The actor recently recovered from Covid. | Fashion Trends
Original: Twinkle Khanna and Akshay Kumar twinned in shimmering traditional looks on Day 4 of the Ambani wedding.
Lemmatized: Twinkle Khanna and Akshay Kumar twinned in shimmering traditional look on Day 4 of the Ambani wedding .
    Sentiment: Neutral
Original: The actor recently recovered from Covid.
Lemmatized: The actor recently recovered from Covid .
    Sentiment: Neutral
Original: | Fashion Trends
Lemmatized: | Fashion Trends
    Sentiment: Neutral
    Article Polarity: 0.0

12. Dengue fever during pregnancy can lead to low birth weights in newborns due to complications from the infection. Prompt medical care and preventive measures are crucial for the health of both mother and baby.
Original: Dengue fever during pregnancy can lead to low birth weights in newborns due to complications from the infection.
Lemmatized: Dengue fever during pregnancy can lead to low birth weight in newborn due to complication from the infection .
    Sentiment: Negative
Original: Prompt medical care and preventive measures are crucial for the health of both mother and baby.
Lemmatized: Prompt medical care and preventive measure are crucial for the health of both mother and baby .
    Sentiment: Neutral
    Article Polarity: -0.03125

13. None
14. This was Donald Trump’s first public appearance after surviving an assassination attempt at a Pennsylvania rally.
Original: This was Donald Trump’s first public appearance after surviving an assassination attempt at a Pennsylvania rally.
Lemmatized: This wa Donald Trump ’ s first public appearance after surviving an assassination attempt at a Pennsylvania rally .
    Sentiment: Positive
    Article Polarity: 0.125

15. Paytm SEBI warning: One 97 Communications, Paytm's parent, received a SEBI warning for unapproved FY 2021-22 related party transactions with Paytm Payments Bank totaling ₹324 crore and ₹36 crore. The July 15, 2024 letter noted compliance lapses. Paytm asserts…
Original: Paytm SEBI warning: One 97 Communications, Paytm's parent, received a SEBI warning for unapproved FY 2021-22 related party transactions with Paytm Payments Bank totaling ₹324 crore and ₹36 crore.
Lemmatized: Paytm SEBI warning : One 97 Communications , Paytm 's parent , received a SEBI warning for unapproved FY 2021-22 related party transaction with Paytm Payments Bank totaling ₹324 crore and ₹36 crore .
    Sentiment: Neutral
Original: The July 15, 2024 letter noted compliance lapses.
Lemmatized: The July 15 , 2024 letter noted compliance lapse .
    Sentiment: Neutral
Original: Paytm asserts…
Lemmatized: Paytm asserts…
    Sentiment: Neutral
    Article Polarity: 0.0

16. None
17. Discover the top 5 high-sugar fruits that individuals with diabetes should avoid to manage their blood sugar levels effectively. Learn about the risks associated with consuming mangoes, grapes, bananas, pineapples, and cherries.
Original: Discover the top 5 high-sugar fruits that individuals with diabetes should avoid to manage their blood sugar levels effectively.
Lemmatized: Discover the top 5 high-sugar fruit that individual with diabetes should avoid to manage their blood sugar level effectively .
    Sentiment: Positive
Original: Learn about the risks associated with consuming mangoes, grapes, bananas, pineapples, and cherries.
Lemmatized: Learn about the risk associated with consuming mango , grape , banana , pineapple , and cherry .
    Sentiment: Neutral
    Article Polarity: 0.18333333333333335

18. Here’s what the firefighter Corey Comperatore said to his family right before he was killed at Trump’s rally in Pennsylvania.
Original: Here’s what the firefighter Corey Comperatore said to his family right before he was killed at Trump’s rally in Pennsylvania.
Lemmatized: Here ’ s what the firefighter Corey Comperatore said to his family right before he wa killed at Trump ’ s rally in Pennsylvania .
    Sentiment: Positive
    Article Polarity: 0.042857142857142844

19. None
20. NASA’s lunar reconnaissance orbiter (LRO) has provided radar data revealing that the Mare Tranquillitatis pit, the deepest known on the moon, leads to a cave that is 45 meters wide and up to 80 meters long. This cave is located about 150 meters beneath the lu…
Original: NASA’s lunar reconnaissance orbiter (LRO) has provided radar data revealing that the Mare Tranquillitatis pit, the deepest known on the moon, leads to a cave that is 45 meters wide and up to 80 meters long.
Lemmatized: NASA ’ s lunar reconnaissance orbiter ( LRO ) ha provided radar data revealing that the Mare Tranquillitatis pit , the deepest known on the moon , lead to a cave that is 45 meter wide and up to 80 meter long .
    Sentiment: Negative
Original: This cave is located about 150 meters beneath the lu…
Lemmatized: This cave is located about 150 meter beneath the lu…
    Sentiment: Neutral
    Article Polarity: -0.037500000000000006
<img width="997" alt="image" src="https://github.com/user-attachments/assets/8958bc4b-8d55-49ca-9ebf-7734f45afba4">

<img width="982" alt="image" src="https://github.com/user-attachments/assets/9613610b-1d2e-4730-865f-931c4dc1c92e">

<img width="994" alt="image" src="https://github.com/user-attachments/assets/b6c57eef-9b98-4e90-ad86-ca5f7af11282">

<img width="1000" alt="image" src="https://github.com/user-attachments/assets/b6a046cd-36a3-41fa-8915-d0598992d68d">

##Plots
<img width="798" alt="image" src="https://github.com/user-attachments/assets/965f7c99-48ca-44fb-86c3-c63d970bcf10">





