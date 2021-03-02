// Proto
helloworld.proto 



Steps.
1 - Generate the grpc-files
$ python3 -m grpc_tools.protoc -I. --python_out=. --grpc_python_out=. ./helloworld.proto
 will generate the following files:
    // Generated files
    helloworld_pb2.py 
    helloworld_pb2_grpc.py


2 - create the server and client files.
    greeter_client.py 
    greeter_server.py 
