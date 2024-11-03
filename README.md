# Detecção de Fraude em Cartão de Crédito

Este projeto implementa um modelo de aprendizado de máquina para detectar transações fraudulentas em cartões de crédito.

## Visão Geral do Projeto
O conjunto de dados é altamente desbalanceado, com uma quantidade muito maior de transações legítimas em comparação com as fraudulentas. Para lidar com isso, aplicamos o **SMOTE (Synthetic Minority Over-sampling Technique)**, uma técnica que gera novas amostras sintéticas da classe minoritária.

## Resultados e Análise
- O modelo obteve uma acurácia razoável, com bons resultados de recall para a classe fraudulenta. A técnica de SMOTE contribuiu para melhorar a detecção de fraudes ao balancear o conjunto de dados.

## Tecnologias Utilizadas
- **Python**
- **Jupyter Notebook**
- **Scikit-Learn**
- **Imbalanced-Learn**
- **Matplotlib & Seaborn**

