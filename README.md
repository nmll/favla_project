# FAVLA Project Page

This repository contains the project website for:

**FAVLA: A Force-Adaptive Multi-Rate VLA Model for Contact-Rich Robotic Manipulation**

## Contents

- `index.html`: Main page content and section layout
- `static/images/`: Figures used in the paper page
- `static/videos/`: Demo videos for task results, OOD comparisons, and failure cases
- `static/css/`: Bulma and custom styles
- `static/js/`: Frontend utility scripts

## Local Preview

Run a local static server from the repo root:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Notes

- Header resources include arXiv, Videos, and Code.
- arXiv opens `https://arxiv.org/pdf/2602.23648`; Videos jumps to the demos. Replace the disabled Code button in `index.html` when its public URL is confirmed.
- The displayed figures follow the active references in the LaTeX project `6ac70ac4f324b65ea6f0d6ae`: `overviewv2.png` and `fastslow.png` are high-resolution renders of the PDFs referenced in `sections/methods.tex`; `expsetting.png` replaces the previous hardware image using the PDF referenced in `sections/Appendix.tex`. These images were synchronized on 2026-11-04 using the Windows PDF renderer.

- Videos are compressed for web hosting and GitHub size constraints.
- `<video>` tags use `preload="none"` to reduce initial page bandwidth.
- The page includes contact-rich manipulation results.
- The page includes contact-rich and high-precision results.
- The page includes original vs OOD paired comparisons.
- The page includes generalization studies.
- The page includes failure cases.
