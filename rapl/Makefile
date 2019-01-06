CC = g++
CFLAGS = -O2 -Wall -std=c++11
LFLAGS = -lm

all:	rapl

rapl:	rapl.o
	$(CC) $(LFLAGS) -o rapl rapl.o

rapl.o:	rapl.cpp
	$(CC) $(CFLAGS) -c rapl.cpp

clean:
	rm -f *.o *~ rapl
