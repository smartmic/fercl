#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([fercl], [0.1], [dev@famic.de])
AM_INIT_AUTOMAKE([subdir-objects])
AC_CONFIG_SRCDIR([src/fercl.c])
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_MACRO_DIRS([m4])

# Checks for programs.
AC_PROG_CC
gl_EARLY

# Checks for libraries.
AC_SEARCH_LIBS([sodium_init],[sodium])

# Checks for header files.
AC_CHECK_HEADERS([stdio.h stdlib.h string.h stdbool.h errno.h unistd.h sodium.h])

# Initialize Gnulib.
gl_INIT

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

AC_CONFIG_FILES([Makefile lib/Makefile])

AC_OUTPUT
