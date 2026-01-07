Stock Market Trend Predictor
- Overview
This project focuses on predicting next-day stock price movement (Up/Down) using a combination of time series analysis, technical indicators, sentiment analysis, and deep learning (Transformer) models.
The goal is to build a decision-support system rather than exact price prediction.
 Key Features
Historical stock price & volume analysis
Technical indicators: SMA, EMA, RSI, MACD, Bollinger Bands
News sentiment integration using NLP
Classical time series baseline (ARIMA)
Transformer-based deep learning model for trend prediction
Model evaluation using accuracy, confusion matrix, and classification report
- Methodology
1. Data Processing & Feature Engineering
Used OHLCV stock data
Created multiple technical indicators to capture trend, momentum, and volatility
Proper time-series sequencing and scaling to avoid data leakage
2. Sentiment Analysis
Simulated daily financial news headlines
Applied VADER sentiment analysis to convert text into numerical scores
Aggregated daily sentiment and merged it with stock features
3. Models Used
ARIMA: Classical time series model used as a baseline
Transformer: Deep learning model using attention to capture long-term dependencies across multiple features
4. Evaluation
Binary classification (Up / Down)
Metrics: accuracy, confusion matrix, classification report
Trend visualization and basic trading signal generation
- Results
Transformer model achieved approximately 52–53% accuracy
Demonstrated improved recall for upward market movement
ARIMA served as a reliable baseline for comparison
Note: Stock markets are noisy and weakly predictable; the focus is on methodology and learning rather than high accuracy.
 Tech Stack
-Languages: Python
Libraries: Pandas, NumPy, Scikit-learn, PyTorch, Statsmodels, NLTK
Models: ARIMA, Transformer
Tools: Jupyter Notebook, GitHub
 How to Run
-Clone the repository
Install required dependencies
Run notebooks in the following order:
Data preprocessing & feature engineering
Sentiment analysis integration
ARIMA baseline modeling
Transformer training & evaluation
- Future Improvements
Integrate real-time news APIs for sentiment data
Try SARIMA / Prophet for seasonal modeling
Improve trading strategy simulation with risk metrics
Hyperparameter tuning with larger datasets
