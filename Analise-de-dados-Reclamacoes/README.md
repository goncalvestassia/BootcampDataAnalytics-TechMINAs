# Análise de dados - Reclamações do Consumidor 

[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://docs.python.org/3.9/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)](https://docs.jupyter.org/en/latest/)
[![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/doc)
[![VSCode](https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)](https://code.visualstudio.com/docs)
[![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://learn.microsoft.com/en-us/power-bi/)

### Tópicos
:small_blue_diamond: [Descrição do projeto :id:](#descrição-do-projeto-id)  
:small_blue_diamond: [Objetivos :dart:](#objetivos-dart)  
:small_blue_diamond: [Dados :open_file_folder:](#dados-open_file_folder)  
:small_blue_diamond: [Relatório no PowerBI :bar_chart:](#relatório-no-powerbi-bar_chart)  
:small_blue_diamond: [Link do projeto no Google Colab :link:](#dependências-e-bibliotecas-utilizadas-books)  

## Descrição do projeto :id:

"Suponha que você trabalha na área de dados do Procon. Diariamente, você e sua equipe recebem dados de diversas reclamações dos consumidores. Cada reclamação, então, tem um determinado tempo para ser resolvida entre o cliente e a companhia em questão.
Dado esse contexto, a sua equipe recebeu do time de operações dados históricos de reclamações de 2012 a 2016 na pasta reclamações-consumidor."

Os dados são uma amostra dos dados extraídos do kaggle oriundos do Procon de 2012 a 2016.

## Objetivos :dart:

Perguntas que devem ser respondidas a área de negócios:

:one: -  Análise dos dados

1 - Existe alguma sazonalidade na data de abertura de uma reclamação? Ou seja, mais consumidores abrem reclamações em determinada época do ano?
2 - Qual o tempo médio de uma reclamação ativa (da abertura até a data de fechamento)?
3 -O numero de reclamações varia de acordo com a região? e de acordo com o estado? E se ponderarmos pela população média do estado?
4 - Quais as empresas que receberam mais reclamações dos consumidores? E por região e estado?

:two: - Modelagem: Prevendo o tempo de uma reclamação ativa.
O time de negócios gostaria que a sua equipe fizesse um modelo de regressão para estimar qual será o tempo médio de uma reclamação ativa. 

1- Quais variáveis podem estar mais correlacionadas com o tempo de uma reclamação ativa?
2- Construa variáveis que podem estar correlacionadas com o tempo de uma reclamação ativa a partir dos dados.
3- Analise a correlação das variáveis
4 - Construa um modelo de regressão linear em que queremos estimar o tempo de uma reclamação ativa.

## Dados :open_file_folder:

Os arquivos .csv referentes aos dados brutos encontram-se na pasta Dados, onde contém os dados do Procon e a população dos estados e regiões no ano de 2016 de acordo com o IBGE.

[Procon](https://www.kaggle.com/datasets/gerosa/procon)
[População IBGE](https://www.ibge.gov.br/estatisticas/sociais/populacao/9103-estimativas-de-populacao.html?edicao=17283&t=downloads)


## Relatório no PowerBI :bar_chart:



## Link do projeto no Google Colab :link:

- [Google Colab](https://colab.research.google.com/drive/1A2QxALFbbF_ZDnQv_JLHNh7vxFjdcURC?usp=sharing)

