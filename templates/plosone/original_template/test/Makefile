fileinfo := Makefile to compile a tex document
author   := github.com/mxochicale 
version  := alpha

FILENAME = plos_latex_template
LATEX 	 = latex
DVIPDF = dvipdf
all:
	$(LATEX) $(FILENAME).tex
	$(LATEX) $(FILENAME).tex
	$(LATEX) $(FILENAME).tex
	$(DVIPDF) $(FILENAME).dvi
	evince $(FILENAME).pdf &
	@echo "================================================"
	@echo " PDF file has been created! :) "
	@echo "================================================"

clean:
	rm -f *~
	rm -f *.aux
	rm -f *.bbl
	rm -f *.blg
	rm -f *.dvi
	rm -f *.log
	rm -f *.out
	rm -f `ls $(FILENAME).* | grep -v .tex | grep -v .pdf`	
	@echo "================================================"
	@echo "All cleaned! :) "
	@echo "================================================"

