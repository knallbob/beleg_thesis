LATEXMK = latexmk
LATEXMK_FLAGS = -pdf --shell-escape

all: pdf 

pdf:
	$(LATEXMK) $(LATEXMK_FLAGS)

clean:
	rm *.aux *.fdb_latexmk *.fls *.log *.bbl *.blg *.lof *.out *.toc

.PHONY: all pdf clean cleanall
