FILE	:= diplomarbeit


diploma:  
	pdflatex $(FILE)
	bibtex $(FILE)
	makeindex $(FILE).nlo -s nomencl.ist -o diplomarbeit.nls
	pdflatex $(FILE)
	

