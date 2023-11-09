# protoapi
Protocol Buffer

# install protoc
1.sudo apt install protobuf-compiler
2.sudo apt install golang-goprotobuf-dev
3.sudo apt install protoc-gen-go
4.go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@latest
5.go install google.golang.org/protobuf/cmd/protoc-gen-go@latest
6.export PATH="$PATH:$(go env GOPATH)/bin"

# generate protfo files with golang
protoc --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative protoapi.proto