# Makefile.in generated by automake 1.12.3 from Makefile.am.
# hl/tools/gif2h5/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994-2012 Free Software Foundation, Inc.

# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.



#
# Copyright by The HDF Group.
# Copyright by the Board of Trustees of the University of Illinois.
# All rights reserved.
#
# This file is part of HDF5.  The full HDF5 copyright notice, including
# terms governing use, modification, and redistribution, is contained in
# the files COPYING and Copyright.html.  COPYING can be found at the root
# of the source code distribution tree; Copyright.html can be found at the
# root level of an installed copy of the electronic HDF5 document set and
# is linked from the top-level documents page.  It can also be found at
# http://hdfgroup.org/HDF5/doc/Copyright.html.  If you do not have
# access to either file, you may request a copy from help@hdfgroup.org.
#
# HDF5 Library Makefile(.in)
#


am__make_dryrun = \
  { \
    am__dry=no; \
    case $$MAKEFLAGS in \
      *\\[\ \	]*) \
        echo 'am--echo: ; @echo "AM"  OK' | $(MAKE) -f - 2>/dev/null \
          | grep '^AM OK$$' >/dev/null || am__dry=yes;; \
      *) \
        for am__flg in $$MAKEFLAGS; do \
          case $$am__flg in \
            *=*|--*) ;; \
            *n*) am__dry=yes; break;; \
          esac; \
        done;; \
    esac; \
    test $$am__dry = yes; \
  }
pkgdatadir = $(datadir)/hdf5
pkgincludedir = $(includedir)/hdf5
pkglibdir = $(libdir)/hdf5
pkglibexecdir = $(libexecdir)/hdf5
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_triplet = x86_64-unknown-linux-gnu
host_triplet = x86_64-unknown-linux-gnu
DIST_COMMON = $(srcdir)/Makefile.am $(srcdir)/Makefile.in \
	$(srcdir)/h52giftest.sh.in $(top_srcdir)/bin/depcomp \
	$(top_srcdir)/bin/mkinstalldirs \
	$(top_srcdir)/config/commence.am \
	$(top_srcdir)/config/conclude.am
bin_PROGRAMS = gif2h5$(EXEEXT) h52gif$(EXEEXT)
noinst_PROGRAMS = h52gifgentst$(EXEEXT)
TESTS = $(TEST_SCRIPT)
subdir = hl/tools/gif2h5
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
mkinstalldirs = $(SHELL) $(top_srcdir)/bin/mkinstalldirs
CONFIG_HEADER = $(top_builddir)/src/H5config.h
CONFIG_CLEAN_FILES = h52giftest.sh
CONFIG_CLEAN_VPATH_FILES =
am__installdirs = "$(DESTDIR)$(bindir)"
PROGRAMS = $(bin_PROGRAMS) $(noinst_PROGRAMS)
am_gif2h5_OBJECTS = gif2hdf.$(OBJEXT) gif2mem.$(OBJEXT) \
	decompress.$(OBJEXT) gifread.$(OBJEXT) writehdf.$(OBJEXT)
