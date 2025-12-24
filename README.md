# options-pricing
Abstract:

This project develops a coherent and mathematically rigorous framework for pricing European
and American vanilla options using the Black-Scholes model, dependent upon an underlying
asset which follows a geometric Brownian motion in the risk-neutral measure. Starting from just
an arbitrage-free, self-financing trading strategy, we derive the Black-Scholes partial differential
equation for European options and formulate the American option price as a variational inequality
tied to an optimal stopping problem. For European claims, we find the closed-form prices under
the Black-Scholes-Merton model, analytic Greek sensitivities, and implied volatility from Newton’s
method with a bisection fallback, whilst also handling asymptotic behaviour. For American
claims, we discretise the variational inequality to create a linear complementarity problem and
analyse the Crank-Nicolson finite difference scheme with Rannacher time-stepping to ensure
unconditional stability and thorough handling of oscillations at payoff kinks. The scheme is
solved by the well-posed projected successive over-relaxation method. The accompanying Python
code is an illustration of how the theoretical results in this paper can be translated into working
numerical code.

