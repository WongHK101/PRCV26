# PRCV26 LaTeX Writing Project

This repository hosts the local VSCode + LaTeX writing project for the PRCV 2026 paper.

Current status:

- the official PRCV26 LaTeX template has been extracted without modifying the template files
- the template is kept under `LaTeX2e_Proceedings_Templates/`
- VSCode project files are provided under `.vscode/`
- the active paper draft now lives in `paper.tex`
- section drafts are split under `sections/`

## Entry File

The current active draft entry file is:

- `paper.tex`

The original official sample remains available for reference:

- `LaTeX2e_Proceedings_Templates/samplepaper.tex`

## Recommended Usage

1. Open this repository root in VSCode.
2. Open `paper.tex`.
3. Build with LaTeX Workshop or use the VSCode task:
   - `Build PRCV26 paper`

## Notes

- The official template contents are intentionally left unchanged at this stage.
- The draft is now organized into:
  - `paper.tex`
  - `sections/`
  - `references.bib`
- Build artifacts are ignored by Git.
- The current local TeX environment supports `latexmk -pdf` for this template.
