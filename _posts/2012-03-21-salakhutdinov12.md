---
title: 'Domain Adaptation: A Small Sample Statistical Approach'
abstract: We study the prevalent problem when a test distribution differs from the
  training distribution. We consider a setting where our training set consists of
  a small number of sample domains, but where we have many samples in each domain.
  Our goal is to generalize to a new domain. For example, we may want to learn a similarity
  function using only certain classes of objects, but we desire that this similarity
  function be applicable to object classes not present in our training sample (e.g.
  we might seek to learn that “dogs are similar to dogs” even though images of dogs
  were absent from our training set). Our theoretical analysis shows that we can select
  many more features than domains while avoiding overfitting by utilizing data-dependent
  variance properties. We present a greedy feature selection algorithm based on using
  T-statistics. Our experiments validate this theory showing that our T-statistic
  based greedy feature selection is more robust at avoiding overfitting than the classical
  greedy procedure.
pdf: http://proceedings.mlr.press/v22/salakhutdinov12/salakhutdinov12.pdf
layout: inproceedings
series: Proceedings of Machine Learning Research
id: salakhutdinov12
month: 0
tex_title: 'Domain Adaptation: A Small Sample Statistical Approach'
firstpage: 960
lastpage: 968
page: 960-968
order: 960
cycles: false
author:
- given: Ruslan
  family: Salakhutdinov
- given: Sham
  family: Kakade
- given: Dean
  family: Foster
date: 2012-03-21
address: La Palma, Canary Islands
publisher: PMLR
container-title: Proceedings of the Fifteenth International Conference on Artificial
  Intelligence and Statistics
volume: '22'
genre: inproceedings
issued:
  date-parts:
  - 2012
  - 3
  - 21
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
