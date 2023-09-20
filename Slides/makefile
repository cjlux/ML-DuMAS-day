all:
	pdflatex -shell-escape slides.tex && okular slides.pdf &

clean:
	rm -f *.aux *.toc *.log *.nav *.out *.snm *~ *.vrb
	rm -rf _minted-slides
