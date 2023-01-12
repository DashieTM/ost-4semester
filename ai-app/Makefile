ai-app.pdf: ai-app.tex ../ost-summary-template.tex
	latexmk -pdf -shell-escape ai-app.tex

clean:
	(rm -f *.aux *.fdb_latexmk *.fls *.log *.out *.synctex.gz *.xdv);\

move: 
	cp ai-app.pdf $${HOME}/Documents/OST\ 4.semester/ai-app.pdf
