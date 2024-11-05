---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My academic research falls into three main areas: (1) Physics-informed model-order reduction, (2) Turbulence dynamics, and (3) Laminar-turbulent transition
in high-speed flows.

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
to the double-cone hypersonic benchmark problem.

Turbulence dynamics

In the field of Turbulence, my research has focused on the identification on linear and nonlinear mechanisms in wall-bounded shear flows. My work pioneered
the use of quasilinear approximations as an interventional tool to suppress certain triadic nonlinear interactions like the energy cascade and inverse energy 
transfer in the near-wall region. In particular, I applied the generalized quasilinear (GQL) approximation (Marston et al., PRL 2016) to turbulent channel 
flow at high friction Reynolds numbers (Reτ≃1700), with emphasis on the energy transfer in the streamwise wavenumber space. The flow is decomposed into low- 
and high-streamwise-wavenumber groups, the former of which is solved by considering the full nonlinear equations whereas the latter is obtained from the 
linearized equations around the former. I found that the QL model (one streamwise mode) exhibits a considerably reduced multi-scale behaviour at the given 
moderately high Reynolds number. This is improved significantly by the GQL approximation which incorporates only a few more streamwise Fourier modes into 
the low-wavenumber group, and it reasonably well recovers the distance-from-the-wall scaling in the turbulence statistics and spectra. I proposed that the 
energy transfer from the low- to the high-wavenumber group in the GQL approximation, referred to as the ‘scattering’ mechanism, depends on the neutrally 
stable leading Lyapunov spectrum of the linearized equations for the high-wavenumber group.


using a flow decomposition defined with spanwise Fourier modes: the flow is decomposed into a set of low-wavenumber spanwise Fourier modes and 
the rest high-wavenumber modes. This decomposition leads to the nonlinear low-wavenumber group that supports the self-sustaining process within the given 
integral length scales, whereas the linearised high-wavenumber group is not able to do so, unlike the GQL models in Part 1, which place a minimal 
mathematical description for the self-sustaining process across all integral scales. Despite not being able to support the self-sustaining process in the 
high-wavenumber group, the GQL models in the present study are found to reproduce some key statistical features in the high-wavenumber group solely through 
the ‘scattering’ mechanism proposed by previous studies. Finally, using the nature of the GQL approximation, a further set of numerical experiments 
suppressing certain triadic nonlinear interactions are carried out.


Laminar-turbulent transition in high-speed flows

HERNÁNDEZ, C. G. & WU, X. 2019 “Receptivity of supersonic boundary layers over smooth and wavy surfaces to impinging slow acoustic waves” J. Fluid Mech., 872, 849-888
Two receptivity mechanisms are considered. The first is new, involving the interaction of two acoustic waves and operating in a boundary layer over a smooth wall. The second involves the interaction between an acoustic wave and the steady perturbation induced by a wavy wall. Both interactions generate a forcing in resonance with a neutral Tollmien–Schlichting (T–S) wave. The latter is thus excited near the lower branch of the neutral curve, and subsequently undergoes exponential amplification. The two receptivity processes with the acoustic waves on the triple-deck scale are much more effective compared with those involving usual sound waves, with the coupling coefficient being greater by a factor of O(R^1/4) and O(R^1/8) in the sound–sound and sound–roughness interactions, respectively. A parametric study for both the reflection and coupling coefficients is conducted for representative T–S waves, to assess the influence of the streamwise and spanwise wavenumbers, and the phase speed (or frequency) of the acoustic wave.







<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
