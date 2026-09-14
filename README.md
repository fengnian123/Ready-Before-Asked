# Ready Before Asked — ICLR 2027 manuscript

This repository contains the anonymous ICLR 2027 paper draft:

**Ready Before Asked: Compositional Evidence-Time Planning for Interruptible Pre-Task Exploration**

The manuscript follows the official ICLR 2027 LaTeX template from the [ICLR Master-Template repository](https://github.com/ICLR/Master-Template/tree/master/iclr2027). The official style files are included unchanged.

## Build

Run:

    make

or:

    latexmk -pdf -interaction=nonstopmode main.tex

The output is main.pdf.

## Structure

- main.tex: paper entry point and required ICLR statements
- sections/: main paper and appendix source
- references.bib: bibliography
- figures/: future figure assets
- iclr2027_conference.sty and .bst: official ICLR 2027 format
- TODO.md: items that must be resolved before submission

All figures and result tables are deliberate placeholders. No synthetic results are included. The manuscript now documents physical deployment on DEEP Robotics LYNX M20, X30, and Lite3 platforms in indoor and outdoor environments; the platform configuration is fixed, while quantitative robot results and qualitative frames remain placeholders. Keep iclrfinalcopy commented for anonymous review and enable it only for the camera-ready version.
