diss : tex1 index bibliography tex2 
	pdflatex Part\ II\ Dissertation.tex

count : 
	detex Part\ II\ Dissertation.tex | tr -cd '0-9A-Za-z \n' | wc -w

index :
	makeindex Part\ II\ Dissertation.tex

bibliography :
	bibtex Part\ II\ Dissertation.tex

tex1 :
	latex Part\ II\ Dissertation.tex

tex2 :
	latex Part\ II\ Dissertation.tex
