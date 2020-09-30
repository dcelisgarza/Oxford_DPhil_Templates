# LaTeX Templates

Thesis and presentation templates with minimal working examples for my PhD. By default these use XeLaTeX. XeLaTeX is the weapon of choice because it offers `.eps` compatibility and offers features that `pdfLaTeX` does not while being more stable than `LuaLaTex`. However, with a few package modifications, it can be made to run with these other engines. The package `minted` requires a working `Python` installation with `pygments` and the `--shell-espcape` option at compilation.

## Thesis

All source files are found in `/thesis_sample/src/`, image files in `/thesis_sample/images/`. I recommend creating custom macros for your purposes and placing them in `macros.tex`, which already contains a few macros that facilitate working with glossaries and indices. For customisation of the document class and finding out about the options available see `genthesis.cls` as it is fully commented and explained with the aim of documenting existing functionality and providing instructions on customisation. The file `glossary.tex` contains a few sample glossary entries.

## Poster

All source files are found in `/poster_sample/src/` and image files in `/poster_sample/images`. It's not flashy, but it's simple, elegant and forces you to be concise. Change the background, header and footer to suit your needs.
