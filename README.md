# 关于grpc

https://grpc.io/



# 生成 *.pd.go

cd src/helloworld  
protoc -I ./ helloworld.proto --go_out=plugins=grpc:.
将proto文件生成到当前目录下面。


# run server & run client

go run server/main.go
go run client/main.go
