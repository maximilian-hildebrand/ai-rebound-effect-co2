# Efficiency as a Trap

Academic research project developed in the context of the course
*Wissenschaftliches Schreiben* at OTH Regensburg (SoSe 2026).

Author: Maximilian Hildebrand

## Research Question
To what extent do rebound effects at the direct and indirect level
counteract the ecological efficiency gains of AI deployment – and
thereby contribute to a deterioration of the global CO₂ balance?

## Status
- [x] Abstract & Keywords
- [x] Introduction
- [x] Theoretical Background
- [x] Direct Rebound Effects
- [x] Indirect Rebound Effects
- [x] Discussion
- [x] Conclusion
- [x] Bibliography included
- [ ] Final proofreading and source verification

## How to compile
```bash
cd paper
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

Usually simpler:
```bash
cd paper
latexmk -pdf main.tex
```

## Requirements
- A TeX distribution with `pdflatex`, `biber`, and `latexmk`
- `paper/lni.cls` (included in this repository)

The repository includes the generated `paper/main.pdf` for convenient viewing.
Build it locally with `latexmk -pdf main.tex` when needed.

`lni.cls` is distributed under the LaTeX Project Public License (LPPL); its
upstream copyright and license notices are retained in the file. The research
sources listed in `paper/main.bib` are credited to their respective authors and
publishers.
