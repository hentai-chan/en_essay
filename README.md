# English Essay Template

## About

Very simplistic LaTeX template for writing English essays featuring an
exemplary bibliography.

## Compile

For the sake of simplicity, keep the name of `tex` and `bib` file the
same. See also [this](https://mirror.las.iastate.edu/tex-archive/support/latexmk/INSTALL)
document for further information. Both TeX Live and MikTeX come with
`latexmk`, though since this is a perl script you need to have perl
installed on your system to run this command.

```
latexmk en_essay.tex -outdir=build -pdf
```

## Clear Cache

```
latexmk -C -outdir=build
```
