# Geometry of Integers
This repository contains two algorithms (intwordmetric and heiswordmetric) which calculate word-metrics for the integer group and for the heisenberg group of 4x4 matrices, respectively. The code was developed in collaboration with a research group at the University of Michigan, and I have attatched our write-up with citations to this repo.

In essense, the first algorithm (intwordmetric) relies on a property of the word-metric: for each integer n and generating set S, we can always find some N < n such that only the largest element of S makes a contribution towards the metric for the portion of the integer represented by (n - N). 

The second (heiswordmetric) builds on work by Sebastien Blachere on the 3x3 Heisenberg matrix. In essense, it is shown that the 4x4 matrix is isomorphic to two copies of the 3x3 matrix, and we build on Blachere's 3x3 algorithm to analytically compute the 4x4 algorithm. 

Please view 'writeup.pdf' for more details.
