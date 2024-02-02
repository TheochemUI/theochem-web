---
title: Method for Calculating Excited Electronic States Using Density Functionals
  and Direct Orbital Optimization with Real Space Grid or Plane-Wave Basis Set
authors:
- Aleksei V. Ivanov
- Gianluca Levi
- Elvar Ö. Jónsson
- Hannes Jónsson
date: '2021-07-01'
publishDate: '2024-02-02T14:14:57.380030Z'
publication_types:
- article-journal
publication: '*Journal of Chemical Theory and Computation*'
doi: 10.1021/acs.jctc.1c00157
abstract: 'A direct orbital optimization method is presented for density functional
  calculations of excited electronic states using either a real space grid or a plane-wave
  basis set. The method is variational, provides atomic forces in the excited states,
  and can be applied to Kohn−Sham (KS) functionals as well as orbital-density-dependent
  (ODD) functionals including explicit self-interaction correction. The implementation
  for KS functionals involves two nested loops: (1) An inner loop for finding a stationary
  point in a subspace spanned by the occupied and a few virtual orbitals corresponding
  to the excited state; (2) an outer loop for minimizing the energy in a tangential
  direction in the space of the orbitals. For ODD functionals, a third loop is used
  to find the unitary transformation that minimizes the energy functional among occupied
  orbitals only. Combined with the maximum overlap method, the algorithm converges
  in challenging cases where conventional self-consistent field algorithms tend to
  fail. The benchmark tests presented include two charge-transfer excitations in nitrobenzene
  and an excitation of CO to degenerate $π$* orbitals where the importance of complex
  orbitals is illustrated. The application of this method to several metal-to-ligand
  charge-transfer and metal-centered excited states of an Fe II photosensitizer complex
  is described, and the results are compared to reported experimental estimates. This
  method is also used to study the effect of the Perdew−Zunger self-interaction correction
  on valence and Rydberg excited states of several molecules, both singlet and triplet
  states, and the performance compared to semilocal and hybrid functionals.'
links:
- name: arXiv
  url: https://arxiv.org/abs/2102.06542
- name: URL
  url: https://pubs.acs.org/doi/10.1021/acs.jctc.1c00157
---
