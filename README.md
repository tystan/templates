## `templates`

A collection of templates I have created and use - possibly created from other templates. Most of these templates are TeX and LaTeX related.

The `pdf` directory contains the expected output from the templates in the current directory.
The `fig` directory contains the file dependencies of the templates.

File | Description
--- | --- | ---
`beamer-template.tex`  | Simple beamer template for presentations.
`default-template.tex`  | Standard article in LaTeX with the packages I use to make things prettier. 
`knitr-template.Rnw`  | A template to include `R` code (evaluated) in TeX documents. to turn an `.Rnw` file to `.pdf`, run this in command line (assuming you have `R` installed/in the system's path, and have the `knitr` package installed in `R`): `Rscript -e "library(knitr); knit2pdf('knitr-template.Rnw')"`.
`poster-template-a2.tex`  | An A2 poster template using LaTeX. Can be made into A1 or A0 sizes if required.



