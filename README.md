# Portfolio : Simulation numérique & IA physique

Emilie Peynaud |
Ingénieure-chercheuse en mathématiques appliquées et calcul scientifique
(INSA Toulouse, doctorat 2013 - CERFACS / Airbus / CIRAD)

## 🧭 En quelques mots

Je conçois et implémente des modèles numériques pour simuler des systèmes
physiques complexes : des schémas éléments finis rigoureux jusqu'aux approches
hybrides couplant modèles physiques et réseaux de neurones (PINN).

Mes méthodes sont transversales. Mes applications ont couvert :
- la propagation acoustique en écoulement subsonique (aéronautique)
- la dynamique racinaire des plantes
- les dynamiques de biomasse en savane africaine
- la modélisation d'agroforêts à base de cacaoyers (Cameroun)

## 🛠️ Stack technique

| Domaine | Outils |
|---|---|
| Langages | Fortran 90, Python, Julia |
| Librairies ML | TensorFlow, PyTorch |
| Méthodes numériques | FEM (continus, Galerkin-Discontinu), PINN |
| Solveurs | MUMPS, Levenberg-Marquardt |
| Visualisation | ParaView (VTK), Matplotlib |
| Workflow | Git, Make, LaTeX, Dataverse, Software Heritage |

## 💼 Parcours

**CIRAD / UMR AMAP** *(2013 - présent)*
Chercheuse en modélisation mathématique → projets FemRoot, TreeGrass, pydata2pde

**CERFACS / Université de Toulouse** *(2009 - 2013)*
Thèse en mathématiques appliquées → simulation acoustique aéronautique

**EADS Innovation Works (Airbus)** *(2009)*
Stage ingénieure recherche → propagation acoustique turboréacteur

## 📁 Projets

| Projet | Méthode | Langage | Statut |
|---|---|---|---|
| [acoustics-aero](./acoustic-aero/README.md) | EF mixtes continus/discontinus | Fortran | ✅ Publié |
| [femroot](./femroot/README.md) | EF Galerkin-Discontinu + Levenberg-Marquardt | Fortran 90 | ✅ Publié |
| [treegrass](./treegrass/README.md) | EF continus + lumping + positivité | Fortran 90 + Python + Julia | 📝 En cours |
| [pydata2pde](./pydata2pde/README.md) | PINN + workflow CEDI | Python + TensorFlow | ✅ Publié |
| [pinn-pytorch](./pinn-pytorch) | PINN pédagogique 1D | Python + PyTorch | 🔧 WIP |

## 📄 Publications sélectionnées

- **Peynaud E. et al. 2025.** A workflow to discover PDEs from data.
  *MethodsX.* https://doi.org/10.1016/j.mex.2025.103560
- **Bonnet-Ben Dhia et al. 2012.** Time-harmonic acoustic scattering
  in a complex flow. *Communications in Computational Physics.*
  https://doi.org/10.4208/cicp.221209.030111s
- **Peynaud E. 2018.** Operator splitting and DG methods for
  advection-reaction-diffusion. *Biomath.*
  https://doi.org/10.11145/j.biomath.2018.12.037

## 👩‍🏫 Enseignement & encadrement
- +200h de cours de niveau master à l'ENSPY (Cameroun) : méthodes numériques pour les EDP, calcul intensif
- Encadrement de 7 stagiaires et 3 ingénieurs (Cameroun, France) sur des thématiques alliant EDP, apprentissage automatique et traitement de données Lidar 

## 🎬 Présentation vidéo

Data-driven PDE modelling: Trick or treat! (40 min)
https://www.youtube.com/watch?v=SerqycB2Jw0

## 📬 Contact & liens

- [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/emilie-peynaud) ← pour me contacter
- 📧 Email : emilie [dot] peynaud [at] cirad [dot] fr ← pour les collaborations scientifiques