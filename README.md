# Story 2 images

### <b> strcture <b>

##### 1. find characters traits 
        1. use NER to find the main characters first appear 
        2. use SUMMARY to summary sentences between character +-$long 
        3. use VICUNA to generate prompts about characters' physical look

##### 2. highlights (!more about the verbs and the face emotions)
        1. find highligh sentence and check the character(s) who would on the picture
                may by coference resolution to check the pronun is who 
        2. find the verb or (face emotions)
        3. generate prompts

### <b> compile proto <b>
    pip install protobuf
    cd ./model_grpc
    protoc --python_out=.. model_server.proto 
    # also need to compile model_server_pb2_grpc.py       