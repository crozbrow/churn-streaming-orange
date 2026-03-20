# Previsão de Cancelamento em Streaming

## 📌 Descrição
Este projeto tem como objetivo prever o cancelamento de clientes (churn) em um serviço de streaming, utilizando técnicas de Machine Learning com a ferramenta Orange Data Mining.

## 📊 Dataset
O conjunto de dados utilizado contém informações sobre clientes, incluindo:
- Idade
- Gênero
- Tipo de plano
- Tempo de assinatura
- Tempo médio de uso
- Valor da mensalidade
- Tipo de pagamento
- Cancelamento (variável alvo)

Arquivo: `Cancelamento_streaming.xlsx`

## ⚙️ Ferramenta utilizada
- Orange Data Mining

## 🔄 Fluxo do projeto
O fluxo foi desenvolvido utilizando os seguintes componentes:
- File
- Select Columns
- Preprocess
- Random Forest
- Test & Score
- Confusion Matrix
- ROC Analysis
- Rank

## 🤖 Modelo utilizado
Foi utilizado o algoritmo **Random Forest**, devido à sua eficiência em problemas de classificação.

## 📈 Avaliação do modelo
O modelo foi avaliado utilizando:
- Validação cruzada (10 folds)
- Matriz de confusão
- Curva ROC (AUC = 1.0)

## 📊 Resultados
O modelo apresentou desempenho perfeito na base utilizada, com:
- 100% de acurácia
- 100% de precisão
- 100% de recall

## 📌 Observação importante
O dataset utilizado é simples e possui padrões bem definidos, o que pode explicar o alto desempenho do modelo.

## 📂 Arquivos do projeto
- `faculdade ia.ows` → fluxo do Orange
- `Cancelamento_streaming.xlsx` → base de dados
- `Machine learning & Chatbot.pdf` → relatório completo

## 👨‍💻 Autor
Alessandro