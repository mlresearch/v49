---
title: Instance-dependent Regret Bounds for Dueling Bandits
abstract: We study the multi-armed dueling bandit problem in which feedback is provided
  in the form of relative comparisons between pairs of actions, with the goal of eventually
  learning to select actions that are close to the best. Following  Dudik et al. (2015),
  we aim for algorithms whose performance approaches that of the optimal randomized
  choice of actions, the von Neumann winner, expressly avoiding more restrictive assumptions,
  for instance, regarding the existence of a single best action (a Condorcet winner).
  In this general setting, the best known algorithms achieve regret O(\sqrtKT) in
  T rounds with K actions. In this paper, we present the first instance-dependent
  regret bounds for the general problem, focusing particularly on when the von Neumann
  winner is sparse. Specifically, we propose a new algorithm whose regret, relative
  to a unique von Neumann winner with sparsity s, is at most O(\sqrtsT), plus an instance-dependent
  constant. Thus, when the sparsity is much smaller than the total number of actions,
  our result indicates that learning can be substantially faster.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: balsubramani16
month: 0
tex_title: Instance-dependent Regret Bounds for Dueling Bandits
firstpage: 336
lastpage: 360
page: 336-360
order: 336
cycles: false
author:
- given: Akshay
  family: Balsubramani
- given: Zohar
  family: Karnin
- given: Robert E.
  family: Schapire
- given: Masrour
  family: Zoghi
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
pdf: http://proceedings.mlr.press/v49/balsubramani16.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
