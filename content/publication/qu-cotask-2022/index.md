---
title: 'CoTask: Correlation-aware task offloading in edge computing'
authors:
- Yuben Qu
- Haipeng Dai
- Lihao Wang
- Weijun Wang
- Fan Wu
- Haisheng Tan
- Shaojie Tang
- Chao Dong
date: '2022-09-01'
publishDate: '2024-02-15T11:00:23.710142Z'
publication_types:
- article-journal
publication: '*World Wide Web*'
doi: 10.1007/s11280-022-01047-w
abstract: In this paper, we first study the problem of Correlation-aware Task computation
  offloading (CoTask) in mobile edge computing. Specifically, considering the correlation
  among multiple computation tasks, we study how to determine a joint task offloading
  decision and resource allocation strategy under the constraints of feasible offloading
  decisions and edge servers’ computation capacity, such that the overall task latency
  is minimized. Before addressing the challenging CoTask problem, we first investigate
  the case without considering task correlation, namely, NonCoTask. We prove that,
  NonCoTask with two combinatorial integer-continuous optimization variables (i.e.,
  integral offloading decision variable and continuous resource allocation variable)
  can be equivalently solved by solving a 0-1 integer programming problem with respect
  to the offloading decision variable only, while the closed-form optimal resource
  allocation can be efficiently obtained under any given offloading decision. The
  0-1 integer programming problem further falls into the realm of minimizing a supermodular
  set function with a matroid base constraint. We then propose a performance-guaranteed
  algorithm for NonCoTask. Next, we rigorously analyze the performance gap between
  CoTask and NonCoTask, and develop a correlation-aware offloading decision and resource
  allocation algorithm with theoretic performance guarantee for CoTask, via a correlation-aware
  exchange search based on the solution to NonCoTask. Extensive evaluation results
  show that our proposed algorithm outperforms several stateof-the-art algorithms
  as well as their enhanced counterparts with correlation in terms of overall task
  latency.
links:
- name: URL
  url: https://link.springer.com/10.1007/s11280-022-01047-w
---
