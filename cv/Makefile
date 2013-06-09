
.PHONY: all clean smallclean show

all: cv.pdf smallclean

cv.pdf: cv.tex
	pdflatex $<

show: all
	evince cv.pdf &

clean: smallclean
	@rm -f cv.pdf

smallclean:
	@rm -f *.aux *.log *.out *~