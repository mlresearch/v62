---
title: Efficient Algorithms for Checking Avoiding Sure Loss
abstract: Sets of desirable gambles provide a general representation of uncertainty
  which can handle partial information in a more robust way than precise probabilities.
  Here we study the effectiveness of linear programming algorithms for determining
  whether or not a given set of desirable gambles avoids sure loss (i.e. is consistent).
  We also suggest improvements to these algorithms specifically for checking avoiding
  sure loss. By exploiting the structure of the problem, (i) we slightly reduce its
  dimension, (ii) we propose an extra stopping criterion based on its degenerate structure,
  and (iii) we show that one can directly calculate feasible starting points in various
  cases, therefore reducing the effort required in the presolve phase of some of these
  algorithms. To assess our results, we compare the impact of these improvements on
  the simplex method and two interior point methods (affine scaling and primal-dual)
  on randomly generated sets of desirable gambles that either avoid or do not avoid
  sure loss. We find that the simplex method is outperformed by the primal-dual and
  affine scaling methods, except for very small problems. We also find that using
  our starting feasible point and extra stopping criterion considerably improves the
  performance of the primal-dual and affine scaling methods.
crossref: isipta17
layout: inproceedings
series: Proceedings of Machine Learning Research
id: nakharutai17a
month: 0
tex_title: Efficient Algorithms for Checking Avoiding Sure Loss
firstpage: 241
lastpage: 252
page: 241-252
order: 241
cycles: false
author:
- given: Nawapon
  family: Nakharutai
- given: Matthias C. M.
  family: Troffaes
- given: Camila C. S.
  family: Caiado
date: 2017-06-20
address: 
publisher: PMLR
container-title: 'Proceedings of the Tenth International Symposium on Imprecise Probability:
  Theories and Applications'
volume: '62'
genre: inproceedings
issued:
  date-parts:
  - 2017
  - 6
  - 20
pdf: http://proceedings.mlr.press/v62/nakharutai17a/nakharutai17a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
