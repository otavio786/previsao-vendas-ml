# Modelo de Previsão de Vendas

Este repositório contém o código de um modelo de previsão de vendas utilizando **regressão linear**. O objetivo do modelo é prever as vendas futuras de um produto com base em variáveis como preço, marketing, etc.

## Passo a Passo

### 1. Criação do Repositório
Criei um repositório no GitHub chamado "previsao-vendas-ml" para organizar o código e documentar o progresso do projeto.

### 2. Criação do Modelo
O modelo foi criado utilizando a biblioteca `scikit-learn`. Primeiro, foi realizado o pré-processamento dos dados (normalização e divisão entre treino e teste), seguido pela criação de um modelo de regressão linear. O modelo foi treinado e avaliado com a métrica de erro absoluto médio (MAE).

### 3. Criação do Ponto de Extremidade
Utilizando o **Azure Machine Learning**, foi configurado um ponto de extremidade para disponibilizar o modelo como um serviço web acessível via API. O arquivo `.json` com a configuração do ponto de extremidade está incluído neste repositório.

### 4. Testes e Validação
O modelo foi validado utilizando a divisão treino/teste e obteve um MAE de [valor]. Os resultados mostram que o modelo é capaz de prever as vendas com precisão razoável.

### 5. Implementação Final
O modelo está agora acessível via API. O arquivo de configuração do ponto de extremidade (`pontos_de_extremidade.json`) está disponível para acesso.

## Tecnologias Utilizadas
- Python
- scikit-learn
- Azure Machine Learning
- Flask (para a criação da API)

## Como Rodar
1. Clone o repositório.
2. Instale as dependências com `pip install -r requirements.txt`.
3. Treine o modelo rodando o script `treinar_modelo.py`.
4. Implante o modelo na nuvem utilizando `deploy_model.py`.
