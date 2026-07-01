# NCPD 2026 Proposal Template

LaTeX template for the NCPD 2026 Inclusive Design Challenge proposal / concept screening round.

## Files

- `main.tex` - XeLaTeX wrapper with page setup, fonts, header, and section includes.
- `sections/` - editable English proposal sections matching the official 1-9 structure.
- `assets/ncpd2026-logo.png` - logo cropped from the provided official PDF.
- `Template_ประกวดนวัตกรรม_NCPD2026 Template รอบที่ 1.pdf` - original reference template.

## Official Section Map

1. Project Title - `sections/project-info.tex`
2. Developer Information - `sections/project-info.tex`
3. Innovation Concept and Background - `sections/intro.tex`
4. Project Objectives - `sections/objectives-users.tex`
5. Target Users - `sections/objectives-users.tex`
6. Innovation Details and Method - `sections/methods.tex`
7. Impact on People with Disabilities and Society - `sections/impact.tex`
8. Feasibility for Real-World Use - `sections/feasibility.tex`
9. Conclusion - `sections/conclusion.tex`

## Requirements

- A TeX distribution with `latexmk` and XeLaTeX.
- A Thai font. The template tries these fonts in order:
  1. `TH Sarabun New`
  2. `TH SarabunPSK`
  3. `Noto Serif Thai`
  4. `Thonburi`

The official instructions specify A4 paper, 1 inch margins, TH SarabunPSK 16 pt, and no more than 10 pages.

## Build

```sh
latexmk -xelatex main.tex
```

The generated PDF will be `main.pdf`.

To remove generated build files:

```sh
latexmk -C main.tex
```

## Editing

Replace the italic placeholder text in the files under `sections/` with the proposal content. Keep tables, figures, diagrams, and screenshots inside the 1 inch page margins.
