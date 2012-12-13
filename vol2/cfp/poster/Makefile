base = cfp-vol2

all: $(base).pdf

$(base).pdf: $(base).tex
	pdflatex $(base).tex

clean:
	rm -f *.log *.bbl *.blg *.aux *.dvi *.out *.*.backup $(base).ps $(base).pdf *.*~
