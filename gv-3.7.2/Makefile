# Makefile.in generated by automake 1.11.1 from Makefile.am.
# Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994, 1995, 1996, 1997, 1998, 1999, 2000, 2001, 2002,
# 2003, 2004, 2005, 2006, 2007, 2008, 2009  Free Software Foundation,
# Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.



# Makefile.am for gv/
#
# Time-stamp: "07/06/25 19:48:00 jemarch"
#
# Copyrigh (C) 2004 José E. Marchesi

# Process this file with automake to get Makefile.in

pkgdatadir = $(datadir)/gv
pkgincludedir = $(includedir)/gv
pkglibdir = $(libdir)/gv
pkglibexecdir = $(libexecdir)/gv
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
build_triplet = i686-pc-linux-gnu
host_triplet = i686-pc-linux-gnu
subdir = .
DIST_COMMON = README $(am__configure_deps) $(srcdir)/Makefile.am \
	$(srcdir)/Makefile.in $(top_srcdir)/configure AUTHORS COPYING \
	ChangeLog INSTALL NEWS config.guess config.sub depcomp \
	install-sh missing
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/m4/00gnulib.m4 \
	$(top_srcdir)/m4/alloca.m4 $(top_srcdir)/m4/canonicalize.m4 \
	$(top_srcdir)/m4/dos.m4 $(top_srcdir)/m4/double-slash-root.m4 \
	$(top_srcdir)/m4/eealloc.m4 $(top_srcdir)/m4/errno_h.m4 \
	$(top_srcdir)/m4/extensions.m4 $(top_srcdir)/m4/getopt.m4 \
	$(top_srcdir)/m4/gettimeofday.m4 \
	$(top_srcdir)/m4/gnulib-common.m4 \
	$(top_srcdir)/m4/gnulib-comp.m4 \
	$(top_srcdir)/m4/include_next.m4 \
	$(top_srcdir)/m4/inttypes-pri.m4 $(top_srcdir)/m4/inttypes.m4 \
	$(top_srcdir)/m4/longlong.m4 $(top_srcdir)/m4/lstat.m4 \
	$(top_srcdir)/m4/malloca.m4 $(top_srcdir)/m4/mkdtemp.m4 \
	$(top_srcdir)/m4/mkstemp.m4 $(top_srcdir)/m4/multiarch.m4 \
	$(top_srcdir)/m4/onceonly.m4 $(top_srcdir)/m4/pathmax.m4 \
	$(top_srcdir)/m4/readlink.m4 $(top_srcdir)/m4/stat.m4 \
	$(top_srcdir)/m4/stdbool.m4 $(top_srcdir)/m4/stddef_h.m4 \
	$(top_srcdir)/m4/stdint.m4 $(top_srcdir)/m4/stdlib_h.m4 \
	$(top_srcdir)/m4/sys_stat_h.m4 $(top_srcdir)/m4/sys_time_h.m4 \
	$(top_srcdir)/m4/tempname.m4 $(top_srcdir)/m4/time_h.m4 \
	$(top_srcdir)/m4/unistd_h.m4 $(top_srcdir)/m4/warn-on-use.m4 \
	$(top_srcdir)/m4/wchar_h.m4 $(top_srcdir)/m4/wchar_t.m4 \
	$(top_srcdir)/m4/wint_t.m4 $(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
am__CONFIG_DISTCLEAN_FILES = config.status config.cache config.log \
 configure.lineno config.status.lineno
mkinstalldirs = $(install_sh) -d
CONFIG_HEADER = $(top_builddir)/src/ac_config.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
SOURCES =
DIST_SOURCES =
RECURSIVE_TARGETS = all-recursive check-recursive dvi-recursive \
	html-recursive info-recursive install-data-recursive \
	install-dvi-recursive install-exec-recursive \
	install-html-recursive install-info-recursive \
	install-pdf-recursive install-ps-recursive install-recursive \
	installcheck-recursive installdirs-recursive pdf-recursive \
	ps-recursive uninstall-recursive
RECURSIVE_CLEAN_TARGETS = mostlyclean-recursive clean-recursive	\
  distclean-recursive maintainer-clean-recursive
AM_RECURSIVE_TARGETS = $(RECURSIVE_TARGETS:-recursive=) \
	$(RECURSIVE_CLEAN_TARGETS:-recursive=) tags TAGS ctags CTAGS \
	distdir dist dist-all distcheck
ETAGS = etags
CTAGS = ctags
DIST_SUBDIRS = $(SUBDIRS)
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
distdir = $(PACKAGE)-$(VERSION)
top_distdir = $(distdir)
am__remove_distdir = \
  { test ! -d "$(distdir)" \
    || { find "$(distdir)" -type d ! -perm -200 -exec chmod u+w {} ';' \
         && rm -fr "$(distdir)"; }; }
am__relativize = \
  dir0=`pwd`; \
  sed_first='s,^\([^/]*\)/.*$$,\1,'; \
  sed_rest='s,^[^/]*/*,,'; \
  sed_last='s,^.*/\([^/]*\)$$,\1,'; \
  sed_butlast='s,/*[^/]*$$,,'; \
  while test -n "$$dir1"; do \
    first=`echo "$$dir1" | sed -e "$$sed_first"`; \
    if test "$$first" != "."; then \
      if test "$$first" = ".."; then \
        dir2=`echo "$$dir0" | sed -e "$$sed_last"`/"$$dir2"; \
        dir0=`echo "$$dir0" | sed -e "$$sed_butlast"`; \
      else \
        first2=`echo "$$dir2" | sed -e "$$sed_first"`; \
        if test "$$first2" = "$$first"; then \
          dir2=`echo "$$dir2" | sed -e "$$sed_rest"`; \
        else \
          dir2="../$$dir2"; \
        fi; \
        dir0="$$dir0"/"$$first"; \
      fi; \
    fi; \
    dir1=`echo "$$dir1" | sed -e "$$sed_rest"`; \
  done; \
  reldir="$$dir2"
DIST_ARCHIVES = $(distdir).tar.gz
GZIP_ENV = --best
distuninstallcheck_listfiles = find . -type f -print
distcleancheck_listfiles = find . -type f -print
ACLOCAL = ${SHELL} /media/KINGSTON/gv-3.7.2/missing --run aclocal-1.11
ALLOCA = 
ALLOCA_H = alloca.h
AMTAR = ${SHELL} /media/KINGSTON/gv-3.7.2/missing --run tar
APPLE_UNIVERSAL_BUILD = 0
AUTOCONF = ${SHELL} /media/KINGSTON/gv-3.7.2/missing --run autoconf
AUTOHEADER = ${SHELL} /media/KINGSTON/gv-3.7.2/missing --run autoheader
AUTOMAKE = ${SHELL} /media/KINGSTON/gv-3.7.2/missing --run automake-1.11
AWK = gawk
BITSIZEOF_PTRDIFF_T = 
BITSIZEOF_SIG_ATOMIC_T = 
BITSIZEOF_SIZE_T = 
BITSIZEOF_WCHAR_T = 
BITSIZEOF_WINT_T = 
CC = gcc
CCDEPMODE = depmode=gcc3
CFLAGS = -g -O2
CPP = gcc -E
CPPFLAGS = 
CYGPATH_W = echo
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EGREP = /bin/grep -E
EMULTIHOP_HIDDEN = 
EMULTIHOP_VALUE = 
ENOLINK_HIDDEN = 
ENOLINK_VALUE = 
EOVERFLOW_HIDDEN = 
EOVERFLOW_VALUE = 
ERRNO_H = 
EXEEXT = 
GETOPT_H = getopt.h
GNULIB_ATOLL = 0
GNULIB_BTOWC = 0
GNULIB_CALLOC_POSIX = 0
GNULIB_CANONICALIZE_FILE_NAME = 1
GNULIB_CHOWN = 0
GNULIB_CLOSE = 0
GNULIB_DUP2 = 0
GNULIB_DUP3 = 0
GNULIB_ENVIRON = 0
GNULIB_EUIDACCESS = 0
GNULIB_FACCESSAT = 0
GNULIB_FCHDIR = 0
GNULIB_FCHMODAT = 0
GNULIB_FCHOWNAT = 0
GNULIB_FSTATAT = 0
GNULIB_FSYNC = 0
GNULIB_FTRUNCATE = 0
GNULIB_FUTIMENS = 0
GNULIB_GETCWD = 0
GNULIB_GETDOMAINNAME = 0
GNULIB_GETDTABLESIZE = 0
GNULIB_GETGROUPS = 0
GNULIB_GETHOSTNAME = 0
GNULIB_GETLOADAVG = 0
GNULIB_GETLOGIN = 0
GNULIB_GETLOGIN_R = 0
GNULIB_GETPAGESIZE = 0
GNULIB_GETSUBOPT = 0
GNULIB_GETTIMEOFDAY = 1
GNULIB_GETUSERSHELL = 0
GNULIB_GRANTPT = 0
GNULIB_IMAXABS = 0
GNULIB_IMAXDIV = 0
GNULIB_LCHMOD = 0
GNULIB_LCHOWN = 0
GNULIB_LINK = 0
GNULIB_LINKAT = 0
GNULIB_LSEEK = 0
GNULIB_LSTAT = 1
GNULIB_MALLOC_POSIX = 0
GNULIB_MBRLEN = 0
GNULIB_MBRTOWC = 0
GNULIB_MBSINIT = 0
GNULIB_MBSNRTOWCS = 0
GNULIB_MBSRTOWCS = 0
GNULIB_MKDIRAT = 0
GNULIB_MKDTEMP = 1
GNULIB_MKFIFO = 0
GNULIB_MKFIFOAT = 0
GNULIB_MKNOD = 0
GNULIB_MKNODAT = 0
GNULIB_MKOSTEMP = 0
GNULIB_MKOSTEMPS = 0
GNULIB_MKSTEMP = 1
GNULIB_MKSTEMPS = 0
GNULIB_MKTIME = 0
GNULIB_NANOSLEEP = 0
GNULIB_PIPE2 = 0
GNULIB_PREAD = 0
GNULIB_PTSNAME = 0
GNULIB_PUTENV = 0
GNULIB_PWRITE = 0
GNULIB_RANDOM_R = 0
GNULIB_READLINK = 1
GNULIB_READLINKAT = 0
GNULIB_REALLOC_POSIX = 0
GNULIB_REALPATH = 1
GNULIB_RMDIR = 0
GNULIB_RPMATCH = 0
GNULIB_SETENV = 0
GNULIB_SLEEP = 0
GNULIB_STAT = 1
GNULIB_STRPTIME = 0
GNULIB_STRTOD = 0
GNULIB_STRTOIMAX = 0
GNULIB_STRTOLL = 0
GNULIB_STRTOULL = 0
GNULIB_STRTOUMAX = 0
GNULIB_SYMLINK = 0
GNULIB_SYMLINKAT = 0
GNULIB_TIMEGM = 0
GNULIB_TIME_R = 0
GNULIB_TTYNAME_R = 0
GNULIB_UNISTD_H_GETOPT = 1
GNULIB_UNISTD_H_SIGPIPE = 0
GNULIB_UNLINK = 0
GNULIB_UNLINKAT = 0
GNULIB_UNLOCKPT = 0
GNULIB_UNSETENV = 0
GNULIB_USLEEP = 0
GNULIB_UTIMENSAT = 0
GNULIB_WCRTOMB = 0
GNULIB_WCSNRTOMBS = 0
GNULIB_WCSRTOMBS = 0
GNULIB_WCTOB = 0
GNULIB_WCWIDTH = 0
GNULIB_WRITE = 0
GREP = /bin/grep
HAVE_ATOLL = 1
HAVE_BTOWC = 1
HAVE_CALLOC_POSIX = 1
HAVE_CANONICALIZE_FILE_NAME = 1
HAVE_CHOWN = 1
HAVE_DECL_ENVIRON = 1
HAVE_DECL_GETLOADAVG = 1
HAVE_DECL_GETLOGIN_R = 1
HAVE_DECL_GETPAGESIZE = 1
HAVE_DECL_GETUSERSHELL = 1
HAVE_DECL_IMAXABS = 1
HAVE_DECL_IMAXDIV = 1
HAVE_DECL_STRTOIMAX = 1
HAVE_DECL_STRTOUMAX = 1
HAVE_DECL_WCTOB = 1
HAVE_DECL_WCWIDTH = 1
HAVE_DUP2 = 1
HAVE_DUP3 = 1
HAVE_EUIDACCESS = 1
HAVE_FACCESSAT = 1
HAVE_FCHDIR = 1
HAVE_FCHMODAT = 1
HAVE_FCHOWNAT = 1
HAVE_FSTATAT = 1
HAVE_FSYNC = 1
HAVE_FTRUNCATE = 1
HAVE_FUTIMENS = 1
HAVE_GETDOMAINNAME = 1
HAVE_GETDTABLESIZE = 1
HAVE_GETGROUPS = 1
HAVE_GETHOSTNAME = 1
HAVE_GETLOGIN = 1
HAVE_GETOPT_H = 1
HAVE_GETPAGESIZE = 1
HAVE_GETSUBOPT = 1
HAVE_GETTIMEOFDAY = 1
HAVE_GRANTPT = 1
HAVE_INTTYPES_H = 1
HAVE_LCHMOD = 1
HAVE_LCHOWN = 1
HAVE_LINK = 1
HAVE_LINKAT = 1
HAVE_LOCALTIME_R = 1
HAVE_LONG_LONG_INT = 1
HAVE_LSTAT = 1
HAVE_MALLOC_POSIX = 1
HAVE_MBRLEN = 1
HAVE_MBRTOWC = 1
HAVE_MBSINIT = 1
HAVE_MBSNRTOWCS = 1
HAVE_MBSRTOWCS = 1
HAVE_MKDIRAT = 1
HAVE_MKDTEMP = 1
HAVE_MKFIFO = 1
HAVE_MKFIFOAT = 1
HAVE_MKNOD = 1
HAVE_MKNODAT = 1
HAVE_MKOSTEMP = 1
HAVE_MKOSTEMPS = 1
HAVE_MKSTEMP = 1
HAVE_MKSTEMPS = 1
HAVE_NANOSLEEP = 1
HAVE_OS_H = 0
HAVE_PIPE2 = 1
HAVE_PREAD = 1
HAVE_PTSNAME = 1
HAVE_PWRITE = 1
HAVE_RANDOM_H = 0
HAVE_RANDOM_R = 1
HAVE_READLINK = 1
HAVE_READLINKAT = 1
HAVE_REALLOC_POSIX = 1
HAVE_REALPATH = 1
HAVE_RPMATCH = 1
HAVE_SETENV = 1
HAVE_SIGNED_SIG_ATOMIC_T = 
HAVE_SIGNED_WCHAR_T = 
HAVE_SIGNED_WINT_T = 
HAVE_SLEEP = 1
HAVE_STDINT_H = 1
HAVE_STRPTIME = 1
HAVE_STRTOD = 1
HAVE_STRTOLL = 1
HAVE_STRTOULL = 1
HAVE_STRUCT_RANDOM_DATA = 1
HAVE_STRUCT_TIMEVAL = 1
HAVE_SYMLINK = 1
HAVE_SYMLINKAT = 1
HAVE_SYS_BITYPES_H = 
HAVE_SYS_INTTYPES_H = 
HAVE_SYS_LOADAVG_H = 0
HAVE_SYS_PARAM_H = 0
HAVE_SYS_TIME_H = 1
HAVE_SYS_TYPES_H = 1
HAVE_TIMEGM = 1
HAVE_TTYNAME_R = 1
HAVE_UNISTD_H = 1
HAVE_UNLINKAT = 1
HAVE_UNLOCKPT = 1
HAVE_UNSETENV = 1
HAVE_UNSIGNED_LONG_LONG_INT = 1
HAVE_USLEEP = 1
HAVE_UTIMENSAT = 1
HAVE_WCHAR_H = 1
HAVE_WCHAR_T = 1
HAVE_WCRTOMB = 1
HAVE_WCSNRTOMBS = 1
HAVE_WCSRTOMBS = 1
HAVE_WINT_T = 1
HAVE__BOOL = 1
INCLUDE_NEXT = include_next
INCLUDE_NEXT_AS_FIRST_DIRECTIVE = include_next
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
INT32_MAX_LT_INTMAX_MAX = 1
INT64_MAX_EQ_LONG_MAX = 0
LDFLAGS = 
LIBGNU_LIBDEPS = 
LIBGNU_LTLIBDEPS = 
LIBINTL = 
LIBOBJS = 
LIBS = -lXinerama -lXaw3d -lXpm -lXmu -lXt -lXext -lSM -lICE -lX11 -lfl -lm 
LTLIBINTL = 
LTLIBOBJS = 
MAINT = #
MAKEINFO = ${SHELL} /media/KINGSTON/gv-3.7.2/missing --run makeinfo
MANUALEDITION = First
MKDIR_P = /bin/mkdir -p
NEXT_AS_FIRST_DIRECTIVE_ERRNO_H = 
NEXT_AS_FIRST_DIRECTIVE_GETOPT_H = <getopt.h>
NEXT_AS_FIRST_DIRECTIVE_INTTYPES_H = <inttypes.h>
NEXT_AS_FIRST_DIRECTIVE_STDDEF_H = 
NEXT_AS_FIRST_DIRECTIVE_STDINT_H = <stdint.h>
NEXT_AS_FIRST_DIRECTIVE_STDLIB_H = <stdlib.h>
NEXT_AS_FIRST_DIRECTIVE_SYS_STAT_H = <sys/stat.h>
NEXT_AS_FIRST_DIRECTIVE_SYS_TIME_H = <sys/time.h>
NEXT_AS_FIRST_DIRECTIVE_TIME_H = <time.h>
NEXT_AS_FIRST_DIRECTIVE_UNISTD_H = <unistd.h>
NEXT_AS_FIRST_DIRECTIVE_WCHAR_H = <wchar.h>
NEXT_ERRNO_H = 
NEXT_GETOPT_H = <getopt.h>
NEXT_INTTYPES_H = <inttypes.h>
NEXT_STDDEF_H = 
NEXT_STDINT_H = <stdint.h>
NEXT_STDLIB_H = <stdlib.h>
NEXT_SYS_STAT_H = <sys/stat.h>
NEXT_SYS_TIME_H = <sys/time.h>
NEXT_TIME_H = <time.h>
NEXT_UNISTD_H = <unistd.h>
NEXT_WCHAR_H = <wchar.h>
OBJEXT = o
PACKAGE = gv
PACKAGE_BUGREPORT = 
PACKAGE_NAME = 
PACKAGE_STRING = 
PACKAGE_TARNAME = 
PACKAGE_URL = 
PACKAGE_VERSION = 
PAPERSIZE = A4
PATH_SEPARATOR = :
PRAGMA_SYSTEM_HEADER = #pragma GCC system_header
PRINT_COMMAND = lpr
PRIPTR_PREFIX = ""
PRI_MACROS_BROKEN = 0
PTRDIFF_T_SUFFIX = 
RANLIB = ranlib
REPLACE_BTOWC = 0
REPLACE_CANONICALIZE_FILE_NAME = 0
REPLACE_CHOWN = 0
REPLACE_CLOSE = 0
REPLACE_DUP = 0
REPLACE_DUP2 = 0
REPLACE_FCHOWNAT = 0
REPLACE_FSTAT = 0
REPLACE_FSTATAT = 0
REPLACE_FUTIMENS = 0
REPLACE_GETCWD = 0
REPLACE_GETGROUPS = 0
REPLACE_GETPAGESIZE = 0
REPLACE_GETTIMEOFDAY = 0
REPLACE_LCHOWN = 0
REPLACE_LINK = 0
REPLACE_LINKAT = 0
REPLACE_LOCALTIME_R = GNULIB_PORTCHECK
REPLACE_LSEEK = 0
REPLACE_LSTAT = 1
REPLACE_MBRLEN = 0
REPLACE_MBRTOWC = 0
REPLACE_MBSINIT = 0
REPLACE_MBSNRTOWCS = 0
REPLACE_MBSRTOWCS = 0
REPLACE_MBSTATE_T = 0
REPLACE_MKDIR = 0
REPLACE_MKFIFO = 0
REPLACE_MKNOD = 0
REPLACE_MKSTEMP = 0
REPLACE_MKTIME = GNULIB_PORTCHECK
REPLACE_NANOSLEEP = GNULIB_PORTCHECK
REPLACE_NULL = 0
REPLACE_PREAD = 0
REPLACE_PUTENV = 0
REPLACE_PWRITE = 0
REPLACE_READLINK = 0
REPLACE_REALPATH = 0
REPLACE_RMDIR = 0
REPLACE_SETENV = 0
REPLACE_SLEEP = 0
REPLACE_STAT = 0
REPLACE_STRTOD = 0
REPLACE_SYMLINK = 0
REPLACE_TIMEGM = GNULIB_PORTCHECK
REPLACE_TTYNAME_R = 0
REPLACE_UNLINK = 0
REPLACE_UNLINKAT = 0
REPLACE_UNSETENV = 0
REPLACE_USLEEP = 0
REPLACE_UTIMENSAT = 0
REPLACE_WCRTOMB = 0
REPLACE_WCSNRTOMBS = 0
REPLACE_WCSRTOMBS = 0
REPLACE_WCTOB = 0
REPLACE_WCWIDTH = 0
REPLACE_WRITE = 0
SAVE_DIR = ~/
SCRATCH_DIR = /tmp/
SET_MAKE = 
SHELL = /bin/bash
SIG_ATOMIC_T_SUFFIX = 
SIZE_T_SUFFIX = 
STDBOOL_H = 
STDDEF_H = 
STDINT_H = 
STRIP = 
SYS_TIME_H_DEFINES_STRUCT_TIMESPEC = 0
TIME_H_DEFINES_STRUCT_TIMESPEC = 1
UINT32_MAX_LT_UINTMAX_MAX = 1
UINT64_MAX_EQ_ULONG_MAX = 0
UNISTD_H_HAVE_WINSOCK2_H = 0
UNISTD_H_HAVE_WINSOCK2_H_AND_USE_SOCKETS = 0
USE_BACKING_PIXMAP = True
VERSION = 3.7.2
WCHAR_T_SUFFIX = 
WINT_T_SUFFIX = 
XMKMF = 
X_CFLAGS = 
X_EXTRA_LIBS = 
X_LIBS = 
X_PRE_LIBS =  -lSM -lICE
abs_builddir = /media/KINGSTON/gv-3.7.2
abs_srcdir = /media/KINGSTON/gv-3.7.2
abs_top_builddir = /media/KINGSTON/gv-3.7.2
abs_top_srcdir = /media/KINGSTON/gv-3.7.2
ac_ct_CC = gcc
am__include = include
am__leading_dot = .
am__quote = 
am__tar = ${AMTAR} chof - "$$tardir"
am__untar = ${AMTAR} xf -
bindir = ${exec_prefix}/bin
build = i686-pc-linux-gnu
build_alias = 
build_cpu = i686
build_os = linux-gnu
build_vendor = pc
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE}
dvidir = ${docdir}
exec_prefix = ${prefix}
gl_LIBOBJS =  getopt.o getopt1.o lstat.o tempname.o
gl_LTLIBOBJS =  getopt.lo getopt1.lo lstat.lo tempname.lo
gltests_LIBOBJS = 
gltests_LTLIBOBJS = 
gltests_WITNESS = IN_GV_GNULIB_TESTS
host = i686-pc-linux-gnu
host_alias = 
host_cpu = i686
host_os = linux-gnu
host_vendor = pc
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /media/KINGSTON/gv-3.7.2/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = /bin/mkdir -p
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /usr/local
program_transform_name = s,x,x,
psdir = ${docdir}
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = 
top_builddir = .
top_srcdir = .
ACLOCAL_AMFLAGS = -I m4
SUBDIRS = lib src doc
EXTRA_DIST = README.I18N README.TRANSLATION
all: all-recursive

