.PHONY: clean all

all:
	latex plos_latex_template.tex
	# bibtex plos_latex_template
	latex plos_latex_template.tex
	latex plos_latex_template.tex
	dvipdf plos_latex_template.dvi


clean:
	rm -f *~
	rm -f *.aux
	rm -f *.bbl
	rm -f *.blg
	rm -f *.dvi
	rm -f *.log
	rm -f *.out
	rm -f *.pdf
