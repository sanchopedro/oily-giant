# Projeto Oily Giant: Explorando Novos Poços de Petróleo para Máximo Lucro

![Oil company](img/oil.png)

Bem-vindo ao projeto Oily Giant! Seu desafio é ajudar a empresa de mineração OilyGiant a encontrar os melhores lugares para desenvolver novos poços de petróleo. Para isso, será necessário usar habilidades de análise de dados e ciência de dados para prever o volume de reservas em diferentes regiões e, em seguida, tomar decisões informadas sobre onde investir.

## Objetivo do Projeto

O principal objetivo deste projeto é identificar a região mais lucrativa para a perfuração de novos poços de petróleo, mantendo o risco de prejuízo abaixo de 2,5%. Você terá dados de exploração geológica para três regiões distintas e precisará usar modelos de regressão linear para prever o volume de reservas em cada poço. Com essas previsões, será possível selecionar as melhores oportunidades para maximizar o lucro total.

## Descrição de Dados

Os dados de exploração geológica para as três regiões estão armazenados em arquivos:

- geo_data_0.csv. [Baixe o conjunto de dados](https://practicum-content.s3.us-west-1.amazonaws.com/datasets/geo_data_0.csv)

- geo_data_1.csv. [Baixe o conjunto de dados](https://practicum-content.s3.us-west-1.amazonaws.com/datasets/geo_data_1.csv)

- geo_data_2.csv. [Baixe o conjunto de dados](https://practicum-content.s3.us-west-1.amazonaws.com/datasets/geo_data_2.csv)

- id — identificador unívoco de poço de petróleo

- f0, f1, f2 — três características de pontos (seu significado específico não é importante, mas as próprias características são significativas)

- product — volume de reservas no poço de petróleo (milhares de barris).

## Como Vamos Fazer Isso?

O projeto envolve uma série de etapas para atingir o objetivo:

1. **Preparação dos Dados:** Primeiro, vamos carregar e preparar os dados para análise. Isso inclui limpeza, tratamento de valores ausentes e divisão dos dados em conjuntos de treinamento e validação.

2. **Treinamento do Modelo:** Em seguida, construiremos um modelo de regressão linear para cada região e testaremos sua precisão. O modelo será treinado em 75% dos dados e testado nos 25% restantes para medir o erro.

3. **Cálculo de Lucro:** Com as previsões feitas pelo modelo, vamos selecionar os 200 poços mais promissores de cada região para calcular o lucro potencial. O orçamento para o desenvolvimento desses poços é de 100 milhões de dólares, então precisamos garantir que cada poço gere receita suficiente para cobrir os custos.

4. **Análise de Riscos e Decisão Final:** A última etapa envolve o uso de bootstrapping para analisar o risco de prejuízo e calcular o lucro médio. Com base nesses resultados, decidiremos qual região é a mais adequada para investimento, garantindo que o risco de perda seja mantido abaixo de 2,5%.

## Critérios de Sucesso

Para considerar este projeto um sucesso, precisamos atender aos seguintes critérios:

- Modelo de Regressão Preciso: O modelo deve ter um erro aceitável e ser capaz de prever com precisão o volume de reservas em cada poço.

- Risco Controlado: O risco de prejuízo deve ser inferior a 2,5%.

- Lucro Máximo: A região escolhida deve oferecer o maior lucro médio entre as três regiões, garantindo o máximo retorno sobre o investimento.

Com tudo isso em mente, você está pronto para começar a trabalhar no projeto Oily Giant. Siga as instruções, mantenha o código organizado e documentado, e boa sorte! Estamos ansiosos para ver sua análise e a região que você recomendará para investimento.