# Spacelike Guessing of Quantum Randomness

Bounds on guessing a vacuum-generated bit from a spacelike region.

Work in progress. Not all claims have been verified by a human.

[Manuscript](index.md) · [LaTeX](main.tex) · [References](references.bib) · [Code](code/)

Compile with `pdflatex main.tex`, `bibtex main`, and `pdflatex main.tex` twice.

Run the numerical checks from `code/`:

```sh
python3 -m pip install -r requirements.txt
python3 numerics/spacelike_guessing/validate.py
```
