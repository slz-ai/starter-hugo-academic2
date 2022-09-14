---
title: Heterogeneous Federated Learning via Grouped Sequential-to-Parallel Training
publication_types:
  - "1"
authors:
  - Shenglai Zeng
  - Zonghang Li
  - Hongfang Yu
  - Yihong He
  - Zenglin Xu
  - Dusit Niyato
  - and Han Yu
publication: DASFAA
publication_short: ""
abstract: >-
  Federated learning (FL) is a rapidly growing privacy preserving collaborative
  machine learning paradigm. In practical FL applications, local data from each
  data silo reflect local usage patterns.

  Therefore, there exists heterogeneity of data distributions among data

  owners (a.k.a. FL clients). If not handled properly, this can lead to model

  performance degradation. This challenge has inspired the research field of

  heterogeneous federated learning, which currently remains open. In this

  paper, we propose a data heterogeneity-robust FL approach, FedGSP,

  to address this challenge by leveraging on a novel concept of dynamic

  Sequential-to-Parallel (STP) collaborative training. FedGSP assigns FL

  clients to homogeneous groups to minimize the overall distribution di-

  vergence among groups, and increases the degree of parallelism by reas-

  signing more groups in each round. It is also incorporated with a novel

  Inter-Cluster Grouping (ICG) algorithm to assist in group assignment,

  which uses the centroid equivalence theorem to simplify the NP-hard

  grouping problem to make it solvable. Extensive experiments have been

  conducted on the non-i.i.d. FEMNIST dataset. The results show that

  FedGSP improves the accuracy by 3.7% on average compared with seven

  state-of-the-art approaches, and reduces the training time and commu-

  nication overhead by more than 90%
draft: false
featured: false
tags: []
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
summary: ""
date: 2022-09-14T07:26:12.763Z
---
