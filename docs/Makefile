main.pdf: main.tex formal.tex intro.tex conclusion.tex eval.tex macros.tex
	pdflatex main.tex

lang.tex: lang.ott
	ott -i lang.ott -o lang.tex -tex_show_meta false

lang.pdf: lang.tex lang.ott
	pdflatex lang.tex

clean:
	rm *.pdf *.aux *.log
