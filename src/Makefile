.PHONY = all clean

CC=gcc
CFLAGS= -Wall

all: server client
	
server: server.cpp
	g++ -pthread server.cpp -o server  $(CFLAGS)
	
client: client.cpp
	g++ -pthread client.cpp -o client  $(CFLAGS)
	
clean:
	rm -rvf server client