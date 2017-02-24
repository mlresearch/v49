---
title: 'Open Problem: Approximate Planning of POMDPs in the class of Memoryless Policies'
abstract: 'Planning plays an important role in the broad class of decision theory.
  Planning has drawn much attention in recent work in the robotics and sequential
  decision making areas. Recently, Reinforcement Learning (RL), as an agent-environment
  interaction problem, has brought further attention to planning methods. Generally
  in RL, one can assume a generative model, e.g. graphical models, for the environment,
  and then the task for the RL agent is to learn the model parameters and find the
  optimal strategy based on these learnt parameters. Based on environment behavior,
  the agent can assume various types of generative models, e.g. Multi Armed Bandit
  for a static environment, or Markov Decision Process (MDP) for a dynamic environment.
  The advantage of these popular models is their simplicity, which results in tractable
  methods of learning the parameters and finding the optimal policy. The drawback
  of these models is again their simplicity: these models usually underfit and underestimate
  the actual environment behavior. For example, in robotics, the agent usually has
  noisy observations of the environment inner state and MDP is not a suitable model.
  More complex models like Partially Observable Markov Decision Process (POMDP) can
  compensate for this drawback. Fitting this model to the environment, where the partial
  observation is given to the agent, generally gives dramatic performance improvement,
  sometimes unbounded improvement, compared to MDP. In general, finding the optimal
  policy for the POMDP model is computationally intractable and fully non convex,
  even for the class of memoryless policies. The open problem is to come up with a
  method to find an exact or an approximate optimal stochastic memoryless policy for
  POMDP models.'
section: open
layout: inproceedings
series: Proceedings of Machine Learning Research
id: azizzadenesheli16b
month: 0
firstpage: 1639
lastpage: 1642
page: 1639-1642
sections: 
author:
- given: Kamyar
  family: Azizzadenesheli
- given: Alessandro
  family: Lazaric
- given: Animashree
  family: Anandkumar
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
pdf: http://proceedings.mlr.press/v49/azizzadenesheli16b.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
