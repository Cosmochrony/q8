# Q8 — Toward a Full-Rank Effective Metric

This repository contains the source of the **Q8 Cosmochrony paper**
*Toward a Full-Rank Effective Metric: No Central Coefficient from the Heisenberg Commutator, and Scale-Free Casimir
Rigidity*.

The effective operator of Q5b, conditional on [H-L] and [H-lift], has a spatial principal symbol of rank two with an
empty central slot. Completing it to a four-dimensional Lorentzian co-metric requires a positive coefficient $A_Z$ of
$k_Z^2$ (open problem Q5b-O2).

## Core Result

- **Rank obstruction (unconditional).** With the left-invariant fields $X = \partial_x + \tfrac{y}{2}\partial_z$,
  $Y = \partial_y - \tfrac{x}{2}\partial_z$, the sub-Laplacian $X^2 + Y^2$ has no first-order part, and the principal
  symbol of $-\Delta_H$ is $(k_X + \tfrac{y}{2}k_Z)^2 + (k_Y - \tfrac{x}{2}k_Z)^2$, of rank two everywhere, with a
  $k_Z^2$ coefficient $(x^2+y^2)/4$ that vanishes at the identity. No lower-order term changes this: the commutator
  $[X, Y] = Z$ does not generate a central coefficient.
- **Homogeneity and scale.** Under the Carnot dilations, $\Delta_H$ is homogeneous of degree two and $Z^2$ of degree
  four. For $A_H\,\Delta_H + A_Z\,Z^2$ the ratio $A_Z/A_H$ scales as $r^2$, so $A_H = A_Z$ selects a length scale.
- **Scale-free rigidity (conditional).** If a positive rank-three target is supplied with the compatibility
  conditions of Q7 and is invariant under the full $\mathfrak{su}(2)$ action, Schur's lemma gives
  $A_H = A_Z = 2\lambda$ with $\lambda > 0$ free. Rotation invariance about one axis gives no relation.
- The Casimir eigenvalue $2$ fixes a normalisation, not a coefficient. No value of $A_Z$ is derived, and Q5b-O2 is
  open.

## Keywords

Heisenberg group, sub-Laplacian, principal symbol, Carnot dilations, su(2)-invariant forms, Casimir operator,
Schur's lemma, effective metric, emergent geometry, Cosmochrony.

## Repository Contents

```
q8/
├── tex/         # LaTeX sources (main + cosmochrony-bibliography.bib)
├── code/        # Python script and requirements
├── compile.sh   # Build script (output in out/, not versioned)
├── zenodo.json  # Zenodo deposition metadata
└── README.md
```

## Links

- 🔗 DOI: [10.5281/zenodo.19879909](https://doi.org/10.5281/zenodo.19879909)
- 🌐 Website: https://cosmochrony.org/science/emergent-geometry/q8/

## Citation

> J. Beau, *Toward a Full-Rank Effective Metric: No Central Coefficient from the Heisenberg Commutator, and
> Scale-Free Casimir Rigidity*, Zenodo, 2026. DOI: 10.5281/zenodo.19879909.

## Acknowledgements

Portions of the analysis and editorial development benefited from iterative interactions with large language
models used as analytical assistants. All mathematical claims and interpretations remain the author's
responsibility.
