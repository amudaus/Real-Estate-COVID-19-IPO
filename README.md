# Real-Estate-COVID-19-IPO

📚 Project Overview

This project explores how macroeconomic factors, technology trends, and the COVID-19 pandemic influenced real estate price movements in major U.S. tech hub cities between 2019 and 2024. Using public data sources and econometric modeling, we analyzed whether tech activity and pandemic-related disruptions significantly explain changes in the housing market.

- We conducted an event study utilizing datasets from:

- Federal Housing Finance Agency (FHFA)

- Federal Reserve Economic Data (FRED)

- Yahoo Finance


⚙️ Setup

All models are based on Ordinary Least Squares (OLS) regression.

All variables are in percentage change form and have passed the Augmented Dickey-Fuller (ADF) test at a 5% significance level, indicating stationarity.

Model evaluation is based on Adjusted R² values.

Our focus is on exploring simultaneous relationships (correlations), not forecasting. Thus, the information set is aligned at time t (not lagged by t-1).


🧠 Research Questions

We structured our study around four key arguments:

1. Does adding COVID variables to macroeconomic variables improve model performance?
(Model 1-1 to 1-2)

2. Does adding tech-related variables further improve model performance beyond macroeconomic and COVID variables?
(Model 2-1 to 2-2)

3. Does the model perform better when cities are classified as "tech" vs. "non-tech" hubs?
(Model 3-1 to 3-3)

4. Does model performance change when comparing pre-COVID, during-COVID, and post-COVID periods?
(Model 4)


📊 Key Findings

- Adding COVID variables alone did not improve explanatory power (Adjusted R² dropped from 0.1429 to 0.1344).

- Adding tech variables improved the model's performance, with Adjusted R² increasing (0.1429 to 0.1561 without COVID variables; 0.1344 to 0.1423 when COVID variables included).

- Tech cities saw better model performance than non-tech cities, but improvements were only partial.

- Pre- and post-COVID periods showed significant increases in model performance when tech factors were added (Adjusted R² rose from 0.2161 to 0.4005 pre-COVID, and from 0.6790 to 0.8125 post-COVID).

- Inflation consistently appeared as a significant explanatory variable across all models.

- Tech IPO activity generally had a positive effect on real estate prices, while Tech IPO percentage and total IPO volume showed negative relationships.

- Real estate prices dropped significantly during COVID but demonstrated strong recovery in the post-COVID period.

⚡ Limitations

- Small sample size, limiting generalizability.

- Low statistical significance for many variables across different models.
