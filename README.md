# Introduction

For this project I have pulled stocks data for companies in the *tech sector*:

1. **Apple: AAPL**
2. **Microsoft: MSFT**
3. **Google: GOOG**

I wanted to investigate how three of the major companies of the tech sector would *correlate* with each other to see how they are affected by the macro environment.

Datasets are based on a **5 year period** to analyze their simple and log returns.

# Return Distributions

Analyzing their return's histograms, we can see that all of them have a *leptokurtic distribution*, which means that **they have more frequently extreme deviations** in their tails and are prone to a higher probability of *extreme outliers*.

*Apple (AAPL)* has a visible tail extending to **~0.15** which means that those were their *big rally days* in terms of returns.

For *Google (GOOG)* I see that it has the **widest spread** of all three, meaning that it's the most *volatile* of all.

# Descriptive Statistics

As we saw in the "Return Distributions" section, we can see that **Apple (AAPL)** kurtosis is notably high *(5.9 - 6.9)*, matching with our histogram extended fat tail to the right.

All **means** are very small *(~0.06 - 0.12%)* of daily returns, but *positive* in all three and consistent for all 5 years.

*Google (GOOG)* has the highest **standard deviation**, meaning that it is the most volatile of all three, matching with its histogram distribution.

# Correlation

Finally, we can see that they are *visibly correlated* to each other, so we expect them to move together with some degree: **a correlation in the 0.55 - 0.75 range confirms that it's meaningful but not extreme**.

**An important caveat** here is that, correlation measures the *strength* of linear relationship, not **causation**. *Apple (AAPL)* going up doesn't cause *Microsoft (MSFT)* to go up; they both react to the same macro environment.

# Closing Thoughts

Going through this project, I saw that effectively they correlate to each other because they are tech companies. However, from a **risk implication** point of view, I wouldn't recommend having a whole investing portfolio in tech companies, because strong movements of a macro environment will affect these three and our money invested.