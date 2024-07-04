# 📊 Resultado: Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao resultado do desafio de projeto Previsão de Estoque Inteligente na AWS com SageMaker Canvas do Bootcamp Nexa - Machine Learning para Iniciantes na AWS em parceria com DIO, esse é meu primeiro contato com SageMaker e com o ambiente AWS com foco em Machine Learning

## 🚀 Passo a Passo

### Passo 1 1️⃣

Foi selecionado o Dataset que foi usado para para treinar e testar seu modelo de ML, o ideal na escolha de datasets para treinar e testar são os que contém informações correlacionadas!
Tive como escolha o dataset-1000-com-preco-variavel-e-renovacao-estoque.csv, disponível no repositório!

### Passo 2 2️⃣

Configurei as variáveis de entrada e saída de acordo com os dados, selecionei algumas informações importante como a "coluna target" e a "coluna id"

A imagem mostra como ficou o ambiente após a configuração
![Build after Configure](https://github.com/diegocgribeiro/lab-aws-sagemaker-canvas-estoque/assets/172605729/b9545448-09fc-4cf1-87df-4bb9f2cacd25)

Após a configuração é necessário clicar em Quick Build e iniciar o treinamento do modelo de ML

### Passo 3 3️⃣

Examinei as métricas de performance do modelo, o qual teve os seguintes resultados

AVG WQL: 0.346, medida usada em problemas de regressão quantílica

MAPE: 0.971, medida usada como a média dos erros absolutos relativos aos valores reais

WAPE: 0.581, essa métrica é útil quando há uma necessidade de considerar a magnitude dos valores reais.

RMSE: 36.006, é uma métrica muito utilizada por ser sensível a grandes erros

MASE: 0.852: é usada para comparar modelos de diferentes séries temporais.

Lembrando que essas métricas são usadas para avaliar a performance de modelos de previsão, cada uma com suas próprias vantagens e desvantagens dependendo do contexto do problema e dos dados.

![Analyze](https://github.com/diegocgribeiro/lab-aws-sagemaker-canvas-estoque/assets/172605729/23c8783a-0d56-49ae-8b58-a021a851d7be)

### Passo 4 4️⃣

Usei o modelo treinado para fazer previsões de estoque e com isso conseguimos ver alguns resultados que irei deixar a imagem abaixo

Sendo que P10 (rosa) seria o pior o cenário, P50 (verde) seria o cenário mediano e já o P90 (amarelo) seria o melhor cenário

![single_prediction_results (2)](https://github.com/diegocgribeiro/lab-aws-sagemaker-canvas-estoque/assets/172605729/57c3280a-009c-43c3-b0a0-30506bfdf55a)

![single_prediction_results (2)](https://github.com/diegocgribeiro/lab-aws-sagemaker-canvas-estoque/assets/172605729/666e8331-086a-440b-b795-db6d1c16dcf8)

# Esse foi o meu resultado junto com os insights do desafio de projeto Previsão de Estoque Inteligente na AWS com SageMaker Canvas
