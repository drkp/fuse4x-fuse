## Process this file with automake to produce Makefile.in

AM_CPPFLAGS = -I$(top_srcdir)/include -D_FILE_OFFSET_BITS=64 -D_REENTRANT
noinst_HEADERS = fioc.h
noinst_PROGRAMS = null hello hello_ll

LDADD = ../lib/libfuse4x.la @libfuse_libs@
