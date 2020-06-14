
.PHONY: all debug release clean

all: debug release

debug: TCP-dbg

TCP-dbg: TCP.cpp
	g++ -g -O0 TCP.cpp -o TCP-dbg -Wall

release: TCP

TCP: TCP.cpp
	g++ -O2 TCP.cpp -o TCP -DNDEBUG -Wall

clean:
	rm -f TCP TCP-dbg

