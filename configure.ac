dnl Standard configure.ac
AC_PREREQ([2.71])
AC_INIT([t2mc],[0.1.0],[manutalcual@gmail.com])
AC_CONFIG_AUX_DIR([build-aux])
AM_INIT_AUTOMAKE([foreign dist-bzip2])
AM_CONFIG_HEADER([config.h:config.in])
AC_CONFIG_SRCDIR([src/main.cc])

AC_CONFIG_MACRO_DIR([m4])

dnl Checks for programs.
AC_PROG_CXX
dnl AC_PROG_CC
dnl AC_PROG_LIBTOOL

CXXFLAGS="-Wall -g -O0 -std=c++20 -Wall -Wextra -pedantic"

dnl Checks for typedefs, structures, and compiler characteristics.
dnl AC_ARG_WITH([categoria],
dnl
dnl 	AS_HELP_STRING([--with-categoria=CAT],[dnl 	Definir categoria de log]),
dnl 	[categoria=$withval], [LOG_CATEGORIA=DEBUG])

dnl if test "$categoria" != ""; then
dnl 	CXXFLAGS="$CXXFLAGS -DLOG_CATEGORIA=\\"$categoria\\""
dnl fi


dnl AM_CONDITIONAL([FEATURE], [test "$the_feature" != ""])
dnl AC_DEFUN([AC_MSG_SUMMARY], [echo $1])
dnl AC_DEFUN([WITH], [dnl
dnl if test $${2_FALSE} ; then
dnl 	echo $1: enabled
dnl else
dnl 	echo $1: disabled
dnl fi
dnl ])
dnl
dnl AC_MSG_SUMMARY(------------------)
dnl AC_MSG_SUMMARY(  FEATURES:)
dnl AC_MSG_SUMMARY(------------------)
dnl WITH([feature  ], FEATURE)
dnl AC_MSG_SUMMARY(------------------)
dnl
dnl Checks for library functions.

dnl AC_SUBST(CPPFLAGS)
dnl AC_SUBST(LDFLAGS)
CFLAGS="-Wall -g $CFLAGS"

AC_SUBST(CFLAGS)
AC_CONFIG_FILES([Makefile src/Makefile])
AC_OUTPUT
