filename=guide

pdf:
	pdflatex ${filename}.tex
	$(MAKE) clean

read:
	okular ${filename}.pdf &

clean:
	rm -f ${filename}.{ps,log,aux,out,dvi,bbl,blg,nav,snm,toc}

cleanall:
	rm -f ${filename}.{ps,pdf,log,aux,out,dvi,bbl,blg,nav,snm,toc}
