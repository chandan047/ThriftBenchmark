# ThriftBenchmark

run c++ client:

$: g++ -o client client.cpp gen-cpp/*.cpp -std=c++11 -I gen-cpp -lboost_system -lpthread -lthrift

$: ./client



run node.js client:

$: npm install microseconds

$: npm install thrift

$: nodejs client.js



run c++ server:

$: g++ -o server server.cpp gen-cpp/*.cpp -std=c++11 -I gen-cpp -lboost_system -lpthread -lthrift

$: ./server
