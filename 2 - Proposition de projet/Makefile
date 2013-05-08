all: proposition

bib: proposition.bbl

proposition: proposition.pdf

proposition.pdf: proposition.tex
	xelatex proposition.tex

proposition.bbl : proposition.tex bibliography.bib
	xelatex proposition.tex
	bibtex proposition
	xelatex proposition.tex
	xelatex proposition.tex
