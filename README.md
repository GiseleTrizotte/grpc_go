go run cmd/grpcServer/main.go 

evans -r repl
package pb 
service CategoryService

Criando banco com sqlite3:
sqlite3 db.sqlite
create table categories ( id string, name string, description string);

export PATH=$PATH:$(go env GOPATH)/bin 
protoc --go_out=. --go-grpc_out=. proto/course_category.proto
