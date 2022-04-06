# CF-induction-guesser
This github repository provides the code used to find sequences <img src="https://latex.codecogs.com/svg.image?c_k" title="https://latex.codecogs.com/svg.image?c_k" /> and <img src="https://latex.codecogs.com/svg.image?d_k" title="https://latex.codecogs.com/svg.image?d_k" /> which, in turn, are used to find series representations for certain PCF's as described in [[1]](#1). These can be evaluated by using other code - also provided in this repository.

## cndn-finder
A jupyter notebook showcasing 3 simple methods for guessing polynomial sequences 
<img src="https://latex.codecogs.com/svg.image?c_k" title="https://latex.codecogs.com/svg.image?c_k" /> and <img src="https://latex.codecogs.com/svg.image?d_k" title="https://latex.codecogs.com/svg.image?d_k" /> such that:

<img src="https://latex.codecogs.com/svg.image?a_k&space;=&space;c_k&space;&plus;&space;d_{k&plus;1}\\b_k&space;=&space;-c_kd_k" title="https://latex.codecogs.com/svg.image?a_k = c_k + d_{k+1}\\b_k = -c_kd_k" />

Where $a_k$ and $b_k$ are integer sequences defining a generalized PCF in the 
following way:

<img src="https://latex.codecogs.com/svg.image?\alpha&space;=&space;a_0&space;&plus;&space;\frac{b_1}{a_1&space;&plus;&space;\frac{b_2}{a_2&space;&plus;&space;\frac{b_3}{a_3&space;&plus;&space;\dots}}}" title="https://latex.codecogs.com/svg.image?\alpha = a_0 + \frac{b_1}{a_1 + \frac{b_2}{a_2 + \frac{b_3}{a_3 + \dots}}}" />

By solving systems of nonlinear equations as described in [[1]](#1).

## Generalization calculator
A jupyter notebook with some derivations for closed form expressions of certain infinite series from [[2]](#2). E.g.

<img src="https://latex.codecogs.com/svg.image?\sum_{n=0}^\infty&space;\frac{n!^2}{(2n)!}\frac{(4x)^n}{2n&space;&plus;&space;2m&space;&plus;&space;1}" title="https://latex.codecogs.com/svg.image?\sum_{n=0}^\infty \frac{n!^2}{(2n)!}\frac{(4x)^n}{2n + 2m + 1}" />

This jupyter notebook also contain calculators for finding a specific value of a certain series given values for m and x. These come in handy when evaluating the series representation of a PCF evaluated by the other jupyter notebook.


## References
<a id="1">[1]</a> 
Hugo M. Nielsen (2022). 
url: ???

<a id="2">[2]</a> 
Series pdf ???
url: ???

