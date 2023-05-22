## Análise Exploratória de Dados

A Análise Exploratória de Dados (AED) faz parte de todo projeto de Machine Learning. O trabalho se fundamenta na técnica de **Knowledge Discovery in Databases** (KDD), ou Descoberta de Conhecimento
em Banco de dados, que é um processo que nos permite extrair conhecimentos úteis a partir de Bancos de dados, onde uma de suas etapas consiste na **mineração dos dados** (Data Mining) sendo ela o ponto central do KDD.

<a href="https://nbviewer.org/github/math3usvalenca/machine-learning-no-combate-a-evasao-estudantil/blob/main/analise-de-dados-estudantis/AED.ipynb" >:rocket: Consulte este link par visualizar o notebook de maneira precisa com todos os gráficos :rocket:</a>

Etapas até se chegar na análise dos dados:

- Aplicação de **Extract, Transform and Load** (ETL) para construção de um **Data Warehouse** (DW):
    - extração dos dados da Plataforma Nilo Peçanha
    - limpeza e pré-processamento dos dados (Data Cleaning)
    - transformação dos dados com modelagem dimensional (modelo Star Schema)
    - carregamento e finalização do DW


Foi possível retirar diversos insights importantes a respeito da evasão entre os cursos, alunos, etc. Alguns exemplos encontram-se abaixo. 


<p align="center">
    <img  style="height:400px;width:700px;align:center;" src="https://res.cloudinary.com/dxwvax3zv/image/upload/v1684796179/newplot_4_zyvnki.png"/>
</p>

 <p align="center">
      <img  style="height:400px;width:700px;align:center;" src="https://res.cloudinary.com/dxwvax3zv/image/upload/v1684796179/newplot_8_espm2n.png"/>
 </p>
