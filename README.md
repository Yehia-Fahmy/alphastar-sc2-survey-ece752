# AlphaStar Survey — ECE 752

Survey report and presentation on DeepMind's AlphaStar system for ECE 752 (Advanced Computer Architecture) at the University of Waterloo, Winter 2026.

**Paper:** Vinyals, O. et al., "Grandmaster Level in StarCraft II Using Multi-Agent Reinforcement Learning," *Nature* 575, 350–354 (2019).

## Contents

| File | Description |
|------|-------------|
| `report.tex` / `report.pdf` | Comprehensive survey report covering architecture, training pipeline, league framework, and results |
| `presentation.tex` / `presentation.pdf` | Beamer slide deck for the in-class presentation |
| `StarcraftPaper-2.pdf` | Original AlphaStar paper |
| `ECE_752_Research_Proposal.pdf` | Initial research proposal |

## Building

Requires a LaTeX distribution (e.g. TeX Live, MacTeX) with TikZ and PGFPlots.

```bash
pdflatex report.tex && pdflatex report.tex   # double-pass for TOC
pdflatex presentation.tex
```
