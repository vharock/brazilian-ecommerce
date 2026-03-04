# brazilian-ecommerce
Construção de Dashboard de Indicadores 

# Problema de negócio

A TUDO AQUI é uma empresa brasileira de e-commerce que começou a crescer, porém até então, a maioria das suas decisões é tomada pelo time diretivo de forma intuitiva, sem muita análise e precisão. Por não analisar indicadores, a empresa já tomou algumas decisões erradas que a levaram a tomar prejuízos.
Para que a empresa continue a crescer de forma saudável, o CEO que se sente “cegoˮ em relação aos dados da empresa, decidiu implementar Business Intelligence com o intuito de ter indicadores que o ajudem a tomar decisões melhores. Devido aos prejuízos identificados, foi estabelecido pelo CEO que a empresa não se apegue mais a suposições, mas que a partir de agora adote a metodologia Data Driven na tomada de decisões estratégicas.

As frentes analisadas serão respectivamente: 

Produto:
1.Quantidade de Produtos Cadastrados
2.Quantidade Total de Categorias
3.Quantidade Total de Fotos
4.Quantidade de Produtos por Categoria
5.Quantidade de Fotos por Categoria

Pagamentos:
1.Quantidade de pedidos
2.Valor total de pagamentos
3.Quantidade de pagamentos
4.Quantidade de pagamentos por tipo de pagamento (um por cartão)

Pedidos:
1.Quantidade de pedidos
2.Quantidade de clientes
3.Quantidade de pedidos do ano de 2017
4.Quantidade de pedidos do ano de 2018
5.Taxa de Crescimento (2017 - 2018)

Avaliações:
1.Quantidade de avaliações únicas
2.Quantidade de avaliações únicas para o score 4 e 5 
3.Média de tempo em dias das avaliações que não receberam retorno no mesmo dia que a avaliação foi criada
4.Média de tempo em horas das avaliações que não receberam retorno no mesmo dia que a avaliação foi criada
5.Quantidade de avaliações únicas para o score 4 e 5 dos clientes dos estados SP e RJ apenas do ano de 2018
6.Taxa de crescimento entre os anos de 2018 e 2017 para os clientes score 4 e 5 dos estados SP e RJ 

Vendedores:
1.Quantidade total de vendedores (Detalhes de Vendedores)
2.Total de vendas
3.Total de vendas dos itens com valor superior a R$500.000 (Detalhes de Itens Vendidos)
4.Quantidade de vendedores que venderam itens com valor superior a R$500.000
5.Quantidade de vendedores que venderam dentro ou acima da meta

Vendas:
1.Total de Vendas
2.Total Acumulado YTD (Ano Atual)
3.Total Acumulado YTD (Ano Anterior)
4.Taxa de Crescimento Acumulado (Ano Atual x Ano Anterior)
5.Porcentagem de Desconto de Frete 


# Premissas da análise

Análise foi feita com dados do Dataset Brazillian e-Commerce - Autoupdated dataset com link para o Kaggle: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce
Marketplace foi o modelo de negócio assumido.
As principais visões de negócio foram: Produto, Pagamentos, Pedidos, Avaliações, Vendedores e Vendas.

#Estratégia da solução
O painel estratégico foi desenvolvido utilizando as métricas que refletem as principais visões do modelo de negócio da empresa:

Cada visão é representada pelo seguinte conjunto de métricas.

Visão Produto:
a.Quantidade de Produtos Cadastrados
b.Quantidade Total de Categorias
c.Quantidade Total de Fotos
d.Quantidade de Produtos por Categoria
e.Quantidade de Fotos por Categoria

Visão Pagamentos:
a.Valor total de pagamentos (por status do pedido)
b.Quantidade de pagamentos (por tipo de pagamento)
c.Hierarquia de valor médio de pagamentos por status do pedido e por tipo de pagamento
d.Detalhes dos pedidos por tipo de pagamento e pela quantidade de pagamentos

Visão Pedidos:
a.Quantidade de pedidos x Meta Anual
b.Quantidade de pedidos x Meta Mensal de 2018
c.Quantidade de Pedidos por Estado do Cliente
d.Detalhes da quantidade de pedidos e meta de pedidos por Ano, Mês,Estado do Cliente e Cidade do Cliente

Visão Avaliações:
a.Um gráfico de dispersão clusterizado por estado do cliente, quantidade de avaliações únicas e a média de tempo em dias das avaliações que 
não receberam retorno no mesmo dia que a avaliação foi criada.
b.Um gráfico de Pizza que exibe a quantidade de avaliações únicas pela classificação da avaliação. 
c.Um gráfico com os principais influenciadores entre a classificação das avaliações e estado do cliente.

Visão Vendedores:
a.Um gráfico de Funil para apresentar os Top 10 estados dos vendedores que mais vendem.
b.Um gráfico de Mapa que contenha a quantidade de vendedores e demonstre essa informação por país, estado e cidade dos vendedores (Detalhes Geográficos).
c.Um gráfico de acompanhamento dinâmico de meta média por Item que permita alterar dinamicamente os valores das metas na tela do Dashboard. 
d.Uma tabela com os detalhes por vendedor e seus respectivos estados que contenha o total de vendas, o total de vendas de itens acima de R$
500.000, a representação do valor de vendas de cada vendedor em relação ao todo, a representação do valor de vendas de cada vendedor em relação ao que está filtrado nas segmentações e quais vendedores venderam dentro ou acima da meta.

Visão Vendas:
a.Uma Análise de Pareto 8020 com o Total de Vendas por Estado de Compra
b.Total de Vendas Acumuladas mês a mês exibindo todos os anos na tela
c.Uma análise de % Retenção de vendedores com COHORT 
d.Uma análise que exiba o Total de Vendas do Ano Atual x Ano Anterior mês a mês em conjunto com a taxa de crescimento exibindo todos os 
anos na tela.

# Top Insights da análise


# Conclusão


# Visualize a análise completa

https://app.powerbi.com/view?r=eyJrIjoiNzY5MzEwYjQtNTRhMS00NjcxLTgyMmUtZDI2YWFhMTE1OTdjIiwidCI6IjcwODUzMjhjLTBkNzQtNDg3My1hZTYyLWVhZWEwYTYyM2UyZSJ9

# Próximos passos
