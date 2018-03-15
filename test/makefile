#
LATEX?=pdflatex

example1 : chemsec.sty example1.tex
	${LATEX} example1.tex
	${LATEX} example1.tex

example1.tex : ../example1.tex
	cp ../example1.tex .

example2 : chemsec.sty example2.tex
	${LATEX} example2.tex
	${LATEX} example2.tex

example2.tex : ../example2.tex
	cp ../example2.tex .

example3 : chemsec.sty example3.tex
	${LATEX} example3.tex
	${LATEX} example3.tex

example3.tex : ../example3.tex
	cp ../example3.tex .

example4 : chemsec.sty example4.tex
	${LATEX} example4.tex
	${LATEX} example4.tex

example4.tex : ../example4.tex
	cp ../example4.tex .

example5 : chemsec.sty example5.tex
	${LATEX} example5.tex
	${LATEX} example5.tex

example5.tex :
	cp ../example5.tex .

chemsec.sty : ../chemsec.sty 
	cp ../chemsec.sty .

clean :
	rm -f example* chemsec.sty
