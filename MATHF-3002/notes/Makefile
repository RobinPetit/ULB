all: notes.pdf
	evince notes.pdf &

notes.pdf: notes.tex
	pdflatex notes.tex
	pdflatex notes.tex

clean:
	rm -f notes.aux notes.log notes.out notes.pdf notes.toc
