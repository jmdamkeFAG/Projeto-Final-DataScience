Previsão de Churn em Telecomunicações: Trabalho Final da disciplina de Ciência de Dados

O objetivo do projeto é aplicar técnicas de Machine Learning para prever a rotatividade de clientes (Churn) em uma empresa de telecomunicações, comparando o desempenho de diferentes algoritmos de classificação.

Alunos Jean Matheus & Matheus Nogueira

Estrutura do Repositório

data/: Contém a base de dados utilizada.
notebooks/: Contém o código fonte do projeto em formato Jupyter Notebook.
apresentacao.pptx: Apresentação final.
README.md: Documentação do projeto.

Metodologia e Algoritmos

1.  Pré-processamento: Limpeza de dados nulos, conversão de tipos (string para float) e tratamento de variáveis categóricas utilizando LabelEncoder.
2.  Modelagem: Aplicação de dois algoritmos de Classificação Supervisionada:
     Regressão Logística: Utilizado como baseline para estabelecer um desempenho mínimo.
     Random Forest (Floresta Aleatória): Utilizado para capturar padrões não-lineares e aumentar a precisão da previsão.
3.  Avaliação: Comparação das métricas de Acurácia (Accuracy) e análise da Matriz de Confusão.

Fonte dos Dados
A base de dados utilizada foi a Telco Customer Churn:
(https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
