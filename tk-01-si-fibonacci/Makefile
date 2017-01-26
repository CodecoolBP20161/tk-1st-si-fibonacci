CC = gcc

fib_calc.o : fib_calc.c fib_calc.h
	$(CC) -c fib_calc.c -g
	
main.o : main.c fib_calc.h
	$(CC) -c main.c -g

all : main.o fib_calc.o
	$(CC) -o fib main.o fib_calc.o