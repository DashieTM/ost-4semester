web2.pdf: web2.tex ../ost-summary-template.tex
	latexmk -pdf -shell-escape web2.tex

clean:
	(rm -f *.aux *.fdb_latexmk *.fls *.log *.out *.synctex.gz *.xdv);\

move: 
	cp web2.pdf $${HOME}/Documents/OST\ 4.semester/web2.pdf
