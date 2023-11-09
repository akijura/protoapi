# protoapi
Protocol Buffer

# generate protfo files with golang
protoc --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative protoapi.proto