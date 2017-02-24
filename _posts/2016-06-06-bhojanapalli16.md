---
title: Dropping Convexity for Faster Semi-definite Optimization
abstract: 'We study the minimization of a convex function f(X) over the set of n \times
  n positive semi-definite matrices, but when the problem is recast as \min_U g(U)
  :=  f(UU^⊤), with U ∈\mathbbR^n \times r and r ≤n. We study the performance of gradient
  descent on g—which we refer to as Factored Gradient Descent (\textscFgd)—under standard
  assumptions on the \em original function f. We provide a rule for selecting the
  step size and, with this choice, show that the \emphlocal convergence rate of \textscFgd
  mirrors that of standard gradient descent on the original f: \emphi.e., after k
  steps, the error is O(1/k) for smooth f, and exponentially small in k when f is
  (restricted) strongly convex. In addition, we provide a procedure to initialize
  \textscFgd for (restricted) strongly convex objectives and when one only has access
  to f via a first-order oracle; for several problem instances, such proper initialization
  leads to \emphglobal convergence guarantees. \textscFgd and similar procedures are
  widely used in practice for problems that can be posed as matrix factorization.
  To the best of our knowledge, this is the first paper to provide precise convergence
  rate guarantees for general convex functions under standard convex assumptions.'
layout: inproceedings
series: Proceedings of Machine Learning Research
id: bhojanapalli16
month: 0
firstpage: 530
lastpage: 582
page: 530-582
sections: 
author:
- given: Srinadh
  family: Bhojanapalli
- given: Anastasios
  family: Kyrillidis
- given: Sujay
  family: Sanghavi
date: 2016-06-06
address: Columbia University, New York, New York, USA
publisher: PMLR
container-title: 29th Annual Conference on Learning Theory
volume: '49'
genre: inproceedings
issued:
  date-parts:
  - 2016
  - 6
  - 6
pdf: http://proceedings.mlr.press/v49/bhojanapalli16/bhojanapalli16.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
