# Makefile.in generated automatically by automake 1.4-p6 from Makefile.am

# Copyright (C) 1994, 1995-8, 1999, 2001 Free Software Foundation, Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.


SHELL = /bin/bash

srcdir = .
top_srcdir = ..

prefix = /usr/local
exec_prefix = ${prefix}

bindir = ${exec_prefix}/bin
sbindir = ${exec_prefix}/sbin
libexecdir = ${exec_prefix}/libexec
datadir = ${prefix}/share
sysconfdir = ${prefix}/etc
sharedstatedir = ${prefix}/com
localstatedir = ${prefix}/var
libdir = ${exec_prefix}/lib
infodir = ${prefix}/info
mandir = ${prefix}/man
includedir = ${prefix}/include/tesseract
oldincludedir = /usr/include

DESTDIR =

pkgdatadir = $(datadir)/
pkglibdir = $(libdir)/
pkgincludedir = $(includedir)/

top_builddir = ..

ACLOCAL = /home/debayan/ocr/trunk/config/missing aclocal-1.4
AUTOCONF = /home/debayan/ocr/trunk/config/missing autoconf
AUTOMAKE = /home/debayan/ocr/trunk/config/missing automake-1.4
AUTOHEADER = /home/debayan/ocr/trunk/config/missing autoheader

INSTALL = /usr/bin/install -c
INSTALL_PROGRAM = ${INSTALL} $(AM_INSTALL_PROGRAM_FLAGS)
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_SCRIPT = ${INSTALL}
transform = s,x,x,

NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
host_alias = 
host_triplet = i686-pc-linux-gnu
CC = gcc
CXX = g++
HAVE_LIB = @HAVE_LIB@
LIB = @LIB@
LTLIB = @LTLIB@
MAINT = #
MAKEINFO = /home/debayan/ocr/trunk/config/missing makeinfo
PACKAGE = 
PACKAGE_DATE = 04/22
PACKAGE_NAME = tesseract
PACKAGE_VERSION = 2.03
PACKAGE_YEAR = 2008
RANLIB = ranlib
VERSION = 

SUBDIRS = 
AM_CPPFLAGS =      -I$(top_srcdir)/cutil -I$(top_srcdir)/ccutil     -I$(top_srcdir)/ccstruct -I$(top_srcdir)/dict     -I$(top_srcdir)/viewer


include_HEADERS =      adaptive.h adaptmatch.h baseline.h blobclass.h chartoname.h     cluster.h clusttool.h cutoffs.h extern.h extract.h featdefs.h     flexfx.h float2int.h fpoint.h fxdefs.h fxid.h hideedge.h     intfx.h intmatcher.h intproto.h kdtree.h mfdefs.h mf.h     mfoutline.h mfx.h normfeat.h normmatch.h ocrfeatures.h     outfeat.h picofeat.h protos.h sigmenu.h speckle.h xform2d.h


lib_LIBRARIES = libtesseract_classify.a
libtesseract_classify_a_SOURCES =      adaptive.cpp adaptmatch.cpp baseline.cpp blobclass.cpp     chartoname.cpp cluster.cpp clusttool.cpp cutoffs.cpp     extract.cpp featdefs.cpp flexfx.cpp float2int.cpp     fpoint.cpp fxdefs.cpp hideedge.cpp intfx.cpp intmatcher.cpp     intproto.cpp kdtree.cpp mf.cpp mfdefs.cpp mfoutline.cpp     mfx.cpp normfeat.cpp normmatch.cpp ocrfeatures.cpp     outfeat.cpp picofeat.cpp protos.cpp sigmenu.cpp speckle.cpp     xform2d.cpp

mkinstalldirs = $(SHELL) $(top_srcdir)/config/mkinstalldirs
CONFIG_HEADER = ../config_auto.h
CONFIG_CLEAN_FILES = 
LIBRARIES =  $(lib_LIBRARIES)


DEFS = -DHAVE_CONFIG_H -I. -I$(srcdir) -I..
CPPFLAGS = 
LDFLAGS = 
LIBS = -ltiff -lpthread -ljpeg -lpng -lz  -lm
libtesseract_classify_a_LIBADD = 
libtesseract_classify_a_OBJECTS =  adaptive.o adaptmatch.o baseline.o \
blobclass.o chartoname.o cluster.o clusttool.o cutoffs.o extract.o \
featdefs.o flexfx.o float2int.o fpoint.o fxdefs.o hideedge.o intfx.o \
intmatcher.o intproto.o kdtree.o mf.o mfdefs.o mfoutline.o mfx.o \
normfeat.o normmatch.o ocrfeatures.o outfeat.o picofeat.o protos.o \
sigmenu.o speckle.o xform2d.o
AR = ar
CXXFLAGS =  -g -O2
CXXCOMPILE = $(CXX) $(DEFS) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CXXFLAGS) $(CXXFLAGS)
CXXLD = $(CXX)
CXXLINK = $(CXXLD) $(AM_CXXFLAGS) $(CXXFLAGS) $(LDFLAGS) -o $@
HEADERS =  $(include_HEADERS)

DIST_COMMON =  Makefile.am Makefile.in


DISTFILES = $(DIST_COMMON) $(SOURCES) $(HEADERS) $(TEXINFOS) $(EXTRA_DIST)

TAR = tar
GZIP_ENV = --best
SOURCES = $(libtesseract_classify_a_SOURCES)
OBJECTS = $(libtesseract_classify_a_OBJECTS)

all: all-redirect
.SUFFIXES:
.SUFFIXES: .S .c .cpp .o .s
$(srcdir)/Makefile.in: # Makefile.am $(top_srcdir)/configure.ac $(ACLOCAL_M4) 
	cd $(top_srcdir) && $(AUTOMAKE) --gnu --include-deps classify/Makefile

