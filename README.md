# FINANCIAL DATA SCIENCE


As financial markets produce vast volumes of structured and unstructured data,
the ability to extract insights and develop predictive models has become increasingly important.
[Financial Data Science Python Notebooks](https://terence-lim.github.io/docs/financial-data-science-notebooks/)
provide a practical guide for analysts, researchers, and data scientists looking to apply Python
and its broad ecosystem of libraries, tools, frameworks, and community resources
to financial analysis, econometrics, and machine learning.

Designed to support financial data science workflows,
the companion [FinDS Python package](https://github.com/terence-lim/financial-data-science)
demonstrates how to use database engines such as SQL, Redis, and MongoDB to manage and access large datasets, including:

- Core financial databases such as CRSP, Compustat, IBES, and TAQ

- Public economic data APIs from sources like FRED and the Bureau of Economic Analysis (BEA)

- Structured and unstructured data from academic and research websites

In addition to data access, it provides practical examples and templates for applying:

- Financial econometrics and time series modeling

- Graph analytics, event studies, and backtesting strategies

- Machine learning for predictive analytics

- Natural language processing (NLP) to extract insights from financial text

- Neural networks and large language models (LLMs) for advanced decision-making


**March 2025**: Updated with data through early 2025 and incorporated the latest LLMs -- Microsoft Phi-4-multimodal (released Feb 2025), Google Gemma-3-12B (March 2025), DeepSeek-R1-14B (January 2025), Meta Llama-3.1-8B (July 2024), GPT-4o-mini (July 2024).


## Topics


| notebook | Financial | Data | Science |
|:--|:--|:--|:--|
| [1.1_stock_prices](1.1_stock_prices.ipynb) | Stock price properties | CRSP stocks | Statistical moments |
| [1.2_jegadeesh_titman](1.2_jegadeesh_titman.ipynb) | Price momentum | CRSP stocks | Hypothesis testing, <br> Newey-West estimator |
| [1.3_fama_french](1.3_fama_french.ipynb) | Value and size | CRSP stocks, <br> Compustat |  Linear regression |
| [1.4_fama_macbeth](1.4_fama_macbeth.ipynb) | CAPM | Fama-French | Non-linear regression, <br> Quadratic optimization |
| [1.5_contrarian_trading](1.5_contrarian_trading.ipynb) | Mean reversion,<br> Implementation shortfall | CRSP stocks | Structural breaks |
| [1.6_quant_factors](1.6_quant_factors.ipynb) | Factor investing, <br> Backtesting | CRSP stocks, <br> Compustat, IBES | Cluster analysis |
| [1.7_event_study](1.7_event_study.ipynb) | Event studies | S&P key developments | Multiple testing, Fourier transforms and convolutions |
| [2.1_economic_indicators](2.1_economic_indicators.ipynb) | Economic data revisions, <br> Employment payrolls | ALFRED | Outlier detection |
| [2.2_regression_diagnostics](2.2_regression_diagnostics.ipynb) | Consumer and<br> producer prices | FRED | Linear regression diagnostics|
| [2.3_time_series](2.3_time_series.ipynb) | Industrial production<br> and inflation | FRED | Time series analysis |
| [2.4_approximate_factors](2.4_approximate_factors.ipynb) | Approximate factor models | FRED-MD | Unit root test, <br>EM Algorithm |
| [2.5_economic_states](2.5_economic_states.ipynb) | State space models | FRED-MD |  Gaussian mixture, <br>hidden Markov models |
| [3.1_term_structure](3.1_term_structure.ipynb) | Interest rates | FRED yield curve | Low-rank approximation |
| [3.2_bond_returns](3.2_bond_returns.ipynb) | Bonds risk factors | FRED bond returns | Principal component analysis |
| [3.3_options_pricing](3.3_options_pricing.ipynb) | Binomial tree, <br> Black-Scholes-Merton | simulated | Monte Carlo simulations |
| [3.4_value_at_risk](3.4_value_at_risk.ipynb) | Value-at-risk | FRED crypto-currencies | Conditional volatility |
| [3.5_covariance_matrix](3.5_covariance_matrix.ipynb) | Portfolio risk | Fama-French industries | Covariance matrix estimation |
| [3.6_market_microstructure](3.6_market_microstructure.ipynb) | Market liquidity | TAQ tick data | High frequency volatility |
| [3.7_event_risk](3.7_event_risk.ipynb) | Earnings expectations | IBES | Poisson regression, <br> generalized linear model |
| [4.1_network_graphs](4.1_network_graphs.ipynb) | Supply chain | Compustat principal customers | Network graphs |
| [4.2_community_detection](4.2_community_detection.ipynb) | Industry taxonomy | Hoberg-Phillips | Community detection |
| [4.3_graph_centrality](4.3_graph_centrality.ipynb) | Input-output uses | Bureau of Economic Analysis | Graph centrality |
| [4.4_link_prediction](4.4_link_prediction.ipynb) | Product markets |  Hoberg-Phillips | Link prediction |
| [4.5_spatial_regression](4.5_spatial_regression.ipynb) | Earnings surprises | IBES, Hoberg-Phillips | Spatial regression |
| [5.1_fomc_topics](5.1_fomc_topics.ipynb) | FOMC meetings | Federal Reserve | Topic modeling |
| [5.2_management_sentiment](5.2_management_sentiment.ipynb) | Management discussions | SEC Edgar, <br> Loughran-Macdonald | Sentiment analysis |
| [5.3_business_textual](5.3_business_textual.ipynb) | Business descriptions | SEC Edgar | Part-of-speech,  <br> Density-based clustering |
| [6.1_classification_models](6.1_classification_models.ipynb) | Industry classification | SEC Edgar | Classification |
| [6.2_regression_models](6.2_regression_models.ipynb) | Macroeconomic forecasts | FRED-MD | Regression |
| [6.3_deep_learning](6.3_deep_learning.ipynb) | Industry classification | SEC Edgar | Neural networks, <br> word embeddings |
| [6.4_convolutional_net](6.4_convolutional_net.ipynb) | Macroeconomic forecasts | FRED-MD | Convolutional neural nets, <br>vector autoregression |
| [6.5_recurrent_net](6.5_recurrent_net.ipynb) | Macroeconomic forecasts | FRED-MD | Recurrent neural nets, <br>dynamic factor models |
| [6.6_reinforcement_learning](6.6_reinforcement_learning.ipynb) | Retirement spending | SBBI | Reinforcement learning |
| [6.7_language_modeling](6.7_language_modeling.ipynb) | Fedspeak | Federal Reserve | Language modeling, <br> Transformers |
| [7.1_large_language_models](7.1_large_language_models.ipynb) | Market risk disclosures | SEC Edgar | Text summarization |
| [7.2_llm_finetuning](7.2_llm_finetuning.ipynb) | Industry classification | SEC Edgar | LLM fine-tuning |
| [7.3_llm_prompting](7.3_llm_prompting.ipynb) | Financial news sentiment | Kaggle | Prompt engineering |
| [7.4_llm_agents](7.4_llm_agents.ipynb) | Corporate philanthropy | [MVCP textbook](https://www.semanticscholar.org/paper/Measuring-the-Value-of-Corporate-Philanthropy:-and-Lim/261c6ac48cf26bdca49832a6c4812d97569b7065) | Multi-agents, chatbots,<br> retrieval-augmented generation |


## Documentation

- [Financial Data Science Notebooks](https://terence-lim.github.io/docs/financial-data-science-notebooks/)

- [Download PDF](https://terence-lim.github.io/docs/financial-data-science-notebooks.pdf)

- [FinDS API reference](https://terence-lim.github.io/docs/financial-data-science/)


## Github repos

- [FinDS package](https://github.com/terence-lim/financial-data-science)

- [Jupyter notebooks](https://github.com/terence-lim/financial-data-science-notebooks)


## Contact

[https://terence-lim.github.io](https://terence-lim.github.io)
