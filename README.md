# Subspace Identification with Constraints on the Impulse Response

This project is based on the implementation of subspace identification methods with constraints on the impulse response, inspired by the research conducted by Ivan Markovsky and Guillaume Mercère.

## Table of Contents

- [Introduction](#introduction)
- [Acknowledgments](#acknowledgments)

## Introduction

Subspace identification methods may produce unreliable model estimates when a small number of noisy measurements are available. In such cases, the accuracy of the estimated parameters can be improved by using prior knowledge about the system. The prior knowledge considered in this project is constraints on the impulse response.

This method has two steps:

1. Estimation of the impulse response with linear equality and inequality constraints.
2. Realization of the estimated impulse response.

The problem in step 1 is shown to be a convex quadratic programming problem. In the case of prior knowledge expressed as equality constraints, the problem admits a closed-form solution. In the general case of equality and inequality constraints, the solution is computed using standard numerical optimization methods.

authors illustrate the performance of the method on a mass-spring-damper system.

## Acknowledgments

This project is based on research conducted by Ivan Markovsky and Guillaume Mercère. The original research paper can be found [here](https://imarkovs.github.io/publications/ijc-rev.pdf).

### Authors

- **Ivan Markovsky**  
  Department ELEC  
  Vrije Universiteit Brussel (VUB)  
  1050 Brussels, Belgium  
  e-mail: [ivan.markovsky@vub.ac.be](mailto:ivan.markovsky@vub.ac.be)

- **Guillaume Mercère**  
  Laboratoire d’Informatique et d’Automatique pour les Systèmes  
  University of Poitiers  
  LIAS-ENSIP, Bât. B25, 2 rue Pierre Brousse  
  TSA 41105, 86073 Poitiers Cedex 9 - France  
  e-mail: [guillaume.mercere@univ-poitiers.fr](mailto:guillaume.mercere@univ-poitiers.fr)
