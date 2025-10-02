---
title: "Zeta expansion for long-range interactions under periodic boundary conditions with applications to micromagnetics"
collection: publications
category: preprints
permalink: /publication/2025-09-30-zeta-expansion-long-range
excerpt: 'This paper addresses the efficient computation of power-law-based interaction potentials of homogeneous n-dimensional bodies with an infinite d-dimensional array of copies, including their higher-order derivatives.'
date: 2025-09-30
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2509.26274'
citation: 'Buchheit, A. A., Busse, J. K., Keßler, T., & Rybakov, F. N. (2025). &quot;Zeta expansion for long-range interactions under periodic boundary conditions with applications to micromagnetics.&quot; <i>arXiv preprint arXiv:2509.26274</i>.'
---
This work establishes the Epstein zeta function as a powerful tool in numerical analysis by rigorously investigating its analytical properties and enabling its efficient computation. Specifically, we derive a compact and computationally efficient representation of the Epstein zeta function and thoroughly examine its analytical properties across all arguments. Furthermore, we introduce a superexponentially convergent algorithm, complete with error bounds, for computing the Epstein zeta function in arbitrary dimensions. We also show that the Epstein zeta function can be decomposed into a power law singularity and an analytic function in the first Brillouin zone. This decomposition facilitates the rapid evaluation of integrals involving the Epstein zeta function and allows for efficient precomputations through interpolation techniques. We present the first high-performance implementation of the Epstein zeta function and its regularisation for arbitrary real arguments in EpsteinLib, a C library with Python and Mathematica bindings, and rigorously benchmark its precision and performance against known formulas, achieving full precision across the entire parameter range. Finally, we apply our library to the computation of quantum dispersion relations of three-dimensional spin materials with long-range interactions and Casimir energies in multidimensional geometries, uncovering higher-order corrections to known asymptotic formulas for the arising forces.
