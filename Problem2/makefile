CFLAGS = -g -Wall --pedantic-errors -O2

default: prob2
prob2: prob2.cpp
	g++ ${CFLAGS} prob2.cpp -o problem2
.PHONY: clean
clean:
	-@rm -f problem2
.PHONY: debug
debug: CFLAGS = -g -fsanitize=address -fno-omit-frame-pointer
debug: prob2