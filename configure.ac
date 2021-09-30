AC_PREREQ([2.69])
AC_INIT([libmilter], [1.0.2], [jon@wroth.org])
AM_INIT_AUTOMAKE
AC_CONFIG_SRCDIR([main.c])
AC_CONFIG_MACRO_DIR([m4])
AC_DISABLE_STATIC
AC_SUBST([milter_ltver])

# Checks for programs.
AC_PROG_CC
AC_PROG_LIBTOOL
LT_INIT

# Checks for libraries.

# Checks for header files.
AC_CHECK_HEADERS([arpa/inet.h fcntl.h stdlib.h string.h sys/socket.h sys/time.h unistd.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_CHECK_HEADER_STDBOOL
AC_TYPE_SIZE_T
AC_TYPE_SSIZE_T

#AC_DEFINE([_FFR_WORKERS_POOL], [1], [Enable FFR Workers Pool])
#AC_DEFINE([SM_CONF_POLL], [1], [Use poll() instead of select()])
#AC_DEFINE([MAX_WORKERS], [10], [Set maximum workers])
#AC_DEFINE([MIN_WORKERS], [2], [Set minimum workers])
#AC_DEFINE([MIN_IDLE], [1], [Set minimum idle workers])
#CFLAGS="-g3 -O0"
#CFLAGS="-O3"

# Checks for library functions.
AC_FUNC_MALLOC
AC_FUNC_REALLOC
AC_CHECK_FUNCS([atexit gethostbyname gethostname gettimeofday isascii memmove memset select socket strcasecmp strchr strdup strncasecmp strpbrk strrchr])

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
