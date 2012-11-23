VERSION=1.0
DATE=$(shell date)

CC=clang
CFLAGS= -Wall -g\
		-DCOMPILE_TIME="\"$(DATE)\""\
		-DVERSION="\"$(VERSION)\""

all: tee.c
	$(CC) $(CFLAGS) tee.c -o ../../bin/tee
