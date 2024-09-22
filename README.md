# Stochastics and Finance


## LSTM and Geometric Brownian Motion

1. Simulate stock prices using Geometric Brownian Motion
2. Use recurrent neural networks (LSTM model) to learn the data and make predictions

## Black Scholes formula and Monte Carlo Simulation

1. Illustration of the Black Scholes formula in the option pricing
2. Compare with the Monte Carlo Simulation

## Linear Regression and Capital Asset Pricing Model (CAPM)
CAPM is a a finiancial model that simply says the expected return of an asset depend linearly on the market. Despite its simplicity, it is widely used throughout finance for pricing risky securities and generating expected returns for assets. 

Let $R_i$, $R_m$, $R_f$ be the expected return of an asset, the market and the risk-free asset. The CAPM stipulates the following
```math
\frac{E\left(R_i\right)-R_f}{\beta_i}=E\left(R_m\right)-R_f
```

$R_f$ is usually a government bond. $R_m$ is often estimated from a major stock index, like the S&P 500. To estimate $\beta_i$, we can perform a linear regression on the past data.
