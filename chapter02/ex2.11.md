Exercise 2.11
=======

Verify that, for the Poisson distribution, if <img src="https://latex.codecogs.com/svg.latex?\mu" /> is an integer, the probability for <img src="https://latex.codecogs.com/svg.latex?x=\mu" /> is equal to the probability for <img src="https://latex.codecogs.com/svg.latex?x=\mu-1" />, <img src="https://latex.codecogs.com/svg.latex?P_p(\mu; \mu)=P_p(\mu - 1; \mu)" />.
-----------

Given the Poisson distribution formula:

<img src="https://latex.codecogs.com/svg.latex?P_p(x; \mu) \equiv \frac{\mu^x}{x!}e^{-\mu}" />

Considerer <img src="https://latex.codecogs.com/svg.latex?x=\mu-1" />:

<img src="https://latex.codecogs.com/svg.latex?P_p(\mu-1; \mu) \equiv \frac{e^{-\mu} \cdot \mu^{\mu-1}}{(\mu-1)!} \equiv \frac{e^{-\mu} \cdot \mu^{\mu}}{(\mu-1)!} \cdot \frac{1}{\mu} \equiv \frac{e^{-\mu} \cdot \mu^{\mu}}{\mu!}" />

Finally:

<img src="https://latex.codecogs.com/svg.latex?P_p(\mu; \mu) \equiv \frac{\mu^{\mu}}{\mu!}e^{-\mu}" />
