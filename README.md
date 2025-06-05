# Expectations Investing: Sentiment vs. Price Dynamics

## Project Overview  
This project tests a core hypothesis derived from Michael Mauboussin and Alfred Rappaport’s *Expectations Investing*, which argues that stock prices reflect the market’s collective expectations about a company’s future cash flows. The goal is to investigate whether **market sentiment lags stock price movements**, providing empirical evidence for or against the book’s assertion that prices lead expectations.
---

## **Thesis from *Expectations Investing***  
Mauboussin and Rappaport propose that investors should:  
1. **Reverse-engineer expectations** embedded in stock prices (via discounted cash flow models) rather than relying on subjective forecasts.  
2. **Focus on expectation revisions**, as stock price changes occur when the market updates its expectations about future performance.  

The book implies that **prices are the best real-time signal of market expectations**, and external sentiment indicators (e.g., news, social media) may merely react to price changes rather than predict them.

---

## **Hypothesis**  
- **Null Hypothesis (H₀)**: Market sentiment *lags* stock price movements, consistent with the idea that prices lead expectations.  
- **Alternative Hypothesis (H₁)**: Market sentiment *leads* stock price movements, suggesting inefficiencies in how expectations are priced.  

---

## **What the Model Seeks to Show**  
1. **Temporal Relationship**:  
   - Quantify the lag/lead relationship between sentiment (from news/social media) and stock prices using cross-correlation and Granger causality tests.  
2. **Expectations Efficiency**:  
   - Determine whether sentiment analysis provides actionable insights beyond what is already reflected in prices, per the principles of expectations investing.  
3. **Behavioral Insights**:  
   - Identify if sentiment-driven noise (e.g., short-term hype or fear) correlates with mispricings or expectation gaps.  

---

## **Implications**  
- If **H₀ is supported**, it reinforces the book’s argument that investors should prioritize price-implied expectations over sentiment trends.  
- If **H₁ is supported**, it may reveal scenarios where sentiment analysis can anticipate expectation revisions, offering opportunities for outperformance.  

---

## **Data & Methodology**  
- **Price Data**: Historical stock prices (e.g., AAPL, TSLA) from Yahoo Finance.  
- **Sentiment Data**: Scraped from Reddit, Twitter/X, or news headlines, processed using NLP (VADER, Transformers).  
- **Analysis**:  
  - Time-series alignment and normalization.  
  - Cross-correlation to measure lagged relationships.  
  - Machine learning models (LSTM/GRU) to test predictive power of sentiment.  

---