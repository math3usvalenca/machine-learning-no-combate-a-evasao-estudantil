# Machine-learning-no-combate-a-evasao-estudantil

## Descrição do problema

A evasão estudantil é um problema complexo no âmbito educacional, podendo estar ligada a diversos fatores. O propósito deste trabalho foi obter um conhecimento, ao encontrar padrões em comum, sobre os alunos que evadem de seus cursos superiores no Instituto Federal de Ciência e Tecnologia da Paraíba e realizar uma análise preditiva na construção de um modelo de Machine Learning para auxiliar no combate a evasão estudantil.

Os dados utilizados foram retirados da Plataforma Nilo Peçanha, que foi instituída com o objetivo de disseminar dados estatísticos de toda a Rede Federal de Educação. 

## Solução

- **Knowledge Discovery in Databases (KDD)** - Usar o método de Knowledge Discovery in Databases, ou Descoberta de Conhecimento
em Banco de dados, que é um processo que permite extrair conhecimentos úteis a partir de
Bancos de dados, onde uma de suas etapas consiste na mineração dos dados (Data Mining)
- **Extract Transform and Load (ETL) e Data Warehouse** - Com este processo foi construído um Data Warehouse para servir de fonte para os
algoritmos de ML, além de garantir melhor organização dos dados;
- **Análise exploratória** - Etapa realizada para obter informações pertinentes
sobre as características de um aluno evadido;
- **Treinamento de algoritmos**
- **Deploy do melhor modelo** - Uma aplicação web foi construída para tornar o uso do modelo uma tarefa mais
prática ao permitir que usuários informem dados sobre um novo aluno e obtenham uma
probabilidade do mesmo pertencer ao grupo de evadidos


## Machine Learning Performance


Para realizar a análise preditiva foram utilizados os algoritmos: Logistic Re-
gression (Regressão Logística), K-Nearest Neighbors, Decision Tree e Support Vector
Machine. Buscou-se encontrar os melhores parâmetros para treinar os modelos com a
função RandomizedSearchCV da biblioteca scikit-learn. As estatísticas dos modelos
treinados encontram-se na Tabela abaixo:

| **Algoritmo**       | **Precision** | **Accuracy** | **Recall** |
|---------------------|---------------|--------------|------------|
| KNN                 | 80%           | 75%          | 88%        |
| Decision Tree       | 83%           | 78%          | 88%        |
| SVM                 | 81%           | 77%          | 91%        |
| Logistic Regression | 80%           | 77%          | 92%        |

Os resultados foram satisfatórios, com uma Precisão na faixa de 80% em todos
os algoritmos utilizados. Além disso, a cobertura (Recall) chegou a valores de 92%,
caso do Logistic Regression. Isso indica um resultado animador, pois essa métrica mede a capacidade do modelo em detectar corretamente
classes positivas (que seriam alunos evadidos). Por fim, os modelos foram comparados
pela área sob a curva ROC, onde o Logistic Regression apresentou um AUC muito
próximo do Decision Tree e acabou sendo escolhido pelo fato de apresentar um valor
de cobertura mais alto (92%).

## Produto final do trabalho

Painel online, hospedado em um Cloud e disponível para acesso em
qualquer dispositivo conectado à internet.
O painel pode ser acessado através desse link: https://data-visualization-and-forecasting-student-dropout.streamlit.app/




### Trabalho de Conclusão de Curso apresentado junto ao Curso Superior de Tecnologia em Análise e Desenvolvimento de Sistemas do *Instituto Federal de Educação, Ciência e Tecnologia da Paraíba - Campus Cajazeiras*, como requisito à obtenção do título de Tecnólogo em Análise e Desenvolvimento de Sistemas.
