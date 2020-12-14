Exercise 2.18
=======

Show that a tangent to the Gaussian function is steepest at <img src="https://latex.codecogs.com/svg.latex?x=\mu\pm\sigma" />, and therefore intersects the curve at the <img src="https://latex.codecogs.com/svg.latex?e^{-1/2}" /> points. Show also that these tangents intersect the axis at <img src="https://latex.codecogs.com/svg.latex?x=\mu\pm 2\sigma" />
-----------

Given the equation of the tangent of <img src="https://latex.codecogs.com/svg.latex?y=f(x)" /> at a point <img src="https://latex.codecogs.com/svg.latex?p_1=(x_1, y_1)" />:

<img src="https://latex.codecogs.com/svg.latex?y-y_1 = \frac{d_y}{d_x}(x-x_1)" />

The probability density function (PDF) of a Gaussian distribution (normal distribution) can be expressed as:

<img src="https://latex.codecogs.com/svg.latex?f(x)=\frac{1}{\sigma\sqrt{2\pi}} \exp \left[ -\frac{1}{2} \left( \frac{x-\mu}{\sigma} \right)^2 \right]" />

Here:

<img src="https://latex.codecogs.com/svg.latex?f^{'}(x)=\frac{1}{\sigma\sqrt{2\pi}} \exp \left[ -\frac{1}{2} \left( \frac{x-\mu}{\sigma} \right)^2 \right] \cdot \left(-\left(\frac{x-\mu}{\sigma}\right)\right) \cdot \frac{1}{\sigma}" /><br />

<img src="https://latex.codecogs.com/svg.latex?f^{''}(x)=\frac{1}{\sigma\sqrt{2\pi}} \exp \left[ -\frac{1}{2} \left( \frac{x-\mu}{\sigma} \right)^2 \right] \cdot \left(\frac{x-\mu}{\sigma}\right)^2 \cdot \frac{1}{\sigma^2} + \exp \left[ -\frac{1}{2} \left( \frac{x-\mu}{\sigma} \right)^2 \right] \cdot \left(-\frac{1}{\sigma}\right) \cdot \frac{1}{\sigma}" /><br />

<img src="https://latex.codecogs.com/svg.latex?f^{''}(x)=0" /><br />

<img src="https://latex.codecogs.com/svg.latex?\left(\frac{x-\mu}{\sigma}\right)^2 \cdot \frac{1}{\sigma^2} - \frac{1}{\sigma^2} = \left(\frac{x-\mu}{\sigma}\right)^2 = 1" /><br />

Therefore:

<img src="https://latex.codecogs.com/svg.latex?x=\mu\pm\sigma" />

Hence slope becomes maximum at <img src="https://latex.codecogs.com/svg.latex?x=\mu\pm\sigma" />:

<img src="https://latex.codecogs.com/svg.latex?f^{'}(x)=\frac{1}{\sigma\sqrt{2\pi}} \exp \left[ -\frac{1}{2} \right] \cdot \left( \pm \frac{1}{\sigma} \right)" /><br />

Tangent <img src="https://latex.codecogs.com/svg.latex?eq^n" />:

<img src="https://latex.codecogs.com/svg.latex?\frac{y-\frac{1}{\sigma\sqrt{2\pi}} \exp \left[ -\frac{1}{2} \right]}{x-(\mu\pm\sigma)} = \pm \frac{\exp \left[ -\frac{1}{2} \right]}{\sigma^2\sqrt{2\pi}}" /><br />

Intersection with <img src="https://latex.codecogs.com/svg.latex?x" /> axis:

<img src="https://latex.codecogs.com/svg.latex?-\frac{1}{\sigma\sqrt{2\pi}} \exp \left[ -\frac{1}{2} \right] = \pm \frac{\exp \left[ -\frac{1}{2} \right]}{\sigma^2\sqrt{2\pi}}(x-\mu\pm\sigma)" /><br />

<img src="https://latex.codecogs.com/svg.latex?\pm\sigma = x-(\mu\pm\sigma)" /><br />

Finally:

<img src="https://latex.codecogs.com/svg.latex?x=\mu\pm2\sigma" /><br />
