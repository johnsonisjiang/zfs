include $(top_srcdir)/config/Rules.am

DEFAULT_INCLUDES += \
	-I$(top_srcdir)/include \
	-I$(top_srcdir)/lib/libspl/include

lib_LTLIBRARIES = libdiskmgt.la

libdiskmgt_la_SOURCES = \
	libdiskmgt.c

#libzfs_core_la_LIBADD = \
#	$(top_builddir)/lib/libnvpair/libnvpair.la

libdiskmgt_la_LDFLAGS = -version-info 1:0:0

EXTRA_DIST = $(USER_C)
