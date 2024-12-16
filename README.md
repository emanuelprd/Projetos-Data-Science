## Sumário
1. Análise de Clustering do Mercado Financeiro dos EUA
2. Análise de Fatores da Curva de Juros dos EUA
3. Análise de Correspondência de Clientes de Instituição Bancária
4. Análise de Regressão do Risco e Retorno do Mercado dos EUA
5. Análise de Regressão Logística para Previsão de Falência de Companhias
6. Análise de Regressão Poisson e BNeg para Análise de Ofertas Públicas

## Modelos

### 1. Análise de Clustering do Mercado Financeiro dos EUA
O projeto teve como objetivo aplicar conhecimentos em análise de clustering para agrupar diferentes tickers representativos do mercado financeiro norte-americano, tais como Treasures, Corporate Bonds, Commodities e Equities, o critério utilizado na clusterização foi o retorno e volatilidade históricas. As bibliotecas utilizadas foram a scikit-learn para rodar os algoritmos de clusterização (hierárquico aglomerativo e não-hierárquico k-means), o pingouin para análise de variância (one-way ANOVA), o yfinance para a extração da base de dados do Yahoo Finance e as bibliotecas numpy e pandas para manipulação de números e dataframes e seaborn e matplotlib para plotagem de gráficos.

<p align="center">
<img src="https://github.com/emanuelprd/Data-Science/blob/main/1.1.%20-%20Gr%C3%A1fico%20Clustering.png" width="700"/>
</p>

### 2. Análise de Fatores da Curva de Juros dos EUA
O projeto teve como objetivo aplicar conhecimentos em análise de fatores por componentes principais (PCA) para extrair os fatores da curva de juros dos EUA. A análise de fatores é um método de machine learning que visa reduzir a dimensionalidade de uma base de dados, por exemplo, podemos reduzir um grande número de variáveis em apenas alguns fatores ou componentes principais que consigam sumarizar o comportamento da minha base de dados original. No caso, buscamos identificar os três componentes tradicionais de uma de curva de juros: nível, inclinação e curvatura. As bibliotecas utilizadas foram a FactorAnalyzer para rodar o algorítimo do PCA e também para fazer o teste de Bartlett, o sympy e scipy para algumas exemplificações de algebra matricial e para criação de tabelas, manipulação numérica e de gráficos foi utilizado bibliotecas como o pandas, numpy, matplotlib e o seaborn.

<p align="center">
<img src="https://github.com/emanuelprd/Data-Science/blob/main/2.1.%20-%20Gr%C3%A1fico%20Fatores.png" width="700"/>
</p>

### 3. Análise de Correspondência de Clientes de Instituição Bancária
O projeto teve como objetivo aplicar conhecimentos em análise de correspondência múltipla (ACM) em uma base de clientes cedida por um banco português, esta base continha diversas variáveis categoricas tais como profissão, educação e faixa etária. A ACM é uma técnica exploratória que transforma variáveis categóricas em coordenadas que podem ser plotadas em um gráfico para identificação de associações entre elas, é muito útil visto que este tipo de variável não pode ser analisada pelos métodos tradicionais como o PCA. As bibliotecas utilizaram foram a prince para a análise de correspondência, o sklearn pois aproveitei os resultados encontrados para rodar um algorítmo de clusterização e as demais bibliotecas conhecidas como o numpy que foi bastante utilizado para algebra matricial, o pandas e o matplotlib. 

<p align="center">
<img src="https://github.com/emanuelprd/Data-Science/blob/main/3.1.%20-%20Gr%C3%A1fico%20de%20Correspond%C3%AAncia.png" width="600"/>
</p>

### 4. Análise de Regressão do Risco e Retorno do Mercado dos EUA
O projeto teve como objetivo aplicar conhecimentos em análise de regressão linear em uma base de dados de diferentes índices representativos do mercado dos EUA, tais como índices de renda fixa, índices setoriais e do mercado em geral. A análise de regressão é uma técnica estatística preditiva que explora a relação de dependência de uma variável em função de uma ou mais outras variáveis chamadas de independentes ou explicativas, o objetivo do projeto foi estimar a relação entre risco e retorno do mercado norte-americano medido pela inclinação (coeficiente angular) da reta de regressão. As bibliotecas utilizadas foram pandas e yahoo finance para extração e tratamento da minha base de dados, o numpy para algumas operações matemáticas, o matplotlib e seaborn para gráficos, o statsmodels para rodar a regressão (OLS) e o scipy para testes estatísticos. 

