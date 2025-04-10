noinst_LTLIBRARIES =
WHIPPET_EMBEDDER_CPPFLAGS = -include $(srcdir)/whippet/benchmarks/mt-gcbench-embedder.h
include whippet/embed.am

noinst_PROGRAMS = whippet/benchmarks/mt-gcbench
whippet_benchmarks_mt_gcbench_SOURCES = \
  whippet/benchmarks/mt-gcbench.c \
  whippet/benchmarks/mt-gcbench-types.h \
  whippet/benchmarks/simple-tagging-scheme.h \
  whippet/benchmarks/simple-gc-embedder.h \
  whippet/benchmarks/simple-roots-api.h \
  whippet/benchmarks/simple-roots-types.h \
  whippet/benchmarks/simple-allocator.h \
  whippet/benchmarks/heap-objects.h \
  whippet/benchmarks/mt-gcbench-embedder.h

AM_CFLAGS = $(WHIPPET_CPPFLAGS) $(WHIPPET_CFLAGS) $(WHIPPET_TO_EMBEDDER_CPPFLAGS)
LDADD = libwhippet.la
