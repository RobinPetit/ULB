TEX_FILES=assignment1.tex
PDF_FILES=$(TEX_FILES:.tex=.pdf)

all: $(PDF_FILES)
	evince assignment1.pdf &

%.pdf: %.tex
	pdflatex $<
	pdflatex $<

clean:
	rm -f *.aux *.log *.pdf
