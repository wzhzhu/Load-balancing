BASE = paper
TEX = ${BASE}.tex
DVI = ${BASE}.dvi
PS = ${BASE}.ps
PDF = ${BASE}.pdf
OUT = ${BASE}.out

LOG = ${BASE}.log
AUX = ${BASE}.aux

ifdef OS
	RM = del
else
	RM = rm -f
endif


.PHONY: all clean

all: ${PDF}

${PDF}: ${TEX}
	pdflatex $<

clean:
	$(RM) ${DVI} ${PS} ${PDF} ${LOG} ${AUX} ${OUT}