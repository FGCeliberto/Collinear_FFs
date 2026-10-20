# TQ4Qhf1.0: Multimodal Fragmentation of All-Heavy Mixed-Flavor Tetraquarks with HF-NRevo
## Multimodal ZM-VFNS fragmentation functions for the all-heavy mixed-flavor $X_{b\bar b c\bar c}$ tetraquark

The **TQ4Qhf1.0** project [1] provides a new generation of multimodal collinear fragmentation functions (FFs) for the all-heavy mixed-flavor tetraquark $X_{b\bar b c\bar c}$ within the Zero-Mass Variable-Flavor Number Scheme (ZM-VFNS).

The present release extends the heavy-flavor fragmentation program to tetraquark configurations containing both charm and bottom constituents, providing a unified description of alternative microscopic formation mechanisms.

The TQ4Qhf1.0 functions describe the production of the hypothetical color-singlet $S$-wave tetraquark

- $X_{b\bar b c\bar c}$, with $J^{PC}=0^{++}$,

through both charm- and bottom-initiated fragmentation channels.

The initial conditions combine two complementary fragmentation mechanisms. The **direct-multiquark** mode describes the fragmentation of a constituent heavy quark into a compact tetraquark through a Suzuki-inspired approach [2,3], while the **scalar-diquark** mode implements a sequential production mechanism mediated by an intermediate mixed-flavor scalar diquark [4].

Both mechanisms are consistently embedded into the **Heavy-Flavor NonRelativistic Evolution (HF-NRevo)** timelike scheme [5,6], and the final LHAPDF grids (central values and replicas) are generated through numerical DGLAP evolution.

The evolution is performed at NLO accuracy in the ZM-VFNS with $n_f=5$ active flavors. Initial-scale inputs are provided for constituent charm and bottom quarks, while gluon and light-parton FFs are dynamically generated through DGLAP evolution.

The natural initial fragmentation scales are determined by the corresponding production thresholds:

- **Direct mode:** $\mu_{F,0}^{\rm [direct]}=3m_Q+2m_{\tilde Q}$.
- **Scalar-diquark mode:** $\mu_{F,0}^{\rm [diquark]}=3m_Q+4m_{\tilde Q}$.

Here, $(Q,\tilde Q)=(c,b)$ for charm-initiated fragmentation and $(Q,\tilde Q)=(b,c)$ for bottom-initiated fragmentation.

The TQ4Qhf1.0 FFs feature an uncertainty-aware construction that combines perturbative and nonperturbative sources of uncertainty.

Perturbative fragmentation missing higher-order uncertainties (F-MHOUs) are estimated through variations of the initial fragmentation scales, while nonperturbative wave-function uncertainties (F-NPWFs) are modeled through controlled variations of the intrinsic transverse-momentum parameter entering the Suzuki-inspired initial conditions.

The resulting replica ensemble allows perturbative and nonperturbative fragmentation uncertainties to be investigated separately or combined consistently in phenomenological applications.

Each production mechanism is represented by nine replicas obtained from a nested scan of perturbative and nonperturbative parameters, giving a total of eighteen FF sets.

### Replica structure

| ID | Mode | $K_{\mu}$ | $\langle {\vec q}_T^{2} \rangle$ [GeV²] |
|----|------|-----------|----------------------------------------|
| 0  | direct  | 1   | 70 |
| 1  | direct  | 1   | 65 |
| 2  | direct  | 1   | 75 |
| 3  | direct  | 0.5 | 70 |
| 4  | direct  | 0.5 | 65 |
| 5  | direct  | 0.5 | 75 |
| 6  | direct  | 2   | 70 |
| 7  | direct  | 2   | 65 |
| 8  | direct  | 2   | 75 |
| 9  | diquark | 1   | 70 |
| 10 | diquark | 1   | 65 |
| 11 | diquark | 1   | 75 |
| 12 | diquark | 0.5 | 70 |
| 13 | diquark | 0.5 | 65 |
| 14 | diquark | 0.5 | 75 |
| 15 | diquark | 2   | 70 |
| 16 | diquark | 2   | 65 |
| 17 | diquark | 2   | 75 |

- $K_{\mu}$ encodes initial fragmentation-scale variations (F-MHOUs).
- $\langle {\vec q}_T^{2} \rangle$ corresponds to the F-NPWF parameter.

