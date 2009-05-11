all: clean presentacion.pdf

pdf: presentacion.pdf

presentacion.pdf: presentacion.tex
	pdflatex presentacion.tex
	pdflatex presentacion.tex


clean: 
	rm -f *.ps *.dvi *.aux *.toc *.idx *.ind *.ilg *.log *.out *.snm *.nav *~ presentacion.pdf