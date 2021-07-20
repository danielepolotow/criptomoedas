# Criptomoedas
Predição do Preço de Criptomoedas

![bit](https://user-images.githubusercontent.com/60848308/126319163-c0169e8d-e98c-42f6-adbb-19b78712b012.jpg)

## INTRODUÇÃO

Criptomoedas apresentam grande volatilidade, apresentando grande variação de preços em períodos curtos de tempo. Devido a sua instabilidade, hipotetizo que o uso de análises clássicas de séries temporais (com apenas o histórico do preço) não é a melhor forma de predizer o preço futuro da moeda. Serão usados dados adicionais para as correlações com as criptomoedas escolhidas, com o objetivo de uma melhor predição de preços futuros. Os dados adicionais preliminares serão notícias do GoogleNews. Os clientes em potencial seriam investidores em geral, interessados em compras de criptomoedas. Os clientes poderiam prever o aumento/diminuição dos preços com o modelo e, hipoteticamente, lucrar com a compra e venda de moedas.

## PERGUNTAS PRELIMINARES

- O aumento ou queda na frequência de pesquisa das palavras "cryptocurrency", "bitcoin" ou "ethereum" no GoogleNews implica um sinal de negociação?
- Existe alguma correlação óbvia entre os diferentes preços de mercado das criptomoedas?
- Se a correlação entre as moedas A e B existe, podemos usar o histórico de preços da moeda A para prever o preço futuro da moeda B? Será mais útil do que usar apenas os preços históricos da moeda B sozinha?

## DADOS

Criptomoedas: dados financeiros de moedas populares disponíveis na API Yahoo Finance, como Bitcoin e Ethereum. A popularidade da moeda é importante neste caso, já que queremos ver a sua relação com a presença na mídia. Mídia: a API não oficial do Google Trends, com número total de buscas por palavra e frequencia de palavras nas notícias. O objetivo é testar a correlação de cada moeda com palavras chave, como o nome da própria moeda. 

## METODOLOGIA

- Obtenção dos dados.
- Identificação de correlações positivas ou negativas e seleção das melhores palavras chave.
- Proposta de um modelo de predição.
