# Case Datarisk - Cientista de Dados Jr

## Descrição

Este projeto tem como objetivo prever a probabilidade de inadimplência em pedidos de crédito para clientes recorrentes. O modelo utiliza técnicas de machine learning, como XGBoost, para classificar os clientes com base em várias variáveis relacionadas ao seu histórico de pagamentos e outros atributos financeiros.

Alguns problemas enfrentados: O problema foi resolvido como classificação e não regressão, o que geraria a probabilidade de inadimplência conforme o enunciado do Case.

## Objetivo

Desenvolver um modelo preditivo para calcular a probabilidade de inadimplência de crédito. O modelo é treinado usando uma base de dados histórica com informações sobre os pagamentos de clientes, onde a variável alvo é "INADIMPLENTE", que indica se o cliente foi inadimplente ou não.


## Arquitetura do Projeto

- **Pré-processamento de Dados**: Limpeza e transformação das variáveis para garantir que os dados estejam prontos para o treinamento.
- **Exploração e Análise de Dados**: Análise das relações entre as variáveis preditoras e a variável alvo.
- **Modelagem**: Utilização do algoritmo XGBoost, um modelo de boosting eficiente, para prever a inadimplência.
- **Avaliação**: Avaliação do modelo utilizando métricas como AUC-ROC, precisão, recall e F1-score.
