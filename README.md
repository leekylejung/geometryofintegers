# Introduction
The study of groups through the investigation of the geometric structures that they create often leads to insightful and applicable results. We take an geometric group theoretic approach towards investigating the large scale structure of the set Z of integers and of the set H(4) of 4x4 Heisenberg matrices.

This repository contains two algorithms (intwordmetric and heiswordmetric) which calculate word-metrics for the integer group and for the heisenberg group of 4x4 matrices, respectively. The code was developed in collaboration with a research group at the University of Michigan, and I have attatched our write-up with citations to this repo.

# intwordmetric
In essense, intwordmetric relies on a property of the word-metric: for generating set S, we can always find some N such that for each integer n, only the largest element of S makes a contribution towards the metric for the portion of the integer represented by (n - N). This recursive algorithm has O(N + n) runtime performance.

# heiswordmetric
The heiswordmetric algorithm builds on work by Sebastien Blachere on the 3x3 Heisenberg matrix. In essense, it is shown that the 4x4 matrix is isomorphic to the cartesian product of two 3x3 matrices, and we build on Blachere's 3x3 algorithm to analytically compute the 4x4 algorithm. This iterative algorithm has O(n) runtime performance, with respect to n, the size of the largest input integer.

Please view 'writeup.pdf' for more details. Special thanks to Dr. Yanlong Hao for his continued support!
