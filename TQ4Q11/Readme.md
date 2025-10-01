# TQ4Q1.1: Quarkoniumlike states from LHC to FCC: Fragmentation and Resummation
## TetraQuarks with 4 heavy Quarks VFNS FFs

We address the formation mechanism of fully heavy tetraquark states, scalar $T_{4Q}(0^{++})$, axial-vector $T_{4Q}(1^{+-})$, and tensor $T_{4Q}(2^{++})$ resonances, via the fragmentation approximation, valid in the large transverse-momentum regime matter of our analysis. To this extent, we release novel NLO FF sets for "TetraQuarks with 4 heavy Quarks", named $\mbox{\tt TQ4Q1.1}$ [1,2,3]. 
For convenience, we also provide [3] three replicas to estimate perturbative uncertainties associated with the fragmentation scale: replica0 is the central set, while replicas1 and~2 correspond to variations of the initial scale by a factor of two. Since the FFs scale linearly with the LDME, users can apply LDME variations independently to assess nonperturbative uncertainties.
They extend and supersede the corresponding {\tt 1.0} version derived in recent studies [4]. The TQ4Q1.1 are built by evolving à la DGLAP potential NRQCD calculations for the both the gluon [5] and the quark function [6]. Final $\mbox{\tt LHAPDF}$ grids (central value only) are evolved via the $\mbox{\tt APFEL++}$ library [7].

To support reproducibility, we provide a stand-alone, self-contained $\mbox{\tt MATHEMATICA}$ notebook extracted from the internal $\mbox{\tt symJETHAD}$ framework, containing all short-distance coefficients used in this work. It requires no external dependencies, is validated against the codebase, and can be used for numerical or symbolic checks. The notebook is also included as Supplemental Material in [3].

Please acknowledge references when using these FF sets!  

References for DGLAP-evolved FFs:

[1] F.G. Celiberto and G. Gatto, "Bottomonium-like states in proton collisions: Fragmentation and resumamtion" [arXiv:2412.10549  [hep-ph]].  
[2] F.G. Celiberto, "Fragmentation functions for axial-vector heavy tetraquarks: A TQ4Q1.1 update", Phys. Rev. D [Letters] 111 (2025) 11, L111501  [arXiv:2504.03949 [hep-ph]].  
[3] F.G. Celiberto, "Fragmentation of fully heavy tetraquarks: The TQ4Q1.1 functions as a case study" [arXiv:2507.09744 [hep-ph]].  
[4] F.G. Celiberto, G. Gatto, A. Papa, "Fully charmed tetraquarks from LHC to FCC: Natural stability from fragmentation", Eur. Phys. J. C 84 (2024) 10, 1071  [arXiv:2405.14773 [hep-ph]].  

References for initial-scale inputs:

[5] F. Feng, Y. Huang, Y. Jia, W.L. Sang, X. Xiong, J.Y. Zhang, Phys. Rev. D 106 (11) (2022), 114029 [arXiv:2009.08450 [hep-ph]].    
[6] X.W. Bai, F. Feng, C.M. Gan, Y. Huang, W.L. Sang, H.F. Zhang, JHEP 09 (2024) 002 [arXiv:2404.13889 [hep-ph]].   

Other references:

[7] V. Bertone, S. Carrazza, J. Rojo, Comput. Phys. Commun. 185 (2014) 1647-1668 [arXiv:1310.1394 [hep-ph]].  
