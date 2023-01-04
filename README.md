# 30+ Financial Data Science Projects

These Jupyter notebooks contain code examples and output from 30+
financial data science projects, which apply quantitative and
machine learning methods to large structured and unstructured
financial data sets. They accompany the [FinDS Python
repo](https://github.com/terence-lim/financial-data-science.git),
but reflect an older version hence do not (yet) sync with the code and examples
presently in that repo.

1. [Track stock identifier changes and price adjustments](stock_prices.ipynb)
   - stock splits, dividends, identifiers, and total holding returns

2. [Construct Jegadeesh-Titman rolling portfolios](jegadeesh_titman.ipynb)
   - Newey-West correction; momentum effect

3. [Construct Fama-French sorted portfolio](fama_french.ipynb)
   - linear regression; value and size anomaly

   ## Expected Returns

4. [Estimate Fama-Macbeth cross-sectional regressions](fama_macbeth.ipynb)
   - CAPM tests; polynomial regression; feature transformations

5. [Backtesting a stock price reversal trading strategy](weekly_reversal.ipynb)
   - Contrarian strategy; statistical arbitrage
   - implementation shortfall; structural change with unknown breakpoint

2. [Event studies of key developments](event_study.ipynb)
   - Abnormal returns; post-announcement drift; multiple testing

2. [Performance evaluation of factor investing](quant_factors.ipynb)
   - Return predicting signals; performance evaluation

   ## Risk

2. [Conditional volatility of cryptocurrencies](conditional_volatility.ipynb)
   - Value at Risk, Expected Shortfall, GARCH, EWMA; bitcoin, etherium

2. [Covariance matrix estimates of industry returns](covariance_matrix.ipynb)
   - Covariance Matrix: PCA, SVD, Shrinkage
   - Risk Decomposition, Black-Litterman, Risk Parity

2. [Visualizing the term structure of interest rates](term_structure.ipynb)
   - yield curve, duration, bootstrap
   
2. [Examine principal components of bond returns](bond_returns.ipynb)
   - Principal components analysis, bond returns
   
2. [Market microstructure: Intra-day liquidity from tick data](market_microstructure.ipynb)
   - TAQ tick data; spreads, Lee-Ready tick test, intra-day volatility

2. Event risk: Count dependent and aggregate loss models
   - frequency and severity of actuarial risks


   ## Econometric Methods

2. [Revisions of macroeconomic time series from ALFRED](revisions_vintage.ipynb)
   - Archival-FRED, vintages

2. [Analyze linear regression gaussian assumptions](linear_diagnostics.ipynb)
   - Residual analysis, outliers, leverage, influential points
   - Multicollinearity; robust standard errors

2. [Forecast inflation time series](econometric_forecast.ipynb)
   - trends, stationarity, seasonality, ARMA, smoothing, cointegration
   - granger causality, impulse response function

2. [Approximate factor model of FRED-MD macroeconomic series](approximate_factors.ipynb)
   - PCA-EM, unit root



   ## Network Science

2. [Ego network of principal customers supply chain](customer_ego.ipynb)
   - Induced subgraph, ego network

2. [Centrality measures of BEA input-output tables](bea_centrality.ipynb)
   - Graph centrality algorithms

2. [Community detection for industry sectoring](industry_community.ipynb)
   - Community detection graph algorithms

2. [Link prediction on company relationships](link_prediction.ipynb)
   - Accuracy metrics; imbalanced sample
   - Random graphs, link prediction graph algorithms


   ## Text Mining

2. [Logistic regression for text classification of key developments
financial news](keydev_classifier.ipynb)
   - Logistic regression, stochastic gradient descent

2. [Sentiment analysis of 10-K management discussion text](mda_sentiment.ipynb)
   - SEC Edgar, Loughran-MacDonald dictionary

2. [Syntactic analysis of 10-K business descriptions for industry
classifications](business_description.ipynb)
   - Softmax regression; POS tagging, named entity recognition

2. [Topic modeling of FOMC meeting minutes](fomc_topics.ipynb)
   - Matrix decomposition algorithms


   ## Machine Learning

2. [Compare classification models for key developments financial news
classification](classification_models.ipynb)
   - Generalized linear models, SVM, KNN, Naive-Bayes, decision tree
   - Cross-validation, feature importances

2. [Compare regression models for inflation prediction](regression_models.ipynb)
   - Subset selection, dimensional reduction, penalized least squares, ensembles
   - Regularization

2. Unsupervised learning: Cluster analysis of factor risk premiums
   - K-Means, hierarchical clustering

2. [Estimate state space economic models](economic_states.ipynb)
   - Mixture models, hidden markov models

2. Bayesian belief networks for fraud detection


   ## Deep Learning

2. [Tune word embeddings for text classification](dan_classifier.ipynb)
   -  Deep averaging networks, Feed forward neural net

2. [Recurrent neural network and dynamic factor models](elman_kalman.ipynb)
   - Long short term memory (LSTM), kalman filter

2. Train language model of fedspeak

2. [Temporal convolutional networks and VAR](tcn_var.ipynb)
   - Convolutional neural network, vector autoregression

2. Deep reinforcement learning and derivatives pricing


   ## Big Data and the Cloud

2. Big data
   - Hadoop, Spark, Hive

2. Cloud computing
