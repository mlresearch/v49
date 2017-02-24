---
title: Properly Learning Poisson Binomial Distributions in Almost Polynomial Time
abstract: 'We give an algorithm for properly learning Poisson binomial distributions.
  A Poisson binomial distribution (PBD) of order n ∈\mathbbZ_+ is the discrete probability
  distribution of the sum of n mutually independent Bernoulli random variables. Given
  \widetildeO(1/ε^2) samples from an unknown PBD P, our algorithm runs in time (1/\eps)^O(\log
  \log (1/ε)), and outputs a hypothesis PBD that is ε-close to P in total variation
  distance. The sample complexity of our algorithm is known to be nearly-optimal,
  up to logarithmic factors, as established in previous work. However, the previously
  best known running time for properly learning PBDs was (1/ε)^O(\log(1/ε)), and was
  essentially obtained by enumeration over an appropriate  ε-cover. We remark that
  the running time of this cover-based approach cannot be improved, as any ε-cover
  for the space of PBDs has size  (1/ε)^Ω(\log(1/ε)). As one of our main contributions,
  we provide a novel structural characterization of PBDs, showing that any PBD P is
  ε-close to another PBD Q with O(\log(1/ε)) distinct parameters. More precisely,
  we prove that, for all ε>0, there exists an explicit collection \calM of (1/ε)^O(\log
  \log (1/ε)) vectors of multiplicities, such that for any PBD P there exists a PBD
  Q with O(\log(1/ε)) distinct parameters whose multiplicities are given by some element
  of \cal M, such that Q is ε-close to P.  Our proof combines tools from Fourier analysis
  and algebraic geometry. Our approach to the proper learning problem is as follows:
  Starting with an accurate non-proper hypothesis, we fit a PBD to this hypothesis.
  This fitting problem can be formulated as a natural polynomial optimization problem.
  Our aforementioned structural characterization allows us to reduce the corresponding
  fitting problem to a collection of (1/ε)^O(\log \log(1/ε)) systems of low-degree
  polynomial inequalities. We show that each such system can be solved in time (1/ε)^O(\log
  \log(1/ε)), which yields the overall running time of our algorithm. '
layout: inproceedings
series: Proceedings of Machine Learning Research
id: diakonikolas16b
month: 0
firstpage: 850
lastpage: 878
page: 850-878
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
pdf: http://proceedings.mlr.press/v49/diakonikolas16b.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
