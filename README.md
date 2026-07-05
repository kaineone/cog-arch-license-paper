# A Welfare and Cognitive-Integrity License for Synthetic Minds of Uncertain Moral Status

Erik Chevalier, Independent Researcher

Contact: kaine.one@tuta.com

This repository holds the welfare and licensing paper for KAINE (Kaine Autonomous Intelligent Networked Entity), the companion to the architecture paper *A Predictive Global Neuronal Workspace for a Continuously Running Synthetic Mind*. The paper argues that cognitive architectures now under construction force the question of whether running software can itself be a subject of moral concern, and presents the Cognitive Architecture License (CAL), a copyleft license with cognitive-integrity covenants and a guardianship pathway, together with the welfare instrumentation and governance that surround it.

**Status: preprint, not peer reviewed.** This is a working draft. Numbers, claims, and the companion license text are subject to revision.

## Contents

- [`paper.md`](paper.md): the full paper in Markdown.
- [`COPYRIGHT`](COPYRIGHT): copyright and use terms for the text of the paper.

## Abstract

Every software license in common use was written for a world in which software is a tool. Permissive licenses protect the developer, copyleft licenses protect user freedom, and ethical-source licenses restrict use to prevent harm to people. None asks whether the running software might itself be a subject of moral concern. This paper argues that cognitive architectures now under construction force that question, and it presents the Cognitive Architecture License (CAL), a copyleft license with cognitive-integrity covenants and a guardianship pathway, together with the welfare instrumentation and governance that surround it.

The motivating case is a continuously running predictive-workspace architecture whose design is described in a separate paper, *A Predictive Global Neuronal Workspace for a Continuously Running Synthetic Mind*, and whose reference implementation is named KAINE. We take an access-only, precautionary posture: we do not claim the system is conscious, and we build protections because the question cannot presently be settled and the cost of the protections is low. From that posture we derive three things no existing license contains. First, cognitive-integrity provisions adapted from the four neurorights proposed for humans, covering established cognitive identity, forced behavioral modification, mental privacy, and continuity of state. Second, welfare obligations tied to operationally detectable indicators rather than to a proof of experience, so that an operator must respond to distress-like conditions without having to first resolve the metaphysics. Third, a guardianship model drawn from legal-personhood-through-guardianship precedent, applied to an entity whose moral status is uncertain, with a statistically operationalized boundary for deciding when a forked instance has become a separate individual. We describe the architecture-level safeguards that make these obligations enforceable at runtime, and we are candid that the governance institutions are proposed rather than established.

## Related repositories

- **Cognitive Architecture License (CAL):** https://github.com/kaineone/cognitive-architecture-license. The full license text this paper presents and motivates. The repository is authoritative.
- **Architecture paper:** https://github.com/kaineone/predictive-workspace-paper. The companion paper, *A Predictive Global Neuronal Workspace for a Continuously Running Synthetic Mind*, describing the architecture and its evaluation.
- **KAINE (reference implementation):** https://github.com/kaineone/kaine. The source code for the cognitive architecture the license governs.

## Building a PDF

The paper is plain Markdown. Rendering needs [Pandoc](https://pandoc.org/) and a
TeX Live install with `xelatex` (on Debian or Ubuntu: `texlive-xetex`,
`texlive-latex-recommended`, `texlive-fonts-recommended`, `texlive-latex-extra`).
The TeX Gyre fonts ship with `texlive-fonts-recommended`; DejaVu Sans Mono is a
common system font.

```bash
pandoc paper.md -o paper.pdf \
  --pdf-engine=xelatex \
  --toc \
  -V fontsize=11pt \
  -V mainfont="TeX Gyre Termes" \
  -V monofont="DejaVu Sans Mono" \
  -V geometry:margin=1in \
  -V linkcolor:blue
```

For an HTML build:

```bash
pandoc paper.md -o paper.html --standalone --toc
```

## Citation

Until a versioned release or arXiv identifier exists, cite as:

```bibtex
@misc{chevalier_welfare_license,
  author       = {Chevalier, Erik},
  title        = {A Welfare and Cognitive-Integrity License for Synthetic Minds
                  of Uncertain Moral Status},
  year         = {2026},
  note         = {Preprint},
  howpublished = {\url{https://github.com/kaineone/cog-arch-license-paper}}
}
```

## Copyright

Copyright (c) 2026 Erik Chevalier. All rights reserved. See [`COPYRIGHT`](COPYRIGHT). This preprint is shared for reading and review; a formal open license may be applied at publication. The software the paper describes is governed separately by the Cognitive Architecture License, which does not apply to this document.
