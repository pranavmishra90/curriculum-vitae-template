# Curriculum Vitae

[![Build-LaTex-Document](https://github.com/pranavmishra90/curriculum-vitae-template/actions/workflows/LaTex-to-PDF/badge.svg?event=push)](https://github.com/pranavmishra90/curriculum-vitae-template/actions)

These are the [Latex](./cv_template_pranav_mishra.tex) sources for my academic CV. It automatically pulls from .tex files in the [/Bibliography](./Bibliography/) directory. Alternatively, it can source all types of citations using the keyword filter in the [cv.bib](./CV.bib).

**Download** the latest compiled PDF:
[curriculum-vitae-template.pdf](https://github.com/pranavmishra90/curriculum-vitae-template/blob/gh-pages/PDF-output/curriculum-vitae-template.pdf)

## Template

You're free to reuse and modify this template under the terms of the BSD
3-clause License (see `LICENSE.md`). Significant credit goes to [Leonardo Uieda](https://github.com/leouieda) who created the original [repository](https://github.com/leouieda/cv). This repository is a modification on his work for content and style.

## Building

I use [Tectonic](https://tectonic-typesetting.github.io) to build the PDF from
the sources.
It's very convenient, can be installed from
[conda-forge](https://github.com/conda-forge/tectonic-feedstock),
and is faster than using a normal LaTeX compiler.
There are many ways to install it (see their website for instructions).

I highly recommend using the `Makefile`:

* `make`: builds the PDF
* `make show`: opens the PDF on the default web browser
* `make clean`: removes the built PDF and any other generated files

## Deploying

A PDF is compiled automatically by GitHub Actions with every commit to the
`main` branch and uploaded to the `gh-pages` branch.
This way, the compiled PDF is updated and served automatically.

## License

All LaTeX template source code is distributed under the
[BSD 3-clause License](https://opensource.org/licenses/BSD-3-Clause). See [License](./LICENSE.md) for more information.
