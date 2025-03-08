# Project Insight - Stock Price Prediction using LLM-powered Sentiment Analysis

Scrapes articles relating to a stock and uses Meta's Llama3.2 Large Language Model to automate sentiment classification. Then using AutoRegressive Integrated Moving Average to predict next week's price action in relation to this week's sentiment changes in news. 


### To run locally: 
need to first run 
```
pip install streamlit langchain_ollama holidays pandas numpy plotly statsmodels finvizfinance yfinance
```
to install necessary packages 

then run 
```streamlit run Insight.py``` 
in the command line to run the web app. 