Makefile: $(srcdir)/Makefile.in  $(top_builddir)/config.status
	cd $(top_builddir) \
	  && CONFIG_FILES=$(subdir)/$@ CONFIG_HEADERS= $(SHELL) ./config.status


mostlyclean-libLIBRARIES:

clean-libLIBRARIES:
	-test -z "$(lib_LIBRARIES)" || rm -f $(lib_LIBRARIES)

distclean-libLIBRARIES:

maintainer-clean-libLIBRARIES:

install-libLIBRARIES: $(lib_LIBRARIES)
	@$(NORMAL_INSTALL)
	$(mkinstalldirs) $(DESTDIR)$(libdir)
	@list='$(lib_LIBRARIES)'; for p in $$list; do \
	  if test -f $$p; then \
	    echo " $(INSTALL_DATA) $$p $(DESTDIR)$(libdir)/$$p"; \
	    $(INSTALL_DATA) $$p $(DESTDIR)$(libdir)/$$p; \
	  else :; fi; \
	done
	@$(POST_INSTALL)
	@list='$(lib_LIBRARIES)'; for p in $$list; do \
	  if test -f $$p; then \
	    echo " $(RANLIB) $(DESTDIR)$(libdir)/$$p"; \
	    $(RANLIB) $(DESTDIR)$(libdir)/$$p; \
	  else :; fi; \
	done

uninstall-libLIBRARIES:
	@$(NORMAL_UNINSTALL)
	list='$(lib_LIBRARIES)'; for p in $$list; do \
	  rm -f $(DESTDIR)$(libdir)/$$p; \
	done

.c.o:
	$(COMPILE) -c $<

.s.o:
	$(COMPILE) -c $<

.S.o:
	$(COMPILE) -c $<

mostlyclean-compile:
	-rm -f *.o core *.core

clean-compile:

distclean-compile:
	-rm -f *.tab.c

maintainer-clean-compile:

libtesseract_classify.a: $(libtesseract_classify_a_OBJECTS) $(libtesseract_classify_a_DEPENDENCIES)
	-rm -f libtesseract_classify.a
	$(AR) cru libtesseract_classify.a $(libtesseract_classify_a_OBJECTS) $(libtesseract_classify_a_LIBADD)
	$(RANLIB) libtesseract_classify.a
.cpp.o:
	$(CXXCOMPILE) -c $<

install-includeHEADERS: $(include_HEADERS)
	@$(NORMAL_INSTALL)
	$(mkinstalldirs) $(DESTDIR)$(includedir)
	@list='$(include_HEADERS)'; for p in $$list; do \
	  if test -f "$$p"; then d= ; else d="$(srcdir)/"; fi; \
	  echo " $(INSTALL_DATA) $$d$$p $(DESTDIR)$(includedir)/$$p"; \
	  $(INSTALL_DATA) $$d$$p $(DESTDIR)$(includedir)/$$p; \
	done

uninstall-includeHEADERS:
	@$(NORMAL_UNINSTALL)
	list='$(include_HEADERS)'; for p in $$list; do \
	  rm -f $(DESTDIR)$(includedir)/$$p; \
	done

# This directory's subdirectories are mostly independent; you can cd
# into them and run `make' without going through this Makefile.
# To change the values of `make' variables: instead of editing Makefiles,
# (1) if the variable is set in `config.status', edit `config.status'
#     (which will cause the Makefiles to be regenerated when you run `make');
# (2) otherwise, pass the desired values on the `make' command line.



all-recursive install-data-recursive install-exec-recursive \
installdirs-recursive install-recursive uninstall-recursive  \
check-recursive installcheck-recursive info-recursive dvi-recursive:
	@set fnord $(MAKEFLAGS); amf=$$2; \
	dot_seen=no; \
	target=`echo $@ | sed s/-recursive//`; \
	list='$(SUBDIRS)'; for subdir in $$list; do \
	  echo "Making $$target in $$subdir"; \
	  if test "$$subdir" = "."; then \
	    dot_seen=yes; \
	    local_target="$$target-am"; \
	  else \
	    local_target="$$target"; \
	  fi; \
	  (cd $$subdir && $(MAKE) $(AM_MAKEFLAGS) $$local_target) \
	   || case "$$amf" in *=*) exit 1;; *k*) fail=yes;; *) exit 1;; esac; \
	done; \
	if test "$$dot_seen" = "no"; then \
	  $(MAKE) $(AM_MAKEFLAGS) "$$target-am" || exit 1; \
	fi; test -z "$$fail"

mostlyclean-recursive clean-recursive distclean-recursive \
maintainer-clean-recursive:
	@set fnord $(MAKEFLAGS); amf=$$2; \
	dot_seen=no; \
	rev=''; list='$(SUBDIRS)'; for subdir in $$list; do \
	  rev="$$subdir $$rev"; \
	  test "$$subdir" != "." || dot_seen=yes; \
	done; \
	test "$$dot_seen" = "no" && rev=". $$rev"; \
	target=`echo $@ | sed s/-recursive//`; \
	for subdir in $$rev; do \
	  echo "Making $$target in $$subdir"; \
	  if test "$$subdir" = "."; then \
	    local_target="$$target-am"; \
	  else \
	    local_target="$$target"; \
	  fi; \
	  (cd $$subdir && $(MAKE) $(AM_MAKEFLAGS) $$local_target) \
	   || case "$$amf" in *=*) exit 1;; *k*) fail=yes;; *) exit 1;; esac; \
	done && test -z "$$fail"
tags-recursive:
	list='$(SUBDIRS)'; for subdir in $$list; do \
	  test "$$subdir" = . || (cd $$subdir && $(MAKE) $(AM_MAKEFLAGS) tags); \
	done

tags: TAGS

