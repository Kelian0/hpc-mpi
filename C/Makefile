
###----------------------------------------------------------------------------
CC=gcc 
LIB=-lm 
CFLAGS=-O3

all: convol

convol: convol.c rasterfile.h 
	${CC} ${CFLAGS} -o $@ $< ${LIB} 

clean: 
	rm -f convol *~ *.o 




