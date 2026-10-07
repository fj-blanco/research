# Boolean Oracles by Waiting

A fixed two-body Hamiltonian implements Boolean oracles through its stopping time, with bounds on the required action.

Work in progress. Not all claims have been verified by a human.

[Manuscript](index.md) · [LaTeX](main.tex) · [References](references.bib) · [Code](code/)

Compile with `pdflatex main.tex`, `bibtex main`, and `pdflatex main.tex` twice.

Run the numerical checks from `code/`:

```sh
python3 -m pip install -r requirements.txt
python3 scripts/check_bounds.py
python3 scripts/check_capacity.py
```
