# Quant Trading Templates

Python notebooks covering the core quantitative trading workflow, from signal generation and factor research to NLP-driven alpha, portfolio optimization and backtesting.

The projects were completed as part of Udacity's **AI for Trading Nanodegree** ([certificate](./AITNDcert.jpg)). Each folder contains the project notebook, helper code, unit tests and a `requirements.txt`.

## Projects

| # | Project | Topics |
|---|---------|--------|
| 1 | [Trading with Momentum](./Project%201%3A%20%20Trading%20with%20Momentum) | Momentum signals, return calculation, long/short portfolio formation, t-tests on alpha |
| 2 | [Breakout Strategy](./Project%202%3A%20%20Breakout%20Strategy) | Rolling highs/lows, breakout signals, lookahead bias, signal filtering |
| 3 | [Smart Beta and Portfolio Optimization](./Project%203%3A%20%20Smart%20Beta%20and%20Portfolio%20Optimization) | Dividend-weighted smart beta, tracking error, convex optimization, rebalancing costs |
| 4 | [Alpha Research and Factor Modeling](./Project%204%3A%20%20Alpha%20Research%20and%20Factor%20Modeling) | Statistical risk models (PCA), alpha factors, factor evaluation, optimization with constraints |
| 5 | [NLP Analysis of Financial Statements](./Project%205%3A%20%20NLP%20Analysis%20of%20Financial%20Statements) | 10-K parsing, sentiment word lists, TF-IDF, cosine/Jaccard similarity as alpha factors |
| 6 | [Sentiment Analysis with Neural Networks](./Project%206%3A%20Sentiment%20Analysis%20with%20Neural%20Networks) | Text preprocessing, embeddings, LSTM sentiment classifier in PyTorch |
| 7 | [Combining Signals for Alpha](./Project%207%3A%20%20Combining%20Signals%20for%20Alpha) | Feature engineering, random forests, non-overlapping samples, alpha combination |
| 8 | [Backtesting](./Project%208%3A%20Backtesting) | Multi-factor risk model, optimization with transaction costs, performance attribution |

## Running the notebooks

```bash
cd "Project 1:  Trading with Momentum"
pip install -r requirements.txt
jupyter notebook
```

Some projects use datasets provided through the Udacity workspace, and those datasets are not included here.

## Tech stack

Python · pandas · NumPy · SciPy · scikit-learn · cvxpy · PyTorch · NLTK · Jupyter

## License

My own code and solutions in this repo are released under the [MIT License](./LICENSE). Starter code, helper modules, unit tests and project materials provided by Udacity remain the property of Udacity and are not covered by this license.
