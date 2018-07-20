all: oldschool

oldschool: oldschool.o
	gcc -lncurses -o oldschool oldschool.o
oldschool.o: oldschool.c
	gcc -lncurses -c oldschool.c
    
clean:
	rm oldschool oldschool.o
