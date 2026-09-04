# Deep Research Library — NAS100 / US30 / GOLD (XAUUSD)

55 open-access papers, downloaded 4 Sep 2026. Sorted into 7 folders.
Every direct PDF link is below, so you can re-download anything individually.

---

## 01_GOLD_XAUUSD — 10 papers

Price prediction:
- Achilles: LSTM + FinBERT gold-vs-USD bot, minute-by-minute — https://arxiv.org/pdf/2410.21291
- Gold Price Prediction, LSTM+MLP + Grey Wolf Optimizer (claims 171% / 3 months, demo account) — https://arxiv.org/pdf/2512.22606
- Predicting Gold Price Using Hybrid Models (ARIMA + regression + ANN) — https://arxiv.org/pdf/2505.01402
- Neural Networks for Intraday Trading in the Gold Market — 1-min XAUUSD, CNN vs LSTM — https://www.scitepress.org/Papers/2023/117944/117944.pdf
- Predicting XAU-USD Forex Prices Using Machine Learning — https://bengielynmae.github.io/files/forex-paper.pdf
- Gold Price Prediction Using Machine Learning (RF / DT / SVM / KNN) — https://www.irjmets.com/uploadedfiles/paper/issue_4_april_2025/72502/final/fin_irjmets1744806228.pdf
- Forecasting Gold Prices Using Temporal Convolutional Networks — https://ceur-ws.org/Vol-3105/paper18.pdf

Macro drivers — why gold moves (more useful than most price models):
- Measuring the Response of Gold Prices to Uncertainty: hedge & safe-haven, quantile-on-quantile — https://arxiv.org/pdf/1806.07623
- VIX, Gold, Silver and Oil: How Commodities React to Financial Market Volatility — http://www.na-businesspress.com/jaf/jubinskid_web13_1_.pdf
- Forecasting Commodity Price Shocks: temporal + semantic fusion with agentic GenAI news — https://arxiv.org/pdf/2508.06497

## 02_NAS100_US30_INDICES — 6 papers
- Beyond Trend Following: deep learning drawdown-risk indicator built on NASDAQ-100 — https://arxiv.org/pdf/2407.13685
- QuantAgent: multi-agent LLM HFT, tested on Nasdaq futures at 1h and 4h — https://arxiv.org/pdf/2509.09995
- Generating Alpha: hybrid AI system benchmarked vs NASDAQ-100 and Dow Jones — https://arxiv.org/pdf/2601.19504
- A Machine Learning Approach to Volatility Forecasting — Dow Jones constituents, beats HAR — https://arxiv.org/pdf/2601.13014
- Inferring Latent Market Forces: gamma exposure, 0DTE and dealer hedging — https://arxiv.org/pdf/2512.17923
- Algorithmic Trading Strategy Development & Optimisation (S&P 500 + FinBERT) — https://arxiv.org/pdf/2603.15848

## 03_ORDERFLOW_EXECUTION — 13 papers
The microstructure layer. This is where intraday NAS100/US30 edge actually lives.
- DeepLOB: CNN + LSTM on limit order books (the canonical paper) — https://arxiv.org/pdf/1808.03668
- BDLOB: Bayesian deep CNNs for limit order books — https://arxiv.org/pdf/1811.10041
- Deep Limit Order Book Forecasting (NASDAQ stocks, LOBFrame; shows high accuracy != tradable) — https://arxiv.org/pdf/2403.09267
- Deep Learning with Stationary LOB Features — https://arxiv.org/pdf/1810.09965
- Efficient Deep Learning for LOB Price Movement (Siamese architecture) — https://arxiv.org/pdf/2505.22678
- DeepFolio: CNNs for portfolios with LOB data — https://arxiv.org/pdf/2008.12152
- Queue Imbalance as a One-Tick-Ahead Price Predictor — https://arxiv.org/pdf/1512.03492
- Returns and Order Flow Imbalances: S&P 500 E-mini futures, intraday + macro news — https://arxiv.org/pdf/2508.06788
- Forecasting High Frequency Order Flow Imbalance (Hawkes processes) — https://arxiv.org/pdf/2408.03594
- Neural Network + Order Flow + Technical Analysis: short-term futures direction (TabNet) — https://arxiv.org/pdf/2203.12457
- Intra-day Equity Price Prediction as a Measure of Market Efficiency (edge decayed after 2009) — https://arxiv.org/pdf/1908.08168
- Forecasting Intraday Volume with ML (VWAP execution) — https://arxiv.org/pdf/2505.08180
- Forecasting Directional Movements with LSTM & Random Forests — https://arxiv.org/pdf/2004.10178

