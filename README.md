# github-actions-go

Executando o github Actions com projetos GO

## Para executar o programa, insira o código hello-world.go e use go run.

```bash 
go run hello-world.go
    hello world
```

## Às vezes, desejaremos transformar nossos programas em binários. Podemos fazer isso usando go build.

```bash 
go build hello-world.go

ls
    hello-world    hello-world.go
```

## Podemos então executar o binário construído diretamente.

```bash 
./hello-world
    hello world
```