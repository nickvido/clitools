CC = gcc
OBJS = oldschool.o
LDLIBS = -lcurses
PROG = oldschool

all: $(PROG)

$(PROG): $(OBJS)
	$(CC) $(OBJS) -o $@ $(LDLIBS)

oldschool.o: oldschool.c
    
clean:
	rm -f $(PROG) $(OBJS) 
