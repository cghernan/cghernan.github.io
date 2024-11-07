---
title: "Physics-Informed Model-Order Reduction"
layout: single-portfolio
#excerpt: "<img src='/images/research/f16_mini.png' alt=''>"
excerpt: "<img src='/images/research/ann.png' alt=''>"
collection: research
order_number: 10
header: 
  #og_image: "research/f16_mini.png"
  og_image: "research/ann.png"
---

<nbsp>
<br/><br/>

<img src='/images/f-16_.png'>

I research how to best combine traditional projection-based model-order reduction (PMOR) and machine learning architectures like artificial neural networks
 (ANNs) and Gaussian Processes (GPs) to mitigate the Kolmogorov barrier to reducibility of parametric and/or highly nonlinear, high-dimensional, 
physics-based models. The main objective of this concept is to reduce the dimensionality of the online approximation of the solution beyond what is 
achievable using affine and quadratic approximation manifolds, while maintaining accuracy. In contrast to previous approaches that exploited one form or 
another of machine learning, the training of the ANN/GP part does not involve data whose dimension scales with that of the high-dimensional model; and the 
resulting PROM-ANN/GP can be efficiently hyperreduced using any well-established hyperreduction method. Hence, unlike many other ANN-based model-order 
reduction approaches, the PROM-ANN/GP concept is practical for large-scale and industry-relevant computational problems. The concept has demonstrated
 the computational tractability of its offline stage and the superior wall clock time performance of its online stage for a large-scale, parametric, 
two-dimensional, model problem that is representative of shock-dominated unsteady flow problems. The PROM-ANN concept has also successfully been applied 
to the double-cone hypersonic benchmark problem. 

<div style="text-align: justify; text-justify: inter-word;">
<img src='/images/mach9.7pressure.png'>
<figure>
    <img src="/images/mach9.7pressure.png" style="max-height: 600px; max-width: 600px;" align="center">
    <figcaption>On a fundamental level, I am also interested in carrying out an extensive study of the capabilities of the reduced-order model of canonical flows issued 
from (H)PROM-ANN/GP, </figcaption>
</figure>

</div>

On a fundamental level, I am also interested in carrying out an extensive study of the capabilities of the reduced-order model of canonical flows issued 
from (H)PROM-ANN/GP, including first- and second-order statistics, velocity and energy spectra, pressure components and physical mechanisms at play; as well
 as an investigation of other potential ML algorithms like convolutional neural networks and transformers for arbitrarily nonlinear approximation manifold 
construction. If you are interested in collaborating, feel free to drop me a line!



## Papers

Hernández, C. G., Tezaur, R. and Farhat, C. “Gaussian-process-augmented projection-based model order reduction for mitigating the Kolmogorov barrier to
reducibility.”, *In preparation* (2024).