ID: $(HEADERS) $(SOURCES) $(LISP)
	list='$(SOURCES) $(HEADERS)'; \
	unique=`for i in $$list; do echo $$i; done | \
	  awk '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	here=`pwd` && cd $(srcdir) \
	  && mkid -f$$here/ID $$unique $(LISP)

TAGS: tags-recursive $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) $(LISP)
	tags=; \
	here=`pwd`; \
	list='$(SUBDIRS)'; for subdir in $$list; do \
   if test "$$subdir" = .; then :; else \
	    test -f $$subdir/TAGS && tags="$$tags -i $$here/$$subdir/TAGS"; \
   fi; \
	done; \
	list='$(SOURCES) $(HEADERS)'; \
	unique=`for i in $$list; do echo $$i; done | \
	  awk '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	test -z "$(ETAGS_ARGS)$$unique$(LISP)$$tags" \
	  || (cd $(srcdir) && etags -o $$here/TAGS $(ETAGS_ARGS) $$tags  $$unique $(LISP))

mostlyclean-tags:

clean-tags:

distclean-tags:
	-rm -f TAGS ID

maintainer-clean-tags:

distdir = $(top_builddir)/$(PACKAGE_NAME)-$(PACKAGE_VERSION)/$(subdir)

subdir = classify

distdir: $(DISTFILES)
	@for file in $(DISTFILES); do \
	  d=$(srcdir); \
	  if test -d $$d/$$file; then \
	    cp -pr $$d/$$file $(distdir)/$$file; \
	  else \
	    test -f $(distdir)/$$file \
	    || ln $$d/$$file $(distdir)/$$file 2> /dev/null \
	    || cp -p $$d/$$file $(distdir)/$$file || :; \
	  fi; \
	done
	for subdir in $(SUBDIRS); do \
	  if test "$$subdir" = .; then :; else \
	    test -d $(distdir)/$$subdir \
	    || mkdir $(distdir)/$$subdir \
	    || exit 1; \
	    chmod 777 $(distdir)/$$subdir; \
	    (cd $$subdir && $(MAKE) $(AM_MAKEFLAGS) top_distdir=../$(top_distdir) distdir=../$(distdir)/$$subdir distdir) \
	      || exit 1; \
	  fi; \
	done
adaptive.o: adaptive.cpp adaptive.h ../cutil/oldlist.h ../cutil/cutil.h \
	../cutil/general.h ../ccutil/host.h ../ccutil/platform.h \
	intproto.h ../dict/matchdefs.h ../cutil/general.h \
	../ccutil/unichar.h protos.h ../cutil/bitvec.h ../cutil/cutil.h \
	../ccutil/unichar.h ../cutil/callcpp.h ../ccutil/varable.h \
	../ccutil/clst.h ../ccutil/host.h ../ccutil/serialis.h \
	../ccutil/memry.h ../ccutil/errcode.h ../ccutil/fileerr.h \
	../ccutil/lsterr.h ../ccutil/strngs.h ../ccutil/unichar.h \
	../ccutil/unicharset.h ../ccutil/unichar.h \
	../ccutil/unicharmap.h ../cutil/emalloc.h ../cutil/callcpp.h \
	../cutil/freelist.h ../cutil/globals.h ../ccutil/tessclas.h \
	../cutil/const.h ../ccutil/unicharset.h ../ccutil/strngs.h
adaptmatch.o: adaptmatch.cpp adaptmatch.h ../cutil/oldlist.h \
	../cutil/cutil.h ../cutil/general.h ../ccutil/host.h \
	../ccutil/platform.h ../ccutil/tessclas.h fxdefs.h \
	../cutil/general.h ../dict/matchdefs.h ../cutil/general.h \
	../ccutil/unichar.h adaptive.h intproto.h protos.h \
	../cutil/bitvec.h ../cutil/cutil.h ../ccutil/unichar.h \
	../cutil/callcpp.h ../ccutil/varable.h ../ccutil/clst.h \
	../ccutil/host.h ../ccutil/serialis.h ../ccutil/memry.h \
	../ccutil/errcode.h ../ccutil/fileerr.h ../ccutil/lsterr.h \
	../ccutil/strngs.h ../ccutil/unichar.h ../ccutil/unicharset.h \
	../ccutil/unichar.h ../ccutil/unicharmap.h ocrfeatures.h \
	../cutil/funcdefs.h ../ccstruct/ratngs.h ../ccutil/clst.h \
	../ccstruct/werd.h ../ccutil/varable.h ../ccutil/bits16.h \
	../ccutil/strngs.h ../ccstruct/blckerr.h ../ccutil/errcode.h \
	../ccstruct/stepblob.h ../ccstruct/coutln.h \
	../ccstruct/crakedge.h ../ccstruct/points.h ../ccutil/elst.h \
	../ccstruct/ipoints.h ../ccstruct/mod128.h ../ccstruct/rect.h \
	../ccutil/ndminx.h ../ccutil/tprintf.h ../ccutil/varable.h \
	../viewer/scrollview.h ../ccstruct/polyblob.h \
	../ccstruct/poutline.h ../ccstruct/polyvert.h ../ccutil/elst2.h \
	../ccstruct/normalis.h ../ccstruct/ocrrow.h \
	../ccstruct/quspline.h ../ccstruct/quadratc.h \
	../ccutil/serialis.h ../ccutil/memry.h ../ccutil/notdll.h \
	../ccutil/unichar.h normfeat.h mfoutline.h fpoint.h baseline.h \
	picofeat.h float2int.h intmatcher.h ../cutil/debug.h \
	../cutil/variables.h ../cutil/oldlist.h ../cutil/callcpp.h \
	cutoffs.h outfeat.h ../cutil/emalloc.h intfx.h hideedge.h \
	../dict/permnum.h ../dict/choicearr.h ../cutil/tessarray.h \
	../dict/choices.h ../cutil/oldlist.h speckle.h \
	../dict/choices.h ../cutil/efio.h normmatch.h ../dict/stopper.h \
	../dict/states.h ../dict/permute.h ../dict/context.h \
	../ccutil/ndminx.h ../cutil/const.h ../cutil/globals.h \
	../ccutil/tessclas.h ../cutil/const.h ../ccutil/unicharset.h \
	../ccutil/strngs.h ../ccstruct/werd.h ../cutil/tordvars.h
