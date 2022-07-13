# Aplicação de desconto

Uma regra comum em diversas modalidades de compra é a aplicação de descontos mediante a quantidade de parcelas selecionadas.
Com base na tabela a seguir, desenvolva uma solução que receba uma lista com valores de uma compra e a quantidade de parcelas e retorne os valores da compra com o desconto adequado.

Quantidade de parcelas|Percentual de desconto
-----|-----
1|10%
2|8%
3|6%
4|4%
5|2%
>5|0%

### Exemplo de entrada
```json
{
	"compras": [
		{
			"valorCompra": 1050,
    		"quantidadeParcelas": 1
		},
		{
			"valorCompra": 1050,
    		"quantidadeParcelas": 2
		},
		{
			"valorCompra": 1050,
    		"quantidadeParcelas": 3
		}
	]
}
```

### Saída esperada
```json
{
    "dados": [
        {
            "valorCompra": 1050,
            "quantidadeParcelas": 1,
			"valorDesconto": 105,
			"valorCompraComDesconto": 945
        },
        {
            "valorCompra": 1050,
            "quantidadeParcelas": 2,
			"valorDesconto": 84,
			"valorCompraComDesconto": 966
        },
        {
            "valorCompra": 1050,
            "quantidadeParcelas": 3,
			"valorDesconto": 63,
			"valorCompraComDesconto": 987
        }
    ]
}
```

