AUTOMAKE_OPTIONS=foreign
AM_CPPFLAGS =-I./jerasure/jerasure/include\
       -I./jerasure/gf-complete/include

AM_CFLAGS = -O3 $(SIMD_FLAGS) -fPIC -Wsign-compare

LDADD= jerasure/libJerasure.a
noinst_LTLIBRARIES = libErasure.a
libErasure_a_SOURCES = erasure_code.h erasure_code.cpp


SUBDIRS = jerasure