.SUFFIXES:
am--refresh:
	@:
$(srcdir)/Makefile.in: # $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      echo ' cd $(srcdir) && $(AUTOMAKE) --gnu'; \
	      $(am__cd) $(srcdir) && $(AUTOMAKE) --gnu \
		&& exit 0; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --gnu Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --gnu Makefile
.PRECIOUS: Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    echo ' $(SHELL) ./config.status'; \
	    $(SHELL) ./config.status;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $@ $(am__depfiles_maybe)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $@ $(am__depfiles_maybe);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	$(SHELL) ./config.status --recheck

$(top_srcdir)/configure: # $(am__configure_deps)
	$(am__cd) $(srcdir) && $(AUTOCONF)
$(ACLOCAL_M4): # $(am__aclocal_m4_deps)
	$(am__cd) $(srcdir) && $(ACLOCAL) $(ACLOCAL_AMFLAGS)
$(am__aclocal_m4_deps):

# This directory's subdirectories are mostly independent; you can cd
# into them and run `make' without going through this Makefile.
# To change the values of `make' variables: instead of editing Makefiles,
# (1) if the variable is set in `config.status', edit `config.status'
#     (which will cause the Makefiles to be regenerated when you run `make');
# (2) otherwise, pass the desired values on the `make' command line.
$(RECURSIVE_TARGETS):
	@fail= failcom='exit 1'; \
	for f in x $$MAKEFLAGS; do \
	  case $$f in \
	    *=* | --[!k]*);; \
	    *k*) failcom='fail=yes';; \
	  esac; \
	done; \
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
	  ($(am__cd) $$subdir && $(MAKE) $(AM_MAKEFLAGS) $$local_target) \
	  || eval $$failcom; \
	done; \
	if test "$$dot_seen" = "no"; then \
	  $(MAKE) $(AM_MAKEFLAGS) "$$target-am" || exit 1; \
	fi; test -z "$$fail"

