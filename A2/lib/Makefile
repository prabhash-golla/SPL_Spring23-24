SHELL = /bin/bash
CC = gcc

library : all
	ar rcs librecrel.a ./order1/soln1.o ./order2/soln2.o ./order3/soln3.o

all:
	cd order1; make
	cd order2; make
	cd order3; make

clean:
	cd order1; make clean
	cd order2; make clean
	cd order3; make clean

distclean:
	rm -r librecrel.a