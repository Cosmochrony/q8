# Q8 — Sub-Principal Symbol of the Effective Operator and Casimir Rigidity

This repository contains the source of the **Q8 Cosmochrony paper**
*Sub-Principal Symbol of the Effective Operator and Casimir Rigidity of the Central
Direction*.

Paper Q7 reduced the open problem Q5b-O2 to a single computable criterion: whether the
sub-principal symbol of the effective operator $L_{\mathrm{eff}}$ in the central direction
$Z = [X, Y]$ of $\mathfrak{heis}_3(\mathbb{R})$ carries coefficient
$A_Z = \mathcal{C}_{\mathfrak{su}(2)} = 2$, the Casimir eigenvalue on the spin-1 module
$\operatorname{Sym}^2(V_\rho)$.

## Core Result

The isotropy condition $A_H = A_Z$ is settled by a **structural argument** requiring no full
computation of the hypoelliptic symbol. The sub-principal term along $Z$ has a unique
algebraic source — the Heisenberg commutator $[X,Y] = Z$ (nilpotency class 2) — which cannot
be mimicked by any other generator. Under the equivariant bridge
$\varphi:\operatorname{Sym}^2(V_\rho)\xrightarrow{\sim}W$ (unique up to positive scalar by
Schur's lemma), this term is forced to be proportional to the unique $\mathfrak{su}(2)$-invariant
quadratic form, the Casimir $2\cdot\mathrm{Id}$. There is no free scalar.

Hence, **given bridge non-obstruction (proved in Q9), $A_Z = 2$ unconditionally** under the
Q5a hypotheses. The effective spatial co-metric is
$g_{\mathrm{sp}} = A_H(k_X^2+k_Y^2) + 2k_Z^2$ with $A_H \to 2$.

## Keywords

Sub-principal symbol, Casimir rigidity, Heisenberg commutator, equivariant bridge,
Schur's lemma, hypoelliptic operator, effective co-metric.

## Repository Contents

```
q8/
├── tex/         # LaTeX sources (main + cosmochrony-bibliography.bib)
├── out/         # Compiled paper PDF (Q8.pdf)
├── zenodo.json  # Zenodo deposition metadata
└── README.md
```

## Links

- 🔗 DOI: [10.5281/zenodo.19879909](https://doi.org/10.5281/zenodo.19879909)
- 🌐 Website: https://cosmochrony.org/science/emergent-geometry/q8/

## Citation

> J. Beau, *Sub-Principal Symbol of the Effective Operator and Casimir Rigidity of the
> Central Direction*, Zenodo, 2026. DOI: 10.5281/zenodo.19879909.

## Acknowledgements

Portions of the editorial refinement benefited from iterative interactions with large
language models, used as analytical assistants. All claims and final formulations remain
the sole responsibility of the author.
