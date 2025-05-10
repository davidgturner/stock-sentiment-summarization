Problem Statement - Stock Market News Sentiment Analysis and Summarization

Business Context
The prices of the stocks of companies listed under a global exchange are influenced by a variety of factors, with the company's financial performance, innovations and collaborations, and market sentiment being factors that play a significant role. News and media reports can rapidly affect investor perceptions and, consequently, stock prices in the highly competitive financial industry. With the sheer volume of news and opinions from a wide variety of sources, investors and financial analysts often struggle to stay updated and accurately interpret its impact on the market. As a result, investment firms need sophisticated tools to analyze market sentiment and integrate this information into their investment strategies.

## Objective

With the overwhelming number of news articles and opinions published daily, I wanted to create a tool that leverages artificial intelligence to interpret stock-related news and its impact on stock prices. This project focuses on analyzing historical daily news for a specific company listed under NASDAQ, alongside its daily stock price and trade volumes.

The goal is to develop an AI-driven sentiment analysis system that automatically processes and analyzes news articles to gauge market sentiment. Additionally, the system summarizes the news at a weekly level to improve the accuracy of stock price predictions and optimize investment strategies. By sharing this project, I hope to empower others with actionable insights and tools to make more informed investment decisions and explore the intersection of AI and financial analysis.

Data Dictionary
* Date: The date the news was released
* News: The content of news articles that could potentially affect the company's stock price
* Open: The stock price (in $) at the beginning of the day
* High: The highest stock price (in $) reached during the day
* Low: The lowest stock price (in $) reached during the day
* Close: The adjusted stock price (in $) at the end of the day
* Volume: The number of shares traded during the day
* Label: The sentiment polarity of the news content
             *  1: Positive
             *  0: Neutral
             * -1: Negative
Points	60


## Export notebook to a HTML file

``` cd .\stock-sentiment-summarization\ ```
``` jupyter nbconvert --execute --to html .\NLP_Project_Full_Code_Mod_Latest3_1.ipynb ```