$(RECURSIVE_CLEAN_TARGETS):
	@fail= failcom='exit 1'; \
	for f in x $$MAKEFLAGS; do \
	  case $$f in \
	    *=* | --[!k]*);; \
	    *k*) failcom='fail=yes';; \
	  esac; \
	done; \
	dot_seen=no; \
	case "$@" in \
	  distclean-* | maintainer-clean-*) list='$(DIST_SUBDIRS)' ;; \
	  *) list='$(SUBDIRS)' ;; \
	esac; \
	rev=''; for subdir in $$list; do \
	  if test "$$subdir" = "."; then :; else \
	    rev="$$subdir $$rev"; \
	  fi; \
	done; \
	rev="$$rev ."; \
	target=`echo $@ | sed s/-recursive//`; \
	for subdir in $$rev; do \
	  echo "Making $$target in $$subdir"; \
	  if test "$$subdir" = "."; then \
	    local_target="$$target-am"; \
	  else \
	    local_target="$$target"; \
	  fi; \
	  ($(am__cd) $$subdir && $(MAKE) $(AM_MAKEFLAGS) $$local_target) \
	  || eval $$failcom; \
	done && test -z "$$fail"
tags-recursive:
	list='$(SUBDIRS)'; for subdir in $$list; do \
	  test "$$subdir" = . || ($(am__cd) $$subdir && $(MAKE) $(AM_MAKEFLAGS) tags); \
	done
