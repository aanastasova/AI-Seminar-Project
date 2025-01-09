# Plan for Earnings Call Transcript Analysis
## Basis step

- Data Cleaning Clean text data (remove irrelevant characters, stop words, punctuation).
Handle missing values in the dataset. - everyone
- Exploratory Data Analysis (EDA) Explore Key statistics - Jasmine

## Sentiment Analysis

- Jorge: stock price prediction segregation - spacy, try different things if needed to track sentiment trends
- Jasmine: real stock prices data
- Yifan: Hugging face, to extraxt valuable insights and how we can use them?? for example, Is there a noticeable shift in sentiment following a negative revenue or profit report? Explore different correlations.

- compare models performance!!! 

**Jorge**: Analyze Sentiment Trends Over Time

Goal: Track sentiment in earnings call transcripts.

Tasks:
Use Spacy or another tool to analyze sentiment.
Look for changes in sentiment over time in the transcripts.
Identify shifts in sentiment before and after earnings calls.

Outcome: Find patterns in sentiment, such as how positive or negative sentiment affects stock price trends.

**Jasmine**: Get Real Stock Price Data
   
Goal: Collect stock prices for companies you're analyzing.
Tasks:
Get historical stock price data (before and after earnings calls).
Ensure you have stock price data for a reasonable timeframe (e.g., a week before and after each earnings report).
Outcome: Have real stock price data ready to compare with sentiment data.

**Yifan**: Extract Insights Using Hugging Face Models

Goal: Use Hugging Face models for sentiment analysis.

Tasks:
Use pre-trained models (like FinBERT) to analyze the transcripts.
Extract sentiment for each earnings call.
Look for correlations between sentiment and stock price movements.

Outcome: Get deeper insights into how sentiment impacts the stock market, like if negative sentiment follows poor earnings reports.

**Nina**: NLP Tasks + Data Integration & Visualization
Goal: Focus on NLP tasks and help with integration/visualization.

Tasks:
Preprocess the transcripts: Clean and tokenize text data (e.g., removing stop words, special characters, and tokenizing sentences/words).
Use additional NLP techniques such as topic modeling (LDA or NMF) to identify key topics discussed during earnings calls.

Integrate data: Combine sentiment data from Yifan with stock price data from Jasmine.

Visualize: Create graphs showing sentiment trends alongside stock prices, such as sentiment over time vs. stock price performance.
Outcome: Provide clean, well-prepared data for analysis and ensure that sentiment data and stock price data are well integrated and visually represented.

Real-World Data Comparison & Reporting 

Responsibilities:

Obtain Real-World Data:
Gather real-world financial data that can be used to compare the sentiment predictions with market reactions. For example:
Stock price movements after the earnings call.
Analyst ratings or market sentiment reports.

Sentiment vs. Market Reaction:
Compare the sentiment predictions from the models (positive, negative, neutral) with the market’s actual response (stock price movements or earnings report reactions).
Check if the model’s sentiment aligns with stock price movement (e.g., positive sentiment predicts a stock price rise).

Reporting:
Document the performance of different sentiment models and correlate the predicted sentiment with real-world financial outcomes.
Draft the final project report that includes model comparison, performance evaluation, real-world validation, and insights from the analysis.
Provide recommendations on which models worked best for earnings call sentiment analysis and how they can be applied to market prediction.