baseline.o: baseline.cpp baseline.h ../cutil/general.h ../ccutil/host.h \
	../ccutil/platform.h ../ccutil/tessclas.h ../cutil/debug.h \
	../cutil/variables.h ../cutil/cutil.h ../cutil/general.h \
	../cutil/oldlist.h ../cutil/callcpp.h ../ccutil/varable.h \
	../ccutil/clst.h ../ccutil/host.h ../ccutil/serialis.h \
	../ccutil/memry.h ../ccutil/errcode.h ../ccutil/fileerr.h \
	../ccutil/lsterr.h ../ccutil/strngs.h ../ccutil/unichar.h \
	hideedge.h
blobclass.o: blobclass.cpp blobclass.h ../cutil/oldlist.h \
	../cutil/cutil.h ../cutil/general.h ../ccutil/host.h \
	../ccutil/platform.h ../ccutil/tessclas.h fxdefs.h \
	../cutil/general.h ../cutil/variables.h ../cutil/oldlist.h \
	extract.h featdefs.h ocrfeatures.h ../cutil/funcdefs.h \
	../cutil/efio.h ../cutil/callcpp.h ../ccutil/varable.h \
	../ccutil/clst.h ../ccutil/host.h ../ccutil/serialis.h \
	../ccutil/memry.h ../ccutil/errcode.h ../ccutil/fileerr.h \
	../ccutil/lsterr.h ../ccutil/strngs.h ../ccutil/unichar.h \
	chartoname.h
chartoname.o: chartoname.cpp
cluster.o: cluster.cpp ../cutil/oldheap.h ../cutil/general.h \
	../ccutil/host.h ../ccutil/platform.h ../cutil/cutil.h \
	../cutil/const.h cluster.h kdtree.h ../cutil/general.h \
	../cutil/cutil.h ocrfeatures.h ../cutil/funcdefs.h \
	../ccutil/tessclas.h fxdefs.h ../cutil/oldlist.h \
	../cutil/emalloc.h ../cutil/callcpp.h ../ccutil/varable.h \
	../ccutil/clst.h ../ccutil/host.h ../ccutil/serialis.h \
	../ccutil/memry.h ../ccutil/errcode.h ../ccutil/fileerr.h \
	../ccutil/lsterr.h ../ccutil/strngs.h ../ccutil/unichar.h \
	../ccutil/tprintf.h ../ccutil/varable.h ../cutil/danerror.h \
	../cutil/freelist.h
clusttool.o: clusttool.cpp clusttool.h ../ccutil/host.h \
	../ccutil/platform.h cluster.h kdtree.h ../cutil/general.h \
	../ccutil/host.h ../cutil/cutil.h ../cutil/general.h \
	ocrfeatures.h ../cutil/funcdefs.h ../ccutil/tessclas.h fxdefs.h \
	../cutil/oldlist.h ../cutil/cutil.h ../cutil/const.h \
	../cutil/danerror.h ../cutil/emalloc.h ../cutil/callcpp.h \
	../ccutil/varable.h ../ccutil/clst.h ../ccutil/host.h \
	../ccutil/serialis.h ../ccutil/memry.h ../ccutil/errcode.h \
	../ccutil/fileerr.h ../ccutil/lsterr.h ../ccutil/strngs.h \
	../ccutil/unichar.h ../ccutil/scanutils.h
cutoffs.o: cutoffs.cpp cutoffs.h ../dict/matchdefs.h ../cutil/general.h \
	../ccutil/host.h ../ccutil/platform.h ../ccutil/unichar.h \
	../cutil/efio.h ../ccutil/scanutils.h ../ccutil/serialis.h \
	../ccutil/memry.h ../ccutil/host.h ../ccutil/errcode.h \
	../ccutil/fileerr.h ../ccutil/unichar.h ../cutil/globals.h \
	../ccutil/tessclas.h ../cutil/const.h ../ccutil/unicharset.h \
	../ccutil/unichar.h ../ccutil/unicharmap.h ../ccutil/strngs.h \
	../ccutil/serialis.h
extract.o: extract.cpp extract.h fxdefs.h ../ccutil/tessclas.h \
	../cutil/general.h ../ccutil/host.h ../ccutil/platform.h \
	featdefs.h ocrfeatures.h ../cutil/funcdefs.h ../cutil/general.h \
	../cutil/variables.h ../cutil/cutil.h ../cutil/oldlist.h \
	flexfx.h ../cutil/danerror.h
featdefs.o: featdefs.cpp featdefs.h ocrfeatures.h ../cutil/funcdefs.h \
	../cutil/general.h ../ccutil/host.h ../ccutil/platform.h \
	../ccutil/tessclas.h fxdefs.h ../cutil/general.h \
	../cutil/emalloc.h ../cutil/callcpp.h ../ccutil/varable.h \
	../ccutil/clst.h ../ccutil/host.h ../ccutil/serialis.h \
	../ccutil/memry.h ../ccutil/errcode.h ../ccutil/fileerr.h \
	../ccutil/lsterr.h ../ccutil/strngs.h ../ccutil/unichar.h \
	../cutil/danerror.h ../ccutil/scanutils.h ../cutil/variables.h \
	../cutil/cutil.h ../cutil/oldlist.h sigmenu.h ../cutil/cutil.h
