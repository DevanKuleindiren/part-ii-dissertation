diss : tex1 index bibliography tex2 
	pdflatex Part\ II\ Dissertation.tex

count : 
	texcount -1 -sum Part\ II\ Dissertation.tex > word.count

index :
	makeindex Part\ II\ Dissertation.tex

bibliography :
	bibtex Part\ II\ Dissertation.tex

tex1 :
	latex Part\ II\ Dissertation.tex

tex2 :
	latex Part\ II\ Dissertation.tex
