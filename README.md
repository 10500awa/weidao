## Disclaimer

I've realized there are many more papers that I didn't knew, I'm going to read them and make this project a Compendium of them all, the Book of the Game of Go (hopefully), that's my spirit. It will take me some time, but I'll get there.

# 圍道 — Wéi Dào: The Art of Surrounding

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![PDF Release](https://img.shields.io/github/v/release/10500awa/EADR.svg?label=PDF+Release)](https://github.com/10500awa/EADR/releases)
*A mathematical and formal exploration of the game of Go, covering its history, rigorous formalizations, and further abstractions.*

## Overview

This repository contains the complete LaTeX source code for **圍道 — Wéi Dào: The Art of Surrounding**. The work is structured into three main parts and one draft:

- **Part I: Foundations** — Historical background spanning from ancient China to its evolution in Argentina, alongside the rules of the game.
- **Part II: Construction** — Formal two-dimensional, two-player mathematical model. Precise formulations of legal moves, captures, Superko resolution (via Zobrist hashing), $n$-dimensional generalization ($m$ players), and group life theory (revisiting David Benson's work).
- **Part III: Abstractions** — Geometric and graph-theoretic behavior of adjacencies in higher dimensions, an analysis of three-dimensional Go, one-dimensional variants, and common underlying structures across abstract board games.

- **Part IV: Abstractions** - WIP, infinite Go discussion.




## Prerequisites & LaTeX Dependencies

To compile `main.tex`, you will need a running distribution of **XeLaTeX** and **Biber**, along with the following packages:

* **Language & Fonts:** `babel` (English), `fontspec`, `xeCJK` (*Noto Serif/Sans CJK SC* fonts), `csquotes`, `newpxtext`, `newpxmath`, `microtype`.
* **Mathematics:** `amsmath`, `amsthm`, `amsfonts`, `mathtools`.
* **Graphics & Diagramming:** `tikz`, `tikz-cd`, `pgfplots`, `xcolor`, `graphicx`, `wrapfig`, `float`, `pdfpages`.
  * *TikZ libraries:* `arrows.meta`, `bending`, `positioning`, `shadows`, `calc`, `shapes.geometric`, `decorations.text`, `babel`.
* **Layout & Editorial:** `geometry`, `fancyhdr`, `tocloft`, `caption`, `epigraph`, `booktabs`, `multicol`, `multirow`, `emptypage`.
* **Citations & Hyperlinks:** `biblatex` (with `biber`), `hyperref`, `xurl`, `xspace`.

## Contributing

Feedback, corrections, and contributions are welcome. If you spot a mathematical error, a typo, or have suggestions for improving the formalizations, please feel free to open an issue or submit a pull request.
