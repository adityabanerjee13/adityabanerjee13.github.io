---
title: "Trainable Nonexpansive Denoisers for Contractive Image Reconstruction"
collection: publications
category: conferences
permalink: /publication/2026-trainable-nonexpansive-denoisers
excerpt: 'A neural network predicts similarity weights while a fixed linear operator does the averaging, so plug-and-play reconstruction is provably contractive. Code: [github.com/arghyasinha/nectr](https://github.com/arghyasinha/nectr).'
date: 2026-07-01
venue: 'International Conference on Machine Learning (ICML)'
paperurl: 'https://arxiv.org/abs/2607.23347'
citation: 'Arghya Sinha, Aditya Banerjee, Trishit Mukherjee, Kunal N. Chaudhury. (2026). &quot;Trainable Nonexpansive Denoisers for Contractive Image Reconstruction.&quot; <i>International Conference on Machine Learning (ICML)</i>.'
---

Plug-and-play methods use a denoiser as the image prior inside an iterative solver. Strong learned denoisers can make that loop diverge. This work keeps the learning in the similarity weights and makes the aggregation a symmetric, stochastic linear operator, so the reconstruction converges to a unique fixed point.

My contribution: linear denoisers (bilateral filtering, non-local means) for deblurring, inpainting and super-resolution, a faster weight computation, and the open-source contribution to [deepinv](https://github.com/deepinv/deepinv).

[Paper (arXiv)](https://arxiv.org/abs/2607.23347) · [Code](https://github.com/arghyasinha/nectr)
