CC=gcc
CFLAGS=-Wall -Werror -g
OBJS=glab.o Graph.o Queue.o Stack.o PQueue.o

glab : $(OBJS)
	$(CC) -o glab $(OBJS)

glab.o : glab.c Graph.h

Graph.o : Graph.c Graph.h Queue.h
Queue.o : Queue.c Queue.h Item.h
Stack.o : Stack.c Stack.h Item.h
PQueue.o : PQueue.c PQueue.h Item.h

clean :
	rm -f glab $(OBJS) core *.dSYM
