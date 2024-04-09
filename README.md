The goal of this project was to price options using the Black Scholes Model.

First off, we calculate the call and put of the option using d1,d2,N(d1), and N(d2).

We observe that the price of the put is higher than the call due to the fact that the strike is higher than the price of the stock therefore the put is already in the money.

Then we calculate the Greeks to see the change in price of the option whenever the price of the underlying asset moves or when the risk-free rate or time to maturity changes.

Theta measures the time decay, the value of the option lost after each day passes.

Vega measures the effect of a change in volatility.

Delta measures the effect of a change in the price of the underlying asset same as gamma.

Then finally rho measures the effect of a change in the risk-free rate on the price of the options.
