# Anotações

## Makefile

Um `makefile` é um arquivo usado para agrupar comandos do Go e executar de forma automatizada
Assim, em vez de rodar cada comando manualmente, basta usar o comando `make`

```bash
make
```

Ele executa a sequência configurada no `makefile`:

1. `go fmt ./...` - formata o código
2. `go vet ./...` - analisa possíveis problemas
3. `go build` - compila o projeto

## Comandos úteis

| Comando | O que faz |
| --- | --- |
| `make` | Formata, verifica e compila o projeto. |
| `make clean` | Executa `go clean`, limpando o binário gerado pelo `go build`. |
