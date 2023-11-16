<h3 align="center">Back-end gRPC em GoLang</h3>

<p align="center">“Software developers are students forever 🧠”</p>


## :warning: Instalação <a name="install"></a>

```bash
# Criar banco sqlite:
$ sqlite3 db.sqlite

# Criando tabela categories:
$ create table categories ( id string, name string, description string);

# development
$ go run cmd/grpcServer/main.go

# Acessando como client com o pacote Evans
$ evans -r repl
$ package pb 
$ service CategoryService
$ call <service>
```

---

by [Gisele Trizotte](https://www.github.com/GiseleTrizotte) ❤️

