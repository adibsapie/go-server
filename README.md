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

To start :
```
1. Open Windows Powershell and go to the project directory. Execute `go run main.go`
2. Powershell will show `Starting server at port 8080`
3. Go to browser, navigate to `locahost:8080`
4. For hello API : `localhost:8080/hello` 
5. For form data : `localhost:8080/form.html` and then click `Submit`
