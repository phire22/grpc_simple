## Running the server

```
make run
```

## Calling the endpoints
```
grpcurl -proto greeter.proto -plaintext -d '{"name":"Alice"}' localhost:50051 proto.Greeter/SayHello

grpcurl -proto timekeeper.proto -plaintext localhost:50051 proto.Timekeeper/GetDate 
```# grpc_simple
