[← Retour au portfolio](../README.md)

# FemRoot : Simulation numérique de dynamiques racinaires

## Contexte
Développement autonome au CIRAD (UMR AMAP). Modélisation de la croissance
racinaire en 2D par résolution d'une équation d'advection-réaction-diffusion
temporelle.

## Méthodes
- Splitting d'opérateur
- Éléments finis de type Galerkin-Discontinu
- Estimation de paramètres par algorithme de Levenberg-Marquardt
- Inversion de la matrice EF via la librairie MUMPS
- Étude numérique de la positivité de la solution

## Stack
Fortran 90 - MUMPS - Make - ParaView (sorties VTK) - GitLab institutionnel


## Publication
Peynaud E. 2018. Operator splitting and discontinuous Galerkin methods
for advection-reaction-diffusion problem: application to plant root growth.
Biomath, 7(2). https://doi.org/10.11145/j.biomath.2018.12.037

---
[← Retour au portfolio](../README.md)