flexfx.o: flexfx.cpp flexfx.h fxdefs.h ../ccutil/tessclas.h \
	../cutil/general.h ../ccutil/host.h ../ccutil/platform.h \
	featdefs.h ocrfeatures.h ../cutil/funcdefs.h ../cutil/general.h \
	../cutil/variables.h ../cutil/cutil.h ../cutil/oldlist.h \
	sigmenu.h ../cutil/cutil.h ../cutil/emalloc.h \
	../cutil/callcpp.h ../ccutil/varable.h ../ccutil/clst.h \
	../ccutil/host.h ../ccutil/serialis.h ../ccutil/memry.h \
	../ccutil/errcode.h ../ccutil/fileerr.h ../ccutil/lsterr.h \
	../ccutil/strngs.h ../ccutil/unichar.h
float2int.o: float2int.cpp float2int.h intmatcher.h ../cutil/debug.h \
	../cutil/variables.h ../cutil/cutil.h ../cutil/general.h \
	../ccutil/host.h ../ccutil/platform.h ../cutil/oldlist.h \
	../cutil/callcpp.h ../ccutil/varable.h ../ccutil/clst.h \
	../ccutil/host.h ../ccutil/serialis.h ../ccutil/memry.h \
	../ccutil/errcode.h ../ccutil/fileerr.h ../ccutil/lsterr.h \
	../ccutil/strngs.h ../ccutil/unichar.h intproto.h \
	../dict/matchdefs.h ../cutil/general.h ../ccutil/unichar.h \
	protos.h ../cutil/bitvec.h ../cutil/cutil.h ../ccutil/unichar.h \
	../cutil/callcpp.h ../ccutil/unicharset.h ../ccutil/unichar.h \
	../ccutil/unicharmap.h cutoffs.h ocrfeatures.h \
	../cutil/funcdefs.h ../ccutil/tessclas.h fxdefs.h \
	../cutil/general.h normmatch.h mfoutline.h ../cutil/oldlist.h \
	fpoint.h baseline.h picofeat.h
fpoint.o: fpoint.cpp ../cutil/const.h fpoint.h ../cutil/general.h \
	../ccutil/host.h ../ccutil/platform.h
fxdefs.o: fxdefs.cpp fxdefs.h ../ccutil/tessclas.h ../cutil/general.h \
	../ccutil/host.h ../ccutil/platform.h featdefs.h ocrfeatures.h \
	../cutil/funcdefs.h ../cutil/general.h mf.h outfeat.h fpoint.h \
	mfoutline.h ../cutil/oldlist.h ../cutil/cutil.h baseline.h \
	picofeat.h normfeat.h
hideedge.o: hideedge.cpp hideedge.h ../cutil/general.h ../ccutil/host.h \
	../ccutil/platform.h ../cutil/debug.h ../cutil/variables.h \
	../cutil/cutil.h ../cutil/general.h ../cutil/oldlist.h \
	../cutil/callcpp.h ../ccutil/varable.h ../ccutil/clst.h \
	../ccutil/host.h ../ccutil/serialis.h ../ccutil/memry.h \
	../ccutil/errcode.h ../ccutil/fileerr.h ../ccutil/lsterr.h \
	../ccutil/strngs.h ../ccutil/unichar.h
intfx.o: intfx.cpp intfx.h ../ccutil/tessclas.h hideedge.h \
	../cutil/general.h ../ccutil/host.h ../ccutil/platform.h \
	intproto.h ../dict/matchdefs.h ../cutil/general.h \
	../ccutil/unichar.h protos.h ../cutil/bitvec.h ../cutil/cutil.h \
	../cutil/general.h ../ccutil/unichar.h ../cutil/callcpp.h \
	../ccutil/varable.h ../ccutil/clst.h ../ccutil/host.h \
	../ccutil/serialis.h ../ccutil/memry.h ../ccutil/errcode.h \
	../ccutil/fileerr.h ../ccutil/lsterr.h ../ccutil/strngs.h \
	../ccutil/unichar.h ../ccutil/unicharset.h ../ccutil/unichar.h \
	../ccutil/unicharmap.h intmatcher.h ../cutil/debug.h \
	../cutil/variables.h ../cutil/cutil.h ../cutil/oldlist.h \
	../cutil/callcpp.h cutoffs.h ../cutil/const.h
intmatcher.o: intmatcher.cpp intmatcher.h ../cutil/debug.h \
	../cutil/variables.h ../cutil/cutil.h ../cutil/general.h \
	../ccutil/host.h ../ccutil/platform.h ../cutil/oldlist.h \
	../cutil/callcpp.h ../ccutil/varable.h ../ccutil/clst.h \
	../ccutil/host.h ../ccutil/serialis.h ../ccutil/memry.h \
	../ccutil/errcode.h ../ccutil/fileerr.h ../ccutil/lsterr.h \
	../ccutil/strngs.h ../ccutil/unichar.h intproto.h \
	../dict/matchdefs.h ../cutil/general.h ../ccutil/unichar.h \
	protos.h ../cutil/bitvec.h ../cutil/cutil.h ../ccutil/unichar.h \
	../cutil/callcpp.h ../ccutil/unicharset.h ../ccutil/unichar.h \
	../ccutil/unicharmap.h cutoffs.h ../cutil/tordvars.h \
	../cutil/globals.h ../ccutil/tessclas.h ../cutil/const.h \
	../ccutil/unicharset.h ../ccutil/strngs.h