The reference configurations are **replica 0** for direct-multiquark fragmentation and **replica 9** for scalar-diquark fragmentation, corresponding to $K_{\mu}=1$ and $\langle {\vec q}_T^{2} \rangle=70~\mathrm{GeV}^2$.

The remaining replicas encode the perturbative and nonperturbative variations around these reference configurations.

The replica ensemble represents a structured scan of theoretical inputs rather than a statistical Monte Carlo sample. It can be used to construct uncertainty bands or to isolate the impact of individual fragmentation-related uncertainty sources.

The effective scalar-diquark form-factor scale is fixed to the reference value $\Lambda_{\mathcal D}=15~\mathrm{GeV}$. Its independent variation over the representative interval $10$--$20~\mathrm{GeV}$ probes an additional normalization-model dependence that is not included in the F-MHOU and F-NPWF replica uncertainties.

## Physics highlights

The TQ4Qhf1.0 framework introduces a multimodal fragmentation description of the all-heavy mixed-flavor $X_{b\bar b c\bar c}$ tetraquark.

The framework provides uncertainty-aware collinear FFs for both charm- and bottom-initiated production, incorporating direct-multiquark and sequential scalar-diquark formation mechanisms within a common perturbative evolution scheme.

The two fragmentation mechanisms exhibit markedly different longitudinal-momentum distributions.

The **direct-multiquark mode** produces a comparatively hard fragmentation pattern, with a broad maximum around $z\simeq0.6$, whereas the **scalar-diquark mode** generates a softer distribution concentrated at smaller momentum fractions, around $z\simeq0.15$--$0.2$.

These differences reflect the distinct microscopic dynamics encoded in the two initial-scale constructions and remain visible after perturbative DGLAP evolution.

The resulting FFs are employed in Ref. [1] to investigate semi-inclusive $X_{b\bar b c\bar c}$ plus jet production at the **14 TeV High-Luminosity LHC (HL-LHC)** and the **100 TeV Future Circular Collider (FCC)** within hybrid high-energy and collinear factorization.

The phenomenological analysis includes rapidity-separation distributions, integrated production rates, and expected event yields. Within the adopted model inputs, direct-multiquark fragmentation dominates over the scalar-diquark contribution, while the enhanced partonic luminosities at FCC energies substantially increase the prospective production rates.

These results illustrate how alternative microscopic tetraquark formation mechanisms can leave distinguishable signatures in fragmentation functions and collider observables.

The TQ4Qhf1.0 sets are intended for precision phenomenological studies of all-heavy mixed-flavor exotic-hadron production at present and future high-energy colliders.

## References

Please acknowledge the relevant references when using these FF sets!

Reference for the TQ4Qhf1.0 release:

[1]&nbsp;&nbsp;J.V. Bulhões, F.G. Celiberto, and V.P. Gonçalves, "The $b\bar b c\bar c$ Fully Heavy Tetraquark at the LHC and the FCC: Multimodal Fragmentation and Observability" (2026).

References for initial-scale inputs:

[2]&nbsp;&nbsp;M. Suzuki, "Spin Property of Heavy Hadron in Heavy Quark Fragmentation: A Simple Model", Phys. Rev. D 33 (1986) 676.

[3]&nbsp;&nbsp;S.M. Moosavi Nejad and N. Amiri, "Ground State Heavy Tetraquark Production in Heavy Quark Fragmentation", Phys. Rev. D 105 (2022) 034001 [arXiv:2110.15251 [hep-ph]].

[4]&nbsp;&nbsp;S.M. Moosavi Nejad, "Heavy Tetraquark Production in High Energy Colliders through the Fragmentation Mechanism in a Diquark Model", Phys. Rev. D 112 (2025) 056020.

References for HF-NRevo:

[5]&nbsp;&nbsp;F.G. Celiberto and F. Lonigro, "Pseudoscalar heavy-quarkonium hadroproduction from nonrelativistic fragmentation at NLL/NLO+", Phys. Rev. D 112 (2025) 11, 114040 [arXiv:2510.10593 [hep-ph]].

[6]&nbsp;&nbsp;F.G. Celiberto, "Towards Quarkonium Fragmentation from NRQCD in a Variable-Flavor Number Scheme", Moriond QCD 2024 [arXiv:2405.08221 [hep-ph]].
