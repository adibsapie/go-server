# go-server
Simple Web-server using Go

## Run 🛠
> All commands are to be run from the root project directory.
> 
> This project uses Go version `1.18`.
> 
> Current `go` executables should detect and install dependencies correctly.

The API structure is very simple:
```
GET  /hello               # return hello
POST /form                # return form data
```

To start the complete API run:
```
go run initial.go
