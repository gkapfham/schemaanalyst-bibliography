# schemaanalyst-bibliography

This repository contains a BibTeX file for papers related to the field of testing database applications. It was created
by Chris J. Wright, Phil McMinn, and Greegory M. Kapfhamer, the researchers who are a part of the [SchemaAnalyst
Project](http://www.schemaanalyst.org). You are free to use any of the entries in this file if you are interested in
citing one of these research papers in your own LaTeX document.

## Installation Instructions

You can type the following command if you want to clone this repository:

```shell
git clone https://github.com/gkapfham/schemaanalyst-bibliography.git
```

Now, you can type `cd schemaanalyst-bibliography` and use the BibTeX file in your own LaTeX project.  Alternatively, a
document that cites all of the entries in this bibliography can be compiled on an Ubuntu 15.04 LTS workstation using
`pdflatex` and `biber`; you may also compile to a PDF file using a wide variety of other tools, such as `latexmk`. You
can type the following commands to create the summary document.

```shell
pdflatex schemaanalyst_bibliography.tex
biber schemaanalyst_bibliography.bcf
pdflatex schemaanalyst_bibliography.tex
pdflatex schemaanalyst_bibliography.tex
```

## Problems or Praise?

If you find that some of the entries are incorrectly formatted and thus your LaTeX and BibTeX tools are not processing
them correctly, please open a new issue and I will attempt to resolve your concerns.  If you find this repository
useful, then I hope that you will star it.