<p align="center">
<img src="https://github.com/emanuelprd/Projetos-Data-Science/blob/main/4.1.%20-%20Gr%C3%A1fico%20Regress%C3%A3o.png" width="700"/>
</p>

### 5. Análise de Regressão Logística para Previsão de Falência de Companhias
O projeto teve como objtivo aplicar conhecimentos em regressão logística para estimar a probabilidade de falência de empresas com base em seus indicadores financeiros, como o nível de endividamento e ROA. A regressão logística, diferente da linear, é usada para estimar a probabilidade de eventos tais como ter alguma doença cardiáca ou votar em um determinado candidato. O objetivo foi analisar como o certas variáveis financeiras bom base nos estudos de Edward Altman podem ser usadas para mensurar a probabilidade de falência de uma companhia. As bibliotecas utilizadas foram pandas para trabalhar e manipular o dataset, o numpy para algumas operações matemáticas, o seaborn e matplotlib.pyplot para criação de gráficos, o statsmodels para rodar o modelo de regressão logística e o scipy para alguns testes estatísticos. 

<p align="center">
<img src="https://github.com/emanuelprd/Projetos-Data-Science/blob/main/5.1.%20-%20Gr%C3%A1fico%20Regress%C3%A3o%20Log%C3%ADstica.png" width="1100"/>
</p>

### 6. Análise de Regressão Poisson e BNeg para estimação de Ofertas Públicas
O projeto teve como objetivo  analisar as variáveis macroeconômicas que estão relacionadas ao número de ofertas públicas (IPO + Fallow-On) no Brasil, o termo IPO significa a 'initial public offering' que trata-se da primeira vez que um empresa coloca ações em negociação no mercado e Fallow-On é uma oferta subsequente onde mais ações são colocadas no mercado. Foi feito uma análise de regressão para dados de contagem visto que estamos analisando o número de ofertas públicas (variável discreta) em função de uma série de variáveis macroeconômicas, trabalhei inicialmente com o modelo Poisson e depois o Binomial Negativo devido a possível diagnóstico de superdispersão, no final comparei ambos os resultados e a relevância das variáveis para explicar o fenômeno estudado. As bibliotecas utilizadas foram o numpy e pandas para trabalhar com a base de dados, o seaborn e matplotlib para gerar gráficos, o stats para gerar a estatística chi-quadrado, o statamodels para rodar os modelos poisson e binomial negativo e o statstests para rodar diagnóstico de superdispersão. 

<p align="center">
<img src="https://github.com/emanuelprd/Projetos-Data-Science/blob/main/6.1.%20-%20Gr%C3%A1fico%20Regress%C3%A3o%20Poisson.png" width="700"/>
</p>

### 7. Análise de Regressão Multinomial

(EM CONSTRUÇÃO)

### 8. Análise de Séries Temporais com o Modelo ARIMA aplicado ao Ibovespa
O projeto teve como objetivo estimar um modelo ARIMA (Autoregressive Integrated Moving Average) para prever o Ibovespa, principal índice de ações do Brasil, utilizando dados históricos dos últimos 15 anos. Foi seguido os procedimentos tradicionalmente indicados para a correta identificação do modelo, tais como teste para identificar quantas defasagens são necessarias para tornar a série estacionária, com base nos gráficos de ACF e PACF quais os parâmetros autoregressivos e de médias móveis, posteriormente foi analisado os resíduos onde foi verificado que seguiam um ruído branco, ou seja, o modelo capturou adequadamente bem a estrutura temporal da série. As bibliotecas utilizadas incluíram yfinance para a extração da cotação do Ibovespa, statsmodels, scipy e sklearn para o rodar o modelo ARIMA e calcular os testes e métricas de erro, pandas para trabalhar com os dados em formato dataframe, o matplotlib e seaborn para geração de gráficos e o numpy para normalizar os dados. 


