#Генерация python файлов для GRPC

#### python3 -m grpc_tools.protoc -I./ --python_out=. --grpc_python_out=. greeting_service.proto
