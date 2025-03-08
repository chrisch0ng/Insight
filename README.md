# Project Insight - Stock Price Prediction using Multiple AI Models

Insight - a stock prediction web app incorporating real-time financial data analysis using DeepSeek-R1 (Perplexity Sonar API), and Sentiment Analysis using Meta’s Llama3, and stock graph technical analysis using Google’s Gemini. The first iteration of this app was a simple logistic regression model focusing only on the stock’s price movements. Next, I started to incorporate large language models (LLMs) into my approach, scraping financial news and using Meta’s Llama model for sentiment analysis and  classification. After this iteration, I improved the design by adding DeepSeek R1 to query for strategies based on broader market data and specific company information.

Scrapes articles relating to a stock and uses Meta's Llama3.2 Large Language Model to automate sentiment classification. Then using AutoRegressive Integrated Moving Average to predict next week's price action in relation to this week's sentiment changes in news. 

![image](https://github.com/user-attachments/assets/d3c3399b-ddb6-4244-9a9a-e04b9a741526)

![Screenshot 2025-03-08 142219](https://github.com/user-attachments/assets/2544c585-2417-40f9-8a60-fbee7e64a04d)

### To run locally: 
need to first run 
```
pip install streamlit langchain_ollama holidays pandas numpy plotly statsmodels finvizfinance yfinance
```
to install necessary packages 

then run 
```streamlit run Insight.py``` 
in the command line to run the web app. 
