# 202210cau_tutorial
tutorial: collider tools at CAU-THEP group

Let me introduce the outline.
I consider briefly investigating the case that:

Leptophobic Spin-1 mediated DM:
the same as Eq. (5) Lagrangian in
https://arxiv.org/abs/1908.06357
{\cal L}^{Z'}_{\mathrm{int}} = \overline{\psi}\gamma^{\mu}(g^V_\psi +g^A_\psi \gamma_5) \psi {Z'_{\mu}}

I planned to let you implement the above Lagrangian with \psi in the above DM and up and down quarks for simplicity.
You can easily extend this to the one with more quarks and/or leptons.

We can do as much as we can from and to:
1) Making FeynRules file on spin-1 mediated DM: Implement the Lagrangian Eq. (5)
2) MadGraph: p p to DM DM j (monojet) with the above file (generating events, see cross section)
3) CalcHep, amplitude squared: DM DM to u ubar, for example (for the relic density)
4) MadAnalysis: with the output of item 2) we can see kinematic distributions
