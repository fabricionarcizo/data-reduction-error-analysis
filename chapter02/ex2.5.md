Exercise 2.5
=======

Show that the sum in Equation (2.6) reduces to <img src="https://latex.codecogs.com/svg.latex?\mu=np" />. *Hint*: Define <img src="https://latex.codecogs.com/svg.latex?y=x-1" /> and <img src="https://latex.codecogs.com/svg.latex?m=n-1" /> and use the fact that:
-----------

<img src="https://latex.codecogs.com/svg.latex?\sum_{y=0}^m=\left[ \frac{m!}{y!(m-y)!} p^y(1-p)^{m-y} \right]=\sum_{y=0}^m P_b(y; m, p)=1" />

There is a solution for this exercise available on [Prob(a)bilistic World](https://www.probabilisticworld.com/binomial-distribution-mean-variance-formulas-proof/) website [Posted on May 19, 2020].

A property of the binomial coefficient:
-----------

Given the binomial coefficient formula:

<img src="https://latex.codecogs.com/svg.latex?\left(\begin{array}{c}
   n\\
   x
   \end{array}
  \right) = \frac{n!}{x!(n-k)!}" />

Let's derive it for the expression <img src="https://latex.codecogs.com/svg.latex?n - 1" /> and <img src="https://latex.codecogs.com/svg.latex?x - 1" />:

<img src="https://latex.codecogs.com/svg.latex?\left(\begin{array}{c}
   n - 1\\
   x - 1
   \end{array}
  \right) = \frac{(n-1)!}{(x-1)!((n-1)-(k-1))!} = \frac{(n-1)!}{(x-1)!(n-k)!" />

The recursive property of the factorial function is:

<img src="https://latex.codecogs.com/svg.latex?x! = x \cdot (x - 1)!" />

Based on this property, let's rewrite the binomial coefficient formula:

<img src="https://latex.codecogs.com/svg.latex?\left(\begin{array}{c}
   n\\
   x
   \end{array}
  \right) = \frac{n!}{x!(n-k)!} = \frac{n(n-1)!}{x(x-1)!(n-k)!} = \frac{n}{x} \cdot \frac{n-1!}{(x-1)!(n-k)!}" />

Let's start another expression:

<img src="https://latex.codecogs.com/svg.latex?x \cdot \left(\begin{array}{c}
   n\\
   x
   \end{array}
  \right) = x \cdot \frac{n}{x} \cdot \frac{n-1!}{(x-1)!(n-k)!} = n \cdot \frac{n-1!}{(x-1)!(n-k)!}" />

Finally, using the expression <img src="https://latex.codecogs.com/svg.latex?n - 1" /> and <img src="https://latex.codecogs.com/svg.latex?x - 1" />, we get the following identity:

<img src="https://latex.codecogs.com/svg.latex?x \cdot \left(\begin{array}{c}
   n\\
   x
   \end{array}
  \right) = n \cdot \left(\begin{array}{c}
   n - 1\\
   x - 1
   \end{array}
  \right)" />

Mean of binomial distributions derivation:
-----------

Here's the general mean of binomial distributions formula:

<img src="https://latex.codecogs.com/svg.latex?\mu=\sum_{x=0}^n \left[ x \frac{n!}{x!(n-x)!} p^x (1-p)^{n-x} \right]=\sum_{x=0}^n x \cdot P(x; n, p)" />

First, let's apply the binomial property from last section to the right-hand side:

<img src="https://latex.codecogs.com/svg.latex?\mu=\sum_{x=0}^n n \cdot \left(\begin{array}{c}
   n - 1\\
   x - 1
   \end{array}
  \right)
  p^x (1-p)^{n-x}" />

<img src="https://latex.codecogs.com/svg.latex?\mu=n \cdot \sum_{x=0}^n \left(\begin{array}{c}
   n - 1\\
   x - 1
   \end{array}
  \right)
  p^x (1-p)^{n-x}" />

Consider the **product rule of exponents** given the exponent <img src="https://latex.codecogs.com/svg.latex?b" />:

<img src="https://latex.codecogs.com/svg.latex?a^b = a \cdot a^{b-1}" />

Let's rewrite <img src="https://latex.codecogs.com/svg.latex?p^x" /> as <img src="https://latex.codecogs.com/svg.latex?p \cdot p^{x-1}" />:

<img src="https://latex.codecogs.com/svg.latex?\mu=n \cdot \sum_{x=0}^n \left(\begin{array}{c}
   n - 1\\
   x - 1
   \end{array}
  \right)
  p \cdot p^{x-1} (1-p)^{n-x}" />

<img src="https://latex.codecogs.com/svg.latex?\mu = np \cdot \sum_{x=0}^n \left(\begin{array}{c}
   n - 1\\
   x - 1
   \end{array}
  \right)
  p^{x-1} (1-p)^{n-x}" />

Finally, let's apply the identity <img src="https://latex.codecogs.com/svg.latex?n-x=(n-1)-(x-1)" /> to the exponent of <img src="https://latex.codecogs.com/svg.latex?(1-p)" />:

<img src="https://latex.codecogs.com/svg.latex?\mu = np \cdot \sum_{x=0}^n \left(\begin{array}{c}
   n - 1\\
   x - 1
   \end{array}
  \right)
  p^{x-1} (1-p)^{(n-1)-(x-1)}" />

The final proof:
-----------

Define <img src="https://latex.codecogs.com/svg.latex?y=x-1" /> and <img src="https://latex.codecogs.com/svg.latex?m=n-1" />:

<img src="https://latex.codecogs.com/svg.latex?\mu = np \cdot \sum_{y=0}^m \left(\begin{array}{c}
   m\\
   y
   \end{array}
  \right)
  p^{y} (1-p)^{m-y}" />

The term inside the sum operator looks exactly like the binomial probability mass function:

<img src="https://latex.codecogs.com/svg.latex?\left(\begin{array}{c}
   m\\
   y
   \end{array}
  \right)
  p^{y} (1-p)^{m-y}" />

Then, by definition:

<img src="https://latex.codecogs.com/svg.latex?\sum_{y=0}^m \left(\begin{array}{c}
   m\\
   y
   \end{array}
  \right)
  p^{y} (1-p)^{m-y} = 1" />

Therefore, we can now condifently state:

<img src="https://latex.codecogs.com/svg.latex?\mu = np \cdot \sum_{y=0}^m \left(\begin{array}{c}
   m\\
   y
   \end{array}
  \right)
  p^{y} (1-p)^{m-y} = np \cdot 1 = np" />
