
all: main

main: main.tex
	pdflatex main

clean:
	$(RM) *.aux *.log *.toc *.nav *.out *.snm

install: main
	cp main.pdf ~/Dropbox/nas/