## 04_TREND_MOMENTUM — 7 papers
Directly relevant to swing-trading indices and gold on futures.
- Two Centuries of Trend Following (the long-horizon evidence base) — https://arxiv.org/pdf/1404.3274
- Enhancing Time Series Momentum Using Deep Neural Networks (Deep Momentum Networks) — https://arxiv.org/pdf/1904.04912
- Slow Momentum with Fast Reversion: deep learning + changepoint detection — https://arxiv.org/pdf/2105.13727
- Trend-Following via Dynamic Momentum Learning (56 futures, +52% Sharpe vs naive) — https://arxiv.org/pdf/2106.08420
- Time-Series Momentum Portfolios with Deep Multi-Task Learning — https://arxiv.org/pdf/2306.13661
- Few-Shot Learning Patterns in Financial Time-Series for Trend Following — https://arxiv.org/pdf/2310.10500
- Follow the Leader: Systematic Trend Following Using Network Momentum — https://arxiv.org/pdf/2501.07135

## 05_VOLATILITY_MACRO — 4 papers
Regime and news-day filters — when to size up and when to stand aside.
- Improving S&P 500 Volatility Forecasting through Regime-Switching Methods — https://arxiv.org/pdf/2510.03236
- Options-Driven Realized Volatility Forecasting via Rough Heston — https://arxiv.org/pdf/2604.02743
- FOMC Announcements and Market Network Structure (spectral graph) — https://arxiv.org/pdf/2510.02705
- Forecasting U.S. Equity Volatility with Attention and Sentiment to the Economy — https://arxiv.org/pdf/2503.19767

## 06_RL_STRATEGY_ENGINES — 8 papers
- Deep Reinforcement Learning for Trading — 50 liquid futures, Oxford-Man — https://arxiv.org/pdf/1911.10107
- An Application of Deep RL to Algorithmic Trading (TDQN) — https://arxiv.org/pdf/2004.06627
- FinRL: open-source DRL framework for automated trading — https://arxiv.org/pdf/2111.09395
- FinRL Contests: Benchmarking Data-Driven Financial RL — https://arxiv.org/pdf/2504.02281
- Deep RL for Optimal Trading with Partial Information — https://arxiv.org/pdf/2511.00190
- Deep Learning + Online Sentiment for High-Frequency Trading — https://arxiv.org/pdf/2309.16679
- From Deep Learning to LLMs: Survey of AI in Quantitative Investment — https://arxiv.org/pdf/2503.21422
- Algorithmic Aspects of Strategic Trading — https://arxiv.org/pdf/2502.07606

## 07_RISK_SIZING_VALIDATION — 7 papers
**Read this folder first.** It is the antidote to every headline return quoted above.
- The Deflated Sharpe Ratio (Bailey & Lopez de Prado) — corrects for selection bias across many backtests — https://www.davidhbailey.com/dhbpapers/deflated-sharpe.pdf
- Re-Examining Profitability of Technical Analysis with White's Reality Check — https://homepage.ntu.edu.tw/~ckuan/pdf/snoop01.pdf
- Technical Analysis and Discrete False Discovery Rate (21,000 rules, 12 markets) — https://arxiv.org/pdf/1811.06766
- Backtesting Trading Strategies with GAN to Avoid Overfitting — https://arxiv.org/pdf/2209.04895
- Sizing Strategies for Algorithmic Trading in Volatile Markets — https://arxiv.org/pdf/2309.09094
- Sizing the Risk: Kelly, VIX and Hybrid Approaches — https://arxiv.org/pdf/2508.16598
- Investment Sizing with Deep Learning Prediction Uncertainties (futures) — https://arxiv.org/pdf/2007.15982

---

## Suggested reading order
1. **07** — so you can judge everything else. Deflated Sharpe first.
2. **04** — trend/momentum is the best-evidenced systematic edge across indices and gold.
3. **03** — if you trade intraday NAS100/US30, this is the real mechanism layer.
4. **05** — regime and news filters.
5. **01 / 02** — asset-specific models.
6. **06** — only once you have a working baseline; RL amplifies bad data.

## Honest caveats
- Nothing here is a signal or a system you can switch on.
- Backtested and demo-account returns quoted in these papers are not live results; several are single-author preprints with no peer review.
- Papers 2403.09267 and 1908.08168 both explicitly find that high statistical accuracy did NOT translate into tradable profit. Take them seriously.