gif2h5_OBJECTS = $(am_gif2h5_OBJECTS)
gif2h5_LDADD = $(LDADD)
gif2h5_DEPENDENCIES = $(LIBH5_HL) $(LIBH5TOOLS) $(LIBHDF5)
AM_V_lt = $(am__v_lt_$(V))
am__v_lt_ = $(am__v_lt_$(AM_DEFAULT_VERBOSITY))
am__v_lt_0 = --silent
am__v_lt_1 = 
gif2h5_LINK = $(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=link $(CCLD) $(AM_CFLAGS) $(CFLAGS) \
	$(gif2h5_LDFLAGS) $(LDFLAGS) -o $@
am_h52gif_OBJECTS = hdf2gif.$(OBJEXT) hdfgifwr.$(OBJEXT)
h52gif_OBJECTS = $(am_h52gif_OBJECTS)
h52gif_LDADD = $(LDADD)
h52gif_DEPENDENCIES = $(LIBH5_HL) $(LIBH5TOOLS) $(LIBHDF5)
h52gif_LINK = $(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=link $(CCLD) $(AM_CFLAGS) $(CFLAGS) \
	$(h52gif_LDFLAGS) $(LDFLAGS) -o $@
am_h52gifgentst_OBJECTS = h52gifgentst.$(OBJEXT)
h52gifgentst_OBJECTS = $(am_h52gifgentst_OBJECTS)
h52gifgentst_LDADD = $(LDADD)
h52gifgentst_DEPENDENCIES = $(LIBH5_HL) $(LIBH5TOOLS) $(LIBHDF5)
AM_V_P = $(am__v_P_$(V))
am__v_P_ = $(am__v_P_$(AM_DEFAULT_VERBOSITY))
am__v_P_0 = false
am__v_P_1 = :
AM_V_GEN = $(am__v_GEN_$(V))
am__v_GEN_ = $(am__v_GEN_$(AM_DEFAULT_VERBOSITY))
am__v_GEN_0 = @echo "  GEN     " $@;
am__v_GEN_1 = 
AM_V_at = $(am__v_at_$(V))
am__v_at_ = $(am__v_at_$(AM_DEFAULT_VERBOSITY))
am__v_at_0 = @
am__v_at_1 = 
DEFAULT_INCLUDES = -I. -I$(top_builddir)/src
depcomp = $(SHELL) $(top_srcdir)/bin/depcomp
am__depfiles_maybe = depfiles
am__mv = mv -f
COMPILE = $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) \
	$(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
LTCOMPILE = $(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) \
	$(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) \
	$(AM_CFLAGS) $(CFLAGS)
AM_V_CC = $(am__v_CC_$(V))
am__v_CC_ = $(am__v_CC_$(AM_DEFAULT_VERBOSITY))
am__v_CC_0 = @echo "  CC      " $@;
am__v_CC_1 = 
CCLD = $(CC)
LINK = $(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=link $(CCLD) $(AM_CFLAGS) $(CFLAGS) \
	$(AM_LDFLAGS) $(LDFLAGS) -o $@
AM_V_CCLD = $(am__v_CCLD_$(V))
am__v_CCLD_ = $(am__v_CCLD_$(AM_DEFAULT_VERBOSITY))
am__v_CCLD_0 = @echo "  CCLD    " $@;
am__v_CCLD_1 = 
SOURCES = $(gif2h5_SOURCES) $(h52gif_SOURCES) $(h52gifgentst_SOURCES)
DIST_SOURCES = $(gif2h5_SOURCES) $(h52gif_SOURCES) \
	$(h52gifgentst_SOURCES)
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
ETAGS = etags
CTAGS = ctags
am__tty_colors_dummy = \
  mgn= red= grn= lgn= blu= brg= std=; \
  am__color_tests=no
am__tty_colors = $(am__tty_colors_dummy)
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} /home/arhofman/shared/arhofman/wes_somatic_var_caller_comp/sim_cancer/eval_vcf/imported_scripts/hdf5/hdf5-1.8.11/bin/missing --run aclocal-1.12
ADD_PARALLEL_FILES = no
AMTAR = $${TAR-tar}

# H5_CFLAGS holds flags that should be used when building hdf5,
# but which should not be exported to h5cc for building other programs.
# AM_CFLAGS is an automake construct which should be used by Makefiles 
# instead of CFLAGS, as CFLAGS is reserved solely for the user to define.
# This applies to FCFLAGS, CXXFLAGS, CPPFLAGS, and LDFLAGS as well.
AM_CFLAGS =  -std=c99 -pedantic -Wall -Wextra -Wundef -Wshadow -Wpointer-arith -Wbad-function-cast -Wcast-qual -Wcast-align -Wwrite-strings -Wconversion -Waggregate-return -Wstrict-prototypes -Wmissing-prototypes -Wmissing-declarations -Wredundant-decls -Wnested-externs -Winline -Wno-long-long -Wfloat-equal -Wmissing-format-attribute -Wmissing-noreturn -Wpacked -Wdisabled-optimization -Wformat=2 -Wunreachable-code -Wendif-labels -Wdeclaration-after-statement -Wold-style-definition -Winvalid-pch -Wvariadic-macros -Wnonnull -Winit-self -Wmissing-include-dirs -Wswitch-default -Wswitch-enum -Wunused-macros -Wunsafe-loop-optimizations -Wc++-compat -Wstrict-overflow -Wlogical-op -Wlarger-than=2048 -Wvla -Wsync-nand -Wframe-larger-than=16384 -Wpacked-bitfield-compat -O3 -fomit-frame-pointer -finline-functions
AM_CPPFLAGS = -D_LARGEFILE_SOURCE -D_LARGEFILE64_SOURCE -D_BSD_SOURCE  -D_POSIX_C_SOURCE=199506L   -DNDEBUG -UH5_DEBUG_API
AM_CXXFLAGS =   
AM_DEFAULT_VERBOSITY = 0
AM_FCFLAGS =   
AM_LDFLAGS =  
AM_MAKEFLAGS = 
AR = ar
AS = as
AUTOCONF = ${SHELL} /home/arhofman/shared/arhofman/wes_somatic_var_caller_comp/sim_cancer/eval_vcf/imported_scripts/hdf5/hdf5-1.8.11/bin/missing --run autoconf
AUTOHEADER = ${SHELL} /home/arhofman/shared/arhofman/wes_somatic_var_caller_comp/sim_cancer/eval_vcf/imported_scripts/hdf5/hdf5-1.8.11/bin/missing --run autoheader
AUTOMAKE = ${SHELL} /home/arhofman/shared/arhofman/wes_somatic_var_caller_comp/sim_cancer/eval_vcf/imported_scripts/hdf5/hdf5-1.8.11/bin/missing --run automake-1.12
AWK = gawk
BYTESEX = little-endian
CC = gcc
CCDEPMODE = depmode=gcc3
CC_VERSION = /usr/bin/gcc ( gcc (GCC) 4.4.7 20120313 )
CFLAGS = 
CLEARFILEBUF = yes
CODESTACK = no
CONFIG_DATE = Tue Jul 19 10:00:59 CEST 2016
CONFIG_MODE = production
CONFIG_USER = arhofman@bs-beerenwinkel02.ethz.ch
CPP = gcc -E
CPPFLAGS = 
CXX = no
CXXCPP = g++ -E
CXXDEPMODE = depmode=gcc3
CXXFLAGS = 
CXX_VERSION = no ( g++ (GCC) 4.4.7 20120313 )
CYGPATH_W = echo
DEBUG_PKG = 
DEFAULT_API_VERSION = v18
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
DEPRECATED_SYMBOLS = yes
DIRECT_VFD = no
DLLTOOL = dlltool
DSYMUTIL = 
DUMPBIN = 
DYNAMIC_DIRS = 
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EGREP = /home/arhofman/root/bin/grep -E
EXEEXT = 
EXTERNAL_FILTERS = deflate(zlib)

# Make sure that these variables are exported to the Makefiles
F9XMODEXT = 
F9XMODFLAG = 
F9XSUFFIXFLAG = 
FC = no
FC2003 = 
FCFLAGS = 
FCFLAGS_f90 = 
FCLIBS = 
FC_VERSION = no ( GNU Fortran (GCC) 4.4.7 20120313 )
FGREP = /home/arhofman/root/bin/grep -F
FILTERS = shuffle,fletcher32,nbit,scaleoffset
FSEARCH_DIRS = 
GPFS = no
GREP = /home/arhofman/root/bin/grep
H5_CFLAGS = -std=c99 -pedantic -Wall -Wextra -Wundef -Wshadow -Wpointer-arith -Wbad-function-cast -Wcast-qual -Wcast-align -Wwrite-strings -Wconversion -Waggregate-return -Wstrict-prototypes -Wmissing-prototypes -Wmissing-declarations -Wredundant-decls -Wnested-externs -Winline -Wno-long-long -Wfloat-equal -Wmissing-format-attribute -Wmissing-noreturn -Wpacked -Wdisabled-optimization -Wformat=2 -Wunreachable-code -Wendif-labels -Wdeclaration-after-statement -Wold-style-definition -Winvalid-pch -Wvariadic-macros -Wnonnull -Winit-self -Wmissing-include-dirs -Wswitch-default -Wswitch-enum -Wunused-macros -Wunsafe-loop-optimizations -Wc++-compat -Wstrict-overflow -Wlogical-op -Wlarger-than=2048 -Wvla -Wsync-nand -Wframe-larger-than=16384 -Wpacked-bitfield-compat -O3 -fomit-frame-pointer -finline-functions
H5_CPPFLAGS = -D_POSIX_C_SOURCE=199506L   -DNDEBUG -UH5_DEBUG_API
H5_CXXFLAGS =  
H5_CXX_SHARED = no
H5_FCFLAGS =  
H5_FORTRAN_SHARED = no
H5_LDFLAGS = 
H5_LONE_COLON = yes
H5_VERSION = 1.8.11
HADDR_T = 
HAVE_DMALLOC = no
HAVE_FORTRAN_2003 = 
HAVE_PTHREAD = 
HDF5_HL = yes
HDF5_INTERFACES = 
HDF_CXX = no
HDF_FORTRAN = no
HDF_FORTRAN2003 = no
HID_T = 
HL = hl
HL_FOR = 
HSIZE_T = 
HSSIZE_T = 
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
INSTRUMENT = no
INSTRUMENT_LIBRARY = no
LARGEFILE = yes
LD = /usr/bin/ld -m elf_x86_64
LDFLAGS = 
LIBOBJS = 
LIBS =  -lz -lrt -ldl -lm 
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LIPO = 
LL_PATH = 
LN_S = ln -s
LTLIBOBJS = 
LT_STATIC_EXEC = 
MAINT = #
MAKEINFO = ${SHELL} /home/arhofman/shared/arhofman/wes_somatic_var_caller_comp/sim_cancer/eval_vcf/imported_scripts/hdf5/hdf5-1.8.11/bin/missing --run makeinfo
MANIFEST_TOOL = :
MKDIR_P = /bin/mkdir -p
MPE = no
MPI_GET_SIZE = 
NM = /usr/bin/nm -B
NMEDIT = 
OBJDUMP = objdump
OBJECT_NAMELEN_DEFAULT_F = 
OBJEXT = o
OTOOL = 
OTOOL64 = 
PACKAGE = hdf5
PACKAGE_BUGREPORT = help@hdfgroup.org
PACKAGE_NAME = HDF5
PACKAGE_STRING = HDF5 1.8.11
PACKAGE_TARNAME = hdf5
PACKAGE_URL = 
PACKAGE_VERSION = 1.8.11
PARALLEL = no
PATH_SEPARATOR = :
PERL = perl
RANLIB = ranlib
ROOT = /net/bs-gridfs/gridexport/shared/arhofman/wes_somatic_var_caller_comp/sim_cancer/eval_vcf/imported_scripts/hdf5/hdf5-1.8.11
RUNPARALLEL = 
RUNSERIAL = 
R_INTEGER = 
R_LARGE = 
SEARCH = VPATH=$(srcdir) $(top_builddir)/src $(top_srcdir)/src
SED = /bin/sed
SETX = set -x
SET_MAKE = 
SHELL = /bin/sh
SIZE_T = 
STATIC_EXEC = no
STATIC_SHARED = static, shared
STRICT_FORMAT_CHECKS = no
STRIP = strip
TESTPARALLEL = 
THREADSAFE = no
TIME = time
TR = /usr/bin/tr
TRACE_API = no
UNAME_INFO = Linux bs-beerenwinkel02.ethz.ch 2.6.32-358.18.1.el6.x86_64 #1 SMP Fri Aug 2 17:04:38 EDT 2013 x86_64 x86_64 x86_64 GNU/Linux
USE_FILTER_DEFLATE = yes
USE_FILTER_FLETCHER32 = yes
USE_FILTER_NBIT = yes
USE_FILTER_SCALEOFFSET = yes
USE_FILTER_SHUFFLE = yes
USE_FILTER_SZIP = no
USINGMEMCHECKER = no
VERSION = 1.8.11
WORDS_BIGENDIAN = no
abs_builddir = /home/arhofman/shared/arhofman/wes_somatic_var_caller_comp/sim_cancer/eval_vcf/imported_scripts/hdf5/hdf5-1.8.11/hl/tools/gif2h5
abs_srcdir = /home/arhofman/shared/arhofman/wes_somatic_var_caller_comp/sim_cancer/eval_vcf/imported_scripts/hdf5/hdf5-1.8.11/hl/tools/gif2h5
abs_top_builddir = /home/arhofman/shared/arhofman/wes_somatic_var_caller_comp/sim_cancer/eval_vcf/imported_scripts/hdf5/hdf5-1.8.11
abs_top_srcdir = /home/arhofman/shared/arhofman/wes_somatic_var_caller_comp/sim_cancer/eval_vcf/imported_scripts/hdf5/hdf5-1.8.11
ac_ct_AR = 
ac_ct_CC = gcc
ac_ct_CXX = 
ac_ct_DUMPBIN = 
ac_ct_FC = 
am__include = include
am__leading_dot = .
am__quote = 
am__tar = $${TAR-tar} chof - "$$tardir"
am__untar = $${TAR-tar} xf -
bindir = ${exec_prefix}/bin
build = x86_64-unknown-linux-gnu
build_alias = 
build_cpu = x86_64
build_os = linux-gnu
build_vendor = unknown
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share

# Install directories that automake doesn't know about
docdir = $(exec_prefix)/doc
dvidir = ${docdir}
enable_shared = yes
enable_static = yes
exec_prefix = ${prefix}
host = x86_64-unknown-linux-gnu
host_alias = 
host_cpu = x86_64
host_os = linux-gnu
host_vendor = unknown
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /home/arhofman/shared/arhofman/wes_somatic_var_caller_comp/sim_cancer/eval_vcf/imported_scripts/hdf5/hdf5-1.8.11/bin/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = $(MKDIR_P)
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /links/grid/shared/arhofman/wes_somatic_var_caller_comp/sim_cancer/eval_vcf/imported_scripts/hdf5/hdf5-1.8.11
program_transform_name = s,x,x,
psdir = ${docdir}
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = ../../../
top_builddir = ../../..
top_srcdir = ../../..

# Shell commands used in Makefiles
RM = rm -f
CP = cp

# Some machines need a command to run executables; this is that command
# so that our tests will run.
# We use RUNEXEC instead of RUNSERIAL directly because it may be that
# some tests need to be run with a different command.  Older versions
# of the makefiles used the command
# $(LIBTOOL) --mode=execute
# in some directories, for instance.
RUNEXEC = $(RUNSERIAL)

# Libraries to link to while building
LIBHDF5 = $(top_builddir)/src/libhdf5.la
LIBH5TEST = $(top_builddir)/test/libh5test.la
LIBH5F = $(top_builddir)/fortran/src/libhdf5_fortran.la
LIBH5FTEST = $(top_builddir)/fortran/test/libh5test_fortran.la
LIBH5CPP = $(top_builddir)/c++/src/libhdf5_cpp.la
LIBH5TOOLS = $(top_builddir)/tools/lib/libh5tools.la
LIBH5_HL = $(top_builddir)/hl/src/libhdf5_hl.la
LIBH5F_HL = $(top_builddir)/hl/fortran/src/libhdf5hl_fortran.la
LIBH5CPP_HL = $(top_builddir)/hl/c++/src/libhdf5_hl_cpp.la

# Note that in svn revision 19400 the '/' after DESTDIR in H5* variables below  
# has been removed. According to the official description of DESTDIR by Gnu at 
# http://www.gnu.org/prep/standards/html_node/DESTDIR.html, DESTDIR is 
# prepended to the normal and complete install path that it precedes for the 
# purpose of installing in a temporary directory which is useful for building 
# rpms and other packages.  The '/' after ${DESTDIR} will be followed by another 
# '/' at the beginning of the normal install path.  When DESTDIR is empty the  
# path then begins with '//', which is incorrect and causes problems at least for 
# Cygwin.   

# Scripts used to build examples
# If only shared libraries have been installed, have h5cc build examples with
# shared libraries instead of static libraries
H5CC = ${DESTDIR}$(bindir)/h5cc
H5CC_PP = ${DESTDIR}$(bindir)/h5pcc
H5FC = ${DESTDIR}$(bindir)/h5fc
H5FC_PP = ${DESTDIR}$(bindir)/h5pfc
H5CPP = ${DESTDIR}$(bindir)/h5c++
ACLOCAL_AMFLAGS = "-I m4"

# The trace script; this is used on source files from the C library to
# insert tracing macros.
TRACE = perl $(top_srcdir)/bin/trace

# .chkexe files are used to mark tests that have run successfully.
# .chklog files are output from those tests.
# *.clog are from the MPE option.
CHECK_CLEANFILES = *.chkexe *.chklog *.clog *.h5 *.gif

# Include src and tools/lib directories
INCLUDES = -I$(top_srcdir)/src -I$(top_srcdir)/tools/lib -I$(top_srcdir)/hl/src

# These are our main targets, the tools
TEST_SCRIPT = h52giftest.sh
check_SCRIPTS = $(TEST_SCRIPT)

# Add h52gif and gif2h5 specific linker flags here
h52gif_LDFLAGS = $(LT_STATIC_EXEC) $(AM_LDFLAGS)
gif2h5_LDFLAGS = $(LT_STATIC_EXEC) $(AM_LDFLAGS)
gif2h5_SOURCES = gif2hdf.c gif2mem.c decompress.c gifread.c writehdf.c 
h52gif_SOURCES = hdf2gif.c hdfgifwr.c 
h52gifgentst_SOURCES = h52gifgentst.c 

# Programs all depend on the hdf5 library, the tools library, and the HL
# library.
LDADD = $(LIBH5_HL) $(LIBH5TOOLS) $(LIBHDF5)

# Automake needs to be taught how to build lib, progs, and tests targets.
# These will be filled in automatically for the most part (e.g.,
# lib_LIBRARIES are built for lib target), but EXTRA_LIB, EXTRA_PROG, and
# EXTRA_TEST variables are supplied to allow the user to force targets to
# be built at certain times. 
LIB = $(lib_LIBRARIES) $(lib_LTLIBRARIES) $(noinst_LIBRARIES)                 \
      $(noinst_LTLIBRARIES) $(check_LIBRARIES) $(check_LTLIBRARIES) $(EXTRA_LIB)

PROGS = $(bin_PROGRAMS) $(bin_SCRIPTS) $(noinst_PROGRAMS) $(noinst_SCRIPTS)   \
        $(EXTRA_PROG)

chk_TESTS = $(check_PROGRAMS) $(check_SCRIPTS) $(EXTRA_TEST) 
TEST_EXTENSIONS = .sh
SH_LOG_COMPILER = $(SHELL)
AM_SH_LOG_FLAGS = 
TEST_PROG_CHKEXE = $(TEST_PROG:=.chkexe_)
TEST_PROG_PARA_CHKEXE = $(TEST_PROG_PARA:=.chkexe_)
TEST_SCRIPT_CHKSH = $(TEST_SCRIPT:=.chkexe_)
TEST_SCRIPT_PARA_CHKSH = $(TEST_SCRIPT_PARA:=.chkexe_)
all: all-am

.SUFFIXES:
.SUFFIXES: .c .lo .o .obj
$(srcdir)/Makefile.in: # $(srcdir)/Makefile.am $(top_srcdir)/config/commence.am $(top_srcdir)/config/conclude.am $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --foreign hl/tools/gif2h5/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --foreign hl/tools/gif2h5/Makefile
.PRECIOUS: Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe);; \
	esac;
$(top_srcdir)/config/commence.am $(top_srcdir)/config/conclude.am:

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure: # $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4): # $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):
h52giftest.sh: $(top_builddir)/config.status $(srcdir)/h52giftest.sh.in
	cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@
install-binPROGRAMS: $(bin_PROGRAMS)
	@$(NORMAL_INSTALL)
	@list='$(bin_PROGRAMS)'; test -n "$(bindir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(bindir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(bindir)" || exit 1; \
	fi; \
	for p in $$list; do echo "$$p $$p"; done | \
	sed 's/$(EXEEXT)$$//' | \
	while read p p1; do if test -f $$p || test -f $$p1; \
	  then echo "$$p"; echo "$$p"; else :; fi; \
	done | \
	sed -e 'p;s,.*/,,;n;h' -e 's|.*|.|' \
	    -e 'p;x;s,.*/,,;s/$(EXEEXT)$$//;$(transform);s/$$/$(EXEEXT)/' | \
	sed 'N;N;N;s,\n, ,g' | \
	$(AWK) 'BEGIN { files["."] = ""; dirs["."] = 1 } \
	  { d=$$3; if (dirs[d] != 1) { print "d", d; dirs[d] = 1 } \
	    if ($$2 == $$4) files[d] = files[d] " " $$1; \
	    else { print "f", $$3 "/" $$4, $$1; } } \
	  END { for (d in files) print "f", d, files[d] }' | \
	while read type dir files; do \
	    if test "$$dir" = .; then dir=; else dir=/$$dir; fi; \
	    test -z "$$files" || { \
	    echo " $(INSTALL_PROGRAM_ENV) $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=install $(INSTALL_PROGRAM) $$files '$(DESTDIR)$(bindir)$$dir'"; \
	    $(INSTALL_PROGRAM_ENV) $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=install $(INSTALL_PROGRAM) $$files "$(DESTDIR)$(bindir)$$dir" || exit $$?; \
	    } \
	; done

uninstall-binPROGRAMS:
	@$(NORMAL_UNINSTALL)
	@list='$(bin_PROGRAMS)'; test -n "$(bindir)" || list=; \
	files=`for p in $$list; do echo "$$p"; done | \
	  sed -e 'h;s,^.*/,,;s/$(EXEEXT)$$//;$(transform)' \
	      -e 's/$$/$(EXEEXT)/' `; \
	test -n "$$list" || exit 0; \
	echo " ( cd '$(DESTDIR)$(bindir)' && rm -f" $$files ")"; \
	cd "$(DESTDIR)$(bindir)" && rm -f $$files

clean-binPROGRAMS:
	@list='$(bin_PROGRAMS)'; test -n "$$list" || exit 0; \
	echo " rm -f" $$list; \
	rm -f $$list || exit $$?; \
	test -n "$(EXEEXT)" || exit 0; \
	list=`for p in $$list; do echo "$$p"; done | sed 's/$(EXEEXT)$$//'`; \
	echo " rm -f" $$list; \
	rm -f $$list

clean-noinstPROGRAMS:
	@list='$(noinst_PROGRAMS)'; test -n "$$list" || exit 0; \
	echo " rm -f" $$list; \
	rm -f $$list || exit $$?; \
	test -n "$(EXEEXT)" || exit 0; \
	list=`for p in $$list; do echo "$$p"; done | sed 's/$(EXEEXT)$$//'`; \
	echo " rm -f" $$list; \
	rm -f $$list
gif2h5$(EXEEXT): $(gif2h5_OBJECTS) $(gif2h5_DEPENDENCIES) $(EXTRA_gif2h5_DEPENDENCIES) 
	@rm -f gif2h5$(EXEEXT)
	$(AM_V_CCLD)$(gif2h5_LINK) $(gif2h5_OBJECTS) $(gif2h5_LDADD) $(LIBS)
h52gif$(EXEEXT): $(h52gif_OBJECTS) $(h52gif_DEPENDENCIES) $(EXTRA_h52gif_DEPENDENCIES) 
	@rm -f h52gif$(EXEEXT)
	$(AM_V_CCLD)$(h52gif_LINK) $(h52gif_OBJECTS) $(h52gif_LDADD) $(LIBS)
h52gifgentst$(EXEEXT): $(h52gifgentst_OBJECTS) $(h52gifgentst_DEPENDENCIES) $(EXTRA_h52gifgentst_DEPENDENCIES) 
	@rm -f h52gifgentst$(EXEEXT)
	$(AM_V_CCLD)$(LINK) $(h52gifgentst_OBJECTS) $(h52gifgentst_LDADD) $(LIBS)

mostlyclean-compile:
	-rm -f *.$(OBJEXT)

distclean-compile:
	-rm -f *.tab.c

include ./$(DEPDIR)/decompress.Po
include ./$(DEPDIR)/gif2hdf.Po
include ./$(DEPDIR)/gif2mem.Po
include ./$(DEPDIR)/gifread.Po
include ./$(DEPDIR)/h52gifgentst.Po
include ./$(DEPDIR)/hdf2gif.Po
include ./$(DEPDIR)/hdfgifwr.Po
include ./$(DEPDIR)/writehdf.Po

.c.o:
	$(AM_V_CC)$(COMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
	$(AM_V_at)$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	$(AM_V_CC)source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(AM_V_CC_no)$(COMPILE) -c $<

.c.obj:
	$(AM_V_CC)$(COMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ `$(CYGPATH_W) '$<'`
	$(AM_V_at)$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	$(AM_V_CC)source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(AM_V_CC_no)$(COMPILE) -c `$(CYGPATH_W) '$<'`

.c.lo:
	$(AM_V_CC)$(LTCOMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
	$(AM_V_at)$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Plo
#	$(AM_V_CC)source='$<' object='$@' libtool=yes \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(AM_V_CC_no)$(LTCOMPILE) -c -o $@ $<

mostlyclean-libtool:
	-rm -f *.lo

clean-libtool:
	-rm -rf .libs _libs

ID: $(HEADERS) $(SOURCES) $(LISP) $(TAGS_FILES)
	list='$(SOURCES) $(HEADERS) $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	mkid -fID $$unique
tags: TAGS

TAGS:  $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) \
		$(TAGS_FILES) $(LISP)
	set x; \
	here=`pwd`; \
	list='$(SOURCES) $(HEADERS)  $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	shift; \
	if test -z "$(ETAGS_ARGS)$$*$$unique"; then :; else \
	  test -n "$$unique" || unique=$$empty_fix; \
	  if test $$# -gt 0; then \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      "$$@" $$unique; \
	  else \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      $$unique; \
	  fi; \
	fi
ctags: CTAGS
CTAGS:  $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) \
		$(TAGS_FILES) $(LISP)
	list='$(SOURCES) $(HEADERS)  $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	test -z "$(CTAGS_ARGS)$$unique" \
	  || $(CTAGS) $(CTAGSFLAGS) $(AM_CTAGSFLAGS) $(CTAGS_ARGS) \
	     $$unique

GTAGS:
	here=`$(am__cd) $(top_builddir) && pwd` \
	  && $(am__cd) $(top_srcdir) \
	  && gtags -i $(GTAGS_ARGS) "$$here"

cscopelist:  $(HEADERS) $(SOURCES) $(LISP)
	list='$(SOURCES) $(HEADERS) $(LISP)'; \
	case "$(srcdir)" in \
	  [\\/]* | ?:[\\/]*) sdir="$(srcdir)" ;; \
	  *) sdir=$(subdir)/$(srcdir) ;; \
	esac; \
	for i in $$list; do \
	  if test -f "$$i"; then \
	    echo "$(subdir)/$$i"; \
	  else \
	    echo "$$sdir/$$i"; \
	  fi; \
	done >> $(top_builddir)/cscope.files

distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH tags

distdir: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
	$(MAKE) $(AM_MAKEFLAGS) $(check_SCRIPTS)
	$(MAKE) $(AM_MAKEFLAGS) check-TESTS
check: check-am
all-am: Makefile $(PROGRAMS) all-local
installdirs:
	for dir in "$(DESTDIR)$(bindir)"; do \
	  test -z "$$dir" || $(MKDIR_P) "$$dir"; \
	done
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	if test -z '$(STRIP)'; then \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	      install; \
	else \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	    "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'" install; \
	fi
mostlyclean-generic:

clean-generic:

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am

clean-am: clean-binPROGRAMS clean-generic clean-libtool \
	clean-noinstPROGRAMS mostlyclean-am

distclean: distclean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
distclean-am: clean-am distclean-compile distclean-generic \
	distclean-tags

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am:

install-dvi: install-dvi-am

install-dvi-am:

install-exec-am: install-binPROGRAMS

install-html: install-html-am

install-html-am:

install-info: install-info-am

install-info-am:

install-man:

install-pdf: install-pdf-am

install-pdf-am:

install-ps: install-ps-am

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-compile mostlyclean-generic \
	mostlyclean-libtool mostlyclean-local

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am: uninstall-binPROGRAMS

.MAKE: check-am install-am install-strip

