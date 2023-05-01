all: v1

v1:
	rm -f Software-Problems-2022_1-0-0.pdf
	pdflatex Software-Problems-2022_1-0-0.tex
	bibtex Software-Problems-2022_1-0-0.aux
	pdflatex Software-Problems-2022_1-0-0.tex
	pdflatex Software-Problems-2022_1-0-0.tex
	rm -f *.blg *.log *.aux *.bbl *blx.bib *.bcf *.run*
