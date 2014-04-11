all:
	latex ej_article.tex
	latex ej_article.tex
	bibtex ej_article
	latex ej_article.tex
	latex ej_article.tex
	dvips -o ej_article.ps ej_article.dvi
	ps2pdf -sPAPERSIZE=a4 -DMaxSubsetPct=100 -dCompatibilityLevel=1.2 -dSubsetFonts=true -dEmbedAllFonts=true memte.ps memte.pdf

clean:
	rm -f *.toc *.ps *.log *.lof *.lot *.dvi *.aux *.blg *.bbl *.*~
