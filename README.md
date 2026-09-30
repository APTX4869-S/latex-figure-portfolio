# LaTeX Figure Portfolio

A demonstration document showcasing professional LaTeX typesetting for
academic and scientific use:

- **Theorem environments** — definitions, theorems, lemmas, proofs (amsthm)
- **Algorithm typesetting** — algorithm2e with line numbering
- **Cross-references** — automatic numbering for theorems, equations, algorithms, figures
- **BibTeX bibliography** — biblatex with numeric style
- **7 TikZ/PGFPlots figures**:
  1. ADMM convergence curves (log-scale residuals)
  2. Soft-thresholding function plot
  3. ADMM flowchart
  4. Robust PCA decomposition illustration
  5. Singular value decay comparison
  6. Matrix completion visualization
  7. ADMM splitting geometry

## Compile

```bash
pdflatex portfolio
bibtex portfolio
pdflatex portfolio
pdflatex portfolio
```

Or with latexmk:
```bash
latexmk -pdf portfolio.tex
```

## Repository structure

```
latex-figure-portfolio/
├── portfolio.tex      # main document (all figures inline)
├── src/
│   └── refs.bib        # BibTeX references
├── portfolio.pdf       # compiled output (after build)
└── README.md
```

## Use cases

This portfolio serves as:
- A **LaTeX typesetting demo** for Fiverr/Upwork gig listings
- A **figure template** — each TikZ block can be adapted to specific needs
- A **learning resource** — examples of amsthm, algorithm2e, pgfplots

## License

MIT
