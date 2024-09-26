#Sentiment Analysis on Amazon Stock through FinViz Website

## **Domain**
**Finance and Data Analytics.**
It combines financial data analysis with sentiment analysis to assess how news sentiment can impact stock market trends, making it relevant for fields like financial analysis, investment research, and market sentiment analysis.

## **Objective**
To analyze the sentiment of financial news articles for specific stock tickers (e.g., AMZN) over time and visualize the trends in sentiment using VADER sentiment analysis and Python libraries. This project aims to identify how news sentiment impacts the stock's perception in the market.

## **Technologies Used**
- Python: As the core programming language.
- BeautifulSoup: For web scraping financial news headlines.
- NLTK's VADER Sentiment Analysis: For scoring sentiment.
- Pandas: For data manipulation and analysis.
- Matplotlib: For visualizing sentiment trends.

  ## **Key Features**
- Web Scraping: Extracted news headlines and timestamps from financial websites (e.g., Finviz) using `BeautifulSoup`.
- Sentiment Analysis: Utilized the VADER SentimentIntensityAnalyzer to score the sentiment of each news headline.
- Data Processing: Organized and transformed data into a structured format using `pandas` DataFrames for further analysis.
- Visualization: Created bar plots to visualize average sentiment trends over time for different stock tickers using `Matplotlib`.

## **Explanation**
The project involves analyzing financial news articles to understand the sentiment around specific stock tickers (e.g., AMZN) over time. Using Python, the project scrapes news headlines from financial websites and then applies the VADER sentiment analysis tool to determine whether each headline expresses a positive, negative, or neutral sentiment. The data is then organized using Pandas, and visualizations are created with Matplotlib to showcase sentiment trends over time.
This approach helps identify patterns in how news sentiment can influence or reflect stock performance, offering valuable insights for investors or analysts in understanding market sentiment.

## **Results/Impact**
- Successfully extracted and analyzed sentiment data for stock-related news articles.
- Generated visual insights showing how sentiment scores fluctuated over time for different stock tickers.
- The project can help investors or analysts identify correlations between news sentiment and stock performance, aiding in decision-making.

## **Summary**
This project demonstrates proficiency in web scraping, sentiment analysis, data processing, and visualization, making it a comprehensive data analysis task.
