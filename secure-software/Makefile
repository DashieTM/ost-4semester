secure-software.pdf: secure-software.tex ../ost-summary-template.tex
	latexmk -pdf -shell-escape secure-software.tex

clean:
	(rm -f *.aux *.fdb_latexmk *.fls *.log *.out *.synctex.gz *.xdv);\

move: 
	cp secure-software.pdf $${HOME}/Documents/OST\ 4.semester/secure-software.pdf
