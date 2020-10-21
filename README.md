### build protobuf
`cd src && protoc -I proto ts.proto --go_out=plugins=grpc:proto/`
