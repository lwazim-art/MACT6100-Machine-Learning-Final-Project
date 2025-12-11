This project investigates whether technical indicators derived from historical price and volume data can meaningfully predict next-day S&P 500 market direction.
Financial theory—specifically the Efficient Market Hypothesis (EMH)—suggests that short-term price movements should be essentially unpredictable.

However, empirical research and quantitative trading literature (e.g., Ernest P. Chan’s Quantitative Trading) motivate exploring whether weak but exploitable signals exist.

This project compares four modelling approaches:
	•	Logistic Regression (GLM) – interpretable baseline
	•	Random Forests – non-linear ensemble method
	•	Gradient Boosting Machines (GBM) – strong performance on structured datasets
	•	Deep Neural Network (DNN) – capable of capturing complex non-linearities

The goal is to determine whether any model can outperform random chance in predicting whether the S&P 500 will close up or down on the next trading day.
