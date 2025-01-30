# Projeto Ship Performance
### Projeto de análise de dados utilizando python e suas bibliotecas com google colab no dataset do Kangle
 <p align="center">
  <img alt="logo" width="40%" src="https://github.com/user-attachments/assets/fcce8d24-ff74-450d-bc76-ba1e1f619d68">
</p>

## Objetivo do Estudo
Realizar uma análise exploratória dos dados de embarcação do Golfo da Guiné, buscando entender padrões que impactam nas Performances destes.

**Pode acessar o link abaixo  para acessar o projeto completo:**
 - [**Projeto no Google Colab**](https://github.com/ArturBensch/Projeto-ShipPerformance/blob/main/Projeto_Ship_Performance.ipynb)

## Fonte de Dados
Todos os dados usados aqui foram obtidos a partir do dataset disponível no [Kanggle](https://www.kaggle.com/datasets/jeleeladekunlefijabi/ship-performance-clustering-dataset/data)

## Tecnologias Utilizadas
<p align="left">  
  <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> 
  <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/22799945?s=280&v=4"  alt="python" width="40" height="40"/> </a> 
  <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> 
  <a href="https://numpy.org/" target="_blank" rel="noreferrer"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" alt="numpy" width="40" height="40"/> 
  <a href="https://matplotlib.org/" target="_blank" rel="noreferrer"> <img src="https://media.licdn.com/dms/image/v2/D4D12AQFq38cGkv_oHQ/article-cover_image-shrink_423_752/article-cover_image-shrink_423_752/0/1679493396295?e=1743638400&v=beta&t=XwEOXZJMdr060xfLKljrmzxSeH7-pkWZuEW_4ylXqGM" alt="Matplotlib" width="50" height="50"/>
</p> 

## Destaques do Projeto

Foram feitas análises para identificar outliers e assim elimina-los, porem nao foi havia nenhum dado discrepante do conjunto total, como mostra o histograma abaixo:
 ### Histograma das Variáveis Númericas
<p align="center">
  <p align="center">
  <img alt="barra" width="60%" src="https://github.com/user-attachments/assets/84ba9486-ba32-48ef-884a-17ee21838162">
</p>


## Tabela de Correlação
Além disso, fiz analise de correlação entre as variaveis para entender quais tem maior relação, porém todas ficaram muito próximas de 0, evidenciando que não havia uma ligaçao direta entre elas. Sendo necessário se aprofundar mais para buscar uma relaçao de impacto.
<p align="center">
  <p align="center">
  <img alt="barra" width="350%" src="https://github.com/user-attachments/assets/fad3878d-173a-40c5-905e-ad033901186c">
</p>

## Lucro Operacional 
Ao criar o campo de lucro conseguimos visualizar uma não linearidade na base, assim atacar essa variável:
<p align="center">
  <p align="center">
  <img alt="barra" width="350%" src="https://github.com/user-attachments/assets/6b4925d8-0f68-46b5-a723-de8a261b8b2d">
</p>

## Obtendo uma Categoria de Alta Performance e Baixa Performance de acordo com a media do Lucro
Aqui, foi estipulado que para uma embarcação ter performance é necessário obter o maior lucro possível, assim criei uma nova categoria e a média entre as principais variáveis.
<p align="center">
  <p align="center">
  <img alt="barra" width="500%" src="https://github.com/user-attachments/assets/3bd98b9f-dcb8-4cc3-b0db-d2125d54b5bc">
</p>

## Identificando o principal tipo de embarcação que possui maiores quantidades de baixa performance 
A partir disso, começamos a aprofundar a análise e a chegar em algumas relações de maiores efeitos para uma queda no lucro dentro dos navios de tipo "Tanker".
Com isso tirando algumas conclusões, como visto no projeto completo no Colab.
<p align="center">
  <p align="center">
  <img alt="barra" width="70%" src="https://github.com/user-attachments/assets/77aa79f4-dfbb-4b4a-84f5-03772aa80d19">
</p>




