# Makefile

LT = pdflatex

# Compile the tex-files

all: project

project: project.tex
	$(LT) project.tex -o project.pdf && $(LT) project.tex -o project.pdf

clean:
	rm -rf *.toc *.aux *.pdf *.lo*
