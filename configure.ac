AC_INIT(substring-frequencies,1.0.0)
AM_INIT_AUTOMAKE([-Wall -Werror foreign subdir-objects])

AM_MAINTAINER_MODE([enable])

m4_ifdef([AM_SILENT_RULES], [AM_SILENT_RULES([yes])])

AC_CONFIG_MACRO_DIR([m4])

AC_PROG_CC
AC_PROG_CXX
AC_PROG_INSTALL
AC_PROG_MAKE_SET
AC_PROG_RANLIB
AM_PROG_AR

AC_SUBST(PACKAGES_CFLAGS)
AC_SUBST(PACKAGES_LIBS)

AC_C_CONST
AC_C_INLINE
AC_DEFINE(INLINE, [inline], [for inline])
AC_DEFINE(PROJECT_VERSION_FULL, [PACKAGE_VERSION], [Define to the version of this package.])

AC_LANG_PUSH([C++])
AX_CXX_COMPILE_STDCXX_14([noext])
AC_LANG_POP([C++])

AC_OUTPUT(Makefile)
