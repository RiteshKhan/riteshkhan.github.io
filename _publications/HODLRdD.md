---
title: "HODLRdD: A new black-box fast algorithm for N-body problems in d-dimensions with guaranteed error bounds: Applications to integral equations and support vector machines"
collection: publications
category: manuscripts
# permalink: https://doi.org/10.1016/j.jcp.2024.112786
# excerpt: 'This paper is about fixing template issue #693.'
date: 2024-01-24
venue: 'Journal of Computational Physics, Volume 501'
paperurl: 'https://doi.org/10.1016/j.jcp.2024.112786'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

We study rank of sub-matrices arising out of kernel functions. Such kernel functions are frequently encountered in a wide range of areas. To our knowledge, this is the first work to formally study rank growth of matrices arising out of a wide range of kernel functions in any dimension. In this article, we prove two new theorems bounding rank of different sub-matrices arising from these kernel functions. Bounds like these are often useful for analyzing the complexity of various hierarchical matrix algorithms. We also plot the numerical rank growth of different sub-matrices arising out of various kernel functions in 1D, 2D, 3D and 4D, which agrees with the proposed theorems. Another significant contribution of this article is that using the obtained rank bounds, we also propose a way to extend the notion of weak-admissibility for hierarchical matrices in higher dimensions. Based on this proposed weak-admissibility condition, we develop a black-box (kernel-independent) fast algorithm for $N$-body problems, hierarchically off-diagonal low-rank matrix in d dimensions (HODLRdD), which can perform matrix-vector products with quasi-linear complexity in any dimension $d$. Our theorems guarantee that p does not grow with any positive power of $N$, which implies our HODLR$d$D algorithm scales almost linearly. The C++ implementation with OpenMP parallelization of the HODLRdD is available at https://github.com/SAFRAN-LAB/HODLRdD. We also discuss the scalability of the HODLRdD algorithm and showcase the applicability by solving an integral equation in 4D and accelerating the training phase of the support vector machines (SVM) for the data sets with four and five features.

