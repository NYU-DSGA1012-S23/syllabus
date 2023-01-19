---
title: Week 10, Apr. 4/6
---

### Structure Without Supervision

The neural network architectures from the first part of the course do not incorporate any explicit notion of syntactic
or semantic structure. But does that mean that these models do not use such structures in any way? This week we discover
that many neural networks _create_ structured representations of linguistic features during training without any
explicit supervision. We will also learn various techniques that have been used to discover such features.

Topics
: Interpretability, representation probing, attention visualization, BERTology

Readings
: [Belinkov and Glass (2019)](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00254/43503/Analysis-Methods-in-Neural-Language-Processing-A),
an overview of interpretability in NLP
: [Rogers et al. (2020)](https://aclanthology.org/2020.tacl-1.54/), on BERTology
: [Coenen et al. (2019)](https://arxiv.org/abs/1906.02715), on the "geometry" of BERT representations ([blog post 
version](https://pair-code.github.io/interpretability/bert-tree/))
: [Bibal et al. (2022)](https://aclanthology.org/2022.acl-long.269/), on whether attention is explanation