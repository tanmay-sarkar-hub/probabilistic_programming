# Probabilistic Programming

**Probabilistic programming (PP)** is a programming paradigm in which probabilistic models are specified and inference for these models is performed automatically.
(Source: https://en.wikipedia.org/wiki/Probabilistic_programming)

> I will be using **PyMC3 package** to solve different problems using probabilistic programming framework.

To read more about PyMC3, please visit - https://docs.pymc.io/

### Some intuition on Bayesian statistics

- We always have some belief: Is this coin fair?

![image](example_data/head-tail.png)

- You toss the coin 5 times

![image](example_data/head.png)
![image](example_data/head.png)
![image](example_data/head.png)
![image](example_data/head.png)
![image](example_data/head.png)

- Is the coin fair?

##### Summary

- We start with some beliefs (Prior)
- We see evidence
- We update our beliefs (Posterior)
- Beliefs can be represented as probability distributions (we are not generally certain)
