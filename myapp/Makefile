CC = gcc
CFLAGS = -g -Wall

.PHONY: all clean

all:
	$(CC) $(CFLAGS) -c -I../include main.c -o main.o
	$(CC) -o main -L../lib main.o -lfuncs

clean:
	rm *.o
