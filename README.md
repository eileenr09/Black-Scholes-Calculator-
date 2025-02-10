# HackHers 2025: Black-Scholes-Calculator

**Introduction:**
This Black-Scholes Option Pricing Model is a crucial tool in financial derivatives trading. It shows the priced options, computed Greeks, analyzes sensitivities and visualizes the results.


**What it does:**
This Options Pricing Model is used to determine the theoretical price of European-styled options. This is primarily used for pricing options contracts, which are financial instruments that give the holder the right (but not the obligation) to buy or sell an asset at a predetermined price within a specific time frame.

In this model, we use the “Greeks” (Delta, Gamma, Theta, Vega), which are risk measures used by options traders, helping them understand the options price with respect to various factors.

**Delta:** Measures the rate of change in the option price with respect to the underlying asset’s price.

**Gamma:** Represents the rate of change in Delta with respect to the underlying asset’s price.
Some may ask why we need Gamma if it's related to Delta. It’s the same reason why we have acceleration even though velocity already exists. Even though they are related, they both help us determine different scenarios. Delta is defined as the first derivative (rate of change), and Gamma is the second derivative (the rate of change of the rate of change). 

**Theta:** Shows the rate of change in the option price with respect to time. How does time decay affect the option price?
**Vega:** Indicated the rate of change in the option price with respect to the volatility.

Implied Volatility can be determined when given a market price. This is crucial for understanding market expectations of future volatility.

The Sensitivity Analysis provides a table showing how the option price changes with different levels of volatility and time to expiration. This helps the trader assess the option’s behavior under various market conditions.
