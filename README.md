# git-latex-diff-compile

This command is a very thin and stupid wrapper around latexdiffcite https://pypi.python.org/pypi/latexdiffcite
It just runs that command to generate a latex diff and then compiles the resulting latex assuming that you want to use pdflatex and bibtex.

## Installation

Put the script in this folder someone on your $PATH, e.g. /usr/local/bin

## Usage

Syntax:

```
    git-latex-diff-compile   input_filename.tex   revision  output_filename.pdf
```

where revision can be a git tag, branch name, or commit hash - see git documentation on finding these.

latexdiffcite has a lot more flexibility than is used here - to do anything more complicated you probably want to use it directly.
