# rest-api-using-go

Install Go:
https://golang.org/doc/install


Git checkout using SSH:
git@github.com:pattsumeet/rest-api-using-go.git

Dependencies for REST API:
go get -u github.com/gorilla/mux

Execute:
go run main.go

Use POSTMAN or similar tool for adding article:

[POST] http://localhost:10000/article
Body: {
    "Id": "3", 
    "Title": "Newly Created Post", 
    "desc": "The description for my new post", 
    "content": "my articles content" 
}

[PUT] http://localhost:10000/article/3
Body: {
    "Id": "3", 
    "Title": "Newly Created Post4", 
    "desc": "The description for my new post4", 
    "content": "my articles content4" 
}
