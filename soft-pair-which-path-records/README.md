# Soft-pair which-path records from a gapped detector

A soft pair-emission channel records path information even when slow switching suppresses detector excitation.

Work in progress. Not all claims have been verified by a human.

[Manuscript](index.md) · [LaTeX](main.tex) · [References](references.bib) · [Code](code/)

Compile with `pdflatex main.tex`, `bibtex main`, and `pdflatex main.tex` twice.

Run the numerical checks from `code/`:

```sh
python3 -m pip install -r requirements.txt
python3 new_paper/verify.py
```
