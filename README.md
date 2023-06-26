# story2imgs

### compile proto
    pip install protobuf
    cd ./model_grpc
    protoc --python_out=. model_server.proto 
    # also need to compile model_server_pb2_grpc.py       