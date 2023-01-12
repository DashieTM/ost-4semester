sep2.pdf: sep2.tex ../ost-summary-template.tex
	latexmk -pdf -shell-escape sep2.tex

clean:
	(rm -f *.aux *.fdb_latexmk *.fls *.log *.out *.synctex.gz *.xdv);\

move: 
	cp sep2.pdf $${HOME}/Documents/OST\ 4.semester/sep2.pdf
