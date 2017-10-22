homework: homework.pdf
	evince homework.pdf &

homework.pdf: homework.tex homework.bib
	latex homework
	bibtex homework
	latex homework
	latex homework
	dvips -o homework.ps -t letterSize homework.dvi
	ps2pdf homework.ps homework.pdf

clean:
	rm -f homework.aux
	rm -f homework.log
	rm -f homework.blg
	rm -f homework.bbl
	rm -f homework.dvi
	rm -f homework.ps
	rm -f homework.pdf
