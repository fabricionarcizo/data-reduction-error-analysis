Exercise 2.12
=======

Shows that the sum in Equation (2.9) reduces to <img src="https://latex.codecogs.com/svg.latex?\sigma^2=\mu" />. *Hint*: Use Equation (2.18) to simplify the expression. Define <img src="https://latex.codecogs.com/svg.latex?y=x-1" /> and show that the sum reduces to <img src="https://latex.codecogs.com/svg.latex?\mu\left<y+1\right>=\mu^2" />.
-----------

There is a solution for this exercise available on [jbstatistics](https://www.youtube.com/watch?v=65n_v92JZeE) YouTube channel [Posted on July 27, 2013].

Mean of Poisson distribution derivation:
-----------

Given the Poisson distribution formula:

<img src="https://latex.codecogs.com/svg.latex?P_p(x;\mu)\equiv\frac{\mu^x}{x!}e^{-\mu}" />


We will need the series of expansion of <img src="https://latex.codecogs.com/svg.latex?a" /> raised to the <img src="https://latex.codecogs.com/svg.latex?\mu" />:

<img src="https://latex.codecogs.com/svg.latex?e^\mu=\sum_{y=0}^{\infty}\frac{\mu^y}{y!}" />

The expectation of a discrete random variable <img src="https://latex.codecogs.com/svg.latex?X" /> is:

<img src="https://latex.codecogs.com/svg.latex?\left<x\right>=\sum_{x=0}^{\infty}x\frac{\mu^x}{x!}e^{-\mu}" />

First, we take out the contant term <img src="https://latex.codecogs.com/svg.latex?e^{-\mu}" /> of the sum operator:

<img src="https://latex.codecogs.com/svg.latex?\left<x\right>=e^{-\mu}\sum_{x=0}^{\infty}x\frac{\mu^x}{x!}" />

Then, change the lower limit of summation to <img src="https://latex.codecogs.com/svg.latex?1" /> and cancel the <img src="https://latex.codecogs.com/svg.latex?x" /> :

<img src="https://latex.codecogs.com/svg.latex?\left<x\right>=e^{-\mu}\sum_{x=1}^{\infty}x\frac{\mu^x}{x!}=e^{-\mu}\sum_{x=1}^{\infty}\frac{\mu^x}{(x-1)!}" />

Let's take a single <img src="https://latex.codecogs.com/svg.latex?\mu" /> out of the equation to have both <img src="https://latex.codecogs.com/svg.latex?x" /> with the same value (i.e., <img src="https://latex.codecogs.com/svg.latex?-1" />):

<img src="https://latex.codecogs.com/svg.latex?\left<x\right>=\mu{e^{-\mu}}\sum_{x=1}^{\infty}\frac{\mu^{x-1}}{(x-1)!}" />

To make the series expansion of e to the mean clearer, let's assume <img src="https://latex.codecogs.com/svg.latex?y=x-1" />:

<img src="https://latex.codecogs.com/svg.latex?\left<x\right>=\mu{e^{-\mu}}\sum_{y=0}^{\infty}\frac{\mu^{y}}{y!}" />

Finally, the expectation of a Poisson random variable is:

<img src="https://latex.codecogs.com/svg.latex?\left<x\right>=\mu{e^{-\mu}}e^{\mu}=\mu{e^{-\mu+\mu}}=\mu{e^0}=\mu" />

Variance of Poisson distribution derivation:
-----------

The variance of a random variable <img src="https://latex.codecogs.com/svg.latex?X" /> is defined as:

<img src="https://latex.codecogs.com/svg.latex?\sigma^2=\left<x^2\right>-\mu^2" />

Using the Poisson probability mass function, the expected value is equal to:

<img src="https://latex.codecogs.com/svg.latex?\left<x^2\right>=\sum_{x=0}^\infty{x^2}\frac{\mu^x}{x!}e^{-\mu}" />

First, we are going to find the expectation of <img src="https://latex.codecogs.com/svg.latex?X(X-1)" />:

<img src="https://latex.codecogs.com/svg.latex?\left<x(x-1)\right>=\sum_{x=0}^\infty{x(x-1)}\frac{\mu^x}{x!}e^{-\mu}" />

Let's take out the contant term <img src="https://latex.codecogs.com/svg.latex?e^{-\mu}" /> of the sum operator:

<img src="https://latex.codecogs.com/svg.latex?\left<x(x-1)\right>=e^{-\mu}\sum_{x=0}^{\infty}x(x-1)\frac{\mu^x}{x!}" />

Then, change the lower limit of summation to <img src="https://latex.codecogs.com/svg.latex?2" /> and cancel the <img src="https://latex.codecogs.com/svg.latex?x" /> :

<img src="https://latex.codecogs.com/svg.latex?\left<x(x-1)\right>=e^{-\mu}\sum_{x=2}^{\infty}x(x-1)\frac{\mu^x}{x!}=e^{-\mu}\sum_{x=2}^{\infty}\frac{\mu^x}{(x-2)!}" />

Let's take a single <img src="https://latex.codecogs.com/svg.latex?\mu" /> out of the equation to have both <img src="https://latex.codecogs.com/svg.latex?x" /> with the same value (i.e., <img src="https://latex.codecogs.com/svg.latex?-2" />):

<img src="https://latex.codecogs.com/svg.latex?\left<x(x-1)\right>=\mu^2e^{-\mu}\sum_{x=2}^{\infty}\frac{\mu^{x-2}}{(x-2)!}" />

To make the series expansion of e to the mean clearer, let's assume <img src="https://latex.codecogs.com/svg.latex?y=x-2" />:

<img src="https://latex.codecogs.com/svg.latex?\left<x(x-1)\right>=\mu^2e^{-\mu}\sum_{y=0}^{\infty}\frac{\mu^{y}}{y!}" />

Finally, the expectation of a Poisson random variable is:

<img src="https://latex.codecogs.com/svg.latex?\left<x(x-1)\right>=\mu^2e^{-\mu}e^{\mu}=\mu^2e^{-\mu+\mu}=\mu^2e^0=\mu^2" /><br />

<img src="https://latex.codecogs.com/svg.latex?\left<x(x-1)\right>=\mu^2" /><br />

<img src="https://latex.codecogs.com/svg.latex?\left<x^2\right>-\left<x\right>=\mu^2" /><br />

<img src="https://latex.codecogs.com/svg.latex?\left<x^2\right>-\mu=\mu^2" /><br />

<img src="https://latex.codecogs.com/svg.latex?\left<x^2\right>=\mu^2+\mu" /><br />

The final prove:

<img src="https://latex.codecogs.com/svg.latex?\sigma^2=\left<x^2\right>-\mu^2=\mu^2+\mu-\mu^2=\mu" />
