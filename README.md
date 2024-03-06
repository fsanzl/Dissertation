# Introduction
This repository contains the source files of my PhD thesis 'Ritmo y estructura de la comedia áurea: posibilidades y límites del análisis digital automático del teatro español clásico'. It fulfils the [formal requisites of the University of Vienna](https://lehre-schmelz.univie.ac.at/waehrend-des-studiums/abschlussarbeiten/). The source code is intended to be compiled with [XeLaTeX](https://tug.org/xetex/) and [Biber](https://www.ctan.org/pkg/biber).

# Structure
The master document, chapters and bibliography are in the ```thesis``` directory. The directory ```thesis/figures``` contains LaTeX code to draw figures, the directory ```thesis/images``` contains binary pictures, the directory ```thesis/tables``` contains LaTeX code for tables, and the directory ```thesis/src``` contains the Python code included in the appendices.

# Compilation

```bash
$ xelatex main && biber main && xelatex main && xelatex main
```

# About the dissertation
The thesis was defended at the [Department of Romance Studies](https://romanistik.univie.ac.at/) of the University of Vienna on 13 March 2024. It aimed at producing a corpus for the project [Sound and Meaning in Spanish Golden Age Literature](https://doi.org/10.55776/P32563). The published dissertation can be found [here](https://doi.org/10.25365/thesis.75102).

## How to cite the dissertation
### BibTeX

```bibtex
@phdthesis{sanzlazaro2024thesis,
  author = {Sanz-Lázaro, Fernando},
  title = {Ritmo y estructura de la comedia áurea: posibilidades y límites del análisis digital automático del teatro español clásico},
  school = {Universität Wien},
  date = {2024},
  doi = {10.25365/THESIS.75102},
  url = {https://hdl.handle.net/11353/10.1678196}, 
  language = {es},
  langid = {Spanish},
  year = {2024}
}
```
### APA

Sanz-Lázaro, F. (2024). *Ritmo y estructura de la comedia áurea: posibilidades y límites del análisis digital automático del teatro español clásico* [Doctoral dissertation, University of Vienna]. PHAIDRA. <https://hdl.handle.net/11353/10.1678196>

# Related work

Please check my other repos containing the practical application of the thesis:
- [libEscansión](https://github.com/fsanzl/libEscansion)
- [Fonemas](https://github.com/fsanzl/fonemas)
- [Silabeador](https://github.com/fsanzl/silabeador)
- [txt2tei](https://github.com/fsanzl/txt2tei)
