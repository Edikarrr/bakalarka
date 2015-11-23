#all: prace.pdf
#
## LaTeX je potreba spustit dvakrat, aby spravne spocital odkazy
#prace.pdf: bak_prace.tex $(wildcard *.tex)
#	pdflatex -jobname=prace $<
#	pdflatex -jobname=prace $<
#
#clean:
#	rm -f *.{log,dvi,aux,toc,lof,out,blg,bbl} prace.pdf
#

all: prace.pdf

# LaTeX je potreba spustit dvakrat, aby spravne spocital odkazy
prace.pdf: $(wildcard *.tex)
	pdflatex bak_prace
	#bibtex bak_prace
	#pdflatex bak_prace
	pdflatex bak_prace
	mv bak_prace.pdf prace.pdf

clean:
	rm -f *.{log,dvi,aux,toc,lof,out,blg,bbl} prace.pdf