.PHONY: CTAGS GTAGS all all-am all-local check check-TESTS check-am \
	clean clean-binPROGRAMS clean-generic clean-libtool \
	clean-noinstPROGRAMS cscopelist ctags distclean \
	distclean-compile distclean-generic distclean-libtool \
	distclean-tags distdir dvi dvi-am html html-am info info-am \
	install install-am install-binPROGRAMS install-data \
	install-data-am install-dvi install-dvi-am install-exec \
	install-exec-am install-html install-html-am install-info \
	install-info-am install-man install-pdf install-pdf-am \
	install-ps install-ps-am install-strip installcheck \
	installcheck-am installdirs maintainer-clean \
	maintainer-clean-generic mostlyclean mostlyclean-compile \
	mostlyclean-generic mostlyclean-libtool mostlyclean-local pdf \
	pdf-am ps ps-am tags uninstall uninstall-am \
	uninstall-binPROGRAMS


# List all build rules defined by HDF5 Makefiles as "PHONY" targets here.
# This tells the Makefiles that these targets are not files to be built but
# commands that should be executed even if a file with the same name already
# exists.
.PHONY: build-check-clean build-check-p build-check-s build-lib build-progs \
        build-tests check-clean check-install check-p check-s check-vfd \
        install-doc lib progs tests uninstall-doc _exec_check-s _test help

