noinst_LTLIBRARIES =
WHIPPET_EMBEDDER_CPPFLAGS = -include whippet/benchmarks/mt-gcbench-embedder.h
include whippet/embed.am

noinst_PROGRAMS = whippet/benchmarks/mt-gcbench

AM_CFLAGS = $(WHIPPET_CPPFLAGS) $(WHIPPET_CFLAGS) $(WHIPPET_TO_EMBEDDER_CPPFLAGS)
LDADD = libwhippet.la
