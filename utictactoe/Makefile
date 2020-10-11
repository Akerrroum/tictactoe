CC=gcc
CFLAGS=-Wall -O
CPPFLAGS=
LDFLAGS=
EXEC=utictactoe
src=src/


all: $(EXEC)

utictactoe: utictactoe.o
			$(CC) -o utictactoe $(src)utictactoe.o $(LDFLAGS)

utictactoe.o: $(src)utictactoe.c
			$(CC) -o $(src)utictactoe.o -c $(src)utictactoe.c $(CFLAGS)

.PHONY: clean 

clean:
		rm -f *.o $(src)*.o core
		rm -rf $(EXEC)		
help: 
	@echo " Help to do "