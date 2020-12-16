Exercise 2.6
=======

On a certain kind of slot machine there are 10 different symbols that can appear in each of three windows. The machine pays off different amounts when either one, two, or three lemons appear. What should the payoff ratio for each of the three possibilities if the machine is honest and there is no cut for the house?
-----------

There is a similar solution for this exercise on [Edward Shore's Blog](http://edspi31415.blogspot.com/2014/01/probability-odds-of-winning-at-slot.html) website [Posted on January 7, 2014].

Payment definition
-----------
As there is no cut for the house, I will assume the maximum payment based on the number of combinations in this slot machine. This machine has three windows which can apper 10 different symbols. Therefore, the number possible combinations is: <img src="https://latex.codecogs.com/svg.latex?10^3=10\times10\times10=1000" />

Number of Winning Combinations
-----------
The payouts are as follows:
1. Three lemons appear in the three slots
2. Any slot show two lemons
3. Any slow show one single lemon

Based on this information, there are the following number of winning combinations:
1. There is only one configuration for three lemons
2. Lemons can appear any two slots: slots 1 and 2, slots 1 and 3, and slots 2 and 3. Hence the total number of winning combinations possible is <img src="https://latex.codecogs.com/svg.latex?1\times1\times9+1\times9\times1+9\times1\times1=27" />
3. Lemons can appear in any slot, the other two slots must have another fruit. In this instance, it does not matter if the other two slots match. The number of combinations is <img src="https://latex.codecogs.com/svg.latex?1\times9\times9+9\times1\times9+9\times9\times1=243" />

Calculate the payoff ratio and payment
-----------
The payoff ratio should be inversely proportional to their probabilities:
1. Three lemons <img src="https://latex.codecogs.com/svg.latex?1/1=1" />
2. Two lemons <img src="https://latex.codecogs.com/svg.latex?1/27=0.0370" />
3. One lemon <img src="https://latex.codecogs.com/svg.latex?1/243=0.0041" />

The payment must be:
1. Three lemons <img src="https://latex.codecogs.com/svg.latex?1\times1000=1000" />
2. Two lemons <img src="https://latex.codecogs.com/svg.latex?0.0370\times1000=37" />
3. One lemon <img src="https://latex.codecogs.com/svg.latex?0.0041\times1000=4.1" />
