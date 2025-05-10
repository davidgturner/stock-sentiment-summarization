Problem Statement - Stock Market News Sentiment Analysis and 

Business Context
The prices of the stocks of companies listed under a global exchange are influenced by a variety of factors, with the company's financial performance, innovations and collaborations, and market sentiment being factors that play a significant role. News and media reports can rapidly affect investor perceptions and, consequently, stock prices in the highly competitive financial industry. With the sheer volume of news and opinions from a wide variety of sources, investors and financial analysts often struggle to stay updated and accurately interpret its impact on the market. As a result, investment firms need sophisticated tools to analyze market sentiment and integrate this information into their investment strategies.
 

Objective
With an ever-rising number of news articles and opinions, an investment startup aims to leverage artificial intelligence to address the challenge of interpreting stock-related news and its impact on stock prices. They have collected historical daily news for a specific company listed under NASDAQ, along with data on its daily stock price and trade volumes.

As a member of the Data Science and AI team in the startup, you have been tasked with analyzing the data, developing an AI-driven sentiment analysis system that will automatically process and analyze news articles to gauge market sentiment, and summarizing the news at a weekly level to enhance the accuracy of their stock price predictions and optimize investment strategies. This will empower their financial analysts with actionable insights, leading to more informed investment decisions and improved client outcomes.
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

More notes
The final notebook should be well-documented, with inline comments explaining the functionality of code and markdown cells containing comments on the observations and insights.
The notebook should be run from start to finish in a sequential manner before submission.

Please refer to the FAQ page for common project-related queries.
 

Scoring guide (Rubric) - Stock Market News Sentiment Analysis and Summarization - Project Rubric
Criteria	Points
Exploratory Data Analysis
- Problem definition - Univariate analysis - Bivariate analysis - Use appropriate visualizations to identify the patterns and insights - Key meaningful observations on individual variables and the relationship between variables
8
Data Preprocessing
- Split the target variable and predictors - Split the data into train, validation, and test sets
2
Word Embeddings
- Using Word2Vec - Using GloVe - Using Sentence Transformer
10
Sentiment Analysis
- Comment on which metric to use and why - Build a ML model with each of the following embedding techniques - Word2Vec - GloVe - Sentence Transformer - Perform hyperparameter tuning for the ML model for each of the following embedding techniques - Word2Vec - GloVe - Sentence Transformer - Comment on model performance across different metrics - Choose the best model from the ones built with proper reasoning - Check the performance of the final model on the test set Note: The ML model to use is at the discretion of the learner.
16
Content Summarization
- Group the data at a week-level - Load the large language model from Hugging Face - Create a function to define the model parameters and generate a response - Define the instruction for the task (the task is to identify the top three positive and negative events from the week that are likely to impact the stock price) - Apply the response generation function to get an output from the model - Create a DataFrame containing the necessary fields from the model's output in a structured manner
12
Actionable Insights and Recommendations
- Share your observations and insights from the analysis conducted - Provide recommendations for the business
4
Presentation/Notebook - Overall Quality
- Structure and flow - Crispness - Visual appeal - All key insights and recommendations covered? OR - Structure and flow - Well commented code - All key insights and recommendations covered?
8
Points	60