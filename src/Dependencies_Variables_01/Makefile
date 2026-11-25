SRC_FILES = main.c message.c
OBJ_FILES = $(SRC_FILES:%.c=%.o)

$(info $(OBJ_FILES))

test: $(OBJ_FILES)
	gcc $^ -o $@

%.o: %.c
	gcc -c $^

run: test
	@./test

clean:
	rm -f *.o
	rm -f test
