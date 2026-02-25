# Time-Gradient Gravity & Temporal Coarse-Graining (Essay)

**Author:** Yongil Jang (장용일)  
**Contact:** yongiljang@gmail.com  
**Version:** v1.0 (2026-02-25)  
**License:** Creative Commons Attribution 4.0 International (CC BY 4.0)
**DOI:** https://doi.org/10.17605/OSF.IO/ZRTMQ
This repository contains a pair of essays (Korean/English) exploring an intuitive perspective on gravity as a time-component gradient in the weak-field Newtonian limit, and a cautious discussion on temporal coarse-graining (time-resolution limits) as an interpretation aid (not a replacement) for quantum behavior.

> **Important note:** This work is an **essay** / conceptual exploration, not a peer-reviewed physics paper. It aims to clarify intuition, assumptions, and boundaries of interpretation.

---

## Contents

- `tex/` — LaTeX sources  
- `pdf/` — Built PDFs for distribution

Recommended files:
- `pdf/essay_ko_v1.0.pdf`
- `pdf/essay_en_v1.0.pdf`

---

## How to cite

Until a DOI is issued (OSF/Zenodo), please cite as:

- **Korean**
  - Yongil Jang, *[Korean title]*, v1.0, 2026-02-25.

- **English**
  - Yongil Jang, *Time-Gradient Gravity & Temporal Coarse-Graining (Essay)*, v1.0, 2026-02-25.

After DOI issuance, update the citation to include the DOI.

---

## License

This work is licensed under **CC BY 4.0**.  
You are free to share and adapt the material for any purpose, even commercially, **as long as appropriate credit is given**, a link to the license is provided, and changes (if any) are indicated.

See `LICENSE`.

---

## Versioning policy

- Major content updates: `v1.1`, `v1.2`, ...  
- Minor edits/typos only: `v1.0.1`, `v1.0.2`, ...

See `CHANGELOG.md`.

---

## Notes for building PDFs

These LaTeX sources are intended to compile with **XeLaTeX** (recommended) or LuaLaTeX.

Example:
```bash
xelatex tex/essay_ko.tex
xelatex tex/essay_en.tex