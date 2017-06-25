main: main.tex
	mkdir ../tmp/
	cp -r * ../tmp
	pdflatex main.tex
	bibtex main
	pdflatex main.tex
	pdflatex main.tex
	mv main.pdf ../Doku.pdf

