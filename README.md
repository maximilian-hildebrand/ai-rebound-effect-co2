# Efficiency as a Trap

**Course:** Wissenschaftliches Schreiben / Scientific Writing – SoSe 2026  
**OTH Regensburg** | Prof. Dr. Karsten Weber

## Research Question
To what extent do rebound effects at the direct and indirect level
counteract the ecological efficiency gains of AI deployment – and
thereby contribute to a deterioration of the global CO₂ balance?

## Status
- [x] Abstract & Keywords
- [ ] Introduction
- [ ] Theoretical Background
- [ ] Direct Rebound Effects
- [ ] Indirect Rebound Effects
- [ ] Discussion
- [ ] Conclusion
- [ ] Bibliography complete

## How to compile
```bash
cd paper
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

Alternative, and usually simpler:
```bash
cd paper
latexmk -pdf main.tex
```

## Requirements
- pdflatex
- lni.cls (download from https://github.com/gi-ev/LNI)
