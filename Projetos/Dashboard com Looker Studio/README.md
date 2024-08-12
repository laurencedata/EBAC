# Análise de Dados da Covid-19 no Brasil em 2021 🦠

<p align="center">
  <img src="https://s3.static.brasilescola.uol.com.br/be/2021/02/covid-19.jpg" alt="COVID-19" />
</p>

## 📌 Introdução:

Este projeto busca explorar os dados da COVID-19 no Brasil durante o ano de 2021. O foco é realizar uma análise completa dos dados, desde a importação até a visualização. Utilizamos o Looker Studio para criar um painel interativo, permitindo uma análise detalhada e a comunicação eficaz dos insights obtidos.

## 🎯 Objetivos:

O objetivo principal deste repositório é criar visualizações detalhadas dos dados relacionados à pandemia de COVID-19. Os pontos específicos são:

- Esclarecer informações sobre a pandemia no Brasil em 2021.
- Simplificar a compreensão dos dados da COVID-19.
- Oferecer reflexões baseadas em dados sobre a situação atual do Brasil por estado.

## 🌐 Fontes dos Dados:

Todas as fontes de dados utilizadas neste projeto estão citadas e detalhadas no notebook.

## 🔎 **Etapas da Análise:**

**Extração dos Dados:** Coleta e importação dos dados brutos de fontes distintas.

**Limpeza e Tratamento:** Identificação e correção de inconsistências dos dados.

**Transformação:** Conversão dos dados para um formato adequado para análise, incluindo criação de novas variáveis.

**Carregamento:** Disponibilização dos dados prontos para visualização e análise no Looker Studio.

Todo o processo é documentado neste notebook, garantindo a reprodução e a compreensão detalhada das análises realizadas.

## ⚙️ Ferramentas Utilizadas:

**Pandas e NumPy:** Utilizados para o tratamento, manipulação e análise dos dados.

**Datetime:** Empregado para selecionar e manipular datas, facilitando a definição do período de análise.

**Iterador:** Ferramenta para filtrar dados de forma eficiente, processando linha por linha nos datasets.

**Looker Studio:** Plataforma utilizada para criar visualizações interativas dos dados, facilitando a interpretação dos resultados.

## 📊 Exploração Interativa dos Dados:

#### KPIs:

O dashboard de dados contem os seguintes indicadores chaves de desempenho (*key performance indicator* ou KPI) consolidados:

1. Casos e mortes nas 24 horas;
1. Média móvel (7 dias) de casos e mortes;
1. Tendência de casos e mortes.

#### EDA (Análise Exploratória dos Dados):

O dashboard de dados contem os seguintes gráficos para a análise exploratória de dados (*exploratory data analysis*
ou EDA) interativa:

1. Distribuição do número de casos e mortes ao longo do tempo.
1. Análise da média móvel (7 dias) do número de casos e mortes ao longo do tempo.
1. Distribuição geográfica dos casos por estado, dia a dia.
1. Evolução temporal dos casos confirmados e mortes.
1. Comparação entre diferentes estados em termos de mortes e casos.
1. Identificação de padrões sazonais e tendências específicas.
1. Percentual diário de aplicações das doses de vacinas (1ª, 2ª e 3ª).
1. Mapa interativo mostrando a distribuição de casos por estado.

## 💡 Insights:

**1. Qual foi o mês com o maior número de mortes durante o período analisado?**

- Abril foi o mês com o maior número de mortes, totalizando mais de 82 mil vítimas.

**2. Em qual mês houve o maior número de casos confirmados?**

- Março registrou o maior número de casos confirmados, com mais de 2 milhões de pessoas infectadas.

**3. Qual foi a região mais afetada pela COVID-19 em 2021?**

- São Paulo foi a região mais afetada em 2021, com mais de 100 mil mortes e mais de 2 milhões de casos registrados.

**4. Quais foram os estados menos afetados em termos de mortes e casos?**
- Acre, Amapá e Roraima foram os estados menos afetados, com menos de 60 mil casos e menos de 5 mil mortes em cada um.

**5. Como foi a evolução do número de mortes ao longo do ano após o pico em abril?**

- Após o pico de mortes em abril, os números começaram a diminuir, chegando a pouco mais de 4 mil mortes em dezembro, uma queda significativa em comparação com o pico de 82 mil.

**6. Qual foi o período com o maior número de casos confirmados?**
- O período de março a junho foi marcado pelo maior número de casos, concentrando a maioria das infecções durante o ano.

## 📝 Storytelling:

Durante o ano de 2021, a pandemia de COVID-19 teve um impacto profundo no Brasil, com momentos de grande preocupação. Abril foi o mês mais sombrio, quando o número de mortes alcançou um pico trágico de mais de 82 mil vítimas. Em março, o país registrou o maior número de casos confirmados, com mais de 2 milhões de pessoas infectadas.

São Paulo se destacou como a região mais afetada, com um total superior a 100 mil mortes e mais de 2 milhões de casos ao longo do ano. Em contrapartida, os estados de Acre, Amapá e Roraima foram os menos impactados, registrando menos de 60 mil casos e menos de 5 mil mortes cada.

Após o devastador pico de abril, o número de mortes começou a diminuir gradativamente, atingindo pouco mais de 4 mil em dezembro. O período mais crítico em termos de novos casos ocorreu entre março e junho, quando a maior parte das infecções foi registrada.
