# WCCM LaTeX Template

This is a public service.
Over [16 million](https://www.microsoft.com/investor/reports/ar21/index.html)
people have to use Microsoft Word everyday. If you, or someone you know, needs
help use this LaTeX template for the next
[World Congress on Condition Monitoring](https://www.wccm2021.com/). You are
not alone.

## Usage

Put all references in `./bibliography.bib`. Add acronyms to `./acronyms.tex`.
Compile the paper with:

```{shell}
% lualatex -shell-escape -enable-write18 paper.tex
% bibtex
% lualatex -shell-escape -enable-write18 paper.tex
% lualatex -shell-escape -enable-write18 paper.tex
```