ctags-recursive:
	list='$(SUBDIRS)'; for subdir in $$list; do \
	  test "$$subdir" = . || ($(am__cd) $$subdir && $(MAKE) $(AM_MAKEFLAGS) ctags); \
	done

ID: $(HEADERS) $(SOURCES) $(LISP) $(TAGS_FILES)
	list='$(SOURCES) $(HEADERS) $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	mkid -fID $$unique
tags: TAGS

TAGS: tags-recursive $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) \
		$(TAGS_FILES) $(LISP)
	set x; \
	here=`pwd`; \
	if ($(ETAGS) --etags-include --version) >/dev/null 2>&1; then \
	  include_option=--etags-include; \
	  empty_fix=.; \
	else \
	  include_option=--include; \
	  empty_fix=; \
	fi; \
	list='$(SUBDIRS)'; for subdir in $$list; do \
	  if test "$$subdir" = .; then :; else \
	    test ! -f $$subdir/TAGS || \
	      set "$$@" "$$include_option=$$here/$$subdir/TAGS"; \
	  fi; \
	done; \
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
CTAGS: ctags-recursive $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) \
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

distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH tags

distdir: $(DISTFILES)
	$(am__remove_distdir)
	test -d "$(distdir)" || mkdir "$(distdir)"
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
	@list='$(DIST_SUBDIRS)'; for subdir in $$list; do \
	  if test "$$subdir" = .; then :; else \
	    test -d "$(distdir)/$$subdir" \
	    || $(MKDIR_P) "$(distdir)/$$subdir" \
	    || exit 1; \
	  fi; \
	done
	@list='$(DIST_SUBDIRS)'; for subdir in $$list; do \
	  if test "$$subdir" = .; then :; else \
	    dir1=$$subdir; dir2="$(distdir)/$$subdir"; \
	    $(am__relativize); \
	    new_distdir=$$reldir; \
	    dir1=$$subdir; dir2="$(top_distdir)"; \
	    $(am__relativize); \
	    new_top_distdir=$$reldir; \
	    echo " (cd $$subdir && $(MAKE) $(AM_MAKEFLAGS) top_distdir="$$new_top_distdir" distdir="$$new_distdir" \\"; \
	    echo "     am__remove_distdir=: am__skip_length_check=: am__skip_mode_fix=: distdir)"; \
	    ($(am__cd) $$subdir && \
	      $(MAKE) $(AM_MAKEFLAGS) \
	        top_distdir="$$new_top_distdir" \
	        distdir="$$new_distdir" \
		am__remove_distdir=: \
		am__skip_length_check=: \
		am__skip_mode_fix=: \
	        distdir) \
	      || exit 1; \
	  fi; \
	done
	-test -n "$(am__skip_mode_fix)" \
	|| find "$(distdir)" -type d ! -perm -755 \
		-exec chmod u+rwx,go+rx {} \; -o \
	  ! -type d ! -perm -444 -links 1 -exec chmod a+r {} \; -o \
	  ! -type d ! -perm -400 -exec chmod a+r {} \; -o \
	  ! -type d ! -perm -444 -exec $(install_sh) -c -m a+r {} {} \; \
	|| chmod -R a+r "$(distdir)"
