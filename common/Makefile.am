###############################################################################
###############################################################################
##
##  Copyright (C) 2009-2019 Red Hat, Inc.
##  
##  This copyrighted material is made available to anyone wishing to use,
##  modify, copy, or redistribute it subject to the terms and conditions
##  of the GNU General Public License v.2.
##
###############################################################################
###############################################################################

MAINTAINERCLEANFILES	 = Makefile.in

noinst_LTLIBRARIES	 = libfence_virt.la

libfence_virt_la_SOURCES = mcast.c ip_lookup.c simple_auth.c tcp.c \
			   debug.c fdops.c log.c

libfence_virt_la_CFLAGS	 = $(AM_CFLAGS) $(nss_CFLAGS)

libfence_virt_la_LDFLAGS = $(AM_LDFLAGS) $(COMMON_LDFLAGS)

libfence_virt_la_LIBADD	 = $(nss_LIBS)
