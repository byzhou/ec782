compiler = pdflatex

default:all
all:
	$(compiler) pre_order.tex
evince:
	evince pre_order.pdf &
clean:
	rm -rf *.aux *.log
