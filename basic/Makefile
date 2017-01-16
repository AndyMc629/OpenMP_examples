CXX := gcc

ARCH := x86-64

CFLAGS := -march=$(ARCH) -O3 -fopenmp -m64 -std=c++11

COMPILE_COMMAND := $(CXX) $(CFLAGS)

OUTPUT := basic

all: basic ; $(COMPILE_COMMAND) -o $(OUTPUT) basic.cpp

clean: ; rm -f *.o $(OUTPUT).*