dist-gzip: distdir
	tardir=$(distdir) && $(am__tar) | GZIP=$(GZIP_ENV) gzip -c >$(distdir).tar.gz
	$(am__remove_distdir)

dist-bzip2: distdir
	tardir=$(distdir) && $(am__tar) | bzip2 -9 -c >$(distdir).tar.bz2
	$(am__remove_distdir)

dist-lzma: distdir
	tardir=$(distdir) && $(am__tar) | lzma -9 -c >$(distdir).tar.lzma
	$(am__remove_distdir)

dist-xz: distdir
	tardir=$(distdir) && $(am__tar) | xz -c >$(distdir).tar.xz
	$(am__remove_distdir)

dist-tarZ: distdir
	tardir=$(distdir) && $(am__tar) | compress -c >$(distdir).tar.Z
	$(am__remove_distdir)

dist-shar: distdir
	shar $(distdir) | GZIP=$(GZIP_ENV) gzip -c >$(distdir).shar.gz
	$(am__remove_distdir)

dist-zip: distdir
	-rm -f $(distdir).zip
	zip -rq $(distdir).zip $(distdir)
	$(am__remove_distdir)

dist dist-all: distdir
	tardir=$(distdir) && $(am__tar) | GZIP=$(GZIP_ENV) gzip -c >$(distdir).tar.gz
	$(am__remove_distdir)

