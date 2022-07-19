
<h1 align="center">Qual o perfil das candidaturas indígenas?

Uma análise das eleições 2020 </h1>


<p align="center">
<img src="https://img.shields.io/badge/Python-100%25-lightgrey">

 <img>
<a href="https://github.com/datalabe/Projeto_Analise_Eleitoral/blob/main/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/datalabe/Projeto_Analise_Eleitoral"></a>
</p>


<p align="center">  Projeto de dados do data_labe eleições 2020  </p>

> <p>“Se parte da população brasileira é indígena, eles devem ocupar espaços de decisão” Bigaira Veloso, uma das 124 candidaturas indígenas no Rio Grande do Sul.</p>
  
<p> A participação indígena nas eleições deu um salto em 2020, em todo o país,  aumentaram 88,51% em relação às eleições de 2016. Com 1917 candidaturas aptas a ir as urnas, 67%  são do gênero masculino mas as candidaturas de mulheres indígenas para prefeituras e câmaras de vereadores também deu um salto de 49% em relação a 2016. Amazonas, Mato Grosso do Sul e Roraima estão no topo dos locais de candidaturas, sendo Piauí e Sergipe os estados com menor número. 8% dos que se candidatam a vereador são eleitos e apenas 0,4% que se candidata a prefeito são eleitos.

De acordo com dados do Censo de 2010, do Instituto Brasileiro de Geografia e Estatística (IBGE), há no Brasil cerca de 817.963 pessoas autodeclaradas indígenas, 0,47% da população total do país. São 256 povos, com mais de 150 línguas diferentes.

Entre as principais pautas dos candidatos estão a demarcação das terras indígenas e o reconhecimento dos seus direitos e existência. Mas não só isso.
</p>


  
##  Dados

<p> Foi feito a extração de dados via sql no data lake Base de dados, as bases coletadas e transformadas em uma única base foram ;

    Base de candidatos selecionando apenas os que declararam como indígena;
    Base de resultado das candidaturas;
    Base de receita com os três diferentes fundos (partidário, especial e outro)

Fonte: [site basededados.org](https://basedosdados.org/)

Ao transformar e juntar as bases obtivemos 2209 registros com 30 colunas, além disso foi realizado uma junção de bases no qual foi identificado os posicionamentos dos partidos.

Após esses tratamentos foi selecionado apenas as candidaturas deferidas, isto é, aptas para ir as urnas, assim obtivemos 1917 registros/linhas para a análise que esse relatório dedicou.
 </p>

#### Neste repositório você encontra:
                   
                   1. Base de dados transformada 
                   2. Jupyter Notebook com a limpeza do dados, as análises e comentários
                   3. Relatório geral da análise
                                  


:nerd_face: | ANALISTA DE DADOS: [Samantha Reis](https://github.com/SamanthaReiis)
  

##   Licença

Ao compartilhar este projeto cite os desenvolvedores!

Os dados e scripts podem ser usados e melhorados por qualquer pessoa! Licença MIT
  
  


Gostou desse projeto? Acesse o site [data_labe](https://datalabe.org/) para ver outros projetos. :sparkling_heart:
