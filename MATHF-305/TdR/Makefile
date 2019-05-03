show: TdR.pdf
	evince $< &

TdR.pdf: TdR.tex
	pdflatex $<
	bibtex TdR
	pdflatex $<
	pdflatex $<

clean:
	rm -f TdR.out TdR.log TdR.snm TdR.toc TdR.pdf TdR.aux TdR.nav TdR.bbl TdR.blg
