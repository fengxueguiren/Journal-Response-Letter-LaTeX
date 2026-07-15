# Response Letter LaTeX Template

A compact and visually polished LaTeX template for journal or conference response letters.

This template is designed for reviewer rebuttals and revision response documents. It provides:

- structured sections for the Associate Editor and each reviewer
- styled comment/response blocks
- optional revised-text excerpts
- page footer with paper ID and page count
- lightweight theme color presets
- `pdflatex` compatibility by default

## Features

- `pdflatex`-friendly setup
- clean serif body text with sans-serif structural labels
- reviewer-level overall recommendation block
- separate environments for comments and responses
- optional color-coded revised text:
  - blue for modified text
  - red for newly added text
- optional page/line and section references
- multiple built-in theme presets

## Preview Structure

The template organizes a response letter as:

1. document title and manuscript ID
2. associate editor section
3. reviewer sections
4. per-comment response blocks
5. optional excerpt boxes showing revised manuscript text

## Requirements

Compile with `pdflatex`.

Required LaTeX packages:

- `geometry`
- `fontenc`
- `inputenc`
- `newtxtext`
- `helvet`
- `xcolor`
- `ifthen`
- `hyperref`
- `xr`
- `titlesec`
- `setspace`
- `tcolorbox`
- `etoolbox`
- `fancyhdr`
- `lastpage`

A standard TeX Live or MiKTeX installation should be sufficient.

## Quick Start

1. Copy the template into a `.tex` file, for example `response_letter.tex`.
2. Replace:
   - `Manuscript Title Here`
   - `# Paper ID`
3. Update the introductory text if needed.
4. Add your editor and reviewer responses using the provided environments.
5. Compile with:

```bash
pdflatex response_letter.tex
pdflatex response_letter.tex
