CFLAGS +=-m32
LDFLAGS += -m32
INCLUDE_PATH    := ./ ../external/include/ ../common/
SOURCE_PATH     := ./ ../common/
DEPENDENCY_PATH := dep
OBJECT_PATH     := obj

EXTERNAL_LIBS := $(wildcard ../external/lib/*.a)
LDLIBS := -lm -lpthread


CFLAGS += -O3

include ../makefile.mk
