# William Hetzinger

Quantitative finance and software engineering: derivatives pricing, volatility modelling, risk, and the systems that run them. Every project here is tested against analytic limits, published benchmarks or independent methods, and runs in CI.

Portfolio site: [willhetzinger.github.io](https://willhetzinger.github.io)

## Featured

### [quant-lab](https://github.com/wchetz13/quant-lab): quantitative finance projects, one per folder

| Project | Highlights |
|---|---|
| [Heston stochastic volatility](https://github.com/wchetz13/quant-lab/tree/main/heston) | Fourier pricing with the "little Heston trap" characteristic function; Andersen QE Monte Carlo agrees within 1 s.e. when the Feller condition is violated |
| [American options](https://github.com/wchetz13/quant-lab/tree/main/american-options) | Longstaff–Schwartz regression Monte Carlo as an out-of-sample lower bound; a Bermudan tree reproduces the original paper's Table 1 |
| [SVI volatility smiles](https://github.com/wchetz13/quant-lab/tree/main/svi) | Quasi-explicit calibration, Durrleman's butterfly condition, calendar checks, and the implied risk-neutral density |

### Engineering

| Repository | Highlights |
|---|---|
| [order-matching-engine](https://github.com/wchetz13/order-matching-engine) | TypeScript limit order book: price-time priority, IOC/FOK/market orders, amendments with exchange priority rules, event-sourced deterministic replay, HTTP API, ~2.3M orders/s |
| [derivatives-pricing-engine](https://github.com/wchetz13/derivatives-pricing-engine) | Typed Python pricing engine: Black–Scholes, binomial and Monte Carlo, with Greeks for every model; CLI, FastAPI service, Docker, CI |

### Earlier work

- [options-payoff-greeks](https://github.com/wchetz13/options-payoff-greeks): Black–Scholes Greeks and a safeguarded Newton implied volatility solver
- [monte-carlo-options-pricing](https://github.com/wchetz13/monte-carlo-options-pricing): Monte Carlo pricing under GBM with antithetic and control variates, validated against Black–Scholes
- [margin-returns-forecasting](https://github.com/wchetz13/margin-returns-forecasting): return, trend and volatility forecasting with ARIMA, Prophet and GARCH

## Toolkit

**Python:** NumPy, SciPy, pandas, pytest, Hypothesis, FastAPI · **TypeScript:** Node, Vitest, zod · **Practice:** strict typing, property-based tests, CI on every PR, reproducible results
