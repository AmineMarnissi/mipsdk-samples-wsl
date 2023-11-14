include ../Makefile.common

DIRS = gstvpspasstru gstvpsjpegtranscoder gstvpsboundingboxes gstvpsxprotect gstvpsdeepstream gstvpsnvdstoonvif

all: setup-outdir
	$(foreach var, $(DIRS), make -C $(var)  OUTDIR=$(OUTDIR);)

clean:
	$(foreach var, $(DIRS), make clean -C $(var);)
