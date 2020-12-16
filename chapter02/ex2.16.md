Exercise 2.16
=======

Shows by numerical calculation that, for the Gaussian probability distribution, the full-width at half maximum <img src="https://latex.codecogs.com/svg.latex?\Gamma" /> is related to the standard deviation by <img src="https://latex.codecogs.com/svg.latex?\Gamma=2.354\sigma" /> [Equation (2.28)].
-----------

There is a solution for this exercise available on [Wolfram MathWorld](https://mathworld.wolfram.com/GaussianFunction.html) website [Posted on December 11, 2020].

The probability density function (PDF) of a Gaussian distribution (normal distribution) can be expressed as:

<img src="https://latex.codecogs.com/svg.latex?P_G=\frac{1}{\sigma\sqrt{2\pi}}\exp\left[-\frac{1}{2}\left(\frac{x-\mu}{\sigma}\right)^2\right]" />

The full-width at half maximum for a Gaussian distribution is found by finding the half-maximum points <img src="https://latex.codecogs.com/svg.latex?x_0" />. The constant scaling factor can be ignored, so we must solve:

<img src="https://latex.codecogs.com/svg.latex?\exp\left[-\frac{1}{2}\left(\frac{x_0-\mu}{\sigma}\right)^2\right]=\frac{1}{2}f(x_{max})" />

As the <img src="https://latex.codecogs.com/svg.latex?f(x_{max})" /> occurs at <img src="https://latex.codecogs.com/svg.latex?x_{max}=\mu" />, so:

<img src="https://latex.codecogs.com/svg.latex?\exp\left[-\frac{1}{2}\left(\frac{x_0-\mu}{\sigma}\right)^2\right]=\frac{1}{2}f(\mu)=\frac{1}{2}" />

Solving:

<img src="https://latex.codecogs.com/svg.latex?\exp\left[-\frac{1}{2}\left(\frac{x_0-\mu}{\sigma}\right)^2\right]=2^{-1}" /><br />

<img src="https://latex.codecogs.com/svg.latex?-\frac{(x_0-\mu)^2}{2\sigma^2}=-\ln2" /><br />

<img src="https://latex.codecogs.com/svg.latex?(x_0-\mu)^2=2\sigma^2\ln2" /><br />

<img src="https://latex.codecogs.com/svg.latex?x_0=\pm\sigma\sqrt{2\ln2}+\mu" /><br />

Finally, we must conclude that the full-width at half maximum is given by:

<img src="https://latex.codecogs.com/svg.latex?\Gamma\equiv2\sqrt{2\ln2}\sigma\approx2.354\sigma" /><br />
