CFLAGS += -Wall
CC = gcc

all: server client

server: server.c common.h
	$(CC) $(CFLAGS) server.c -lrt -o server

client: client.c common.h
	$(CC) $(CFLAGS) client.c -lrt -o client

clean:
	-rm -rf *.o server client
