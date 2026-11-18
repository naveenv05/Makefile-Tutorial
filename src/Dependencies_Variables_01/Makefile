OBJ_FILES = main.o message.o

test: $(OBJ_FILES)
	gcc $^ -o test

%.o: %.c
	gcc -c $^

run: test
	@./test

clean:
	rm -f *.o
	rm -f test
