---
title: "Zeta Expansion for Long-Range Interactions under Periodic Boundary Conditions with Applications to Micromagnetics"
collection: publications
category: manuscripts
permalink: /publication/2026-03-24-zeta-expansion-long-range
excerpt: 'This paper addresses the efficient computation of power-law-based interaction potentials of homogeneous n-dimensional bodies with an infinite d-dimensional array of copies, including their higher-order derivatives.'
date: 2026-03-24
venue: 'Journal of Computational Physics'
paperurl: 'https://doi.org/10.1016/j.jcp.2026.114885'
citation: 'Buchheit, A. A., Busse, J. K., Keßler, T., & Rybakov, F. N. (2026). "Zeta Expansion for Long-Range Interactions under Periodic Boundary Conditions with Applications to Micromagnetics." <i>Journal of Computational Physics</i>, 114885. DOI: <a href="https://doi.org/10.1016/j.jcp.2026.114885">10.1016/j.jcp.2026.114885</a>'
---
This work establishes the Epstein zeta function as a powerful tool in numerical analysis by rigorously investigating its analytical properties and enabling its efficient computation. Specifically, we derive a compact and computationally efficient representation of the Epstein zeta function and thoroughly examine its analytical properties across all arguments. Furthermore, we introduce a superexponentially convergent algorithm, complete with error bounds, for computing the Epstein zeta function in arbitrary dimensions. We also show that the Epstein zeta function can be decomposed into a power law singularity and an analytic function in the first Brillouin zone. This decomposition facilitates the rapid evaluation of integrals involving the Epstein zeta function and allows for efficient precomputations through interpolation techniques. We present the first high-performance implementation of the Epstein zeta function and its regularisation for arbitrary real arguments in EpsteinLib, a C library with Python and Mathematica bindings, and rigorously benchmark its precision and performance against known formulas, achieving full precision across the entire parameter range. Finally, we apply our library to the computation of quantum dispersion relations of three-dimensional spin materials with long-range interactions and Casimir energies in multidimensional geometries, uncovering higher-order corrections to known asymptotic formulas for the arising forces.
