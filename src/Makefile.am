lib_LTLIBRARIES = liboldX.la

liboldX_la_SOURCES = \ 
         XCrAssoc.c \
         XDelAssoc.c \
         XDestAssoc.c \
         XDraw.c \
         XLookAssoc.c \
         XMakeAssoc.c

INCLUDES = -I$(top_srcdir)/include/X11


liboldX_la_LIBADD = @DEP_LIBS@
liboldX_la_CFLAGS = @DEP_CFLAGS@

liboldX_la_LDFLAGS = -version-info 7:0:0 -no-undefined


liboldXincludedir = $(includedir)/X11
liboldXinclude_HEADERS = \
    $(top_srcdir)/include/X11/X10.h

