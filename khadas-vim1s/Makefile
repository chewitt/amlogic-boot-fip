O ?= .
TMP ?= .
BL33 ?=

.phony: clean distclean

all: ${O}/u-boot.bin

clean:
	# no-op

distclean: clean

${O}/u-boot.bin:
	cp u-boot.bin.sd.bin.signed ${O}/u-boot.bin