help:
	@$(top_srcdir)/bin/makehelp

# lib/progs/tests targets recurse into subdirectories. build-* targets
# build files in this directory.
build-lib: $(LIB)
build-progs: $(LIB) $(PROGS)
build-tests: $(LIB) $(PROGS) $(chk_TESTS)

# General rule for recursive building targets.
# BUILT_SOURCES contain targets that need to be built before anything else
# in the directory (e.g., for Fortran type detection)
lib progs tests check-s check-p :: $(BUILT_SOURCES)
	@$(MAKE) $(AM_MAKEFLAGS) build-$@ || exit 1;
	@for d in X $(SUBDIRS); do                                             \
	    if test $$d != X && test $$d != .; then                           \
	        (set -x; cd $$d && $(MAKE) $(AM_MAKEFLAGS) $@) || exit 1;     \
	    fi;                                                               \
	done

# General rule for recursive cleaning targets.  Like the rule above,
# but doesn't require building BUILT_SOURCES.
check-clean ::
	@$(MAKE) $(AM_MAKEFLAGS) build-$@ || exit 1;
	@for d in X $(SUBDIRS); do                                             \
	    if test $$d != X && test $$d != .; then                           \
	        (set -x; cd $$d && $(MAKE) $(AM_MAKEFLAGS) $@) || exit 1;     \
	    fi;                                                               \
	done

