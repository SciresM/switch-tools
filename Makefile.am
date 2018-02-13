# Makefile.am -- Process this file with automake to produce Makefile.in
bin_PROGRAMS = elf2nso elf2nro build_pfs0 nacptool build_romfs

build_pfs0_SOURCES	=	src/build_pfs0.c src/types.h
build_romfs_SOURCES = src/build_romfs.c src/filepath.c src/filepath.h src/types.h
elf2nro_SOURCES	=	src/elf2nro.c src/elf64.h src/elf_common.h
elf2nso_SOURCES	=	src/elf2nso.c src/sha256.c src/sha256.h src/elf64.h src/elf_common.h
nacptool_SOURCES	=	src/nacptool.c

elf2nso_LDADD = @LZ4_LIBS@

EXTRA_DIST = autogen.sh
