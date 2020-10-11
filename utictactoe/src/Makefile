CC=gcc
CFLAGS=-Wall -O
CPPFLAGS=
LDFLAGS=
EXEC=utictactoe


all: $(EXEC)

utictactoe: utictactoe.o
			$(CC) -o utictactoe utictactoe.o $(LDFLAGS)

utictactoe.o: utictactoe.c
			$(CC) -o utictactoe.o -c utictactoe.c $(CFLAGS)

.PHONY: clean 

clean:
		rm -f *.o core
		rm -rf $(EXEC)		
help: 
	@echo " Help to do "