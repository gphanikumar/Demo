# usage:
#   make once -> single compilation to fix syntax issues
#   make all -> multiple compilation steps to come upto pdf file
# The dependencies are as per included images and bibliographic info.

once: assn4.tex
	latex assn4.tex
all: assn4.tex
	latex assn4.tex
	bibtex assn4
	latex assn4.tex
	dvipdf assn4.dvi
# If the above steps are executed successfully, the file sample.pdf should be ready.
#
# make clean -> to remove temporary files from the folder
clean:
	rm -f assn4.aux assn4.bbl assn4.log assn4.dvi assn4.blg assn4.lot assn4.lof assn4.out assn4.toc
# end of Makefile
