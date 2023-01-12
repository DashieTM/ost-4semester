besys2.pdf: besys2.tex ../ost-summary-template.tex
	latexmk -pdf -shell-escape besys2.tex

clean:
	(rm -f *.aux *.fdb_latexmk *.fls *.log *.out *.synctex.gz *.xdv);\

move: 
	cp besys2.pdf $${HOME}/Documents/OST\ 4.semester/besys2.pdf
