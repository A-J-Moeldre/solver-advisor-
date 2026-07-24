Solver Advisor — MVP
Ein Tool zur automatischen Analyse von Matrizen aus wissenschaftlichen Simulationen.
Es erkennt strukturelle Eigenschaften und empfiehlt geeignete Solver und Preconditioner.

Features
Sparsity‑Analyse

Symmetrie‑Erkennung

Konditionsschätzung

Spektralradius (Lanczos)

Solver‑Empfehlungen (CG, GMRES, MINRES, ILU, AMG)

Beispiel
solver-advisor analyze examples/diffusion.mtx
Ausgabe:

Matrix: 5000x5000 sparse (0.3%)
Symmetrie: symmetric
Kondition: ~1.2e7
Empfehlung: CG + ILU(0)
