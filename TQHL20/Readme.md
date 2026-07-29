# TQHL2.0: Multimodal Fragmentation of Hidden-Heavy Scalar Tetraquarks with HF-NRevo
## State-driven multimodal ZM-VFNS fragmentation functions for hidden-heavy scalar tetraquarks

The **TQHL2.0** project provides a new generation of multimodal collinear fragmentation functions (FFs) for hidden-heavy scalar tetraquarks within the Zero-Mass Variable-Flavor Number Scheme (ZM-VFNS). It extends the previous **TQHL1.1** [2] and **TQHL1.0** [3,4] releases by introducing a **state-driven** description of heavy-flavor fragmentation, where different microscopic production mechanisms are associated with the internal structure of the produced exotic hadron.

The present release focuses on the hidden-heavy scalar tetraquark states

- $X(3860)$,
- $X(3960)$,
- $X_b(s)$,

which provide representative benchmarks for the hidden-charm and hidden-bottom sectors.

The initial conditions combine two complementary fragmentation mechanisms. The **direct** mode describes the fragmentation of a heavy quark into a compact tetraquark through a Suzuki-inspired approach [5,6], while the **scalar-diquark** mode implements a sequential production mechanism mediated by an intermediate heavy-light scalar diquark [7]. Both mechanisms are consistently embedded into the **Heavy-Flavor NonRelativistic Evolution (HF-NRevo)** timelike scheme [8,9], and the final LHAPDF grids (central values and replicas) are generated using all-order numerical DGLAP evolution.

The TQHL2.0 FFs feature an uncertainty-aware construction that consistently combines perturbative and nonperturbative sources of uncertainty. Perturbative effects are estimated through fragmentation missing higher-order uncertainties (F-MHOUs)) through energy-scale variations, while nonperturbative wave-function effects (F-NPWFs) are modeled via controlled variations of the intrinsic transverse-momentum parameter entering the Suzuki-inspired initial conditions.

The resulting replica ensemble provides a unified determination of fragmentation uncertainties for both production mechanisms. This structure allows perturbative and nonperturbative effects to be investigated separately or combined consistently in phenomenological applications.

Each production mechanism is represented by nine replicas obtained from a nested scan of perturbative and nonperturbative parameters, giving a total of eighteen FF sets.

### Replica structure

| ID | mode    | $K_{\mu}$ | $\langle {\vec q}_T^{2} \rangle$ [GeV²] |
|----|--------|-----------|----------------|
| 0  | direct  | 1   | 4   |
| 1  | direct  | 1   | 3.5 |
| 2  | direct  | 1   | 4.5 |
| 3  | direct  | 0.5 | 4   |
| 4  | direct  | 0.5 | 3.5 |
| 5  | direct  | 0.5 | 4.5 |
| 6  | direct  | 2   | 4   |
| 7  | direct  | 2   | 3.5 |
| 8  | direct  | 2   | 4.5 |
| 9  | diquark | 1   | 4   |
| 10 | diquark | 1   | 3.5 |
| 11 | diquark | 1   | 4.5 |
| 12 | diquark | 0.5 | 4   |
| 13 | diquark | 0.5 | 3.5 |
| 14 | diquark | 0.5 | 4.5 |
| 15 | diquark | 2   | 4   |
| 16 | diquark | 2   | 3.5 |
| 17 | diquark | 2   | 4.5 |

- $K_{\mu}$ encodes energy-scale variations (F-MHOUs)  
- $\langle {\vec q}_T^{2} \rangle$ corresponds to the F-NPWF parameter

The central value corresponds to the default parameter configuration, while the replica ensemble can be used to estimate uncertainty bands in phenomenological applications.

This structure allows users to isolate perturbative and nonperturbative effects or combine them consistently in uncertainty estimates.

## Physics highlights

The TQHL2.0 framework introduces a state-driven description of hidden-heavy tetraquark fragmentation.

The framework provides the first uncertainty-aware determination of multimodal FFs for hidden-heavy scalar tetraquarks.

Rather than assuming a universal production mechanism, the relative importance of the direct and scalar-diquark fragmentation modes depends on the internal structure of the produced tetraquark. This behavior naturally propagates from the fragmentation functions to collider observables, making rapidity-dependent tetraquark-plus-jet production a sensitive probe of exotic-hadron formation.

These FF sets are intended for precision phenomenological studies of hidden-heavy scalar tetraquark production at current and future colliders.


## References

Please acknowledge references when using these FF sets!  

References for DGLAP-evolved FFs:

[1]&nbsp;&nbsp;F.G. Celiberto, "Multimodal Fragmentation of Hidden-Heavy Scalar Tetraquarks with HF-NRevo".  
[2]&nbsp;&nbsp;F.G. Celiberto and G. Gatto, "Bottomonium-like states in proton collisions: Fragmentation and resummation" Phys.Rev.D 111 (2025) 3, 3 [arXiv:2412.10549 [hep-ph]].  
[3]&nbsp;&nbsp;F.G. Celiberto and A. Papa, "A high-energy QCD portal to exotic matter: Heavy-light tetraquarks at the HL-LHC", Phys. Lett. B 848 (2024) 138406 [arXiv:2308.00809 [hep-ph]].  
[4]&nbsp;&nbsp;F.G. Celiberto, "Exotic Tetraquarks at the HL-LHC with JETHAD: A High-Energy Viewpoint", Symmetry 16 (2024) 5, 550 [arXiv:2403.15639 [hep-ph]]. 

References for initial-scale inputs:

[5]&nbsp;&nbsp;M. Suzuki, Phys. Rev. D 33 (1986) 676.  
[6]&nbsp;&nbsp;S.M. Moosavi Nejad and N. Amiri, Phys. Rev. D 112 (1) (2025) 056020.  
[7]&nbsp;&nbsp;S.M. Moosavi Nejad and N. Amiri, Phys. Rev. D 105 (3) (2022) 034001 [arXiv:2110.15251 [hep-ph]].  

References for HF-NRevo:

[8]&nbsp;&nbsp;F.G. Celiberto and F. Lonigro, "Pseudoscalar heavy-quarkonium hadroproduction from nonrelativistic fragmentation at NLL/NLO+", Phys. Rev. D 112 (2025) 11, 114040 [arXiv:2510.10593 [hep-ph]].  
[9]&nbsp;&nbsp;F.G. Celiberto, "Towards Quarkonium Fragmentation from NRQCD in a Variable-Flavor Number Scheme", Moriond QCD 2024 [arXiv:2405.08221 [hep-ph]]. 
