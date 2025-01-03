---
title: "Turbulence Dynamics <br/><br/>"
layout: single-portfolio
excerpt: "<img src='/images/research/gqlx.png' alt=''>"
collection: research
order_number: 20
header: 
  og_image: "research/gqlx.png"
---

In the field of Turbulence, my research has focused on the identification on linear and nonlinear mechanisms in wall-bounded shear flows. My work pioneered
the use of quasilinear approximations as an interventional tool to suppress certain triadic nonlinear interactions like the energy cascade and inverse energy 
transfer in the near-wall region. In particular, I applied the generalized quasilinear (GQL) approximation (Marston et al., PRL 2016) to turbulent channel 
flow at high friction Reynolds numbers (Re_tau=1700), with emphasis on the energy transfer in the streamwise wavenumber space. The flow is decomposed into low- 
and high-streamwise-wavenumber groups, the former of which is solved by considering the full nonlinear equations whereas the latter is obtained from the 
linearized equations around the former. I found that the QL model (one streamwise mode) exhibits a considerably reduced multi-scale behaviour at the given 
moderately high Reynolds number. This is improved significantly by the GQL approximation which incorporates only a few more streamwise Fourier modes into 
the low-wavenumber group, and it reasonably well recovers the distance-from-the-wall scaling in the turbulence statistics and spectra. I proposed that the 
energy transfer from the low- to the high-wavenumber group in the GQL approximation, referred to as the ‘scattering’ mechanism, depends on the neutrally 
stable leading Lyapunov spectrum of the linearized equations for the high-wavenumber group.

<div style="text-align: center; text-justify: inter-word;">
<figure>
    <img src="/images/triad.png" style="max-height: 500px; max-width: 500px;" align="center">
    <figcaption>Set of triadic interactions for energy transfer in turbulent channel flow to (a–c) low and (d–f) high wavenumbers from interactions (a,d) between low wavenumbers 
(LL-L, LL-H), (b,e) between low and high wavenumbers (LH-L, LH-H), and (c,f) between high wavenumbers (HH-L, HH-H). In the GQL approximation, three 
interactions – (a) LL-L, (c) HH-L, (e) LH-H) – are retained out of six in total.</figcaption>
</figure>

</div>

Based on the GQL approximation, I have also proposed a type of decomposition into spanwise Fourier modes that leads to a nonlinear low-wavenumber group 
that supports the self-sustaining process within the given integral length scales, while the linearized high-wavenumber group is not able to do so, unlike 
the GQL models proposed until date, which place a minimal mathematical description for the self-sustaining process across all integral scales. Despite not 
being able to support the self-sustaining process in the high-wavenumber group, these GQL models are found to reproduce some key statistical features in 
the high-wavenumber group solely through the ‘scattering’ mechanism proposed by previous studies. 

<div style="text-align: center; text-justify: inter-word;">
<figure>
    <img src="/images/gqlx_.png" style="max-height: 500px; max-width: 500px;" align="center">
    <figcaption> Instantaneous flow fields of the DNS and GQLX simulations. The blue isosurfaces indicate u' = 2, while the red ones are v' = 0.5.</figcaption>
</figure>

</div>

The GQL approximation is an interesting physics-based reduced-order model that has captured the attention of several groups working in Turbulence. There is
scope for extension of this work in two directions: improving the 'tool' to better agree with Townsend's attached-eddy hypothesis, and exploring the 
addition of other physical effects like rotation or buoyancy, compressibility and the simulation of streamwise-evolving flows like boundary layers.

I use the nature of the GQL approximation to propose numerical experiments suppressing certain triadic nonlinear interactions to study scale interactions 
comprehensively. If you have new ideas on the matter, I am more than happy to collaborate!

## Papers

Hernández, C. G., Cao, K., Herrmann, B., Brunton, S. andMcKeon, B. J. “Toward
data-driven resolvent analysis of nonlinear flows.” *CTR Ann. Res. Briefs* (2024).
[Article](https://ctr.stanford.edu/publications/annual-research-briefs/){: .btn--research} 

Luo, Z., Hernández, C. G. and Hwang, Y. “Generalized quasilinear approximations in
homogeneous shear turbulence.” *Phys. Rev. Fluids* 8, 064604 (2023),
[Article](https://doi.org/10.1103/PhysRevFluids.8.064604){: .btn--research} 

Hernández, C. G., Yang, Q. and Hwang, Y. “Generalised quasilinear approximations of
turbulent channel flow: Part 2. Spanwise triadic scale interactions”.” *J. Fluid Mech.* 944, A34. (2022)
[Article](https://doi.org/10.1017/jfm.2022.499){: .btn--research} 

Hernández, C. G., Yang, Q. and Hwang, Y. “Generalised quasilinear approximations of
turbulent channel flow: Part 1. Streamwise nonlinear energy transfer.” *J. Fluid Mech.* 936, A33. (2022)
[Article](https://doi.org/10.1017/jfm.2022.59){: .btn--research} 

Hernández, C. G. and Hwang, Y. “Spectral energetics of a quasilinear approximation in
uniform shear turbulence.” *J. Fluid Mech.* 904, A11. (2020)
[Article](https://doi.org/10.1017/jfm.2020.678){: .btn--research} 
