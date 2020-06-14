
.PHONY: all debug release clean

all: debug release

debug: UDP-dbg

UDP-dbg: UDP.cpp
	g++ -g -O0 UDP.cpp -o UDP-dbg -Wall

release: UDP

UDP: UDP.cpp
	g++ -O2 UDP.cpp -o UDP -DNDEBUG -Wall

clean:
	rm -f UDP UDP-dbg

