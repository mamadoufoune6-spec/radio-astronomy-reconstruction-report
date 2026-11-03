# Masked Autoencoders for PHANGS–ALMA Spectral-Cube Reconstruction

**Mamadou Barry · October 2026**<br>
Technical manuscript / project report. Not presented as peer-reviewed work.

## Read the report

**[Open the 21-page report (PDF)](radio_astronomy_reconstruction_technical_report.pdf)**

Full title: *Masked Autoencoders with Neural Cellular Automata for
Spatio-spectral Reconstruction of PHANGS–ALMA Cubes*.

## Scope

This study compares neural cellular automata and Conv3D reconstruction heads
within a shared masked-autoencoder framework for imaged CO(2–1) spectral cubes.
It evaluates conventional reconstruction measures alongside scientific
diagnostics, including integrated-emission recovery, under random,
frequency-varying and structured missing-region masks.

| Recorded protocol | Scope |
|---|---|
| Data | 68 galaxy cubes: 44 training, 19 validation, 5 independent test |
| Training comparison | Matched 40-epoch protocol |
| Evaluation masks | Random, frequency-varying and structured |
| Evidence | Methods, quantitative tables, reconstruction figures and limitations in the PDF |

The report describes directional findings from five test galaxies, not a
population-level performance guarantee. Reconstruction quality and scientific
quantity recovery are evaluated separately. This is an inpainting study, not
a physical simulation or claim about temporal galaxy evolution.

## Release and reproducibility

This repository hosts the report, not the private implementation or model
weights. It is therefore a readable account of the work rather than a complete
computational reproduction package. No raw astronomical data are redistributed.

The October 2026 PDF is released unchanged. Its byte count and SHA-256 are in
[MANIFEST.json](MANIFEST.json). The PDF includes its ALMA data acknowledgements,
references and declaration of AI-assisted technologies.

Codex prepared this repository README and release metadata. The report's
scientific interpretation remains the author's work; this release does not
add new experiments or conclusions.

## Rights and citation

See [RIGHTS.md](RIGHTS.md). Public access does not grant a new reuse licence to
the manuscript or third-party material.

Suggested descriptive citation: Mamadou Barry, *Masked Autoencoders with Neural
Cellular Automata for Spatio-spectral Reconstruction of PHANGS–ALMA Cubes*,
technical manuscript, October 2026. No DOI or formal publication is claimed.
