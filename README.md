## Projects

Three projects on decisions under uncertainty: solving a game, testing trading strategies, and turning demand forecasts into inventory decisions.

### [PokerLab](https://github.com/N1rvana777/pokerlab)
A heads-up no-limit hold'em postflop solver workbench in Rust and Python. It solves flop, turn and river spots with DCFR, builds opponent models from behavioural traits, node locks and player profiles, and computes exploitative best responses against a fixed opponent strategy. Results are checked against linear-programming and closed-form references. Built on the open-source postflop-solver engine (AGPL-3.0). It also includes paused research on heads-up PLO.

### [CryptoLab](https://github.com/N1rvana777/cryptolab)
Systematic strategy research for crypto perpetual swaps: Donchian trend following and gradient-boosted quantile models on 138 features, walk-forward validation with an embargo, fractional Kelly sizing, and a strict holdout protocol. No strategy survived the final holdout, and the research log records how the earlier positive results fell apart.

### [RetailLab](https://github.com/N1rvana777/retaillab)
Demand forecasting and replenishment for a regional supermarket chain. LightGBM quantile forecasts of daily store-SKU demand feed a newsvendor order rule, with censored-demand estimation and a leakage audit. The partner's data is not included.
