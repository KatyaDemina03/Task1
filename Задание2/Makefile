start: compile run delete

compile: 
	g++ -c main.c  -o main.o
	g++ -c funcs.c -o funcs.o
	g++ main.o -o main

run: main
	./main

delete: 
	rm -f *.o
	rm main
