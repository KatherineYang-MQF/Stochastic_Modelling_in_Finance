Introduction: This is a course project, which consists of 4 parts. 

Contents: Theoretical basis is option valuation-related models: Black-Scholes model, Displaced-Diffusion model, SABR model, and Brownian motion.
Python-related methods include interpolate, brentq, fsolve, least_squares, and plotting.

Programming Language: Python

Part 1: Analytical option formulae

Define vanilla European call and put options under 4 models: Black-Scholes model, Bachelier model, Black76 model, and Displaced-Diffusion model.

Part 2: Model calibration

First, use interpolate method to generate risk-free rate. Based on market strike price, use brentq or fsolve methold to generate implied volatility from Black-Scholes model. Second, match volatilities from Displaced-Diffusion model against market implied volatilities. Use least_squares method to calibrate Displaced-Diffusion model, and obtain the only unknown parameter. Third, calibrate SABR model against market implied volatitilities, and obtain three unknown parameters. Fourth, plot volatility smile of market, Displaced-Diffusion model, and SABR model. Fifth, go the extra miles. Adjust parameters of both models and observe the changes of volatility smile.

Part 3: Static replication

Based on derived formulae, define valuation of a derivative contract,

Part 4: Dynamic hedging

Suppose we sell an ATM call option, hedge 21 or 84 times within a month. First, define Brownian motion to generate stock prices for each timestamp. Second, based on given hedging formulae, define hedging error and plot histogram for 21 times and 84 times hedging strategies respectively.