# This target untars the dist file and tries a VPATH configuration.  Then
# it guarantees that the distribution is self-contained by making another
# tarfile.
distcheck: dist
	case '$(DIST_ARCHIVES)' in \
	*.tar.gz*) \
	  GZIP=$(GZIP_ENV) gzip -dc $(distdir).tar.gz | $(am__untar) ;;\
	*.tar.bz2*) \
	  bzip2 -dc $(distdir).tar.bz2 | $(am__untar) ;;\
	*.tar.lzma*) \
	  lzma -dc $(distdir).tar.lzma | $(am__untar) ;;\
	*.tar.xz*) \
	  xz -dc $(distdir).tar.xz | $(am__untar) ;;\
	*.tar.Z*) \
	  uncompress -c $(distdir).tar.Z | $(am__untar) ;;\
	*.shar.gz*) \
	  GZIP=$(GZIP_ENV) gzip -dc $(distdir).shar.gz | unshar ;;\
	*.zip*) \
	  unzip $(distdir).zip ;;\
	esac
	chmod -R a-w $(distdir); chmod a+w $(distdir)
	mkdir $(distdir)/_build
	mkdir $(distdir)/_inst
	chmod a-w $(distdir)
	test -d $(distdir)/_build || exit 0; \
	dc_install_base=`$(am__cd) $(distdir)/_inst && pwd | sed -e 's,^[^:\\/]:[\\/],/,'` \
	  && dc_destdir="$${TMPDIR-/tmp}/am-dc-$$$$/" \
	  && am__cwd=`pwd` \
	  && $(am__cd) $(distdir)/_build \
	  && ../configure --srcdir=.. --prefix="$$dc_install_base" \
	    $(DISTCHECK_CONFIGURE_FLAGS) \
	  && $(MAKE) $(AM_MAKEFLAGS) \
	  && $(MAKE) $(AM_MAKEFLAGS) dvi \
	  && $(MAKE) $(AM_MAKEFLAGS) check \
	  && $(MAKE) $(AM_MAKEFLAGS) install \
	  && $(MAKE) $(AM_MAKEFLAGS) installcheck \
	  && $(MAKE) $(AM_MAKEFLAGS) uninstall \
	  && $(MAKE) $(AM_MAKEFLAGS) distuninstallcheck_dir="$$dc_install_base" \
	        distuninstallcheck \
	  && chmod -R a-w "$$dc_install_base" \
	  && ({ \
	       (cd ../.. && umask 077 && mkdir "$$dc_destdir") \
	       && $(MAKE) $(AM_MAKEFLAGS) DESTDIR="$$dc_destdir" install \
	       && $(MAKE) $(AM_MAKEFLAGS) DESTDIR="$$dc_destdir" uninstall \
	       && $(MAKE) $(AM_MAKEFLAGS) DESTDIR="$$dc_destdir" \
	            distuninstallcheck_dir="$$dc_destdir" distuninstallcheck; \
	      } || { rm -rf "$$dc_destdir"; exit 1; }) \
	  && rm -rf "$$dc_destdir" \
	  && $(MAKE) $(AM_MAKEFLAGS) dist \
	  && rm -rf $(DIST_ARCHIVES) \
	  && $(MAKE) $(AM_MAKEFLAGS) distcleancheck \
	  && cd "$$am__cwd" \
	  || exit 1
	$(am__remove_distdir)
	@(echo "$(distdir) archives ready for distribution: "; \
	  list='$(DIST_ARCHIVES)'; for i in $$list; do echo $$i; done) | \
	  sed -e 1h -e 1s/./=/g -e 1p -e 1x -e '$$p' -e '$$x'
