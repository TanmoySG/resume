# Resume – Tanmoy Sen Gupta

LaTeX source for Tanmoy Sen Gupta's resume.

## Files

| File | Description |
|------|-------------|
| `resume.tex` | LaTeX source file (Jake's Resume template) |
| `resume.pdf` | Compiled PDF output |

## Installation

`pdflatex` is a LaTeX typesetting binary — **not** a Python package. Do **not** use `pip install pdflatex`. Install it through your system package manager:

**macOS (Homebrew)**

```bash
# Minimal TeX installation (recommended)
brew install basictex

# — or — full MacTeX distribution
brew install --cask mactex
```

After installing BasicTeX you may need to update `tlmgr` and install additional packages used by this template:

```bash
sudo tlmgr update --self
sudo tlmgr install latexmk collection-fontsrecommended enumitem
```

**Linux (Debian / Ubuntu)**

```bash
sudo apt-get update
sudo apt-get install texlive-latex-base texlive-fonts-recommended texlive-latex-extra
```

**Windows**

Download and install [MiKTeX](https://miktex.org/download) or [TeX Live](https://tug.org/texlive/).

## Build

```bash
pdflatex resume.tex
```

The compiled `resume.pdf` will be created in the same directory.
