Exercise 2.1
=======

Consider five coins labeled *a*, *b*, *c*, *d*, and *e*. Let *x* = *number of heads showing*.
-----------

a) Manually count and tabulate all possible permutation for each of the following configurations:

i. *x* = 0
```
0,0,0,0,0
```

ii. *x* = 1
```
a,0,0,0,0
0,a,0,0,0
0,0,a,0,0
0,0,0,a,0
0,0,0,0,a
```

iii. *x* = 2
```
a,b,0,0,0
b,a,0,0,0
0,a,b,0,0
a,0,b,0,0
b,0,a,0,0
0,b,a,0,0
0,b,0,a,0
b,0,0,a,0
0,0,b,a,0
0,a,0,b,0
a,0,0,b,0
0,0,a,b,0
0,0,0,a,b
0,0,a,0,b
a,0,0,0,b
0,a,0,0,b
b,0,0,0,a
0,b,0,0,a
0,0,b,0,a
0,0,0,b,a
```

iv. *x* = 3
```
a,b,c,0,0
b,a,c,0,0
c,a,b,0,0
a,c,b,0,0
b,c,a,0,0
c,b,a,0,0
c,b,0,a,0
b,c,0,a,0
0,c,b,a,0
c,0,b,a,0
b,0,c,a,0
0,b,c,a,0
0,a,c,b,0
a,0,c,b,0
c,0,a,b,0
0,c,a,b,0
a,c,0,b,0
c,a,0,b,0
b,a,0,c,0
a,b,0,c,0
0,b,a,c,0
b,0,a,c,0
a,0,b,c,0
0,a,b,c,0
0,0,a,b,c
a,0,0,b,c
0,a,0,b,c
a,0,b,0,c
0,a,b,0,c
b,a,0,0,c
a,b,0,0,c
0,b,a,0,c
b,0,a,0,c
0,0,b,a,c
b,0,0,a,c
0,b,0,a,c
c,0,0,a,b
0,c,0,a,b
0,0,c,a,b
0,0,a,c,b
a,0,0,c,b
0,a,0,c,b
a,c,0,0,b
c,a,0,0,b
0,a,c,0,b
a,0,c,0,b
c,0,a,0,b
0,c,a,0,b
b,c,0,0,a
c,b,0,0,a
0,b,c,0,a
b,0,c,0,a
c,0,b,0,a
0,c,b,0,a
0,c,0,b,a
c,0,0,b,a
0,0,c,b,a
0,b,0,c,a
b,0,0,c,a
0,0,b,c,a
```

v. *x* = 4
```
a,b,c,d,0
b,a,c,d,0
c,a,b,d,0
a,c,b,d,0
b,c,a,d,0
c,b,a,d,0
c,b,d,a,0
b,c,d,a,0
d,c,b,a,0
c,d,b,a,0
b,d,c,a,0
d,b,c,a,0
d,a,c,b,0
a,d,c,b,0
c,d,a,b,0
d,c,a,b,0
a,c,d,b,0
c,a,d,b,0
b,a,d,c,0
a,b,d,c,0
d,b,a,c,0
b,d,a,c,0
a,d,b,c,0
d,a,b,c,0
0,a,b,c,d
a,0,b,c,d
b,0,a,c,d
0,b,a,c,d
a,b,0,c,d
b,a,0,c,d
b,a,c,0,d
a,b,c,0,d
c,b,a,0,d
b,c,a,0,d
a,c,b,0,d
c,a,b,0,d
c,0,b,a,d
0,c,b,a,d
b,c,0,a,d
c,b,0,a,d
0,b,c,a,d
b,0,c,a,d
a,0,c,b,d
0,a,c,b,d
c,a,0,b,d
a,c,0,b,d
0,c,a,b,d
c,0,a,b,d
d,0,a,b,c
0,d,a,b,c
a,d,0,b,c
d,a,0,b,c
0,a,d,b,c
a,0,d,b,c
a,0,b,d,c
0,a,b,d,c
b,a,0,d,c
a,b,0,d,c
0,b,a,d,c
b,0,a,d,c
b,d,a,0,c
d,b,a,0,c
a,b,d,0,c
b,a,d,0,c
d,a,b,0,c
a,d,b,0,c
0,d,b,a,c
d,0,b,a,c
b,0,d,a,c
0,b,d,a,c
d,b,0,a,c
b,d,0,a,c
c,d,0,a,b
d,c,0,a,b
0,c,d,a,b
c,0,d,a,b
d,0,c,a,b
0,d,c,a,b
0,d,a,c,b
d,0,a,c,b
a,0,d,c,b
0,a,d,c,b
d,a,0,c,b
a,d,0,c,b
a,c,0,d,b
c,a,0,d,b
0,a,c,d,b
a,0,c,d,b
c,0,a,d,b
0,c,a,d,b
d,c,a,0,b
c,d,a,0,b
a,d,c,0,b
d,a,c,0,b
c,a,d,0,b
a,c,d,0,b
b,c,d,0,a
c,b,d,0,a
d,b,c,0,a
b,d,c,0,a
c,d,b,0,a
d,c,b,0,a
d,c,0,b,a
c,d,0,b,a
0,d,c,b,a
d,0,c,b,a
c,0,d,b,a
0,c,d,b,a
0,b,d,c,a
b,0,d,c,a
d,0,b,c,a
0,d,b,c,a
b,d,0,c,a
d,b,0,c,a
c,b,0,d,a
b,c,0,d,a
0,c,b,d,a
c,0,b,d,a
b,0,c,d,a
0,b,c,d,a
```

