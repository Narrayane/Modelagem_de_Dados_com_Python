# Análise de Dados de Vendas de Lojas

Este projeto realiza uma análise exploratória dos dados de vendas de quatro lojas distintas. O objetivo deste desafio é extrair insights sobre faturamento, desempenho por categoria de produto, avaliação dos clientes e custos de frete para auxiliar na tomada de decisões estratégicas.

## Dados

Os dados utilizados neste projeto são provenientes de quatro arquivos CSV, cada um representando as vendas de uma loja diferente. Os datasets contêm informações como:

- `Produto`: Nome do produto vendido.
- `Categoria do Produto`: Categoria a qual o produto pertence.
- `Preço`: Preço unitário do produto.
- `Frete`: Custo do frete para a venda.
- `Data da Compra`: Data em que a compra foi realizada.
- `Vendedor`: Vendedor responsável pela venda.
- `Local da compra`: Localidade (estado) onde a compra foi realizada.
- `Avaliação da compra`: Avaliação da compra pelo cliente (escala de 1 a 5).
- `Tipo de pagamento`: Método de pagamento utilizado.
- `Quantidade de parcelas`: Número de parcelas, caso o pagamento seja parcelado.
- `lat`, `lon`: Coordenadas geográficas do local da compra (embora não utilizadas diretamente nesta análise).

## Análises Realizadas

O projeto abrange as seguintes análises:

1.  **Análise do Faturamento:** Cálculo do faturamento total de cada loja e o faturamento geral das quatro lojas combinadas.
2.  **Vendas por Categoria:** Análise das vendas totais por categoria de produto para cada loja individualmente e o total consolidado.
3.  **Média de Avaliação das Lojas:** Cálculo da avaliação média das compras para cada loja, indicando a satisfação geral dos clientes.
4.  **Produtos Mais e Menos Vendidos:** Identificação dos 3 produtos que geraram mais receita e os 3 que geraram menos receita em cada loja.
5.  **Frete Médio por Loja:** Cálculo do custo médio de frete por loja.
6.  **Visualizações:** Geração de gráficos para visualizar:
    - Receitas Totais por Loja (Gráfico de Barras)
    - Receita Média por Venda por Loja (Gráfico de Linha)
    - Participação de Cada Loja nas Receitas Totais (Gráfico de Pizza)

## Tecnologias Utilizadas

- Python
- Pandas (para manipulação e análise de dados)
- Matplotlib (para visualização de dados)

## Como Executar o Projeto

1.  Clone este repositório para sua máquina local.
2.  Certifique-se de ter o Python instalado, juntamente com as bibliotecas Pandas e Matplotlib. Você pode instalá-las via pip:
