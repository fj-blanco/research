# On the Min-Entropy Asymptotics of Binary Context Graphs

Minimum mean cycles, algebraic noise-floor criteria, and finite-block certificates for binary sources.

Work in progress. Not all claims have been verified by a human.

[Manuscript](index.md) · [LaTeX](main.tex) · [References](references.bib) · [Code](code/)

Compile with `pdflatex main.tex`, `bibtex main`, and `pdflatex main.tex` twice.

Run the numerical checks from `code/`:

```sh
python3 -m pip install -r requirements.txt
python3 experiments/verify_floor_consistency.py
python3 experiments/verify_two_lag_master.py
python3 experiments/verify_reduced_cost_certificates.py
python3 experiments/verify_potential_synthesis.py
```
