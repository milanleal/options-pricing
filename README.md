# options-pricing
Jupyter notebooks for vanilla options under geometric Brownian motion in the risk-neutral measure.

European options: Black-Scholes prices with comparison to Monte Carlo prices with error analysis; analytic and finite difference Greeks; implied volatility via Newton's method with bisection fallback; no-arbitrage checks and model validation through put-call parity and monotonicity and convexity in strike.

American options: LCP via Crank-Nicolson finite difference scheme with Rannacher startup; prices found through projected successive over-relaxation; finite difference Greeks; partitioning of continuation and exercise region with free boundary curve.
