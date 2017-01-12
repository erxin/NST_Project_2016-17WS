# NST_Project_2016-17WS
This is the project which is implemented by Bo Huang, Bi Wang and Erxin Wang in winter semester 2016/17 at TUM


This folder contains a LaTeX template to write a student report for Advanced
Seminars and Practical Laboratories. In order to generate a PDF file, you need
to invoke latex, pdflatex, latexmk, or any other suitable LaTeX processor. Make
sure to invoke your latex processor and bibtex in the correct order and the
right number of times. For instance, for pdflatex the compilation sequence is:

	pdflatex file.tex
	bibtex file.tex
	pdflatex file.tex
	pdflatex file.tex

Some processors will handle the correct invokation by themselves, for instance
latexmk. For latexmk, the only necessary command to generate a pdf is

	latexmk -pdf file.tex

Obviously, file.tex needs to be replaced with your filename in all examples. The
file bibliography.bib contains bibtex entries for all referenced literature