# Tell Automake to build tests when the user types `make all' (this is
# not its default behavior).  Also build EXTRA_LIB and EXTRA_PROG since
# Automake won't build them automatically, either.
all-local: $(EXTRA_LIB) $(EXTRA_PROG) $(chk_TESTS)

# make install-doc doesn't do anything outside of doc directory, but
# Makefiles should recognize it.
# UPDATE: docs no longer reside in this build tree, so this target
# is depreciated.
install-doc uninstall-doc:
	@echo "Nothing to be done."

# clean up files generated by tests so they can be re-run.
build-check-clean:
	$(RM) -rf $(CHECK_CLEANFILES)

# run check-clean whenever mostlyclean is run
mostlyclean-local: build-check-clean

# check-install is just a synonym for installcheck
check-install: installcheck

# Run each test in order, passing $(TEST_FLAGS) to the program.
# Since tests are done in a shell loop, "make -i" does apply inside it.
# Set HDF5_Make_Ignore to a non-blank string to ignore errors inside the loop.
# The timestamps give a rough idea how much time the tests use.
#
# Note that targets in chk_TESTS (defined above) will be built when the user
# types 'make tests' or 'make check', but only programs in TEST_PROG,
# TEST_PROG_PARA, or TEST_SCRIPT will actually be executed.
check-TESTS: test

