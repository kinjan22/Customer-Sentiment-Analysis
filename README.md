# Customer-Sentiment-Analysis
This project analyzes customer sentiment towards the iPhone 15 (128GB) using product reviews from Flipkart. The goal is to extract, process, and analyze customer feedback to understand overall sentiment and identify areas for product improvement.

## Features of This Project

* Web Scraping: Extracts customer reviews using Selenium and BeautifulSoup.
* Data Cleaning: Removes duplicates, handles missing values, and preprocesses text.
* Sentiment Analysis: Uses TextBlob to classify reviews as positive, negative, or neutral.
* Data Visualization: Generates insights through graphs and visual analysis.
* Insights & Recommendations: Helps in decision-making based on sentiment trends.

## Project Workflow

* Data Collection (Web Scraping)
  Extracts at least 350 reviews from Flipkart.
  Captures reviewer name, city, date, review text, and rating.
* Data Cleaning & Preprocessing
  Converts text to lowercase, removes unnecessary words.
  Handles missing values and duplicates.
* Sentiment Analysis
  Uses TextBlob to calculate polarity scores.
  Classifies sentiment as Positive, Negative, or Neutral.
* Data Visualization & Insights
  Sentiment Distribution: Shows overall sentiment trends.
  Review Length Analysis: Correlates review length with sentiment.
  Ratings vs Sentiment: Checks if higher ratings have more positive sentiment.

## Project Insights

* The average sentiment is positive, with a polarity score of 0.51.
* Most reviews praise camera quality, battery life, and performance.
* Negative feedback mentions heating issues and price concerns.
* Higher ratings (4-5 stars) strongly correlate with positive sentiment.

## Technologies Used

* Python (Data processing & analysis)
* Selenium & BeautifulSoup (Web scraping)
* Pandas & NumPy (Data handling)
* TextBlob & NLTK (Sentiment analysis)
* Matplotlib & Seaborn (Visualization)


