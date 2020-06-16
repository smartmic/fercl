ACLOCAL_AMFLAGS = -I m4
EXTRA_DIST = m4/gnulib-cache.m4
SUBDIRS = lib

# libsodium dependency is handled by AC_SEARCH_LIBS (assumes
# installation in standard location for libraries).  If it fails or
# alternatively, use pkg-config to find the library:
#
#AM_CFLAGS=`pkg-config --cflags libsodium`
#AM_LDFLAGS=`pkg-config --libs libsodium`

bin_PROGRAMS = src/fercl
src_fercl_SOURCES = src/fercl.c
src_fercl_CPPFLAGS = -I$(top_builddir)/lib -I$(top_srcdir)/lib
src_fercl_LDADD = lib/libgnu.a 
