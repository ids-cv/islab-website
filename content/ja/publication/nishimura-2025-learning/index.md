---
title: Learning Relative Gene Expression Trends from Pathology Images in Spatial Transcriptomics
authors:
- Kazuya Nishimura
- Haruka Hirose
- Ryoma Bise
- Kaito Shiku
- Yasuhiro Kojima
date: '2025-01-01'
publishDate: '2025-12-09T01:20:22.534885Z'
publication_types:
- paper-conference
publication: '*The Thirty-ninth Annual Conference on Neural Information Processing
  Systems (Neurips)*'
abstract: Gene expression estimation from pathology images has the potential to reduce
  the RNA sequencing cost. Point-wise loss functions have been widely used to minimize
  the discrepancy between predicted and absolute gene expression values.  However,
  due to the complexity of the sequencing techniques and intrinsic variability across
  cells, the observed gene expression contains stochastic noise and batch effects,
  and estimating the absolute expression values accurately remains a significant challenge.
  To mitigate this, we propose a novel objective of learning relative expression patterns
  rather than absolute levels. We assume that the relative expression levels of genes
  exhibit consistent patterns across independent experiments, even when absolute expression
  values are affected by batch effects and stochastic noise in tissue samples. Based
  on the assumption, we model the relation and propose a novel loss function called
  STRank that is robust to noise and batch effects. Experiments using synthetic datasets
  and real datasets demonstrate the effectiveness of the proposed method. The code
  is available at https://github.com/naivete5656/STRank.
---
