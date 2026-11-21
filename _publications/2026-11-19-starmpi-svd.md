---
title: "StarMPI-SVD: Distributed-Memory Parallel Star-M Tensor SVD"
collection: publications
category: preprints
permalink: /publication/2026-11-19-starmpi-svd
excerpt: 'The first distributed-memory implementations of the star-M tensor SVDs t-SVDM-I and t-SVDM-II, generalized to N-way tensors, reaching at least 70% parallel efficiency on up to 128 nodes (6144 cores).'
date: 2026-11-19
venue: 'arXiv preprint'
venueurl: 'https://arxiv.org/abs/2611.26451'
paperurl: 'https://arxiv.org/pdf/2611.26451'
doi: '10.48550/arXiv.2611.26451'
authors: '<b>Naman Pesricha</b>, Grey Ballard, Srinivas Eswar, Md Taufique Hussain, Vishwas Rao, Phani Motamarri'
---

Star-M tensor algebra carries the optimal compression of the matrix SVD over to higher-order tensors. This work covers two decompositions: t-SVDM-I, which uses slice-wise truncated SVDs with a prescribed rank, and its adaptive multirank variant t-SVDM-II, which picks slice-wise ranks to meet an error tolerance. Until now these were available only in shared memory.

We present the first distributed-memory implementations of t-SVDM-I and t-SVDM-II, generalized to N-way tensors. They use asynchronous, non-blocking communication for data redistribution and for the key computational kernels. In strong-scaling experiments they reach at least 70% parallel efficiency on up to 128 nodes (6144 cores), and we apply them to application datasets of up to 768 GB.

[arXiv abstract page](https://arxiv.org/abs/2611.26451) · [PDF](https://arxiv.org/pdf/2611.26451)
