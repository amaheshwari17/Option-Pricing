# Option-Pricing

Option Pricing Models are mathematical models that use certain variables to calculate the theoretical value of an option.

Call is an option contract that gives you the right, but not the obligation, to buy the underlying asset at a predetermined price before or at expiration day.
Put is an option contract that gives you the right, but not the obligation, to sell the underlying asset at a predetermined price before or at expiration day.

Options may also be classified according to their exercise time:
1. European style options may be exercised only at the expiration date.
2. American style options can be exercised anytime between purchase and expiration date.

<> Risk-neutral Probability

The risk-neutral probability is a theoretical probability of future outcomes adjusted for risk. There are two main assumptions behind this concept:
1. The current value of an asset is equal to its expected payoff discounted at the risk-free rate.
2. There are no arbitrage opportunities in the market.

The risk-neutral probability is the probability that the stock price would rise in a risk-neutral world. However, we neither assume that all the investors in the market are risk-neutral, nor the fact that risky assets will earn the risk-free rate of return. This theoretical value measures the probability of buying and selling the assets as if there was a single probability for everything in the market.

<> Binomial Option Pricing Model
The simplest method to price the options is to use a binomial option pricing model. This model uses the assumption of perfectly efficient markets. Under this assumption, the model can price the option at each point of a specified time frame.

Under the binomial model, we consider that the price of the underlying asset will either go up or down in the period. Given the possible prices of the underlying asset and the strike price of an option, we can calculate the payoff of the option under these scenarios, then discount these payoffs and find the value of that option as of today.

<> Black-Scholes-Merton Model
Assumptions:
1. Stock returns are lognormally distributed.
2. The risk free rate is known and stays constant during the option term.
3. The stock’s volatility is known and stays constant during the option term.
4. Transaction costs are omitted from the model.
5. Dividends are excluded.
6. The options cannot be exercised until expiration (i.e. the option is European).

Weaknesses in BSM Assumptions:
1. It is good for candidates to understand that BSM is not without its flaws; it is after all a theoretical model.
2. The risk free rate is not always “known” and may not stay constant for the option’s life; further an investor is unlikely to be able to borrow at the risk free rate.
3. A stock’s volatility is not likely to remain constant over the life of the option.
4. In reality, investors face transaction costs.
5. Many stocks pay dividends.
6. The investor may be trading American options and not European style options.
