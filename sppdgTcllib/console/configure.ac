#----------------------------------------------------------------
#
#  configure.ac
#
#  Autoconf source file for the Console package wrapped
#  around Tkcon.
#
#  This file, along with aclocal, autoconf, Makefile.am,
#  and automake can produce a highly functional configuration
#  script and Makefile.
#
#  Bob Techentin
#  January 22, 2004
#  Copyright 2004 Mayo Foundation.  All Rights Reserved
#
#  $Id: configure.ac,v 1.3 2004/02/10 15:58:02 techenti Exp $
#
#----------------------------------------------------------------


#----------------------------------------------------------------
#  Declare the package name and version.
#  All the bouquets and brickbats go to Bob. :-)
#----------------------------------------------------------------
AC_INIT([console],[1.1],[techentin.robert@mayo.edu])

#----------------------------------------------------------------
#  Give autoconf a point of reference, and tell it that
#  we're going to use automake later.
#----------------------------------------------------------------
AC_CONFIG_SRCDIR
AM_INIT_AUTOMAKE


#----------------------------------------------------------------
#  Don't bother checking for host type, libraries, or
#  header file variations, as we're just dealing
#  with highly portable scripts at this level.
#----------------------------------------------------------------

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
