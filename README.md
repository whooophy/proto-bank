PROTO-BANK
This repository is used to centralize the results of generating proto contracts that will be used by clients

requirements:
`libprotoc 3.21.9`


Usage:

`protoc --proto_path=api/{{dir}} api/{{dir}}/proto/*.proto --go_out=api/{{dir}}/protobuf --go-grpc_out=api/{{dir}}/protobuf`

contoh