test _test:
	@$(MAKE) build-check-s
	@$(MAKE) build-check-p

# Actual execution of check-s.
build-check-s: $(LIB) $(PROGS) $(chk_TESTS)
	@if test -n "$(TEST_PROG)$(TEST_SCRIPT)"; then      \
	   echo "===Serial tests in `echo ${PWD} | sed -e s:.*/::` begin `date`==="; \
	fi
	@$(MAKE) $(AM_MAKEFLAGS) _exec_check-s
	@if test -n "$(TEST_PROG)$(TEST_SCRIPT)"; then      \
	    echo "===Serial tests in `echo ${PWD} | sed -e s:.*/::` ended `date`===";\
	fi

_exec_check-s: $(TEST_PROG_CHKEXE) $(TEST_SCRIPT_CHKSH)

# The dummy.chkexe here prevents the target from being
# empty if there are no tests in the current directory.
# $${log} is the log file.
# $${tname} is the name of test.
$(TEST_PROG_CHKEXE) $(TEST_PROG_PARA_CHKEXE) dummy.chkexe_:
	@if test "X$@" != "X.chkexe_" && test "X$@" != "Xdummy.chkexe_"; then \
	   tname=$(@:.chkexe_=)$(EXEEXT);\
	   log=$(@:.chkexe_=.chklog); \
	   echo "============================"; \
	   if $(top_srcdir)/bin/newer $(@:.chkexe_=.chkexe) $${tname}; then \
	      echo "No need to test $${tname} again."; \
	   else \
	      echo "============================" > $${log}; \
	      if test "X$(FORTRAN_API)" = "Xyes"; then \
	         echo "Fortran API: Testing $(HDF5_DRIVER) $${tname} $(TEST_FLAGS)"; \
	         echo "Fortran API: $(HDF5_DRIVER) $${tname} $(TEST_FLAGS) Test Log" >> $${log}; \
	      elif test "X$(CXX_API)" = "Xyes"; then \
	         echo "C++ API: Testing $(HDF5_DRIVER) $${tname} $(TEST_FLAGS)"; \
	         echo "C++ API: $(HDF5_DRIVER) $${tname} $(TEST_FLAGS) Test Log" >> $${log};\
	      else \
	         echo "Testing $(HDF5_DRIVER) $${tname} $(TEST_FLAGS)"; \
	         echo "$(HDF5_DRIVER) $${tname} $(TEST_FLAGS) Test Log" >> $${log}; \
	      fi; \
	      echo "============================" >> $${log}; \
	      srcdir="$(srcdir)" \
	         $(TIME) $(RUNEXEC) ./$${tname} $(TEST_FLAGS) >> $${log} 2>&1 \
	         && touch $(@:.chkexe_=.chkexe) || \
	         (test $$HDF5_Make_Ignore && echo "*** Error ignored") || \
	         (cat $${log} && false) || exit 1; \
	      echo "" >> $${log}; \
	      echo "Finished testing $${tname} $(TEST_FLAGS)" >> $${log}; \
	      echo "============================" >> $${log}; \
	      echo "Finished testing $${tname} $(TEST_FLAGS)"; \
	      cat $${log}; \
	   fi; \
	fi

