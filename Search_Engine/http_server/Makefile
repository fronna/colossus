FLAG=-std=c++11 -lpthread -I ../../../cppjieba/include

http_server:http_server.cc ../searcher/libsearcher.so
	g++ http_server.cc ../searcher/libsearcher.so -o http_server $(FLAG)
