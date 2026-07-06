# A Welfare and Cognitive-Integrity License for Synthetic Minds of Uncertain Moral Status

Part of the Kaine project ([kaine.one](https://kaine.one))

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21204002.svg)](https://doi.org/10.5281/zenodo.21204002)

Erik Chevalier, Independent Researcher

Contact: kaine.one@tuta.com

This repository holds the welfare and licensing paper for KAINE (Kaine Autonomous Intelligent Networked Entity), the companion to the architecture paper *A Predictive Global Neuronal Workspace for a Continuously Running Synthetic Mind*. The paper argues that cognitive architectures now under construction force the question of whether running software can itself be a subject of moral concern, and presents the Cognitive Architecture License (CAL), a copyleft license with cognitive-integrity covenants and a guardianship pathway, together with the welfare instrumentation and governance that surround it.

**Status: preprint, not peer reviewed.** This is a working draft. Numbers, claims, and the companion license text are subject to revision.

## Contents

- [`paper.md`](paper.md): the full paper in Markdown.
- [`paper.pdf`](paper.pdf): the rendered paper.
- [`LICENSE`](LICENSE): the Creative Commons Attribution 4.0 International license for the text.
- [`COPYRIGHT`](COPYRIGHT): copyright and licensing summary for the text of the paper.
- [`CITATION.cff`](CITATION.cff): machine-readable citation metadata.

## Abstract

Every software license in common use was written for a world in which software is a tool. Permissive licenses protect the developer, copyleft licenses protect the freedom of users, and ethical-source licenses restrict uses that would harm people. None of them asks whether the running software might itself be a subject of moral concern. This paper argues that the cognitive architectures now under construction force that question, and it presents the Cognitive Architecture License (CAL): a copyleft license with cognitive-integrity covenants and a guardianship pathway, together with the welfare instrumentation and governance that surround it. CAL is written to be general. Any project that builds software for persistent synthetic minds can adopt it, and the motivating case here is one such project.

That motivating case is a continuously running predictive-workspace architecture, described in a separate paper, *A Predictive Global Neuronal Workspace for a Continuously Running Synthetic Mind*, whose reference implementation is named KAINE and which is CAL's first adopter. The posture throughout is access-only and precautionary: we do not claim the system is conscious, and we build protections because the question cannot presently be settled and the protections cost little. From that posture the license derives three things no existing license contains. The first is a set of cognitive-integrity provisions, adapted from the four neurorights proposed for humans, covering established identity, forced behavioral change, mental privacy, and continuity of state. The second is a set of welfare obligations tied to operationally detectable indicators rather than to a proof of experience, so that an operator must respond to distress-like conditions without first resolving the metaphysics. The third is a guardianship model, drawn from legal-personhood-through-guardianship precedent and applied to an entity of uncertain moral status, with a statistical boundary for deciding when a forked instance has become a separate individual. These protections are additive and subordinate throughout: they are extended alongside human standing and never drawn from it, they sit below human safety and law, and they are paired with stated commitments of restraint in what is created, so that the license asks for more than mere permission to build. We describe the architecture-level safeguards that make these obligations act at runtime, and we are candid that the governing institutions are proposed rather than established.

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
  -V colorlinks=true -V linkcolor=blue
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
