SRC := $(wildcard *.c)
OBJ := $(patsubst %.c, %.o, $(SRC))
final : $(OBJ)
	gcc -o $@ $^ -Wall -lm
clean :
	rm *.o *.out 
