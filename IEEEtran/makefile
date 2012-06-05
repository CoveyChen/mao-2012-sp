all: bare_conf.pdf

bare_conf.pdf: bare_conf.tex mycontent.tex mybib.bib
	pdflatex bare_conf.tex
	bibtex bare_conf.aux
	pdflatex bare_conf.tex
	pdflatex bare_conf.tex