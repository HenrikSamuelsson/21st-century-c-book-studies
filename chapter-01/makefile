CC     = gcc
CFLAGS = -g -Wall -O3
RM     = rm -f

default: all

all: Hello

Hello: hello.c
	$(CC) $(CLFAGS) -o Hello hello.c

clean veryclean:
	$(RM) Hello