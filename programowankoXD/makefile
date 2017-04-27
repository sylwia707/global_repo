CC = gcc -Wall

all: main.o hello.o
	$(CC) main.o hello.o -o plic

main.o: main.c
	$(CC) main.c -c -o main.o

hello.o: hello.c hello.h
	$(CC) hello.c -c -o hello.o

clean: 
	rm *.o plic
