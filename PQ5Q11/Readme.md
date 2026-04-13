# PQ5Q1.1: Multimodal Fragmentation of All-Heavy Pentaquarks: Uncertainty-Aware Predictions for Hadron Colliders
## PentaQuarks with 5 heavy Quarks multimodal VFNS FFs

We address the leading-power fragmentation of fully heavy pentaquarks ($|Q\bar{Q}QQQ\rangle$ $P_{5Q}$ states) in the color-singlet $S$-wave channel. We introduce a new set of hadron-structure-oriented, $\mbox{\emph{multimodal}}$ collinear fragmentation functions, named $\mbox{\tt PQ5Q1.1}$ [1], which extend and supersede the previous $\mbox{\tt PQ5Q1.0}$ set [2].

They rely on an enhanced calculation of the initial-scale input for the constituent heavy-quark fragmentation channel, making them well suited to describe the short-distance emission of either a compact multiquark configuration [3] or a diquark-driven production mechanism [4]. Final $\mbox{\tt LHAPDF}$ grids (central value and replicas) are evolved via the $\mbox{\tt APFEL++}$ library [5].

The $\mbox{\tt PQ5Q1.1}$ functions feature an uncertainty-aware construction, consistently accounting for both perturbative and nonperturbative sources of uncertainty. Perturbative effects are estimated via missing higher-order variations in the fragmentation dynamics (F-MHOUs), while the nonperturbative wave function is modeled through controlled variations of its transverse-momentum structure (NPWF).

These contributions are combined within a replica-like framework, providing a coherent set of FF replicas that encode the combined impact of perturbative and nonperturbative uncertainties. The replica set consists of 18 members, organized into two blocks corresponding to the direct and scalar-diquark production mechanisms. Within each block, the replicas are constructed through a nested scan, where for each choice of energy-scale variation (F-MHOU) the transverse-momentum parameter $\langle {\vec q}_T^{\;2} \rangle$ is varied over the range $\langle {\vec q}_T^{\;2} \rangle = 80,\,90,\,100~\text{GeV}^2$, thus probing NPWF uncertainties.

### Replica structure

| ID | mode    | $K_{\mu}$ | \langle {\vec q}_T^{\;2} \rangle [GeV$^2$] |
|----|--------|-----------|----------------|
| 0  | direct  | 1   | 90  |
| 1  | direct  | 1   | 80  |
| 2  | direct  | 1   | 100 |
| 3  | direct  | 0.5 | 90  |
| 4  | direct  | 0.5 | 80  |
| 5  | direct  | 0.5 | 100 |
| 6  | direct  | 2   | 90  |
| 7  | direct  | 2   | 80  |
| 8  | direct  | 2   | 100 |
| 9  | diquark | 1   | 90  |
| 10 | diquark | 1   | 80  |
| 11 | diquark | 1   | 100 |
| 12 | diquark | 0.5 | 90  |
| 13 | diquark | 0.5 | 80  |
| 14 | diquark | 0.5 | 100 |
| 15 | diquark | 2   | 90  |
| 16 | diquark | 2   | 80  |
| 17 | diquark | 2   | 100 |

- $K_{\mu}$ encodes energy-scale variations (F-MHOUs)  
- $\langle {\vec q}_T^{\;2} \rangle$ corresponds to the NPWF parameter

The central value corresponds to the default parameter configuration, while the replica ensemble can be used to estimate uncertainty bands in phenomenological applications.

This structure allows users to isolate perturbative and nonperturbative effects or combine them consistently in uncertainty estimates.


Please acknowledge references when using these FF sets!  

References for DGLAP-evolved FFs:

[1]&nbsp;&nbsp;F.G. Celiberto, "Multimodal Fragmentation of All-Heavy Pentaquarks: Uncertainty-Aware Predictions for Hadron Colliders".
[2]&nbsp;&nbsp;F.G. Celiberto, "Heavy-fragmentation to S-wave pentacharms at next-generation hadron colliders", Eur. Phys. J. C 85 (2025) 12, 1395 [arXiv:2502.11136 [hep-ph]].  

References for initial-scale inputs:

[3]&nbsp;&nbsp;R. Farasheian, S.M. Moosavi Nejad, Eur. Phys. J. A 60 (2024) 3, 65.    
[4]&nbsp;&nbsp;R. Farasheian, S.M. Moosavi Nejad, Eur. Phys. J. A 60 (2024) 7, 143.  

Other references:

[5]&nbsp;&nbsp;V. Bertone, S. Carrazza, J. Rojo, Comput. Phys. Commun. 185 (2014) 1647-1668 [arXiv:1310.1394 [hep-ph]].  
