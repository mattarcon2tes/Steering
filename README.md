# Steering
Multipartite steering inequalities for the three-qubit W state

This folder contains steering inequalities for entanglement certification of the three-qubit W state assuming that each untrusted party
performs one out of 3 dichotomic measurements. Each inequality acts as a linear functional over a quantum assemblage, as described in 
arXiv:1609.00226. The distinct elements defining each inequality are matrices stacked one below the next one, indexing in a faster manner
the measurement outcomes and subsequently the measurement settings. 

For instance, consider the case of two untrusted devices, whose measurements performed are labeled x=0,1,2 and y=0,1,2 respectively. 
The outcomes are labeled a=0,1 for the first device and b=0,1 for the second one. Then, the file "Inequality for Genuine Tripartite 
Entanglement in the W state with two untrusted devices (experimental)"  has 36 matrices (corresponding to all cases for the variables
a,b,x and y, and the ordering goes as: 
ab|xy: 00|00, 00|01, 00|10, .... 01|00 .... 10|00 ... 11|11.
