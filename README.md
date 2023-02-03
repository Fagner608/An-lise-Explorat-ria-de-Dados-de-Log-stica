
- Análise exploratória;
- Vizualização de dados
- Geoprocessamento

# Análise Exploratória de Dados de Logística da [Loggi](https://www.loggi.com/)
Projeto realizado como atividade curricular do curso: Formação Analista de Dados da [EBAC](https://ebaconline.com.br/)

- Análise, visualização e geração de insights. A análise realizada explora a localização geoespacial das entregas realizadas pela empresa Loggi no Distrito Federal (Brasília/Brasil).

  
Objetivo: obter as primeiras impressões sobre o comportamento das entregas no Distrito Federal. Em um segundo momento (na próxima etapa do projeto) iremos identificar os melhores pontos para os hubs de distribuição.


Fonte dos dados: 

1 - Dados das entregas, fornecidos pelo Prof. [André Marcos Perez](https://github.com/andre-marcos-perez) (EBAC): https://raw.githubusercontent.com/andre-marcos-perez/ebac-course-utils/main/dataset/deliveries.json e https://raw.githubusercontent.com/andre-marcos-perez/ebac-course-utils/main/dataset/deliveries-geodata.csv

2 - Shape file, adquirods no [IBGE](https://geoftp.ibge.gov.br/cartas_e_mapas/bases_cartograficas_continuas/bc100/go_df/versao2016/shapefile/bc100_go_df_shp.zip)



  - Para correta visualização do projeto, com os mapas, clique aqui no ícone a seguir: 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Fagner608/An-lise-Explorat-ria-de-Dados-de-Log-stica/blob/5250fd5ff9f674c346fb8d6d0d9e4b2004c4bd23/An%C3%A1lise_Explorat%C3%B3ria_de_Dados_de_Log%C3%ADstica.ipynb)


## Tecnologias Utilizadas


- Python para:

  * Análise exploratória, visualização e geração de insights.
  
  * Principais pacotes utilizados:Pandas, Seaborn, Numpy, Geopy, Foliun
  

- Conceitos aplicados:

  * Data-wrangling
  
  * Data-Viz com geoprocessamento
  
## Funcionalidades

- A analise foi conduzida para responder às seguintes questões de negócio:

  * Qual foi o método de venda que mais gerou lucro operacional, no período analisado?
  
  * Quais foram os 3 maiores vendedores, do método de venda que mais gerou lucro operacional?.
  
  * Ranking das cidades que mais registraram vendas online.
  
  * Mostrar em um mapa as cidades que registraram vendas online.

## Visualizar

1 - Acesse clicando no arquivo 'projeto.ipynb', neste repositório, ou

2 - Clique no seguinte link, para visualizar palo Google Colab (indicado, para o processamento dos dados dos mapas): [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Fagner608/adidas_sales_analytics/blob/main/projeto.ipynb)

## Resultados

Como resultado da análise, obtivemos as respostas desejadas, com base nos dados das vendas.


Qual foi o método de venda que mais gerou lucro operacional, no período analisado?


![image](https://user-images.githubusercontent.com/96034581/216680936-7a7f92de-9e9a-4543-b05b-823557efd265.png)

Quais foram os 3 maiores vendedores, do método de venda que mais gerou lucro operacional?.


![image](https://user-images.githubusercontent.com/96034581/216681072-dde2af0d-a166-4514-8252-b4d21f4ed53e.png)

Ranking das cidades que mais registraram vendas online.


![image](https://user-images.githubusercontent.com/96034581/216681184-ee809e0d-c6c0-4b68-8d52-7340f6f3f9bb.png)

Mostrar em um mapa as cidades que registraram vendas online.


![image](https://user-images.githubusercontent.com/96034581/216681286-e0c18e87-2d6e-4864-91ed-9152ce01a1b5.png)

Ainda, foram observadas mais características das vendas:

  - Quais produtos geraram mais lucro operacional;
  
  - Lucro operacional dos produtor, por sexo;
  
  - etc.

## Conclusão


Realizando alguns agrupamentos e sumarização dos dados, pode-se perceber que:


 - As vendas online são as que mais geraram lucro operacional no período analisando, correspondente sozinha à 53.26%;
 
 - Das vendas online, são os Top-3 vendedores: I - Foot Locker, II - West Gear e III - Sports Direct. o destaque vai para a Foot Locker, que corresponde sozinha a 40.22% do lucro operacional gerado com as vendas online;
 
 - Quanto as características geográficas iniciais das cidades que registraram lucro operacional das vendas online, percebe-se que nenhuma das cidades foi capaz de se destacar visivelmente das demais. Quando ranquedas, as cidades se apresentam bem próximas, e, o agrupamento revelou que não se pode ignorar as cidades com menos de 1% do lucro gerado, pois, quando agregadas, represetam mais de 7% - posição em que nenhuma cidade isolada alcançou.
 
 - As mulheres que realizaram compra de quaisquer dos estilos do produto "Footwear", foram responsáveis pela maior parte do lucro operacional das vendas online, registrado no centro-leste dos EUA.


Como próximo passo, poderíamos adicionar à nossa análise, dados demográficos dos EUA, bem como dados relacionados à localização dos centros de distribuição das empresas que apresentadas no projeto. Razendo alguns agrupamentos, poderíamos dar mais um passo, aplicando algumas estatísticas básicas na expliração dos dados, algoritmos de agrupamento, e, realizar previsões.


## Referências


Fonte dos dados: [kaggle](https://www.kaggle.com/datasets/heemalichaudhari/adidas-sales-dataset)

  - Para correta visualização do projeto, com os mapas, clique aqui no ícone a seguir: 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Fagner608/adidas_sales_analytics/blob/main/projeto.ipynb)


