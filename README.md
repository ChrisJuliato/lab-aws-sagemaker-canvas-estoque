# Previsão de Séries Temporais para Controle de Estoque de Máquinas Agrícolas

## Visão Geral
Este projeto foi desenvolvido com base na minha experiência em uma empresa agrícola, utilizando dados e cenários que refletem as operações reais da empresa. O objetivo é criar e utilizar um dataset para previsão de séries temporais de estoques de máquinas agrícolas usando o AWS SageMaker Canvas, otimizando assim a gestão do inventário e dos recursos.

## Dataset
O dataset foi elaborado para atender aos requisitos de previsões de séries temporais, simulando um ambiente real de gestão de estoque em uma empresa de máquinas agrícolas com entradas históricas detalhadas para cada produto:

- **ID do Produto**: Identificador único para cada máquina.
- **Nome do Produto**: Descrição do produto.
- **Categoria**: Tipo da máquina (ex: Trator, Colheitadeira).
- **Quantidade em Estoque**: Quantidade disponível em cada entrada.
- **Data de Entrada**: Data em que o produto foi adicionado ao estoque.
- **Fornecedor**: Nome do fornecedor da máquina.
- **Localização no Estoque**: Local específico no armazém.
- **Data de Venda**: Data em que ocorreu a venda.
- **Quantidade Vendida**: Número de unidades vendidas.

## Processo de Previsão
Utilizando o AWS SageMaker Canvas, configurei um modelo de previsão de séries temporais que analisa as tendências históricas de vendas e adições ao estoque para prever futuras necessidades. O modelo foi ajustado para garantir que cada ID de produto tivesse pelo menos cinco valores históricos, seguindo as melhores práticas para previsões de séries temporais. O modelo prevê as necessidades de estoque para os próximos 30 dias.

## Resultados
O modelo de previsão desenvolvido foi capaz de identificar padrões nos dados de estoque e fornecer previsões precisas para as futuras necessidades de estoque nos próximos 30 dias, permitindo uma gestão de estoque mais proativa e eficiente.


