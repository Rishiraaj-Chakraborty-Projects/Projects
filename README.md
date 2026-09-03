# Rishiraaj Chakraborty Projects

This organization contains a collection of my finance projects, mainly written in C++.

I am mainly interested in **options pricing, merger arbitrage, and statistics**, and these projects are my way of exploring the mathematics and implementation behind them. Some of the projects also cover areas such as market microstructure, Monte Carlo simulation, and low-latency programming.

## Projects

### Welford's Method for Computing Variance

A numerically stable way to calculate statistics such as mean, variance, skewness, kurtosis, and covariance in a single pass through the data. The project also looks at why standard formulas can lose accuracy when working with large numbers.

### SPSC Ring Buffer

A lock-free single-producer, single-consumer ring buffer built for fast communication between two threads. The project focuses on atomic operations, memory ordering, and efficient data exchange.

### Binomial American Options

An implementation of the binomial tree model for pricing American options. It explores how option values are calculated through the tree and how the possibility of early exercise affects the price.

### Deal Probability From Options

An attempt to estimate the market-implied probability that a merger will close using option prices. The project uses the relationship between option prices and the distribution of future prices, with a focus on the option curve around the deal price.

### Limit Order Book

A price-level limit order book with order matching, cancellations, amendments, market orders, and microprice calculation. The project explores how orders interact inside a market and how the book can be represented and updated efficiently.

### Monte Carlo Variance Reduction

A Monte Carlo pricing project exploring techniques that reduce simulation noise and improve the accuracy of estimates without simply increasing the number of simulated paths.

## Areas of Interest

I am mainly interested in:

* **Options pricing**
* **Merger arbitrage**
* **Statistics and probability**


Each repository contains a more detailed explanation of the underlying idea, mathematics, implementation, and results.
