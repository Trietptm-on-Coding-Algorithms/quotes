all: message.pdf

message.pdf: message.tex
	texi2pdf -q -c $<

clean:
	rm -f *.aux *.log *.out *.toc *.blg *.bbl
