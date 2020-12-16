Exercise 2.7
=======

Show that the sum in Equation (2.7) reduces to <img src="https://latex.codecogs.com/svg.latex?\sigma=np(1-p)" />. *Hint*: Define <img src="https://latex.codecogs.com/svg.latex?y=x-1" /> and <img src="https://latex.codecogs.com/svg.latex?m=n-1" /> and use the results of Exercise 2.5.
-----------

There is a solution for this exercise available on [Prob(a)bilistic World](https://www.probabilisticworld.com/binomial-distribution-mean-variance-formulas-proof/) website [Posted on May 19, 2020].

Variance of binomial distributions derivation:
-----------

Here's an alternative variance formula:

<img src="https://latex.codecogs.com/svg.latex?\sigma^2=\left<x^2\right>-\mu^2" />

First, we can plug <img src="https://latex.codecogs.com/svg.latex?\mu^2=(np)^2" /> to get:

<img src="https://latex.codecogs.com/svg.latex?\sigma^2=\left<x^2\right>-(np)^2" />

Using the binomial probability mass function, the expected value is equal to:

<img src="https://latex.codecogs.com/svg.latex?\left<x^2\right>=\sum_{x=0}^nx^2\cdot\left(\begin{array}{c}n\\x\end{array}\right)p^x(1-p)^{n-x}" />

Then we take out the contant term <img src="https://latex.codecogs.com/svg.latex?n" /> of the sum operator:

<img src="https://latex.codecogs.com/svg.latex?\left<x^2\right>=n\cdot\sum_{x=0}^nx\cdot\left(\begin{array}{c}n-1\\x-1\end{array}\right)p^x(1-p)^{n-x}" />

Next, let's use the <img src="https://latex.codecogs.com/svg.latex?p^x=p\cdotp^{x-1}" /> identity to rewrite this as:

<img src="https://latex.codecogs.com/svg.latex?\left<x^2\right>=np\cdot\sum_{x=0}^nx\cdot\left(\begin{array}{c}n-1\\x-1\end{array}\right)p^{x-1}(1-p)^{n-x}" />

Finally:

<img src="https://latex.codecogs.com/svg.latex?\left<x^2\right>=np\cdot\sum_{x=0}^nx\cdot\left(\begin{array}{c}n-1\\x-1\end{array}\right)p^{x-1}(1-p)^{(n-1)-(x-1)}" />

Simplifying the sum
-----------

Define <img src="https://latex.codecogs.com/svg.latex?y=x-1" /> and <img src="https://latex.codecogs.com/svg.latex?m=n-1" />:

<img src="https://latex.codecogs.com/svg.latex?\sum_{x=0}^n(y+1)\cdot\left(\begin{array}{c}m\\y\end{array}\right)p^{y}(1-p)^{m-y}" />

Slipt the sum into two sums:

<img src="https://latex.codecogs.com/svg.latex?=\sum_{x=0}^ny\cdot\left(\begin{array}{c}m\\y\end{array}\right)p^{y}(1-p)^{m-y}+\sum_{x=0}^n\left(\begin{array}{c}m\\y\end{array}\right)p^{y}(1-p)^{m-y}" />

These individual sums represents *the expected value*:

<img src="https://latex.codecogs.com/svg.latex?\sum_{x=0}^ny\cdot\left(\begin{array}{c}m\\y\end{array}\right)p^{y}(1-p)^{m-y}=mp=(n-1)p" />

and *the sum of probabilities* of a binomial distribution:

<img src="https://latex.codecogs.com/svg.latex?\sum_{x=0}^n\left(\begin{array}{c}m\\y\end{array}\right)p^{y}(1-p)^{m-y}=1" />

Therefore, the final sum reduces to:

<img src="https://latex.codecogs.com/svg.latex?\sum_{x=0}^n(y+1)\cdot\left(\begin{array}{c}m\\y\end{array}\right)p^{y}(1-p)^{m-y}=(n-1)p+1" />

The final proof
-----------

Let's write this into the full expression for <img src="https://latex.codecogs.com/svg.latex?\left<x^2\right>" />:

<img src="https://latex.codecogs.com/svg.latex?\left<x^2\right>=np\cdot\sum_{x=0}^nx\cdot\left(\begin{array}{c}n-1\\x-1\end{array}\right)p^{x-1}(1-p)^{n-x}" />

<img src="https://latex.codecogs.com/svg.latex?=np\cdot((n-1)p+1)=(np)^2-np^2+np" />

<img src="https://latex.codecogs.com/svg.latex?=(np)^2+np(1-p)" />

Then, by definition:

<img src="https://latex.codecogs.com/svg.latex?\sigma^2=\left<x^2\right>-(np)^2" />

Therefore, we can now get the prove:

<img src="https://latex.codecogs.com/svg.latex?\sigma^2=(np)^2+np(1-p)-(np)^2=np(1-p)" />
