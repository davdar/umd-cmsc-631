out/favorite-pl.pdf: tmp/favorite-pl.autogen.tex favorite-pl.tex
	mkdir -p out
	pdflatex --output-directory out favorite-pl.tex

tmp/favorite-pl.autogen.tex: favorite-pl.markdown
	mkdir -p tmp
	pandoc -f markdown -t latex -o tmp/favorite-pl.autogen.tex favorite-pl.markdown

clean:
	rm -rf tmp
	rm -rf out
