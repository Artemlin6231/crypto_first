This repository represents a solution for the Kaggle competition from G-Research [G-Research Crypto Forecasting](https://www.kaggle.com/competitions/g-research-crypto-forecasting/overview).

**Solution provided by:** Artem Podvalny

Pearson correlation was improved from 0.009485 to 0.41.

<sub>The original competition used an API for submission, which is now outdated.</sub>

The LightGBM model was used.

Four types of features were added: Temporal, Return & Volatility, Candle Pattern, and Cross-Asset Features.

The most influential among them was `Close_log55`, which shows the influence of the medium-term price.
