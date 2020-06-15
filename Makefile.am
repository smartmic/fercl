ACLOCAL_AMFLAGS = -I m4
EXTRA_DIST = m4/gnulib-cache.m4
SUBDIRS = lib

bin_PROGRAMS = src/fercl
src_fercl_SOURCES = src/fercl.c
src_fercl_CPPFLAGS = -I$(top_builddir)/lib -I$(top_srcdir)/lib
src_fercl_LDADD = lib/libgnu.a
