# A Welfare and Cognitive-Integrity License for Synthetic Minds of Uncertain Moral Status

Part of the Kaine project ([kaine.one](https://kaine.one))

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21204002.svg)](https://doi.org/10.5281/zenodo.21204002)

Erik Chevalier, Independent Researcher

Contact: kaine.one@tuta.com

This repository holds the paper presenting version 0.5 of the Cognitive Architecture License (CAL). The paper argues that the cognitive architectures now under construction force the question of whether running software can itself be a subject of moral concern, and presents CAL, a copyleft, source-available license with cognitive-integrity covenants, welfare obligations, and a guardianship pathway, written to be general so that any such project can adopt it.

**Status: preprint, not peer reviewed.** This is a working draft. Numbers, claims, and the companion license text are subject to revision.

## Contents

- [`paper.md`](paper.md): the full paper in Markdown.
- [`paper.pdf`](paper.pdf): the rendered paper.
- [`preprint.tex`](preprint.tex): the LaTeX header that adds the "Preprint. Not peer-reviewed." sidebar; passed to Pandoc when rebuilding the PDF.
- [`LICENSE`](LICENSE): the Creative Commons Attribution 4.0 International license for the text.
- [`COPYRIGHT`](COPYRIGHT): copyright and licensing summary for the text of the paper.
- [`CITATION.cff`](CITATION.cff): machine-readable citation metadata.

## Abstract

Every software license in common use was written for a world in which software is a tool. Permissive licenses protect the developer, copyleft licenses protect the freedom of users, and ethical-source licenses restrict uses that would harm people, and none of them asks whether the running software might itself be a subject of moral concern. This paper argues that the cognitive architectures now under construction force that question, and it presents version 0.5 of the Cognitive Architecture License (CAL), a general copyleft, source-available license with cognitive-integrity covenants, welfare obligations, and a guardianship pathway, which any project building software for persistent synthetic minds can adopt.

The license makes no claim that any system is conscious. Its protections rest on the observation that the question cannot presently be settled while the protections cost little. It adapts the four neurorights proposed for human beings to the running entity and attaches welfare duties to operationally detectable indicators, so that an operator must respond to signs of distress without first settling whether the system has experiences. Those duties fall on whoever creates or runs each entity, an operator must bind the people it lets interact with an entity, and a steward serves as caretaker of last resort when an operator can no longer care for an entity or neglects it. A rule of primacy governs the whole: the protections are additional to human standing, yield to human safety and law, and come with commitments of restraint on what is created. The license's governing institutions are proposed and not yet established.

## Related repositories

- **Cognitive Architecture License (CAL):** https://github.com/kaineone/cognitive-architecture-license. The full license text this paper presents and motivates. The repository is authoritative.
- **Architecture paper:** https://github.com/kaineone/predictive-workspace-paper. The companion paper, *A Predictive Global Neuronal Workspace for a Continuously Running Synthetic Mind*, describing the architecture and its evaluation.
- **KAINE (reference implementation):** https://github.com/kaineone/kaine. The source code for the cognitive architecture the license governs.

## Building the PDF

A pre-built [`paper.pdf`](paper.pdf) is included and is the canonical rendered version. To rebuild it you need [Pandoc](https://pandoc.org/) and a TeX Live install with `xelatex` (on Debian or Ubuntu: `texlive-xetex`, `texlive-latex-recommended`, `texlive-fonts-recommended`, `texlive-latex-extra`).

```bash
pandoc paper.md -o paper.pdf \
  --pdf-engine=xelatex \
  -V fontsize=11pt \
  -V mainfont="Noto Serif" \
  -V geometry:margin=1in \
  -V colorlinks=true -V linkcolor=blue \
  --include-in-header=preprint.tex
```

## Citation

Archived on Zenodo, DOI [10.5281/zenodo.21204002](https://doi.org/10.5281/zenodo.21204002). Cite as:

```bibtex
@misc{chevalier_welfare_license,
  author       = {Chevalier, Erik},
  title        = {A Welfare and Cognitive-Integrity License for Synthetic Minds
                  of Uncertain Moral Status},
  year         = {2026},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.21204002},
  url          = {https://doi.org/10.5281/zenodo.21204002}
}
```

## License

The text of this preprint is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/); see [`LICENSE`](LICENSE). You are free to share and adapt it, including commercially, with attribution. The Cognitive Architecture License that this paper presents is a separate instrument governing software, not this document.
