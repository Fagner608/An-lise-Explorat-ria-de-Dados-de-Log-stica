# Análise Exploratória de Dados de Logística da [Loggi](https://www.loggi.com/)
Projeto realizado como atividade curricular do curso: Formação Analista de Dados da [EBAC](https://ebaconline.com.br/)

Para melhor vizualização do projeto, acesse por: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Fagner608/An-lise-Explorat-ria-de-Dados-de-Log-stica/blob/5250fd5ff9f674c346fb8d6d0d9e4b2004c4bd23/An%C3%A1lise_Explorat%C3%B3ria_de_Dados_de_Log%C3%ADstica.ipynb)


- Análise, visualização e geração de insights. A análise realizada explora a localização geoespacial das entregas realizadas pela empresa Loggi no Distrito Federal (Brasília/Brasil).

  
Objetivo: obter as primeiras impressões sobre o comportamento das entregas no Distrito Federal. Em um segundo momento (na próxima etapa do projeto) iremos identificar os melhores pontos para os hubs de distribuição.


Fonte dos dados: 


1 - Dados das entregas, fornecidos pelo Prof. [André Marcos Perez](https://github.com/andre-marcos-perez) (EBAC):

  - https://raw.githubusercontent.com/andre-marcos-perez/ebac-course-utils/main/dataset/deliveries.json
  - https://raw.githubusercontent.com/andre-marcos-perez/ebac-course-utils/main/dataset/deliveries-geodata.csv
  

2 - Shape file, adquirods no [IBGE](https://geoftp.ibge.gov.br/cartas_e_mapas/bases_cartograficas_continuas/bc100/go_df/versao2016/shapefile/bc100_go_df_shp.zip)



  - Para correta visualização do projeto, com os mapas, clique aqui no ícone a seguir: 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Fagner608/An-lise-Explorat-ria-de-Dados-de-Log-stica/blob/5250fd5ff9f674c346fb8d6d0d9e4b2004c4bd23/An%C3%A1lise_Explorat%C3%B3ria_de_Dados_de_Log%C3%ADstica.ipynb)


## Tecnologias Utilizadas


- Python para:


  * Análise exploratória, visualização e geração de insights.
  
  
  * Principais pacotes utilizados:Pandas, Seaborn, Numpy, Geopy, Geopandas.
 
 
  * Processamento de dados em formato Json.
  
  

- Conceitos aplicados:


  * Data-wrangling
  
  
  * Data-Viz com geoprocessamento
  
  
## Funcionalidades


- A analise foi conduzida para identificar, no mapa da Capital Federal, a localização geográfica das entreas, com intuito de:


  * Identificar regiões com mais frequências de entregas, inicialmente;
  * 
  
  * Identificar a melhor posição dos hubs de distribuição, e alocação de caminhões (para um próximo projeto).
  
  

## Visualizar


1 - Acesse clicando no arquivo 'Análise_Exploratória_de_Dados_de_Logística.ipynb', neste repositório, ou


2 - Clique no seguinte link, para visualizar palo Google Colab (indicado, para o processamento dos dados dos mapas): [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Fagner608/An-lise-Explorat-ria-de-Dados-de-Log-stica/blob/5250fd5ff9f674c346fb8d6d0d9e4b2004c4bd23/An%C3%A1lise_Explorat%C3%B3ria_de_Dados_de_Log%C3%ADstica.ipynb)


## Resultados


Como resultado da análise, idenfificamos, visualmente os principais pontos de entrega, e a atualização atual dos hubs de distribuição.


![image](https://user-images.githubusercontent.com/96034581/216703214-b32d56e2-d287-4671-87e6-d28efdbbef65.png)



Ainda, identificamos a proporção de entregas por região:


![image](https://user-images.githubusercontent.com/96034581/216703304-0c9692e9-96ac-462f-8024-036f65d137f3.png)


## Conclusão



Realizando alguns agrupamentos e sumarização dos dados, pode-se perceber que:



 - A área de entrega está divida em 3 (três) setores, e a atual localização dos centros de distribuição fica bem próxima a grande massa de entregas


 - Foi disponibilizado a mesma capacidade de entregas paras as 3 regiões, contudo, a diferença entre a quantidade de entragas realizadas é bastante grande.


Como próximo passo, poderíamos tentar reagrupar as área, explorando demais variáveis do dataset, bem como as característiacs geográficas da região, instituindo mais hubs, e realocando a atual capacidade disponível, com objetivo de atender de mais ágilmente entregas distantes dos atuais hubs, e, gerar economia nos insumos necessários para operação de entrega.


## Referências


Fonte dos dados: 


1 - Dados das entregas, fornecidos pelo Prof. [André Marcos Perez](https://github.com/andre-marcos-perez) (EBAC): https://raw.githubusercontent.com/andre-marcos-perez/ebac-course-utils/main/dataset/deliveries.json e https://raw.githubusercontent.com/andre-marcos-perez/ebac-course-utils/main/dataset/deliveries-geodata.csv


2 - Shape file, adquirods no [IBGE](https://geoftp.ibge.gov.br/cartas_e_mapas/bases_cartograficas_continuas/bc100/go_df/versao2016/shapefile/bc100_go_df_shp.zip)


  - Para correta visualização do projeto, com os mapas, clique aqui no ícone a seguir: 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Fagner608/An-lise-Explorat-ria-de-Dados-de-Log-stica/blob/5250fd5ff9f674c346fb8d6d0d9e4b2004c4bd23/An%C3%A1lise_Explorat%C3%B3ria_de_Dados_de_Log%C3%ADstica.ipynb)

