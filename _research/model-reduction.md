---
title: "Model Reduction"
layout: single-portfolio
excerpt: "<img src='/images/research/epr.png' alt=''>"
collection: research
order_number: 10
header: 
  og_image: "research/f16-mini.png"
---

Physics-informed model-order reduction


I research how to best combine traditional projection-based model-order reduction (PMOR) and machine learning architectures like artificial neural networks
 (ANNs) and Gaussian Processes (GPs) to mitigate the Kolmogorov barrier to reducibility of parametric and/or highly nonlinear, high-dimensional, 
physics-based models. The main objective of this concept is to reduce the dimensionality of the online approximation of the solution beyond what is 
achievable using affine and quadratic approximation manifolds, while maintaining accuracy. In contrast to previous approaches that exploited one form or 
another of machine learning, the training of the ANN/GP part does not involve data whose dimension scales with that of the high-dimensional model; and the 
resulting PROM-ANN/GP can be efficiently hyperreduced using any well-established hyperreduction method. Hence, unlike many other ANN-based model-order 
reduction approaches, the PROM-ANN/GP concept is practical for large-scale and industry-relevant computational problems. The concept has demonstrated
 the computational tractability of its offline stage and the superior wall clock time performance of its online stage for a large-scale, parametric, 
two-dimensional, model problem that is representative of shock-dominated unsteady flow problems. The PROM-ANN concept has also successfully been applied 
to the double-cone hypersonic benchmark problem. On a fundamental level, I am also interested in carrying out an extensive study of the capabilities of 
the reduced-order model of canonical flows issued from (H)PROM-ANN/GP, including first- and second-order statistics, velocity and energy spectra, pressure
components and physical mechanisms at play; as well as an investigation of other potential ML algorithms like convolutional neural networks and transformers
for arbitrarily nonlinear approximation manifold construction. If you are interested in collaborating, feel free to drop me a line!

## Article

Rob Williams. "Turning the Lights on to Keep Them in the Fold: How Governments Preempt Secession Attempts." *Conflict management and Peace Science*.

> There are many regions that meet the necessary conditions for sovereign governance in the world, but few secessionist conflicts. I argue that this relative paucity of secessionist violence is the result of government preemption of potential secessionist movements. Using cross-national geospatial data from 1992 to 2013, I find that governments invest more, measured via nighttime light emissions, in more secession-prone regions. The same factors that make territory attractive for secession, such as large populations and international borders, also make governments willing to work to retain control of that territory, contributing to the scarcity of separatist civil conflicts.

[Article](https://doi.org/10.1177/07388942211015242){: .btn--research} [Preprint](/files/pdf/research/Turning the Lights on.pdf){: .btn--research} [Supplemental Information](/files/pdf/research/Turning the Lights on SI.pdf){: .btn--research} [Replication Archive](https://journals.sagepub.com/doi/suppl/10.1177/07388942211015242){: .btn--research} [GitHub Repo](https://github.com/jayrobwilliams/conflict-preemption){: .btn--research} [Poster](/files/pdf/research/PSS 2018 Poster.pdf){: .btn--research}
