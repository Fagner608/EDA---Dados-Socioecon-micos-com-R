# Análise Exploratória de dados sociecômicos em R


Projeto integrante do curso de Formação Cientista de [Dados da Data Science Academy](https://www.datascienceacademy.com.br/).



- Carga, DataWrangling, DataMunging, DataViz, geração de insights, machine learning. O projeto visa explorar os dados para responder à questões de negócios relacionadas à dados socieconîmicos de 155 países.

  
Objetivo: em um primeiro momento, conhecer os dados, e, concluir se estão em ordem para serem análisados estatica e graficamente.


Fonte dos dados: 


1 - Dados disponibilizados por Laurel Hanscon, e podem ser encontrados [aqui](https://data.world/laurel/world-happiness-report-data).

## Tecnologias Utilizadas


- R para:

  * Pré-processamento.
 
  * Tramento.
 
  * Manipulação.
 
  * Transformação.
  
  * Análise exploratória, visualização e geração de insights.
  
  
  
  * Principais pacotes utilizados: dplyt, ggplot2, moments, visdat, lattice, naniar.
 
 
- Conceitos aplicados:

  * DataWrangling
 
  * DataMunging
    
  * Data-Viz
  
  
  
## Funcionalidades

- A analise foi conduzida para, ao final, possibilitar responder às questões de negócio levantadas, com bases no conjunto de dados. A apresentação foi feita na forma de StoryTelling.

## Visualizar


1 - Acesse clicando no arquivo acima com extensão '.ipynb', neste repositório, ou


2 - Faça o clone do repositório para participar deste projeto.

## Resultados


Como resultado da análise, idenfificamos que existem diferenças notáveis na correlação de alguns indicadores, quando realizamos uma classificação de acordo com o PIB *per capta* em **pobre** ou **rico**. A exemplo do que ocorre entre o indicador de corrupção, e o nível de vida.


I - Avaliando correlação entre as variáveis mencionadas, sem considerar o agrupamento entre **pobres** e **ricos**:

![image](https://github.com/Fagner608/EDA---Dados-Socioecon-micos-com-R/assets/96034581/070924c6-e95d-45bb-91ef-7cc2c22269eb)

I.I - Avaliando correlação entre as variáveis mencionadas, considerarando o agrupamento entre **pobres** e **ricos**:

![image](https://github.com/Fagner608/EDA---Dados-Socioecon-micos-com-R/assets/96034581/50cb77ed-6134-48d7-929d-9e4b8b4136c3)


II -  Isso, aliás, avaliza o resultado obtido quando se compara se o país que menor índice de suporte social, também é o país com maior índice de corrupção:

![image](https://github.com/Fagner608/EDA---Dados-Socioecon-micos-com-R/assets/96034581/eca68c6e-6c66-4070-ba47-1905746875b4)


## Conclusão



Como resultado, temos uma todas as questões de negócio respondidas, com base em dados reais.
