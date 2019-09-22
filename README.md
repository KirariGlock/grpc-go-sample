# grpc-go-sample
grpcの自己学習用リポジトリ

# Run the sample code
To compile and run the server, assuming you are in the root of the route_guide
folder, i.e., .../examples/route_guide/, simply:

```sh
$ go run server/server.go
```

Likewise, to run the client:

```sh
$ go run client/client.go
```

# Optional command line flags
The server and client both take optional command line flags. For example, the
client and server run without TLS by default. To enable TLS:

```sh
$ go run server/server.go -tls=true
```

and

```sh
$ go run client/client.go -tls=true
```


# 参考資料
- [公式のチュートリアル](https://grpc.io/docs/tutorials/basic/go/)
- [Go で実装しながら gRPC を理解する](https://reboooot.net/post/hello-grpc/)

