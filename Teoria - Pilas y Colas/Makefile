###############################################################################
# Makefile
###############################################################################

SRC = $(wildcard *.c *.cc *.cpp)
EXE = $(basename $(SRC))

CXXFLAGS = -std=c++11 -w

###############################################################################

default: $(EXE)

all: default

clean:
	$(RM) -fv $(EXE) core.* *~

###############################################################################

.PHONY: all clean default
.NOEXPORT:

###############################################################################