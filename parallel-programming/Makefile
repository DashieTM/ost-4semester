parallel-programming.pdf: parallel-programming.tex ../ost-summary-template.tex
	latexmk -pdf -shell-escape parallel-programming.tex

clean:
	(rm -f *.aux *.fdb_latexmk *.fls *.log *.out *.synctex.gz *.xdv);\

move: 
	cp parallel-programming.pdf $${HOME}/Documents/OST\ 4.semester/parallel-programming.pdf
