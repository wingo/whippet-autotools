AC_PREREQ([2.69])
AC_INIT([whippet-autotools-example],[0.1.0])
AC_CONFIG_SRCDIR([whippet/benchmarks/mt-gcbench.c])
AC_CONFIG_AUX_DIR([build-aux])
AC_CONFIG_MACRO_DIRS([m4 whippet])
AM_INIT_AUTOMAKE([subdir-objects foreign])

WHIPPET_ENABLE_LTO

LT_INIT

WARN_CFLAGS=-Wall
AC_ARG_ENABLE([Werror],
  AS_HELP_STRING([--disable-Werror],
                 [Don't stop the build on errors]),
  [],
  WARN_CFLAGS="-Wall -Werror")
CFLAGS="$CFLAGS $WARN_CFLAGS"

WHIPPET_PKG

AC_CONFIG_FILES(Makefile)
AC_OUTPUT
