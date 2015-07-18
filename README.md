To compile thrift file
` thrift --gen cpp hello.thrift`

to compile server
`g++ gen-cpp/hello_types.cpp gen-cpp/HelloSvc.cpp server.cpp -o server -lthrift`

to compile client
`g++ gen-cpp/hello_types.cpp gen-cpp/HelloSvc.cpp client.cpp -o client -lthrift`

