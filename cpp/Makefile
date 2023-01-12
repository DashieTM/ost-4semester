cpp.pdf: cpp.tex ../ost-summary-template.tex
	latexmk -pdf -shell-escape cpp.tex

clean:
	(rm -f *.aux *.fdb_latexmk *.fls *.log *.out *.synctex.gz *.xdv);\

move: 
	cp cpp.pdf $${HOME}/Documents/OST\ 4.semester/cpp.pdf
