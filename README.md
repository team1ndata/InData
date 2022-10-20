![portada](https://user-images.githubusercontent.com/93687273/196827800-f59a9384-a362-4804-8fe5-601c9a3b0a58.png)


# Life Expentacy
Este proyecto esta basado en determinar ciertos aspectos que influyen  en la espectativa de vida en distintas regiones del mundo.
Para ello se utilizaron datos extraidos del  [WorldBank](https://data.worldbank.org/) y la [OMS](https://www.who.int/es/data).
#### Series
Se utilizaron 13 series , las cuales 11 son provenientes del [WorldBank](https://data.worldbank.org/) y 2 de la [OMS](https://www.who.int/es/data), los datos extraidos estuvieron en un intervalo de 30 años (1990-2020)

|  Adolescent fertility rate (births per 1,000 women ages 15-19) | Birth rate, crude (per 1000 people) | Current health expenditure (% of GDP) | Current health expenditure per capita (current US$)  | Fertility rate, total (births per woman)  |Life expectancy at birth, total (years)   | Mortality rate, infant (per 1,000 live births)  | Population growth (annual %) | Population, total  | Suicide mortality rate (per 100,000 population)  |GDP(constant LCU)   | BMI &GreaterEqual; 25 (crude estimate) (%)  | revalence of hypertension among adults aged 30-79 years  |
| ----------- | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |  ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png)  | ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png)   |  ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png)  |  ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png) | ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png)  | ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png)  | ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png)  | ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png)  | ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png)   |  ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png) | ![](https://logos-download.com/wp-content/uploads/2016/03/The_World_Bank_Group_logo.png)  |   ![](https://www.un.org/youthenvoy/wp-content/uploads/2014/09/WHO.jpg) | ![](https://www.un.org/youthenvoy/wp-content/uploads/2014/09/WHO.jpg)  |
| 1(WB)  |2(WB)   |3(WB)   | 4(WB)  | 5(WB)  | 6(WB)  | 7(WB)  | 8(WB)  | 9(WB)  | 10(WB)  | 11(WB)  | 12(OMS)  | 13(OMS)  |

#### Análisis Exploratorio (EDA)
Se hizo uso de un análisis exploratorio   para detectar características concretas o anormales 
de tal manera que podamos inferir  la influencia de ciertos parametros en la espectativa de vida.
- Mediante graficos y de manera intuitiva se pueden vizualizar en el apartado (Graficas x Series) dentro de  esta   [aplicación](https://brakions-streamlit-test-app-ifwq1h.streamlitapp.com/) hecha en [Streamlit](https://streamlit.io/).

![seriesxregion](https://user-images.githubusercontent.com/93687273/196828202-24ce1011-dc1b-481c-8c19-54a8476f772c.png)



#### Análisis Predictivo
Se identificaron las relaciones que existen entre las variables en eventos pasados para luego explotarlas y predecir lo que puede ocurrir si ciertas estadisticas varian, se utilizo RandomForestRegression para esta [aplicación](https://brakions-streamlit-test-app-ifwq1h.streamlitapp.com/), se estandarizaron los valores de -2 a 2.

![predict](https://user-images.githubusercontent.com/93687273/196829652-3e0ba988-7e68-4b50-bc89-f5fdc0466781.png)
