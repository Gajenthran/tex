NAME=diapo
TEX=$(NAME).tex
SRC=$(TEX) $(NAME).bib
PDF=$(TEX:.tex=.pdf)

all: $(PDF)

$(PDF):	$(SRC)
	xelatex $(TEX)
	# bibtex   $(NAME)
	xelatex $(TEX)
	xelatex $(TEX)

clean:
	rm -f $(PDF) $(NAME).bcf $(NAME).nav $(NAME).run.xml $(NAME).snm $(NAME).synctex.gz $(NAME).toc $(NAME).aux $(NAME).out $(NAME).log $(NAME).loa $(NAME).lof $(NAME).bbl $(NAME).blg $(NAME).locs *~
