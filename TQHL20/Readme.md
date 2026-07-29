# TQHL2.0: Multimodal Fragmentation of Hidden-Heavy Scalar Tetraquarks with HF-NRevo
## TetraQuarks with Heavy and Light flavor multimodal, state-driven VFNS FFs

We address the leading-power fragmentation of all-charm pentaquarks ($|c\bar{c}ccc\rangle$ $P_{5c}$ pentacharms) in the color-singlet $S$-wave channel. We introduce a new set of hadron-structure-oriented, $\mbox{\emph{multimodal}}$ collinear fragmentation functions, named $\mbox{\tt TQHL2.0}$ [1], which extend the previous $\mbox{\tt TQHL1.1}$ [2] and $\mbox{\tt TQHL1.0}$ [3,4] implementations.

They rely on an enhanced calculation of the Suzuki-like initial-scale input [5] for the charm-quark fragmentation channel, making them well suited to describe the short-distance emission of either a compact multiquark configuration [6] or a diquark-driven production mechanism [7]. Final $\mbox{\tt LHAPDF}$ grids (central value and replicas) are evolved via the $\mbox{\tt APFEL++}$ library [8].

The $\mbox{\tt TQHL2.0}$ functions feature an uncertainty-aware construction, consistently accounting for both perturbative and nonperturbative sources of uncertainty. Perturbative effects are estimated via missing higher-order variations in the fragmentation dynamics (F-MHOUs), while the nonperturbative wave function is modeled through controlled variations of its transverse-momentum structure (F-NPWF).

These contributions are combined within a replica-like framework, providing a coherent set of FF replicas that encode the combined impact of perturbative and nonperturbative uncertainties. The replica set consists of 18 members, organized into two blocks corresponding to the direct and scalar-diquark production mechanisms. Within each block, the replicas are constructed through a nested scan, where for each choice of energy-scale variation (F-MHOU) the transverse-momentum parameter $\langle {\vec q}_T^{2} \rangle$ is varied over the range $\langle {\vec q}_T^{2} \rangle = 80,\,90,\,100~\text{GeV}^2$, thus probing F-NPWF uncertainties.

### Replica structure

| ID | mode    | $K_{\mu}$ | $\langle {\vec q}_T^{2} \rangle$ [GeV²] |
|----|--------|-----------|----------------|
| 0  | direct  | 1   | 4   |
| 1  | direct  | 1   | 3,5 |
| 2  | direct  | 1   | 4,5 |
| 3  | direct  | 0.5 | 4   |
| 4  | direct  | 0.5 | 3,5 |
| 5  | direct  | 0.5 | 4,5 |
| 6  | direct  | 2   | 4   |
| 7  | direct  | 2   | 3,5 |
| 8  | direct  | 2   | 4,5 |
| 9  | diquark | 1   | 4   |
| 10 | diquark | 1   | 3,5 |
| 11 | diquark | 1   | 4,5 |
| 12 | diquark | 0.5 | 4   |
| 13 | diquark | 0.5 | 3,5 |
| 14 | diquark | 0.5 | 4,5 |
| 15 | diquark | 2   | 4   |
| 16 | diquark | 2   | 3,5 |
| 17 | diquark | 2   | 4,5 |

- $K_{\mu}$ encodes energy-scale variations (F-MHOUs)  
- $\langle {\vec q}_T^{2} \rangle$ corresponds to the F-NPWF parameter

The central value corresponds to the default parameter configuration, while the replica ensemble can be used to estimate uncertainty bands in phenomenological applications.

This structure allows users to isolate perturbative and nonperturbative effects or combine them consistently in uncertainty estimates.


Please acknowledge references when using these FF sets!  

References for DGLAP-evolved FFs:

[1]&nbsp;&nbsp;F.G. Celiberto, "Multimodal Fragmentation of Hidden-Heavy Scalar Tetraquarks with HF-NRevo".  
[2]&nbsp;&nbsp;F.G. Celiberto and G. Gatto, "Bottomonium-like states in proton collisions: Fragmentation and resumamtion" Phys.Rev.D 111 (2025) 3, 3 [arXiv:2412.10549 [hep-ph]].  
[3]&nbsp;&nbsp;F.G. Celiberto and A. Papa, "A high-energy QCD portal to exotic matter: Heavy-light tetraquarks at the HL-LHC", Phys. Lett. B 848 (2024) 138406 [arXiv:2308.00809 [hep-ph]].  
[4]&nbsp;&nbsp;F.G. Celiberto, "Exotic Tetraquarks at the HL-LHC with JETHAD: A High-Energy Viewpoint", Symmetry 16 (2024) 5, 550 [arXiv:2403.15639 [hep-ph]]. 

References for initial-scale inputs:

[5]&nbsp;&nbsp;M. Suzuki, Phys. Rev. D 33 (1986) 676.  
[6]&nbsp;&nbsp;S.M. Moosavi Nejad and N. Amiri, Phys. Rev. D 112 (1) (2025) 056020.  
[7]&nbsp;&nbsp;S.M. Moosavi Nejad and N. Amiri, Phys. Rev. D 105 (3) (2022) 034001 [arXiv:2110.15251 [hep-ph]].  

Other references:

[8]&nbsp;&nbsp;V. Bertone, S. Carrazza, J. Rojo, Comput. Phys. Commun. 185 (2014) 1647-1668 [arXiv:1310.1394 [hep-ph]].  
