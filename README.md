#
# [![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&duration=2000&pause=2000&color=1AA9F7&width=435&lines=En+Datos+basamos+nuestro+trabajo+para+brindar;%E2%9C%94++An%C3%A1lisis+y+soluciones++inteligentes++)](https://git.io/typing-svg)
![portada](https://user-images.githubusercontent.com/93687273/196827800-f59a9384-a362-4804-8fe5-601c9a3b0a58.png)
## Video proyecto: 
<iframe width="560" height="315" src="https://www.youtube.com/embed/n5r_dq2Oa5I" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

#
# [![Typing SVG](https://readme-typing-svg.demolab.com?font=Cinzel&size=35&pause=10000&color=72F722&width=455&lines=Life+Expectancy)](https://git.io/typing-svg)
Este proyecto esta basado en determinar ciertos aspectos que influyen en la expectativa de vida en distintas regiones del mundo.
Para ello se utilizaron datos extraídos del  [WorldBank](https://data.worldbank.org/) y la [OMS](https://www.who.int/es/data).
#
## [![Typing SVG](https://readme-typing-svg.demolab.com?font=Yrsa&pause=10000&color=F7F7F7&width=535&lines=Series+%3A)](https://git.io/typing-svg)
Se utilizaron 14 series , las cuales 12 son provenientes del [WorldBank](https://data.worldbank.org/) y 2 de la [OMS](https://www.who.int/es/data), los datos extraídos estuvieron en un intervalo de 30 años (1990-2020)

|  Adolescent fertility rate (births per 1,000 women ages 15-19) | Birth rate, crude (per 1000 people) | Current health expenditure (% of GDP) |GDP per capita(current US$)    |Current health expenditure per capita (current US$)  | Fertility rate, total (births per woman)  |Life expectancy at birth, total (years)   | Mortality rate, infant (per 1,000 live births)  | Population growth (annual %) | Population, total  | Suicide mortality rate (per 100,000 population)  |GDP(current US$)   | BMI &GreaterEqual; 25 (crude estimate) (%)  | Prevalence of hypertension among adults aged 30-79 years  |          
| ----------- | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |  ------------ | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png)  | ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png)   |  ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png)  |  ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png) | ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png)  | ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png)  | ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png)  | ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png)  | ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png)   |  ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png) |![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png)   | ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png)  |   ![](https://www.un.org/youthenvoy/wp-content/uploads/2014/09/WHO.jpg) | ![](https://www.un.org/youthenvoy/wp-content/uploads/2014/09/WHO.jpg)  |
| 1(WB)  |2(WB)   |3(WB)   | 4(WB)  | 5(WB)  | 6(WB)  | 7(WB)  | 8(WB)  | 9(WB)  | 10(WB)  | 11(WB)  | 12(WB) | 13(OMS)  | 14(OMS)  |
#
#### Análisis Exploratorio (EDA)
#
Se hizo uso de un análisis exploratorio   para detectar características concretas o anormales 
de tal manera que podamos inferir  la influencia de ciertos parametros en la expectativa de vida.
- Mediante graficos y de manera intuitiva se pueden visualizar en el apartado (Graficas x Series) dentro de  esta   [aplicación](https://brakions-streamlit-test-app-ifwq1h.streamlitapp.com/) hecha en [Streamlit](https://streamlit.io/).

![seriesxregion](https://user-images.githubusercontent.com/93687273/196828202-24ce1011-dc1b-481c-8c19-54a8476f772c.png)


#
#### Análisis Predictivo
#
Se identificaron las relaciones que existen entre las variables en eventos pasados para luego explotarlas y predecir lo que puede ocurrir si ciertas estadisticas varían, se utilizó RandomForestRegression para esta [aplicación](https://brakions-streamlit-test-app-ifwq1h.streamlitapp.com/), se estandarizaron los valores de -2 a 2.

![predict](https://user-images.githubusercontent.com/93687273/196829652-3e0ba988-7e68-4b50-bc89-f5fdc0466781.png)


