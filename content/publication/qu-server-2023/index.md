---
title: 'Server Placement for Edge Computing: A Robust Submodular Maximization Approach'
authors:
- Yuben Qu
- Lihao Wang
- Haipeng Dai
- Weijun Wang
- Chao Dong
- Fan Wu
- Song Guo
date: '2023-06-01'
publishDate: '2024-02-15T11:00:23.718156Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Mobile Computing*'
doi: 10.1109/TMC.2021.3136868
abstract: In this work, we study the problem of Robust Server Placement (RSP) for
  edge computing, i.e., in the presence of uncertain edge server failures, how to
  determine a server placement strategy to maximize the expected overall workload
  that can be served by edge servers. We mathematically formulate the RSP problem
  in the form of robust max-min optimization, derived from two consequentially equivalent
  transformations of the problem that does not consider robustness and followed by
  a robust conversion. RSP is challenging to solve, because the explicit expression
  of the objective function in RSP is hard to obtain, and it is a robust max-min problem
  with knapsack constraints, which is still an unexplored problem in the literature.
  We reveal that the objective function is monotone submodular, and propose two solutions
  to RSP. First, after proving that the involved constraints form a p-independence
  system constraint, where p is a parameter determined by the coefﬁcients in the knapsack
  constraints, we propose an algorithm that achieves a provable approximation ratio
  in polynomial time. Second, we prove that one of the knapsack constraints is a matroid
  contraint, and propose another polynomial time algorithm with a better approximation
  ratio. Furthermore, we discuss the applicability of the aforementioned algorithms
  to the case with an additional server number constraint. Both synthetic and trace-driven
  simulation results show that, given any maximum number of server failures, our proposed
  algorithms outperform four state-of-the-art algorithms and approaches the optimal
  solution, which applies exhaustive exponential searches, while the proposed latter
  algorithm brings extra performance gains compared with the former one.
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/9657204/
---