intproto.o: intproto.cpp intproto.h ../dict/matchdefs.h \
	../cutil/general.h ../ccutil/host.h ../ccutil/platform.h \
	../ccutil/unichar.h protos.h ../cutil/bitvec.h ../cutil/cutil.h \
	../cutil/general.h ../ccutil/unichar.h ../cutil/callcpp.h \
	../ccutil/varable.h ../ccutil/clst.h ../ccutil/host.h \
	../ccutil/serialis.h ../ccutil/memry.h ../ccutil/errcode.h \
	../ccutil/fileerr.h ../ccutil/lsterr.h ../ccutil/strngs.h \
	../ccutil/unichar.h ../ccutil/unicharset.h ../ccutil/unichar.h \
	../ccutil/unicharmap.h picofeat.h ocrfeatures.h \
	../cutil/funcdefs.h ../ccutil/tessclas.h fxdefs.h \
	../cutil/general.h ../cutil/debug.h ../cutil/variables.h \
	../cutil/cutil.h ../cutil/oldlist.h ../cutil/callcpp.h \
	mfoutline.h ../cutil/oldlist.h fpoint.h baseline.h \
	../cutil/emalloc.h ../cutil/const.h ../ccutil/ndminx.h \
	adaptmatch.h adaptive.h ../ccstruct/ratngs.h ../ccutil/clst.h \
	../ccstruct/werd.h ../ccutil/varable.h ../ccutil/bits16.h \
	../ccutil/strngs.h ../ccstruct/blckerr.h ../ccutil/errcode.h \
	../ccstruct/stepblob.h ../ccstruct/coutln.h \
	../ccstruct/crakedge.h ../ccstruct/points.h ../ccutil/elst.h \
	../ccstruct/ipoints.h ../ccstruct/mod128.h ../ccstruct/rect.h \
	../ccutil/ndminx.h ../ccutil/tprintf.h ../ccutil/varable.h \
	../viewer/scrollview.h ../ccstruct/polyblob.h \
	../ccstruct/poutline.h ../ccstruct/polyvert.h ../ccutil/elst2.h \
	../ccstruct/normalis.h ../ccstruct/ocrrow.h \
	../ccstruct/quspline.h ../ccstruct/quadratc.h \
	../ccutil/serialis.h ../ccutil/memry.h ../ccutil/notdll.h \
	../ccutil/unichar.h ../cutil/globals.h ../ccutil/tessclas.h \
	../cutil/const.h ../ccutil/unicharset.h ../ccutil/strngs.h
kdtree.o: kdtree.cpp kdtree.h ../cutil/general.h ../ccutil/host.h \
	../ccutil/platform.h ../cutil/cutil.h ../cutil/general.h \
	ocrfeatures.h ../cutil/funcdefs.h ../ccutil/tessclas.h fxdefs.h \
	../cutil/const.h ../cutil/emalloc.h ../cutil/callcpp.h \
	../ccutil/varable.h ../ccutil/clst.h ../ccutil/host.h \
	../ccutil/serialis.h ../ccutil/memry.h ../ccutil/errcode.h \
	../ccutil/fileerr.h ../ccutil/lsterr.h ../ccutil/strngs.h \
	../ccutil/unichar.h ../cutil/freelist.h
mf.o: mf.cpp mfdefs.h ../cutil/oldlist.h ../cutil/cutil.h \
	../cutil/general.h ../ccutil/host.h ../ccutil/platform.h \
	../dict/matchdefs.h ../cutil/general.h ../ccutil/unichar.h \
	xform2d.h fpoint.h ../cutil/general.h ../cutil/variables.h \
	../cutil/oldlist.h mf.h ocrfeatures.h ../cutil/funcdefs.h \
	../ccutil/tessclas.h fxdefs.h mfx.h
mfdefs.o: mfdefs.cpp mfdefs.h ../cutil/oldlist.h ../cutil/cutil.h \
	../cutil/general.h ../ccutil/host.h ../ccutil/platform.h \
	../dict/matchdefs.h ../cutil/general.h ../ccutil/unichar.h \
	xform2d.h fpoint.h ../cutil/general.h ../cutil/emalloc.h \
	../cutil/callcpp.h ../ccutil/varable.h ../ccutil/clst.h \
	../ccutil/host.h ../ccutil/serialis.h ../ccutil/memry.h \
	../ccutil/errcode.h ../ccutil/fileerr.h ../ccutil/lsterr.h \
	../ccutil/strngs.h ../ccutil/unichar.h
mfoutline.o: mfoutline.cpp clusttool.h ../ccutil/host.h \
	../ccutil/platform.h cluster.h kdtree.h ../cutil/general.h \
	../ccutil/host.h ../cutil/cutil.h ../cutil/general.h \
	ocrfeatures.h ../cutil/funcdefs.h ../ccutil/tessclas.h fxdefs.h \
	../cutil/oldlist.h ../cutil/cutil.h ../cutil/emalloc.h \
	../cutil/callcpp.h ../ccutil/varable.h ../ccutil/clst.h \
	../ccutil/host.h ../ccutil/serialis.h ../ccutil/memry.h \
	../ccutil/errcode.h ../ccutil/fileerr.h ../ccutil/lsterr.h \
	../ccutil/strngs.h ../ccutil/unichar.h mfoutline.h fpoint.h \
	baseline.h ../cutil/debug.h ../cutil/variables.h \
	../cutil/oldlist.h hideedge.h ../ccstruct/blobs.h \
	../ccstruct/vecfuncs.h ../ccutil/tessclas.h ../cutil/const.h \
	mfx.h
mfx.o: mfx.cpp mfdefs.h ../cutil/oldlist.h ../cutil/cutil.h \
	../cutil/general.h ../ccutil/host.h ../ccutil/platform.h \
	../dict/matchdefs.h ../cutil/general.h ../ccutil/unichar.h \
	xform2d.h fpoint.h ../cutil/general.h ../cutil/variables.h \
	../cutil/oldlist.h sigmenu.h ../cutil/cutil.h mfoutline.h \
	fxdefs.h ../ccutil/tessclas.h baseline.h clusttool.h \
	../ccutil/host.h cluster.h kdtree.h ocrfeatures.h \
	../cutil/funcdefs.h ../cutil/const.h intfx.h hideedge.h \
	intproto.h protos.h ../cutil/bitvec.h ../ccutil/unichar.h \
	../cutil/callcpp.h ../ccutil/varable.h ../ccutil/clst.h \
	../ccutil/host.h ../ccutil/serialis.h ../ccutil/memry.h \
	../ccutil/errcode.h ../ccutil/fileerr.h ../ccutil/lsterr.h \
	../ccutil/strngs.h ../ccutil/unichar.h ../ccutil/unicharset.h \
	../ccutil/unichar.h ../ccutil/unicharmap.h