vi. *x* = 5
```
a,b,c,d,e
b,a,c,d,e
c,a,b,d,e
a,c,b,d,e
b,c,a,d,e
c,b,a,d,e
c,b,d,a,e
b,c,d,a,e
d,c,b,a,e
c,d,b,a,e
b,d,c,a,e
d,b,c,a,e
d,a,c,b,e
a,d,c,b,e
c,d,a,b,e
d,c,a,b,e
a,c,d,b,e
c,a,d,b,e
b,a,d,c,e
a,b,d,c,e
d,b,a,c,e
b,d,a,c,e
a,d,b,c,e
d,a,b,c,e
e,a,b,c,d
a,e,b,c,d
b,e,a,c,d
e,b,a,c,d
a,b,e,c,d
b,a,e,c,d
b,a,c,e,d
a,b,c,e,d
c,b,a,e,d
b,c,a,e,d
a,c,b,e,d
c,a,b,e,d
c,e,b,a,d
e,c,b,a,d
b,c,e,a,d
c,b,e,a,d
e,b,c,a,d
b,e,c,a,d
a,e,c,b,d
e,a,c,b,d
c,a,e,b,d
a,c,e,b,d
e,c,a,b,d
c,e,a,b,d
d,e,a,b,c
e,d,a,b,c
a,d,e,b,c
d,a,e,b,c
e,a,d,b,c
a,e,d,b,c
a,e,b,d,c
e,a,b,d,c
b,a,e,d,c
a,b,e,d,c
e,b,a,d,c
b,e,a,d,c
b,d,a,e,c
d,b,a,e,c
a,b,d,e,c
b,a,d,e,c
d,a,b,e,c
a,d,b,e,c
e,d,b,a,c
d,e,b,a,c
b,e,d,a,c
e,b,d,a,c
d,b,e,a,c
b,d,e,a,c
c,d,e,a,b
d,c,e,a,b
e,c,d,a,b
c,e,d,a,b
d,e,c,a,b
e,d,c,a,b
e,d,a,c,b
d,e,a,c,b
a,e,d,c,b
e,a,d,c,b
d,a,e,c,b
a,d,e,c,b
a,c,e,d,b
c,a,e,d,b
e,a,c,d,b
a,e,c,d,b
c,e,a,d,b
e,c,a,d,b
d,c,a,e,b
c,d,a,e,b
a,d,c,e,b
d,a,c,e,b
c,a,d,e,b
a,c,d,e,b
b,c,d,e,a
c,b,d,e,a
d,b,c,e,a
b,d,c,e,a
c,d,b,e,a
d,c,b,e,a
d,c,e,b,a
c,d,e,b,a
e,d,c,b,a
d,e,c,b,a
c,e,d,b,a
e,c,d,b,a
e,b,d,c,a
b,e,d,c,a
d,e,b,c,a
e,d,b,c,a
b,d,e,c,a
d,b,e,c,a
c,b,e,d,a
b,c,e,d,a
e,c,b,d,a
c,e,b,d,a
b,e,c,d,a
e,b,c,d,a
```

Compare your results to those given by Equation (2.2).

<img src="https://latex.codecogs.com/svg.latex?Pm(n,x)=\frac{n!}{(n-x)!}" />

i. *x* = 0
```
Pm(x, y) = 1 permutation
```

ii. *x* = 1
```
Pm(x, y) = 5 permutations
```

iii. *x* = 2
```
Pm(x, y) = 20 permutations
```

iv. *x* = 3
```
Pm(x, y) = 60 permutations
```

v. *x* = 4
```
Pm(x, y) = 120 permutations
```

vi. *x* = 5
```
Pm(x, y) = 120 permutations
```

b) Manually delete all duplicate permutations from each example of part (*a*), that is, cross out permutations that repeat a previous combination in a different order. Compare your results to those given by Equation (2.3).

<img src="https://latex.codecogs.com/svg.latex?C(n,x)=\frac{n!}{x!(n-x)!}" />

i. *x* = 0
```
C(x, y) = 1 combination

0,0,0,0,0
```

ii. *x* = 1
```
C(x, y) = 5 combinations

a,0,0,0,0
0,b,0,0,0
0,0,c,0,0
0,0,0,d,0
0,0,0,0,e
```

iii. *x* = 2
```
C(x, y) = 10 combinations

a,b,0,0,0
a,0,c,0,0
a,0,0,d,0
a,0,0,0,e
0,b,c,0,0
0,b,0,d,0
0,b,0,0,e
0,0,c,d,0
0,0,c,0,e
0,0,0,d,e
```

iv. *x* = 3
```
C(x, y) = 10 combinations

a,b,c,0,0
a,b,0,d,0
a,b,0,0,e
a,0,c,d,0
a,0,c,0,e
a,0,0,d,e
0,b,c,d,0
0,b,c,0,e
0,b,0,d,e
0,0,c,d,e
```

v. *x* = 4
```
C(x, y) = 5 combinations

a,b,c,d,0
a,b,c,0,e
a,b,0,d,e
a,0,c,d,e
0,b,c,d,e
```

vi. *x* = 5
```
C(x, y) = 1 combination

a,b,c,d,e
```

The sum of all combinations can be summarized as:

<img src="https://latex.codecogs.com/svg.latex?\sum_{k=0}^5\left(\begin{array}{c}5\\k\end{array}\right)=(1+1)^5=2^5=32" />
