# Relatório Gerencial

### Problema de negócio: 

Páginas com Avaliações de Usuários Aumentam as Vendas de Produtos Online?

- Variante A (Grupo de Controle) : Mostra o número atual de comentários e avaliações de usuários

- Variante B (Grupo de Tratamento) : Não mostra os comentários de usuários no site

### Dados

![image](https://user-images.githubusercontent.com/119424591/209132604-8e230cfc-ce2c-4e24-aa5b-1bccf53ed8d0.png)

Primeiras linhas da tabela dataset.csv.

### Dado que um indivíduo estava no grupo de controle, qual é a probabilidade de venda?
15.21% 

### Dado que um indivíduo estava no grupo de tratamento, qual é a probabilidade de venda?
19.62%

Como vemos, a probabilidade total de conversão do grupo é de 19%. Precisamos checar se temos evidências suficientes para dizer que o grupo de tratamento leva a um aumento das conversões.

## Teste de Hipóteses

![image](https://user-images.githubusercontent.com/119424591/209661057-2deaa02f-0b20-4294-81ef-e13c17b0f46a.png)

Conforme vemos acima, o grupo de controle (Azul) tem um maior percentual de chance de ocorrência porém com baixa taxa de conversão. 

O grupo de tratamento tem menor percentual de chance ocorrência porém com maior taxa de conversão. 

Para efetivarmos uma escolha plausível, iremos normalizar os dados com o intuito de igualarmos as grandezas e para consigamos chegar a um veredicto.

## Resultado

![image](https://user-images.githubusercontent.com/119424591/209661252-8293ea0c-9005-4f90-8ed3-81ec21d1a17f.png)

Visualmente, o gráfico para as hipóteses nula e alternativa é muito semelhante aos outros gráficos acima. Felizmente, as duas curvas têm formato idêntico, portanto, podemos apenas comparar a distância entre as médias das duas distribuições. Podemos ver que a curva de hipótese alternativa sugere que o grupo de teste tem uma taxa de conversão maior do que o grupo de controle. Este gráfico também pode ser usado para determinar diretamente o poder estatístico; ou seja, temos 99,99% de certeza das evidências mostradas acima.
