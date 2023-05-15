calc.out : main.o add.o mul.o sub.o
	gcc -o calc.out main.o add.o mul.o sub.o
main.o: main.c
	gcc -c main.c
add.o: add.c
	gcc -c add.c
sub.o: sub.c
	gcc -c sub.c
mul.o: mul.c
	gcc -c mul.c	
clean:
	rm *.out *.o

