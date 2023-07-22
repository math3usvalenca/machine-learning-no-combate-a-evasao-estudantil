## Análise Exploratória de Dados

A Análise Exploratória de Dados (AED) faz parte de todo projeto de Machine Learning. Este trabalho se fundamenta na técnica de **Knowledge Discovery in Databases** (KDD), ou Descoberta de Conhecimento
em Banco de dados, que é um processo que nos permite extrair conhecimentos úteis a partir de Bancos de dados, onde uma de suas etapas consiste na **mineração dos dados** (Data Mining) sendo ela o ponto central do KDD.

<a href="https://nbviewer.org/github/math3usvalenca/machine-learning-no-combate-a-evasao-estudantil/blob/main/analise-de-dados-estudantis/AED.ipynb" target="_blank" >:rocket: Consulte este link para visualizar o notebook de maneira precisa com todos os gráficos :rocket:</a>

Etapas até se chegar na análise dos dados:

- Aplicação de **Extract, Transform and Load** (ETL) para construção de um **Data Warehouse** (DW):
    - extração dos dados da Plataforma Nilo Peçanha
    - limpeza e pré-processamento dos dados (Data Cleaning)
    - transformação dos dados com modelagem dimensional (modelo Star Schema)
    - carregamento e finalização do DW


Foi possível retirar diversos insights importantes a respeito da evasão entre os cursos, alunos, etc. Alguns exemplos encontram-se abaixo. 


<p align="center">
    <img  style="height:450px;width:800px;align:center;" src="https://res.cloudinary.com/dxwvax3zv/image/upload/v1690052297/newplot_3.png"/>
</p>

 <p align="center">
      <img  style="height:450px;width:800px;align:center;" src="https://res.cloudinary.com/dxwvax3zv/image/upload/v1690052296/newplot_6.png"/>
 </p>
