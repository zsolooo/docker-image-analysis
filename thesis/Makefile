pdf: sketch.pdf
	pandoc \
		--latex-engine=xelatex \
		-H preamble.tex \
		-V fontsize=12pt \
		-V documentclass:book \
		-V papersize:a4paper \
		-V classoption:openright \
		--chapters \
		--bibliography=papers.bib \
		--csl="csl/nature.csl" \
		-o "sketch.pdf" \
		sketch.md 