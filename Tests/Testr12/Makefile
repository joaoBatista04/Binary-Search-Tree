FLAGS = -Wall -Wno-unused-result

DEPS = vector.h binary_tree.h
OBJ = vector.c binary_tree.c testr-12-main.c

%.o: %.c $(DEPS)
	gcc -g -c -o $@ $< $(FLAGS)

all: $(OBJ)
	gcc -g -o main $(OBJ) $(FLAGS)

clean:
	rm -f main *.o

run: 
	./main