# Real-Time Stock Sentiment Analysis Platform
# AI-Driven Sentiment Analysis & Weekly News Summarization for Stock Price Prediction

Financial markets react rapidly to news, making it challenging to track and interpret large volumes of information manually. This project leverages AI and NLP to analyze historical stock-related news and price movements, providing actionable insights for investment decisions.

Sentiment analysis models is implemented using Word2Vec, GloVe, and Sentence Transformers to quantify sentiment and evaluate its impact on stock prices. Performance is measured using metrics such as accuracy, F1-score, and correlation with price movements.

Additionally, a Large Language Model (LLM) is used to generate weekly summaries of financial news, highlighting key positive and negative events. This helps investors quickly identify critical information, reduce information overload, and make data-driven decisions.

## What This Does
- Extracts financial news
- Applies sentiment analysis
- Tracks sentiment vs stock movement
- Enables trading insights
## Architecture
Data Ingestion → NLP Processing → Sentiment Scoring → Visualization
## Tech Stack
- Python (Pandas, NLP)
- APIs (news sources)
- Visualization (Matplotlib / Plotly)
## Business Value
Transforms unstructured financial news into actionable signals.
# Example Outputs
# Sentiment Distribution
Positive sentiment spike → Stock price increase (lag effect observed)
<img width="299" height="261" alt="image" src="https://github.com/user-attachments/assets/615ee132-bc9c-4bbf-98f4-1c9c76108c7f" />
# Stock Price Distribution
<img width="328" height="211" alt="image" src="https://github.com/user-attachments/assets/3787945a-22b9-4aff-ab4f-32a4654c81b6" />
# News Length Distribution
<img width="350" height="220" alt="image" src="https://github.com/user-attachments/assets/e70ed43a-2d80-4813-a23d-6e09abf8ec01" />
# Correlation Matrix
<img width="332" height="305" alt="image" src="https://github.com/user-attachments/assets/cae78722-6b31-4f4d-bfdd-931233ffc522" />

# Run the Model
Open directly in Google Colab:https://colab.research.google.com/github/njotuguilly-blip/Stock_news_analysis


