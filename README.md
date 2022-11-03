# Modelo de previsão para CHURN de uma companhia Telefônica

Neste projeto, faz-se uma limpeza e preparação de dados de uma companhia telefônica, a partir de um conjunto de datasets fornecido pelo site *Maven Analytics*.

Foram levados em consideração critérios como tratamento de dados nulos, dados com baixa variância, dados com alta correlação ou mesmo o próprio significado de cada feature e seu impacto em análises

Como critério adicional, fez-se a preparação desse mesmo conjunto de dados para um possível projeto de ML, convertendo-se as features categóricas nominais em numéricas discretas.

Por fim, criou-se um modelo de classificação, utilizando uma árvore de decisão, com as devidas redução de dimensionalidade, avaliação de métricas adequadas (acurácia, precisão e recall), validação do modelo com diferentes dados de teste e busca de melhores parâmetros para o algoritmo.

Conseguiu-se uma acurácia de cerca de 83% em média e uma precisão de cerca de 84% em média. O que pode ser positivo para um cenário em que se busque identificar o perfil dos clientes que deixam de contratar os serviços e as razões dos mesmos para tal.

## Tecnologias

* Python versão 3.7.14
* Arquivos em formatos diversos (csv, xlsx, json, etc)

## Serviços utilizados

* Google Colab
* https://www.mavenanalytics.io/

## Features

* Análise exploratória
* Limpeza de dados
* Transformação de dados
* Modelos de classificação
* Árvore de decisão
* Validação de modelos
* Variação de hiperparâmetros
* Matriz de confusão

## Versão

* 1.0.0.0

## Autores

* Matheus Henrique de Souza: @Matheus2510 (https://github.com/Matheus2510)
