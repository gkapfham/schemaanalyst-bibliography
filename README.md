# schemaanalyst-bibliography

This repository contains a BibTeX file for papers related to the field of testing database applications. It was created
by Chris J. Wright, Phil McMinn, and Gregory M. Kapfhamer, the researchers who are a part of the [SchemaAnalyst
Project](http://www.schemaanalyst.org). You are free to use any of the entries in this file if you are interested in
citing one of these research papers in your own LaTeX document.

## Installation Instructions

You can type the following command if you want to clone this repository:

```shell
git clone https://github.com/gkapfham/schemaanalyst-bibliography.git
```

Now, you can type `cd schemaanalyst-bibliography` and use the BibTeX file in your own LaTeX project.  Alternatively, a
document that cites all of the entries in this bibliography can be compiled on an Ubuntu 15.04 LTS workstation using
`pdflatex` and `bibtex`; you may also compile to a PDF file using a wide variety of other tools, such as `latexmk`. You
can type the following commands to create the summary document.

```shell
pdflatex schemaanalyst_bibliography.tex
bibtex schemaanalyst_bibliography.bcf
pdflatex schemaanalyst_bibliography.tex
pdflatex schemaanalyst_bibliography.tex
```

Alternatively, you can use the repository as a git submodule of another repository. To do this, type the following
command:

```shell
git submodule add -b master https://github.com/gkapfham/schemaanalyst-bibliography.git bibtex
```

where the final parameter ("bibtex") is the name of the directory that you wish to install the repository. Following 
this, you will need to invoke the following commands:

```shell
git submodule init
git submodule update
```

Of course, the submodule will need to be pulled periodically to receive any changes. This can be done by changing 
directory to the submodule and issue the usual ``git pull``. (If Git has detached the submodule from its HEAD, it
may be reattached by issuing the command ``git checkout master`` from the submodule's directory.

Another means of ensuring the submodule is updated when pulling from the main repository is to issue the following 
command, which will also update all submodules:

```shell
git pull --recurse-submodules
```

## Problems or Praise?

If you find that some of the entries are incorrectly formatted and thus your LaTeX and BibTeX tools are not processing
them correctly, then please open a new issue and one of us will attempt to resolve your concerns.  Please note that the
provided BibTeX file is not likely to compile correctly &mdash; due to issues with encoding in Unicode &mdash; if you
try to use `biber` as your BibTeX file manager. Finally, if you find this repository useful, then we hope that you will
star it.