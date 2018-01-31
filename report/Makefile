all: report.pdf

report.pdf: report.tex introduction.tex related.tex ctlskd.tex alternative.tex reduction.tex modelcheck.tex multiagent.tex conclusion.tex appendix.tex ../bib/slii.bib
	pdflatex report.tex
	bibtex report.aux
	pdflatex report.tex
	pdflatex report.tex

clean:
	-rm *.aux
	-rm *.bbl
	-rm *.log
	-rm *.blg
	-rm *.toc
	-rm report.pdf
