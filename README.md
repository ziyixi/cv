# TIAN Dongdong (田冬冬)'s Curriculum Vitae

[![Build](https://github.com/seisman/cv/actions/workflows/build.yaml/badge.svg)](https://github.com/seisman/cv/actions/workflows/build.yaml)
[![GitHub](https://img.shields.io/github/license/seisman/cv)](https://github.com/seisman/cv/blob/main/LICENSE.txt)

These are the LaTeX source files for my academic CV.

## Download

Download my CV:

- [English version](https://github.com/seisman/cv/raw/gh-pages/DTian_cv_en.pdf)
- [Chinese version](https://github.com/seisman/cv/raw/gh-pages/DTian_cv_cn.pdf)

## Build

To build the CV, you need to have LaTeX installed. The full LaTeX distribution
(e.g., TeXLive on Linux or MacTeX on macOS) are usually too big (>5 GB).
I recommend to install the lightweight [TinyTeX](https://yihui.org/tinytex/)
(< 100MB).

1. 	Install TinyTeX:

		curl -sL "https://yihui.org/tinytex/install-bin-unix.sh" | sh

2. 	Install LaTeX packages needed by the CV template:

		make install_packages

3. 	Build the CV:

		make

## License

The CV template is released under the terms of the BSD 3-clause License.

## Acknowledgemnt

The CV template is modified from https://github.com/leouieda/cv.
