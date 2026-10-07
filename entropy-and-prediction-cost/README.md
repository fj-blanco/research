# Identical Entropy Profiles, Different Prediction Costs

Stationary binary sources with the same entropy profiles can have sharply different prediction costs.

Work in progress. Not all claims have been verified by a human.

[Manuscript](index.md) · [LaTeX](main.tex) · [References](references.bib) · [Code](code/)

Compile with `pdflatex main.tex`, `bibtex main`, and `pdflatex main.tex` twice.

Run the numerical checks from `code/`:

```sh
python3 -m pip install -r requirements.txt
python3 scripts/validate_profile.py
python3 scripts/validate_decision_cost.py
python3 scripts/validate_estimation.py
```
