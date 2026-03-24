(WiP)

# Conditional Copula VaR Model

A sophisticated Value at Risk (VaR) implementation using conditional copula methods for modeling time-varying dependence structures between financial assets, with particular focus on extreme market conditions and tail risk.

Traditional VaR models often fail to capture the complex dynamics of financial markets during crises. This project implements a conditional copula approach that addresses these limitations by:

- Modeling time-varying correlations between assets
- Capturing nonlinear and asymmetric dependence structures
- Accounting for tail dependence (joint extreme events)
- Incorporating volatility clustering and dependence dynamics

Key Features

- **Dynamic Dependence Structure**: Copula parameters evolve over time based on market conditions
- **Flexible Marginal Models**: Support for various GARCH-family models (GARCH, EGARCH, GJR-GARCH)
- **Multiple Copula Types**: Gaussian, Student-t, Clayton, Gumbel, and rotated variants
- **Observation-Driven Parameters**: GARCH-style updating of copula parameters
- **Comprehensive VaR Estimation**: Full simulation-based VaR calculation pipeline
- **Backtesting Capabilities**: Model validation using various statistical tests

