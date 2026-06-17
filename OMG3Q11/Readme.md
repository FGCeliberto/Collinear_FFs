# OMG3Q1.1: Toward Precision Fragmentation of $\Omega_{3Q}$ Baryons
## OMeGa baryons with 3 heavy Quarks VFNS FFs

We address the leading-power fragmentation of all-heavy baryons ($\Omega_{3Q}$ states, with $Q=c,b$) in the color-singlet $S$-wave channel. We introduce a new generation of hadron-structure-oriented collinear fragmentation functions, named **$\mbox{\tt OMG3Q1.1}$** [1], which extend and supersede the previous **$\mbox{\tt OMG3Q1.0}$** determinations [2,3].

The $\mbox{\tt OMG3Q1.1}$ sets are based on a Suzuki-inspired heavy-fragmentation framework combined with diquark-like proxy-model calculations for the initial-scale constituent-heavy-quark [4] and gluon [5] channels. The resulting inputs are evolved through a threshold-aware DGLAP evolution implemented within the **$\mbox{\tt HF-NRevo}$** scheme [6-8], which provides a consistent treatment of heavy-parton thresholds and variable-flavor-number evolution for heavy-hadron fragmentation.

Unlike the central-value-only $\mbox{\tt OMG3Q1.0}$ release, the $\mbox{\tt OMG3Q1.1}$ sets feature an uncertainty-aware construction. Perturbative effects are quantified through fragmentation missing higher-order uncertainties (**F-MHOUs**), while nonperturbative effects are estimated through controlled variations of the transverse-momentum parameter entering the bound-state wave function (**F-NPWFs**).

These sources of uncertainty are organized into a replica-based structure. The replicas do not represent Monte Carlo statistical samples, but rather a structured scan over physically motivated perturbative and nonperturbative variations. This organization allows uncertainties to be propagated directly to collider observables while preserving a transparent interpretation of their physical origin.

Final **$\mbox{\tt LHAPDF}$** grids (central values and replicas) are evolved through the **$\mbox{\tt APFEL++}$** library [9].

### Replica structure

The $\mbox{\tt OMG3Q1.1}$ release contains **9 replicas** for each baryonic species ($\Omega_{3c}$ and $\Omega_{3b}$).

| ID | $K_{\mu}$ | $\langle \vec{q}_T^{2} \rangle$ [GeV²] |
|----|-----------|----------------------------------------------|
| 0 | 1.0 | 60 |
| 1 | 1.0 | 55 |
| 2 | 1.0 | 65 |
| 3 | 0.5 | 60 |
| 4 | 0.5 | 55 |
| 5 | 0.5 | 65 |
| 6 | 2.0 | 60 |
| 7 | 2.0 | 55 |
| 8 | 2.0 | 65 |

where

- $K_{\mu}$ controls the perturbative F-MHOU variation;
- $\langle \vec{q}_T^{2} \rangle$ controls the nonperturbative F-NPWF variation.

The central replica corresponds to the default parameter configuration. The full ensemble can be used to construct uncertainty envelopes and to disentangle perturbative and nonperturbative effects in phenomenological applications.

Please acknowledge the following references when using these FF sets!

References for DGLAP-evolved FFs

[1] F.G. Celiberto, *Toward Precision Fragmentation of $\Omega_{3Q}$ Baryons: An Uncertainty-Aware Approach*.

[2] F.G. Celiberto, *Unwinding the rare $\Omega$ sector: Fragmentation of fully charmed baryons from HL-LHC to FCC*, Phys. Rev. D **112** (2025) 074023, arXiv:2505.00776 [hep-ph].

[3] F.G. Celiberto, *Triply Heavy Ω Baryons with JETHAD: A High-Energy Viewpoint*, Symmetry **18** (2026) 29, arXiv:2604.01871 [hep-ph].

References for initial-scale inputs

[4] S.M. Moosavi Nejad, Phys. Rev. D **96** (2017) 114021.

[5] M. Delpasand, S.M. Moosavi Nejad, Phys. Rev. D **99** (2019) 114028.

References for the HF-NRevo evolution framework

[6] F.G. Celiberto, Moriond QCD 2024, arXiv:2405.08221 [hep-ph].

[7] F.G. Celiberto, PoS DIS2024 (2025) 168, arXiv:2406.10779 [hep-ph].

[8] F.G. Celiberto, Acta Phys. Polon. Supp. **18** (2025) 1-A22, arXiv:2412.05661 [hep-ph].

Evolution library

[9] V. Bertone, S. Carrazza, J. Rojo, Comput. Phys. Commun. **185** (2014) 1647-1668, arXiv:1310.1394 [hep-ph].
