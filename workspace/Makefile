main.pdf: main.tex
	vlna -l -f main.tex main_v.tex
	pdflatex main_v.tex
	pdflatex main_v.tex
	mv main_v.pdf main.pdf

all: clean main.pdf

show:
	xdg-open main.pdf

clean:
	rm -fv *.log *.aux *.pdf *.dvi *.toc
