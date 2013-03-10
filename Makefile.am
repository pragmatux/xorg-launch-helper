
EXTRA_DIST = AUTHORS COPYING INSTALL

AM_CFLAGS = $(LIBSYSTEMD_DAEMON_CFLAGS) -Wall -Wno-uninitialized

bin_PROGRAMS = xorg-launch-helper
xorg_launch_helper_SOURCES = src/main.c
xorg_launch_helper_LDADD = $(LIBSYSTEMD_DAEMON_LIBS)