normfeat.o: normfeat.cpp normfeat.h ocrfeatures.h ../cutil/funcdefs.h \
	../cutil/general.h ../ccutil/host.h ../ccutil/platform.h \
	../ccutil/tessclas.h fxdefs.h ../cutil/general.h mfoutline.h \
	../cutil/oldlist.h ../cutil/cutil.h fpoint.h baseline.h intfx.h \
	hideedge.h intproto.h ../dict/matchdefs.h ../cutil/general.h \
	../ccutil/unichar.h protos.h ../cutil/bitvec.h ../cutil/cutil.h \
	../ccutil/unichar.h ../cutil/callcpp.h ../ccutil/varable.h \
	../ccutil/clst.h ../ccutil/host.h ../ccutil/serialis.h \
	../ccutil/memry.h ../ccutil/errcode.h ../ccutil/fileerr.h \
	../ccutil/lsterr.h ../ccutil/strngs.h ../ccutil/unichar.h \
	../ccutil/unicharset.h ../ccutil/unichar.h \
	../ccutil/unicharmap.h ../cutil/efio.h
normmatch.o: normmatch.cpp normmatch.h ../dict/matchdefs.h \
	../cutil/general.h ../ccutil/host.h ../ccutil/platform.h \
	../ccutil/unichar.h ocrfeatures.h ../cutil/funcdefs.h \
	../cutil/general.h ../ccutil/tessclas.h fxdefs.h \
	../cutil/general.h clusttool.h ../ccutil/host.h cluster.h \
	kdtree.h ../cutil/cutil.h ../cutil/oldlist.h ../cutil/cutil.h \
	normfeat.h ../cutil/debug.h ../cutil/variables.h \
	../cutil/oldlist.h ../cutil/callcpp.h ../ccutil/varable.h \
	../ccutil/clst.h ../ccutil/host.h ../ccutil/serialis.h \
	../ccutil/memry.h ../ccutil/errcode.h ../ccutil/fileerr.h \
	../ccutil/lsterr.h ../ccutil/strngs.h ../ccutil/unichar.h \
	../cutil/const.h ../cutil/efio.h ../cutil/emalloc.h \
	../cutil/globals.h ../ccutil/tessclas.h ../cutil/const.h \
	../ccutil/unicharset.h ../ccutil/unichar.h \
	../ccutil/unicharmap.h ../ccutil/strngs.h ../ccutil/scanutils.h
ocrfeatures.o: ocrfeatures.cpp ocrfeatures.h ../cutil/funcdefs.h \
	../cutil/general.h ../ccutil/host.h ../ccutil/platform.h \
	../ccutil/tessclas.h fxdefs.h ../cutil/general.h \
	../cutil/emalloc.h ../cutil/callcpp.h ../ccutil/varable.h \
	../ccutil/clst.h ../ccutil/host.h ../ccutil/serialis.h \
	../ccutil/memry.h ../ccutil/errcode.h ../ccutil/fileerr.h \
	../ccutil/lsterr.h ../ccutil/strngs.h ../ccutil/unichar.h \
	../cutil/callcpp.h ../cutil/danerror.h ../cutil/freelist.h \
	../ccutil/scanutils.h
outfeat.o: outfeat.cpp outfeat.h ocrfeatures.h ../cutil/funcdefs.h \
	../cutil/general.h ../ccutil/host.h ../ccutil/platform.h \
	../ccutil/tessclas.h fxdefs.h ../cutil/general.h fpoint.h \
	mfoutline.h ../cutil/oldlist.h ../cutil/cutil.h baseline.h \
	../cutil/variables.h ../cutil/oldlist.h sigmenu.h \
	../cutil/cutil.h ../cutil/efio.h
picofeat.o: picofeat.cpp picofeat.h ocrfeatures.h ../cutil/funcdefs.h \
	../cutil/general.h ../ccutil/host.h ../ccutil/platform.h \
	../ccutil/tessclas.h fxdefs.h ../cutil/general.h mfoutline.h \
	../cutil/oldlist.h ../cutil/cutil.h fpoint.h baseline.h \
	../cutil/variables.h ../cutil/oldlist.h sigmenu.h \
	../cutil/cutil.h hideedge.h ../cutil/efio.h
protos.o: protos.cpp protos.h ../cutil/bitvec.h ../cutil/cutil.h \
	../cutil/general.h ../ccutil/host.h ../ccutil/platform.h \
	../ccutil/unichar.h ../cutil/debug.h ../cutil/variables.h \
	../cutil/cutil.h ../cutil/oldlist.h ../cutil/callcpp.h \
	../ccutil/varable.h ../ccutil/clst.h ../ccutil/host.h \
	../ccutil/serialis.h ../ccutil/memry.h ../ccutil/errcode.h \
	../ccutil/fileerr.h ../ccutil/lsterr.h ../ccutil/strngs.h \
	../ccutil/unichar.h ../cutil/const.h ../cutil/emalloc.h \
	../cutil/freelist.h ../cutil/callcpp.h ../ccutil/tprintf.h \
	../ccutil/varable.h adaptmatch.h ../cutil/oldlist.h \
	../ccutil/tessclas.h fxdefs.h ../cutil/general.h \
	../dict/matchdefs.h ../cutil/general.h ../ccutil/unichar.h \
	adaptive.h intproto.h ../ccutil/unicharset.h \
	../ccutil/unichar.h ../ccutil/unicharmap.h ocrfeatures.h \
	../cutil/funcdefs.h ../ccstruct/ratngs.h ../ccutil/clst.h \
	../ccstruct/werd.h ../ccutil/varable.h ../ccutil/bits16.h \
	../ccutil/strngs.h ../ccstruct/blckerr.h ../ccutil/errcode.h \
	../ccstruct/stepblob.h ../ccstruct/coutln.h \
	../ccstruct/crakedge.h ../ccstruct/points.h ../ccutil/elst.h \
	../ccstruct/ipoints.h ../ccstruct/mod128.h ../ccstruct/rect.h \
	../ccutil/ndminx.h ../ccutil/tprintf.h ../viewer/scrollview.h \
	../ccstruct/polyblob.h ../ccstruct/poutline.h \
	../ccstruct/polyvert.h ../ccutil/elst2.h ../ccstruct/normalis.h \
	../ccstruct/ocrrow.h ../ccstruct/quspline.h \
	../ccstruct/quadratc.h ../ccutil/serialis.h ../ccutil/memry.h \
	../ccutil/notdll.h ../ccutil/unichar.h ../ccutil/scanutils.h \
	../cutil/globals.h ../ccutil/tessclas.h ../cutil/const.h \
	../ccutil/unicharset.h ../ccutil/strngs.h
