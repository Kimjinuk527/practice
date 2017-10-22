CC = gcc
CFLAGS = -g -Wall -I../include
OUTPUT = libfuncs.a
OBJFILES = foo1.o foo2.o
.SUFFIXES: .o .c

.PHONY: clean

$(OUTPUT): $(OBJFILES)
	ar rv $(OUTPUT) $(OBJFILES)

#%.o: %.c
#	$(CC) $(CFLAGS) -c $< -o $@

clean:
	rm *.o $(OUTPUT)
