# schemaanalyst-bibliography

This repository contains a BibTeX file for all of the research papers, presentations, volumes edited, supervised theses,

and supervised presentations of me, [Gregory M. Kapfhammer](http://www.cs.allegheny.edu/sites/gkapfham). You are free to
use any of the entries in this file if you are interested in citing one of these research deliverables in a LaTeX
document.

## Installation Instructions

You can type the following command if you want to clone this repository:

```shell
git clone https://github.com/gkapfham/schemaanalyst-bibliography.git
```

Now, you can type `cd research-bibliography` and use the BibTeX file in your own LaTeX project.  Alternatively, a
document that cites all of the entries in this bibliography can be compiled on an Ubuntu 15.04 LTS workstation using
`pdflatex` and `biber`; you may also compile to a PDF file using a wide variety of other tools, such as `latexmk`. You
can type the following commands to create the summary document.

```shell
pdflatex research_bibliography.tex
biber research_bibliography.bcf
pdflatex research_bibliography.tex
pdflatex research_bibliography.tex
```

If you find that some of the entries are incorrectly formatted and thus your LaTeX and BibTeX tools are not processing
them correctly, please open a new issue and I will attempt to resolve your concerns.  If you find this repository
useful, then I hope that you will star it.

## Troubleshooting
