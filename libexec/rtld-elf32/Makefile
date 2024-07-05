
#NEED_COMPAT=	32
#.include <bsd.compat.mk>

#PROG=	ld-elf32.so.1
#MAN=
#MLINKS=	rtld.1 ld-elf32.so.1

#.PATH:  ${SRCTOP}/libexec/rtld-elf
#.include "${SRCTOP}/libexec/rtld-elf/Makefile"
#

NEED_COMPAT=	32
.include <bsd.compat.mk>

PROG=	ld-elf32.so.1
MAN=
MLINKS=	rtld.1 ld-elf32.so.1

# Boş bir dosya oluşturmak için hedef
.PHONY: all install clean

all:
	@echo "Skipping ld-elf32.so.1 creation"
	@touch ${PROG}

install:
	@echo "Installing empty ld-elf32.so.1"
	@install -m 755 ${PROG} ${DESTDIR}/libexec

clean:
	@echo "Cleaning up"
	@rm -f ${PROG}

.PATH:  ${SRCTOP}/libexec/rtld-elf
.include "${SRCTOP}/libexec/rtld-elf/Makefile"