distuninstallcheck:
	@$(am__cd) '$(distuninstallcheck_dir)' \
	&& test `$(distuninstallcheck_listfiles) | wc -l` -le 1 \
	   || { echo "ERROR: files left after uninstall:" ; \
	        if test -n "$(DESTDIR)"; then \
	          echo "  (check DESTDIR support)"; \
	        fi ; \
	        $(distuninstallcheck_listfiles) ; \
	        exit 1; } >&2
distcleancheck: distclean
	@if test '$(srcdir)' = . ; then \
	  echo "ERROR: distcleancheck can only run from a VPATH build" ; \
	  exit 1 ; \
	fi
	@test `$(distcleancheck_listfiles) | wc -l` -eq 0 \
	  || { echo "ERROR: files left in build directory after distclean:" ; \
	       $(distcleancheck_listfiles) ; \
	       exit 1; } >&2
check-am: all-am
check: check-recursive
all-am: Makefile
installdirs: installdirs-recursive
installdirs-am:
install: install-recursive
install-exec: install-exec-recursive
install-data: install-data-recursive
uninstall: uninstall-recursive

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-recursive
install-strip:
	$(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	  install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	  `test -z '$(STRIP)' || \
	    echo "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'"` install
mostlyclean-generic:

clean-generic:

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-recursive

clean-am: clean-generic mostlyclean-am

distclean: distclean-recursive
	-rm -f $(am__CONFIG_DISTCLEAN_FILES)
	-rm -f Makefile
distclean-am: clean-am distclean-generic distclean-tags

dvi: dvi-recursive

dvi-am:

html: html-recursive

html-am:

info: info-recursive

info-am:

install-data-am:

install-dvi: install-dvi-recursive

install-dvi-am:

install-exec-am:

install-html: install-html-recursive

install-html-am:

install-info: install-info-recursive

install-info-am:

install-man:

install-pdf: install-pdf-recursive

install-pdf-am:

install-ps: install-ps-recursive

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-recursive
	-rm -f $(am__CONFIG_DISTCLEAN_FILES)
	-rm -rf $(top_srcdir)/autom4te.cache
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-recursive

mostlyclean-am: mostlyclean-generic

pdf: pdf-recursive

pdf-am:

ps: ps-recursive

ps-am:

uninstall-am:

.MAKE: $(RECURSIVE_CLEAN_TARGETS) $(RECURSIVE_TARGETS) ctags-recursive \
	install-am install-strip tags-recursive

.PHONY: $(RECURSIVE_CLEAN_TARGETS) $(RECURSIVE_TARGETS) CTAGS GTAGS \
	all all-am am--refresh check check-am clean clean-generic \
	ctags ctags-recursive dist dist-all dist-bzip2 dist-gzip \
	dist-lzma dist-shar dist-tarZ dist-xz dist-zip distcheck \
	distclean distclean-generic distclean-tags distcleancheck \
	distdir distuninstallcheck dvi dvi-am html html-am info \
	info-am install install-am install-data install-data-am \
	install-dvi install-dvi-am install-exec install-exec-am \
	install-html install-html-am install-info install-info-am \
	install-man install-pdf install-pdf-am install-ps \
	install-ps-am install-strip installcheck installcheck-am \
	installdirs installdirs-am maintainer-clean \
	maintainer-clean-generic mostlyclean mostlyclean-generic pdf \
	pdf-am ps ps-am tags tags-recursive uninstall uninstall-am


# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
