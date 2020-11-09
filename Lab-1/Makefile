SRC = main.c main.h
CC = gcc
OUTPUT = main
LIBS = -lpthread
FLAGS = -std=c99 -D_GNU_SOURCE
all: 
	$(CC) $(FLAGS) -o $(OUTPUT) $(SRC) $(LIBS) 

clean:
	rm -f main *.o