# The dummysh.chkexe here prevents the target from being
# empty if there are no tests in the current directory.
# $${log} is the log file.
# $${tname} is the name of test.
$(TEST_SCRIPT_CHKSH) $(TEST_SCRIPT_PARA_CHKSH) dummysh.chkexe_:
	@if test "X$@" != "X.chkexe_" && test "X$@" != "Xdummysh.chkexe_"; then \
	   cmd=$(@:.chkexe_=);\
	   tname=`basename $$cmd`;\
	   chkname=`basename $(@:.chkexe_=.chkexe)`;\
	   log=`basename $(@:.chkexe_=.chklog)`; \
	   echo "============================"; \
	   if $(top_srcdir)/bin/newer $${chkname} $$cmd $(SCRIPT_DEPEND); then \
	      echo "No need to test $${tname} again."; \
	   else \
	      echo "============================" > $${log}; \
	      if test "X$(FORTRAN_API)" = "Xyes"; then \
	         echo "Fortran API: Testing $${tname} $(TEST_FLAGS)"; \
	         echo "Fortran API: $${tname} $(TEST_FLAGS) Test Log" >> $${log}; \
	      elif test "X$(CXX_API)" = "Xyes"; then \
	         echo "C++ API: Testing $${tname} $(TEST_FLAGS)"; \
	         echo "C++ API: $${tname} $(TEST_FLAGS) Test Log" >> $${log}; \
	      else \
	         echo "Testing $${tname} $(TEST_FLAGS)"; \
	         echo "$${tname} $(TEST_FLAGS) Test Log" >> $${log}; \
	      fi; \
	      echo "============================" >> $${log}; \
	      RUNSERIAL="$(RUNSERIAL)" RUNPARALLEL="$(RUNPARALLEL)"           \
	      srcdir="$(srcdir)" \
	         $(TIME) $(SHELL) $$cmd $(TEST_FLAGS) >> $${log} 2>&1 \
	         && touch $${chkname} || \
	         (test $$HDF5_Make_Ignore && echo "*** Error ignored") || \
	         (cat $${log} && false) || exit 1; \
	      echo "" >> $${log}; \
	      echo "Finished testing $${tname} $(TEST_FLAGS)" >> $${log}; \
	      echo "============================" >> $${log}; \
	      echo "Finished testing $${tname} $(TEST_FLAGS)"; \
	      cat $${log}; \
	   fi; \
	   echo "============================"; \
	fi

# Actual execution of check-p.
build-check-p: $(LIB) $(PROGS) $(chk_TESTS)
	@if test -n "$(TEST_PROG_PARA)$(TEST_SCRIPT_PARA)"; then      \
	   echo "===Parallel tests in `echo ${PWD} | sed -e s:.*/::` begin `date`==="; \
	fi
	@if test -n "$(TEST_PROG_PARA)"; then                                \
	    echo "**** Hint ****";                                            \
	    echo "Parallel test files reside in the current directory"        \
	         "by default.";                                               \
	    echo "Set HDF5_PARAPREFIX to use another directory. E.g.,";       \
	    echo "    HDF5_PARAPREFIX=/PFS/user/me";                          \
	    echo "    export HDF5_PARAPREFIX";                                \
	    echo "    make check";                                            \
	    echo "**** end of Hint ****";                                     \
	fi
	@for test in $(TEST_PROG_PARA) dummy; do                             \
	   if test $$test != dummy; then                                      \
	      $(MAKE) $(AM_MAKEFLAGS) $$test.chkexe_ \
	      RUNEXEC="$(RUNPARALLEL)" || exit 1; \
	   fi;                                                                \
	done
	@for test in $(TEST_SCRIPT_PARA) dummy; do                           \
	  if test $$test != dummy; then                                      \
	    $(MAKE) $(AM_MAKEFLAGS) $$test.chkexe_ || exit 1; \
	  fi;                                                                 \
	done
	@if test -n "$(TEST_PROG_PARA)$(TEST_SCRIPT_PARA)"; then      \
	    echo "===Parallel tests in `echo ${PWD} | sed -e s:.*/::` ended `date`===";\
	fi

# Run test with different Virtual File Driver
check-vfd: $(LIB) $(PROGS) $(chk_TESTS)
	@for vfd in $(VFD_LIST) dummy; do                                     \
	    if test $$vfd != dummy; then                                      \
	        echo "============================";                          \
	        echo "Testing Virtual File Driver $$vfd";                     \
	        echo "============================";                          \
	        $(MAKE) $(AM_MAKEFLAGS) check-clean || exit 1;                \
	        HDF5_DRIVER=$$vfd $(MAKE) $(AM_MAKEFLAGS) check || exit 1;    \
	    fi;                                                               \
	done

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