sigmenu.o: sigmenu.cpp sigmenu.h ../cutil/cutil.h ../cutil/general.h \
	../ccutil/host.h ../ccutil/platform.h ../cutil/oldlist.h \
	../cutil/cutil.h ../cutil/emalloc.h ../cutil/callcpp.h \
	../ccutil/varable.h ../ccutil/clst.h ../ccutil/host.h \
	../ccutil/serialis.h ../ccutil/memry.h ../ccutil/errcode.h \
	../ccutil/fileerr.h ../ccutil/lsterr.h ../ccutil/strngs.h \
	../ccutil/unichar.h ../ccutil/secname.h
speckle.o: speckle.cpp speckle.h baseline.h ../cutil/general.h \
	../ccutil/host.h ../ccutil/platform.h ../ccutil/tessclas.h \
	../dict/choices.h ../cutil/oldlist.h ../cutil/cutil.h \
	../cutil/general.h ../cutil/debug.h ../cutil/variables.h \
	../cutil/oldlist.h ../cutil/callcpp.h ../ccutil/varable.h \
	../ccutil/clst.h ../ccutil/host.h ../ccutil/serialis.h \
	../ccutil/memry.h ../ccutil/errcode.h ../ccutil/fileerr.h \
	../ccutil/lsterr.h ../ccutil/strngs.h ../ccutil/unichar.h \
	../ccstruct/blobs.h ../ccstruct/vecfuncs.h ../ccutil/tessclas.h
xform2d.o: xform2d.cpp xform2d.h fpoint.h ../cutil/general.h \
	../ccutil/host.h ../ccutil/platform.h

info-am:
info: info-recursive
dvi-am:
dvi: dvi-recursive
check-am: all-am
check: check-recursive
installcheck-am:
installcheck: installcheck-recursive
install-exec-am: install-libLIBRARIES
install-exec: install-exec-recursive

install-data-am: install-includeHEADERS
install-data: install-data-recursive

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am
install: install-recursive
uninstall-am: uninstall-libLIBRARIES uninstall-includeHEADERS
uninstall: uninstall-recursive
all-am: Makefile $(LIBRARIES) $(HEADERS)
all-redirect: all-recursive
install-strip:
	$(MAKE) $(AM_MAKEFLAGS) AM_INSTALL_PROGRAM_FLAGS=-s install
installdirs: installdirs-recursive
installdirs-am:
	$(mkinstalldirs)  $(DESTDIR)$(libdir) $(DESTDIR)$(includedir)


mostlyclean-generic:

clean-generic:

distclean-generic:
	-rm -f Makefile $(CONFIG_CLEAN_FILES)
	-rm -f config.cache config.log stamp-h stamp-h[0-9]*

maintainer-clean-generic:
mostlyclean-am:  mostlyclean-libLIBRARIES mostlyclean-compile \
		mostlyclean-tags mostlyclean-generic

mostlyclean: mostlyclean-recursive

clean-am:  clean-libLIBRARIES clean-compile clean-tags clean-generic \
		mostlyclean-am

clean: clean-recursive

distclean-am:  distclean-libLIBRARIES distclean-compile distclean-tags \
		distclean-generic clean-am

distclean: distclean-recursive

maintainer-clean-am:  maintainer-clean-libLIBRARIES \
		maintainer-clean-compile maintainer-clean-tags \
		maintainer-clean-generic distclean-am
	@echo "This command is intended for maintainers to use;"
	@echo "it deletes files that may require special tools to rebuild."

maintainer-clean: maintainer-clean-recursive

.PHONY: mostlyclean-libLIBRARIES distclean-libLIBRARIES \
clean-libLIBRARIES maintainer-clean-libLIBRARIES uninstall-libLIBRARIES \
install-libLIBRARIES mostlyclean-compile distclean-compile \
clean-compile maintainer-clean-compile uninstall-includeHEADERS \
install-includeHEADERS install-data-recursive uninstall-data-recursive \
install-exec-recursive uninstall-exec-recursive installdirs-recursive \
uninstalldirs-recursive all-recursive check-recursive \
installcheck-recursive info-recursive dvi-recursive \
mostlyclean-recursive distclean-recursive clean-recursive \
maintainer-clean-recursive tags tags-recursive mostlyclean-tags \
distclean-tags clean-tags maintainer-clean-tags distdir info-am info \
dvi-am dvi check check-am installcheck-am installcheck install-exec-am \
install-exec install-data-am install-data install-am install \
uninstall-am uninstall all-redirect all-am all installdirs-am \
installdirs mostlyclean-generic distclean-generic clean-generic \
maintainer-clean-generic clean mostlyclean distclean maintainer-clean


# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
