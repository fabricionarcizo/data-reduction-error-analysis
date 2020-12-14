Exercise 2.17
=======

The probability that an electron is at a distance r from the center of the nucleus of a hydrogen atom is given by:
-----------

<img src="https://latex.codecogs.com/svg.latex?dP(r) = Cr^2 e^{-r/R} dr" />

Find the mean radius <img src="https://latex.codecogs.com/svg.latex?\overline{r}" /> and the standar deviation. Find the value of the constant <img src="https://latex.codecogs.com/svg.latex?C" />.
-----------

There is a solution for this exercise available on [Chegg Study](https://www.chegg.com/homework-help/questions-and-answers/probability-density-electron-distance-r-center-nucleus-hydrogen-atom-given-dp-r-c-r-2-exp--q11130013?trackid=97fabb174a65&strackid=a97cfc98a0b6) website [Accessed on December 14, 2020].

The electron must lie somewhere from 0 to  <img src="https://latex.codecogs.com/svg.latex?\infty" />, we get the value of the constant  <img src="https://latex.codecogs.com/svg.latex?C" /> by normalizing the probability density function (PDF):

<img src="https://latex.codecogs.com/svg.latex?dP(r) = C \int_{0}^{\infty} r^2 e^{-r/R} dr = 1" />

We use the integral identity:

<img src="https://latex.codecogs.com/svg.latex?\int r^2 e^{kr} dr = e^{kr} \frac{r^2}{k}-\frac{2r}{k^2}+\frac{2}{k^3}" />

Here, <img src="https://latex.codecogs.com/svg.latex?k=-1/R" />

The integral resolves to:

<img src="https://latex.codecogs.com/svg.latex?dP(r) = C e^{-r/R} -Rr^2 - 2Rr - 2R^3" />

Putting the limits <img src="https://latex.codecogs.com/svg.latex?r=0" /> and <img src="https://latex.codecogs.com/svg.latex?\infty" /> and equating it 1, we get <img src="https://latex.codecogs.com/svg.latex?C=1/2R^3" />. The mean radius of the atom is the average value of <img src="https://latex.codecogs.com/svg.latex?r" /> calculated as:

<img src="https://latex.codecogs.com/svg.latex?\left< r \right> = \frac{1}{2R^3} \int_{0}^{\infty} r \cdot r^2 e^{-r/R} dr" /><br />

<img src="https://latex.codecogs.com/svg.latex?\int r^n e^{kr} dr = \frac{1}{k} r^n e^{kr}-\frac{n}{k} \int r^{n-1} e^{kr} dr" />

Using the above identify and applying limits we get mean radius:

<img src="https://latex.codecogs.com/svg.latex?\left< r \right> = -e^{-r/R} \frac{Rr^3 + 3R^2r^2 + 6R^3r + 6R^4}{2R^3}" /><br />

For <img src="https://latex.codecogs.com/svg.latex?r=8" />, thewhole term vanish and for <img src="https://latex.codecogs.com/svg.latex?r=0" /> except the last term all other vanish:

<img src="https://latex.codecogs.com/svg.latex?\left< r \right> = 6R^4/2R^3=3R" /><br />

In Quantum mechanics standard deviation is uncertainty in position:

<img src="https://latex.codecogs.com/svg.latex?\Delta r = \sqrt{\left< r^2 \right> - \left< r \right>^2}" /><br />

We get <img src="https://latex.codecogs.com/svg.latex?\left< r \right>^2" /> by evaluating the integral:

<img src="https://latex.codecogs.com/svg.latex?\frac{1}{2R^3} \int_{0}^{\infty} r^2 \cdot r^2 e^{-r/R} dr" /><br />

<img src="https://latex.codecogs.com/svg.latex?\left< r \right>^2 = 12R^2" /><br />

Then, the standard deviation is defined by:

<img src="https://latex.codecogs.com/svg.latex?\Delta r = \sqrt{12R^2 - (3R)^2} = 3R" />
