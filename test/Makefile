test: test.cpp
	#gcc -o test test.cpp -lpthread -lm  -lleveldb -I../include -L../out-shared
	g++ -pthread -I. -I../include -std=c++0x -fno-builtin-memcmp -pthread -g2 test.cpp -L../out-shared -lleveldb -o test
