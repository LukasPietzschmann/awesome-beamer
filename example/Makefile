PAPER = main.tex
OUT_FOLDER = ./aux
ARGS = -pdflua -silent -rc-report- -view=pdf -outdir=$(OUT_FOLDER)
PRIORITY_ARGS =

all:
	latexmk $(ARGS) $(PRIORITY_ARGS) $(PAPER)

verbose:
	latexmk $(ARGS) -verbose $(PRIORITY_ARGS) $(PAPER)

draft:
	latexmk $(ARGS) -d $(PRIORITY_ARGS) $(PAPER)

clean:
	latexmk -C ; rm -rf $(OUT_FOLDER)

show:
	latexmk $(ARGS) -pv $(PRIORITY_ARGS) $(PAPER)

watch:
	latexmk $(ARGS) -pvc $(PRIORITY_ARGS) $(PAPER)

force:
	latexmk $(ARGS) -g $(PRIORITY_ARGS) $(PAPER)

.PHONY: all clean display
