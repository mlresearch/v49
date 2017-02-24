---
title: Delay and Cooperation in Nonstochastic Bandits
abstract: 'We study networks of communicating learning agents that cooperate to solve
  a common nonstochastic bandit problem. Agents use an underlying communication network
  to get messages about actions selected by other agents, and drop messages that took
  more than d hops to arrive, where d is a delay parameter. We introduce Exp3-Coop,
  a cooperative version of the Exp3 algorithm and prove that with K actions and N
  agents the average per-agent regret after T rounds is at most of order \sqrt\left(d+1
  + \fracKN\alpha_≤d\right)(T\ln K), where \alpha_≤d is the independence number of
  the d-th power of the communication graph G. We then show that for any connected
  graph, for d=\sqrtK the regret bound is K^1/4\sqrtT, strictly better than the minimax
  regret \sqrtKT for noncooperating agents. More informed choices of d lead to bounds
  which are arbitrarily close to the full information minimax regret \sqrtT\ln K when
  G is dense. When G has sparse components, we show that a variant of Exp3-Coop, allowing
  agents to choose their parameters according to their centrality in G, strictly improves
  the regret. Finally, as a by-product of our analysis, we provide the first characterization
  of the minimax regret for bandit learning with delay. '
layout: inproceedings
series: Proceedings of Machine Learning Research
id: cesa-bianchi16
month: 0
firstpage: 605
lastpage: 622
page: 605-622
sections: 
author:
- given: Nicol‘o
  family: Cesa-Bianchi
- given: Claudio
  family: Gentile
- given: Yishay
  family: Mansour
- given: Alberto
  family: Minora
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
pdf: http://proceedings.mlr.press/v49/cesa-bianchi16.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
