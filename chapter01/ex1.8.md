Exercise 1.8
=======

Justify the second equality in Equations (1.8) and (1.14).
-----------

a) The variance <img src="https://latex.codecogs.com/svg.latex?\sigma^2" /> is defined as the limit of the average of the squares of the deviations from the mean <img src="https://latex.codecogs.com/svg.latex?\mu" />:

<img src="https://latex.codecogs.com/svg.latex?\sigma^2 \equiv \lim_{N \rightarrow \infty} \left[ \frac{1}{N} \sum (x_i - \mu)^2 \right]" />

Solving the internal parenthesis:

<img src="https://latex.codecogs.com/svg.latex?\sigma^2 \equiv \lim_{N \rightarrow \infty} \left[ \frac{1}{N} \sum (x_i^2 - 2x_i\mu + \mu^2) \right]" /><br />

And spliting the sum in individual components:

<img src="https://latex.codecogs.com/svg.latex?\sigma^2 \equiv \lim_{N \rightarrow \infty} \left[ \frac{1}{N} \sum x_i^2 - \frac{1}{N} \sum x_i2\mu + \frac{1}{N} \sum \mu^2 \right]" /><br />

Given:

<img src="https://latex.codecogs.com/svg.latex?\frac{\sum x_i}{N} = \mu" /><br />

Then:

<img src="https://latex.codecogs.com/svg.latex?\sigma^2 \equiv \lim_{N \rightarrow \infty} \left[ \frac{1}{N} \sum x_i^2 - \mu\cdot2\mu + \frac{1}{\cancel{N}}\cancel{N}\mu^2 \right]" /><br />

Therefore:

<img src="https://latex.codecogs.com/svg.latex?\sigma^2 \equiv \lim_{N \rightarrow \infty} \left[ \frac{1}{N} \sum x_i^2 - \mu^2 \right]" /><br />

<img src="https://latex.codecogs.com/svg.latex?\sigma^2 \equiv \lim_{N \rightarrow \infty} \left( \frac{1}{N} \sum x_i^2 \right) - \mu^2" /><br />

b) The variance <img src="https://latex.codecogs.com/svg.latex?\sigma^2" /> becomes the second central product moment:

<img src="https://latex.codecogs.com/svg.latex?\sigma^2 = \int_{-\infty}^{\infty} (x - \mu)^2 p(x) dx" />

Solving the internal parenthesis:

<img src="https://latex.codecogs.com/svg.latex?\sigma^2 = \int_{-\infty}^{\infty} (x^2 - 2x\mu + \mu^2) p(x) dx" />

And spliting the equation in individual components:

<img src="https://latex.codecogs.com/svg.latex?\sigma^2 = \int_{-\infty}^{\infty} x^2 p(x) dx - 2\mu (x \cdot p(x)) dx + \mu^2 p(x) dx" />

Given:

<img src="https://latex.codecogs.com/svg.latex?x \cdot p(x) = \mu " /> and <img src="https://latex.codecogs.com/svg.latex?\int_{-\infty}^{\infty} p(x)dx = 1" />

Then:

<img src="https://latex.codecogs.com/svg.latex?\sigma^2 = \int_{-\infty}^{\infty} x^2 p(x) dx - 2\mu \cdot \mu \cdot dx + \mu^2 \cdot 1 \cdot dx" />

Finally:

<img src="https://latex.codecogs.com/svg.latex?\sigma^2 = \int_{-\infty}^{\infty} x^2 p(x) dx - \mu^2" />
