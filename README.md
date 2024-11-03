# Detecção de Fraude em Cartão de Crédito

Este projeto implementa um modelo de aprendizado de máquina para detectar transações fraudulentas em cartões de crédito. Utiliza a técnica de **SMOTE** para balancear o conjunto de dados e um modelo de **Regressão Logística** para previsão.

## Índice
- [Visão Geral do Projeto](#visão-geral-do-projeto)
- [Configuração e Execução](#configuração-e-execução)
- [Resultados e Análise](#resultados-e-análise)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Contribuir](#como-contribuir)

## Visão Geral do Projeto
O conjunto de dados é altamente desbalanceado, com uma quantidade muito maior de transações legítimas em comparação com as fraudulentas. Para lidar com isso, aplicamos o **SMOTE (Synthetic Minority Over-sampling Technique)**, uma técnica que gera novas amostras sintéticas da classe minoritária.

### Distribuição das Classes
![Distribuição de Fraudes e Não Fraudes](images/fraud_distribution.png)

## Configuração e Execução

Para reproduzir este projeto:
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute o Jupyter Notebook para treinar o modelo e visualizar os resultados.

## Resultados e Análise
- **Acurácia do Modelo**: xx%
- **Matriz de Confusão**: ...
- O modelo obteve uma acurácia razoável, com bons resultados de recall para a classe fraudulenta. A técnica de SMOTE contribuiu para melhorar a detecção de fraudes ao balancear o conjunto de dados.

## Tecnologias Utilizadas
- **Python**
- **Jupyter Notebook**
- **Scikit-Learn**
- **Imbalanced-Learn**
- **Matplotlib & Seaborn** para visualização

## Como Contribuir
Se você tiver sugestões ou melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

