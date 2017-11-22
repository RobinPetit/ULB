TEX_FILES=assignment1.tex assignment2.tex
PDF_FILES=$(TEX_FILES:.tex=.pdf)

all: $(PDF_FILES)

%.pdf: %.tex
	pdflatex $<
	pdflatex $<

clean:
	rm -f *.aux *.log *.pdf
