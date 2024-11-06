---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}

<div style="text-align: justify; text-justify: inter-word;">

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
to the double-cone hypersonic benchmark problem. On a fundamental level, I am also interested in carrying out an extensive study of the capabilities of 
the reduced-order model of canonical flows issued from (H)PROM-ANN/GP, including first- and second-order statistics, velocity and energy spectra, pressure
components and physical mechanisms at play; as well as an investigation of other potential ML algorithms like convolutional neural networks and transformers
for arbitrarily nonlinear approximation manifold construction. If you are interested in collaborating, feel free to drop me a line!

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

Based on the GQL approximation, I have also proposed a type of decomposition into spanwise Fourier modes that leads to a nonlinear low-wavenumber group 
that supports the self-sustaining process within the given integral length scales, while the linearized high-wavenumber group is not able to do so, unlike 
the GQL models proposed until date, which place a minimal mathematical description for the self-sustaining process across all integral scales. Despite not 
being able to support the self-sustaining process in the high-wavenumber group, these GQL models are found to reproduce some key statistical features in 
the high-wavenumber group solely through the ‘scattering’ mechanism proposed by previous studies. 

The GQL approximation is an interesting physics-based reduced-order model that has captured the attention of several groups working in Turbulence. There is
scope for extension of this work into two

I use the nature of the GQL approximation to propose numerical experiments suppressing certain triadic nonlinear interactions to study scale interactions 
comprehensively. If you have new ideas on the matter, I am more than happy to collaborate!


Laminar-turbulent transition in high-speed flows


I am interested in the receptivity of high-speed boundary layers, the process in which external perturbations (e.g. oncoming sound waves, free-stream 
turbulence and entropy, and localized or distributed roughness) excite instability modes. These intrinsic instabilities may amplify to attain amplitudes 
far above those of the external disturbances, eventually leading the boundary layer to turbulence. Instability modes that may arise depend on the Mach 
number. In the subsonic regime, they are Tollmien-Schlichting (T-S) waves, which have a viscous origin. In the super- and hypersonic regimes, there exist 
multiple families of modes (Mack, 1984) including the so-called first Mack modes, which are continuation of T-S modes into the compressible regime, and 
the second Mack modes, which are essentially inviscid.

I have worked on two new receptivity mechanisms. The first is new, involving the interaction of two acoustic waves and operating in a boundary layer over 
a smooth wall. The second involves the interaction between an acoustic wave and the steady perturbation induced by a wavy wall. Both interactions generate 
a forcing in resonance with a neutral Tollmien–Schlichting (T–S) wave. The latter is thus excited near the lower branch of the neutral curve, and 
subsequently undergoes exponential amplification. The two receptivity processes with the acoustic waves on the triple-deck scale are found to be much more 
effective compared with those involving usual sound waves, with the coupling coefficient being greater by a factor of O(R^1/4) and O(R^1/8) in the 
sound–sound and sound–roughness interactions, respectively.

I am currently working on other receptivity mechanisms pertaining to high-speed boundary layers, and am looking to compare the high-Reynolds-number
asymptotics results to numerical simulations and experiments. Receptivity has received far less attention than Instability, and there are a number of
low-hanging fruits to be collected in this area. If you are an asymptotician, a numericist or an experimentalist, feel free to reach out!



</div>


<nbsp>






