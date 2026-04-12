# TQ4Q2.0: Quarkoniumlike states from LHC to FCC: A high-precision fragmentation perspective
## TetraQuarks with 4 heavy Quarks VFNS FFs

We present the $\mbox{\tt TQ4Q2.0}$ fragmentation-function (FF) sets for all-heavy tetraquarks, including scalar $T_{4Q}(0^{++})$, axial-vector $T_{4Q}(1^{+-})$, and tensor $T_{4Q}(2^{++})$ states, constructed within the fragmentation approximation valid at large transverse momentum.

These sets supersede the previous $\mbox{\tt TQ4Q1.1}$ [2-4] and $\mbox{\tt TQ4Q1.0}$ [5] implementations, providing a substantially improved and more complete description of the fragmentation mechanism. In particular, $\mbox{\tt TQ4Q2.0}$ includes all partonic channels at the initial scale, embodying also nonconstituent light- and heavy-quark contributions, and implements an upgraded treatment of perturbative uncertainties.

A key new feature is the introduction of a replica-based strategy to estimate perturbative fragmentation uncertainties (F-MHOUs). Instead of a limited set of scale variations, we generate $\mathcal{O}(100)$ replicas by varying renormalization and factorization scales entering the short-distance coefficients simultaneously, through pseudorandom factors in the range $[1/2, 2]$ around their natural values. This provides a dynamically correlated and more realistic estimate of missing higher-order effects.

Long-distance matrix elements (LDMEs) are kept fixed in the replica construction, as they enter as constant nonperturbative coefficients and can be varied independently by the user if needed.

This replica ensemble is designed not only to quantify theoretical uncertainties, but also to enable future data-driven studies. In particular, it provides a natural interface for the extraction of nonperturbative parameters from differential cross-section measurements and offers a suitable input for modern statistical and machine-learning approaches to QCD phenomenology.

The FFs are constructed from NRQCD-based calculations for both gluon and quark channels [6-8] and evolved via DGLAP equations within the $\mbox{\tt HFNRevo}$ framework. Final grids are provided in $\mbox{\tt LHAPDF6}$ format and evolved using the $\mbox{\tt APFEL++}$ library [9].

To support reproducibility, we provide a stand-alone, self-contained $\mbox{\tt MATHEMATICA}$ notebook extracted from the internal $\mbox{\tt symJETHAD}$ framework, containing all short-distance coefficients (SDCs) used in this work. It requires no external dependencies, is validated against the codebase, and can be used for numerical or symbolic checks.

Please acknowledge references when using these FF sets!  

References for DGLAP-evolved FFs:


[1]&nbsp;&nbsp;F.G. Celiberto, "All-charm tetraquarks at hadron colliders: A high-precision fragmentation perspective" [arXiv:2604.xxxxx [hep-ph]].  
[2]&nbsp;&nbsp;F.G. Celiberto and G. Gatto, "Bottomonium-like states in proton collisions: Fragmentation and resummation", Phys.Rev.D 112 (2025) 7, 074041 [arXiv:2412.10549  [hep-ph]].  
[3]&nbsp;&nbsp;F.G. Celiberto, "Fragmentation functions for axial-vector heavy tetraquarks: A TQ4Q1.1 update", Phys. Rev. D [Letters] 111 (2025) 11, L111501  [arXiv:2504.03949 [hep-ph]].  
[4]&nbsp;&nbsp;F.G. Celiberto, "Fragmentation of fully heavy tetraquarks: The TQ4Q1.1 functions as a case study", Phys.Rev.D 112 (2025) 7, 074041 [arXiv:2507.09744 [hep-ph]].  
[5]&nbsp;&nbsp;F.G. Celiberto, G. Gatto, A. Papa, "Fully charmed tetraquarks from LHC to FCC: Natural stability from fragmentation", Eur. Phys. J. C 84 (2024) 10, 1071 [arXiv:2405.14773 [hep-ph]].  

References for initial-scale inputs:

[6]&nbsp;&nbsp;F. Feng, Y. Huang, Y. Jia, W.L. Sang, X. Xiong, J.Y. Zhang, Phys. Rev. D 106 (11) (2022), 114029 [arXiv:2009.08450 [hep-ph]].    
[7]&nbsp;&nbsp;X.W. Bai, F. Feng, C.M. Gan, Y. Huang, W.L. Sang, H.F. Zhang, JHEP 09 (2024) 002 [arXiv:2404.13889 [hep-ph]]. 
[8]&nbsp;&nbsp;X.W. Bai, Y. Huang, W.L. Sang, Phys. Rev. D 111 (2025) 5, 054006 [arXiv:2411.19296 [hep-ph]]

Other references:

[9]&nbsp;&nbsp;V. Bertone, S. Carrazza, J. Rojo, Comput. Phys. Commun. 185 (2014) 1647-1668 [arXiv:1310.1394 [hep-ph]].  

