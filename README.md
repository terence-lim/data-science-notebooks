# Financial Data Science Jupyter Notebooks

These notebooks contain code examples and results from exploring data science and machine learning methods
on large and textual financial data sets.

[https://github.com/terence-lim/financial-data-science](https://github.com/terence-lim/financial-data-science)

by: [Terence Lim](https://www.linkedin.com/in/terencelim)

&nbsp;


### Approximate Factor Models, VAR and TCN from FRED-MD

[approximate_factors.ipynb](approximate_factors.ipynb)

- PCA, EM, vector autoregression, temporal convolutional networks
- Bai and Ng (2002), McCracken and Ng (2016), and others

### Graph Centrality and BEA Input-Output Use Tables

[bea_centrality.ipynb](bea_centrality.ipynb)

- igraph, network, centrality, BEA Input-Output Use Table
- Choi and Foerster (2017), Bureau of Economic Analysis, and others

### Bond Market Index Components and Interest Rate Indicators

[bond_returns.ipynb](bond_returns.ipynb)

- PCA, St Louis Fed FRED

### Classification Models and Events Text

[classification_models.ipynb](classification_models.ipynb)

- sklearn, naivebayes, logistic, linearsvc, mlp, decisiontree, wordcloud
- text classification, S&P Key Developments, Wharton Research Data Services

### Conditional Volatility Models

[conditional_volatility.ipynb](conditional_volatility.ipynb)

- Value at Risk, GARCH, EWMA, Scholes-Williams Beta
- VIX, Bitcoin, St Louis Fed FRED

### Principal Customers Network

[customer_ego.ipynb](customer_ego.ipynb)

- igraph, ego graph, betweenness centrality
- S&P Compustat, Wharton Research Data Services

### DAN for text classification

[dan_classifier.ipynb](dan_classifier.ipynb)

- pytorch, deep averaging networks, word embeddings, spacy
- S&P Key Developments, Wharton Research Data Services

### Forecasting and Econometrics

[econometric_forecast.ipynb](econometric_forecast.ipynb)

- seasonality, spectral density, unit root, stationarity
- autocorrelation functions, AR, MA, SARIMAX
- scipy, statsmodels, seaborn, St Louis Fed FRED

### LSTM Networks, State Space Models and Mixtures from FRED-MD

[economic_states.ipynb](economic_states.ipynb)

- Long Short-Term Memory networks, hidden states, state space models, Gaussian mixtures
- pytorch, hmmlearn, statsmodels, sklearn

### Event Study Abnormal Returns

[event_study.ipynb](event_study.ipynb)

- CAR, BHAR, post-event drift, order statistics, Bonferroni adjustment
- S&P Key Developments, Wharton Research Data Services


### Fama French and momentum research factors

[fama_french.ipynb](fama_french.ipynb)

- CRSP, Compustat, Wharton Research Data Services

### Risk premiums from Fama-Macbeth cross-sectional regressions

[fama_macbeth.ipynb](fama_macbeth.ipynb)

- pandas datareader, Fama French data library


### Topic Models and FOMC meeting minutes

[fomc_topics.ipynb](fomc_topics.ipynb)

- NMF, LSA, LDA, PLSI matrix decomposition models

### Industry Sectoring

[industry_community.ipynb](industry_community.ipynb)

- igraph, community detection, modularity
- Text-based Network Industry Classification (Hoberg and Phillips, 2016)

### Classification of events text

[keydev_classifier.ipynb](keydev_classifier.ipynb)

- text classification, logistic regression, stochastic gradient descent
- confusion matrix, precision, recall, ROC curve
- S&P Key Developments, Wharton Research Data Services


### Linear Regression Diagonostics and Residual Plots

[linear_diagnostics.ipynb](linear_diagnostics.ipynb)

- linear regression assumptions, residual plots, robust standard errors
- outliers, leverage, multicollinearity
- statsmodels, St Louis Fed FRED

### Market Microstructure

[market_microstructure.ipynb](market_microstructure.ipynb)

- intraday liquidity, variance ratio, effective spreads, tick sign test
- tick data, NYSE Daily TAQ 

### Factor Investing

[quant_factors.ipynb](quant_factors.ipynb)

- return predicting signals, portfolios sorts, backtests
- CRSP, Compustat, IBES, Wharton Research Data Services
- Green, Hand and Zhang (2013) and others

### Supervised learning models for regression

[regression_models.ipynb](regression_models.ipynb)

- subset selection, partial least squares, ridge, lasso regression
- cross validation, feature importances, dimension reduction
- gradient boosting, random boosting, ensembles
- sklearn, statsmodels, St Louis Fed FRED, GDP

### Economic time series and releases: revisions and vintages

[revisions_vintage.ipynb](revisions_vintage.ipynb)

- St Louis Fed FRED/ALFRED

### Sentiment Analysis of Edgar Company Filings

[sec_sentiment.ipynb](sec_sentiment.ipynb)

- Cohen, Malloy and Nguyen (2020), Loughran and McDonald (2011), and others
- sklearn, nltk, SEC Edgar, Wharton Research Data Services

### Social Network Analysis of BEA Industries

[social_iouse.ipynb](social_iouse.ipynb)

- Input-Output Use Tables, Social Relations Regression Model
- igraph, rpy2, Bureau of Economic Analysis

### Factor and Empirical Covariance Matrix from NYSE TAQ

[taq_covariance.ipynb](taq_covariance.ipynb)

- covariance matrix shrinkage, PCA, minimum variance portfolios
- high frequency tick data, NYSE Daily TAQ

### Term Structure of Interest Rates

[term_structure.ipynb](term_structure.ipynb)

- bootstrap, splines, yield curve, duration
- Liu and Wu (2020), St Louis Fed FRED


### Unsupervised learning models for clustering economic series

[unsupervised_economics.ipynb](unsupervised_economics.ipynb)

- KMeans, agglomerative, spectral clustering, nearest neighbors, PCA
- sklearn, FRED-MD

### Weekly Reversals Strategy

[weekly_reversal.ipynb](weekly_reversal.ipynb)

- information coefficient, slippage, cross-sectional dispersion
- structural breaks, unknown changepoint
- rpy2, CRSP, Wharton Research Data Services


