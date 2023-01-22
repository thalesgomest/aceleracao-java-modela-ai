# Exercício: Modela Ai

Execute a aplicação e faça um post na rota `http://localhost:8080/api/car` com o seguinte corpo:

```JSON
{
	"modelo": "Fiat Argo 1.3",
	"fabricante": "Fiat",
	"dataFabricacao": "10/02/2006",
	"valor": 10.000,
	"anoModelo": 2023
}
```

As informações seram salvas no banco de dados instanciado na memória enquanto a aplicação estiver rodando.

Para obter os dados armazenados faça um GET para a seguinte rota `http://localhost:8080/api/car`, obtendo:

```JSON
{
    "id": 1,
	"modelo": "Fiat Argo 1.3",
	"fabricante": "Fiat",
	"dataFabricacao": "10/02/2006",
	"valor": 10.000,
	"anoModelo": 2023
}
```
