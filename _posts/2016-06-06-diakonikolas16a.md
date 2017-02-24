---
title: Optimal Learning via the Fourier Transform for Sums of Independent Integer
  Random Variables
abstract: 'We study the structure and learnability of sums of independent integer
  random variables (SIIRVs). For k ∈\mathbbZ_+, a \emk-SIIRV of order n ∈\mathbbZ_+
  is the probability distribution of the sum of n mutually independent random variables
  each supported on {0, 1, …, k-1}. We denote by \cal S_n,k the set of all k-SIIRVs
  of order n. How many samples are required to learn an arbitrary distribution in
  \cal S_n,k? In this paper, we tightly characterize the sample and computational
  complexity of this problem. More precisely, we design a computationally efficient
  algorithm that uses \widetildeO(k/ε^2) samples, and learns an arbitrary k-SIIRV
  within error ε, in total variation distance. Moreover, we show that the \em optimal
  sample complexity of this learning problem is Θ((k/ε^2)\sqrt\log(1/ε)), i.e., we
  prove an upper bound and a matching information-theoretic lower bound. Our algorithm
  proceeds by learning the Fourier transform of the target k-SIIRV in its effective
  support. Its correctness relies on the \em approximate sparsity of the Fourier transform
  of k-SIIRVs – a structural property that we establish, roughly stating that the
  Fourier transform of k-SIIRVs has small magnitude outside a small set. Along the
  way we prove several new structural results about k-SIIRVs. As one of our main structural
  contributions, we give an efficient algorithm to construct a sparse \em proper ε-cover
  for \cal S_n,k, in total variation distance. We also obtain a novel geometric characterization
  of the space of k-SIIRVs. Our characterization allows us to prove a tight lower
  bound on the size of ε-covers for \cal S_n,k – establishing that our cover upper
  bound is optimal – and is the key ingredient in our tight sample complexity lower
  bound. Our approach of exploiting the sparsity of the Fourier transform in distribution
  learning is general, and has recently found additional applications. In a subsequent
  work, we use a generalization of this idea to obtain the first computationally efficient
  learning algorithm for Poisson multinomial distributions. In a separate work, we
  build on our Fourier-based approach to obtain the fastest known proper learning
  algorithm for Poisson binomial distributions (2-SIIRVs). '
layout: inproceedings
series: Proceedings of Machine Learning Research
id: diakonikolas16a
month: 0
firstpage: 831
lastpage: 849
page: 831-849
sections: 
author:
- given: I.
  family: Diakonikolas
- given: D. M.
  family: Kane
- given: A.
  family: Stewart
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
pdf: http://proceedings.mlr.press/v49/diakonikolas16a.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
