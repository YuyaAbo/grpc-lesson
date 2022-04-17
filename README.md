# grpc-lesson

https://www.udemy.com/course/go-grpc-x/ を受講した成果物

## require
Protocol Buffersのコンパイラ
```bash
$ brew install protobuf
$ protoc --version
libprotoc 3.19.4
```
gRPCのGo言語用プラグイン（参考 https://grpc.io/docs/languages/go/quickstart/）
```bash
$ go install google.golang.org/protobuf/cmd/protoc-gen-go@v1.28
$ go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@v1.2
```
