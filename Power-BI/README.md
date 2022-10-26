
## Información a analizar

La información analizada proveniente del [WorldBank](https://data.worldbank.org/) y la [OMS](https://www.who.int/es/data), fue discretizada en 5 regiones, en donde se intentó tomar regiones y países representativos en cantidad de población y que compartieran rasgos en común, así:


1. Latin America & Caribeann(CLA)
   BRA(Brazil)-MEX(Mexico)-COL(Colombia)-ARG(Argentina)-PER(Peru)-CHL(Chile)

2. Africa(AFR)
   NGA(Nigeria)-ETH(Ethiopia)-EGY(Egipto)-COD(Congo)-TZA(Tanzania)-ZAF(South Africa)
3. European Union(EUU)
   DEU(Germany)-FRA(Francia)-ITA(Italia)-ESP(España)-POL(Polonia)-ROU(Romania)
4. South Asia(SAS)
   IND(India)-PAK(Pakistan)-BGD(Bangladesh)-AFG(Afghanistan)-NPL(Nepal)-LKA(Sri Lanka)
5. World(WLD)
   CHN(China)-RUS(Rusia)-USA(United States)-IDN(Indonesia)-GBR(Gran Bretaña)-AUS(Australia)



Notas:

- La región "World" fue creada para incluir aquellos países referentes a nivel mundial que quedaron fuera de la selección de regiones representativas, por lo que es posible que sus valores presenten comportamientos no correlacionados entre sí.
- En la región CLA se decidió excluir a Venezuela toda vez que la información disponible presentaba mala calidad en cuanto a la cantidad de datos y se incluyó Chile.

## KPIs

De acuerdo a diversas fuentes consultadas, entre ellas la OMS y la tesis de grado en Economía [La relación entre esperanza de vida, desarrollo económico y medio ambiente]([https://ruc.udc.es/dspace/bitstream/handle/2183/16409/RodriguezRodriguez_David_TFG_2015.pdf?sequence=2](https://ruc.udc.es/dspace/bitstream/handle/2183/16409/RodriguezRodriguez_David_TFG_2015.pdf?sequence=2)) de David Rodríguez Rodríguez en la Universidad de la Coruña, la Esperanza de vida al nacer tiene una estrecha relación con el nivel de desarrollo del país, medido en cuanto a su PBI per cápita. Así las cosas, uno de los KPIs se definió basado en esta información y teniendo en cuenta la clasificación según los niveles de ingresos establecidos por el [Banco Mundial](https://blogs.worldbank.org/es/datos/nuevas-clasificaciones-de-los-paises-elaboradas-por-el-banco-mundial-segun-los-niveles-de-ingreso).

Por otra parte, teniendo en cuenta que la Esperanza de vida al nacer es una medida del promedio de edad en que las personar fallecieron en un periodo de tiempo, en este caso se mide de forma anual, es entendible que un factor que puede llegar a castigar en gran medida este valor es el de la mortaliada infantil, debido a que, en términos estádisticos, la muerte de niños pesa mucho en el promedio en que se basa esta medida. Al respecto, la OMS ha fijado como [meta](https://www.who.int/es/news-room/fact-sheets/detail/children-reducing-mortality) para el 2030, que la mortalidad infantil sea menor a 25 muertes por cada 1000 niños, esta meta ha sido definida como objetivo para la medición de otro de los KPI.

En línea con lo anterior, de acuerdo con la publicación de la OMS [Hypertension](https://www.who.int/news-room/fact-sheets/detail/hypertension), la hipertensión es la mayor causa de muerte prematura a nivel mundial, por lo que controlar el valor de prevalencia de esta afección en los adultos, puede impactar de forma positiva a la Esperanza de vida. De nuevo, se tiene como parámetro la [meta](https://www.who.int/news-room/fact-sheets/detail/hypertension) establecida por la OMS de disminuir la prevalencia de hipertensión en adultos a un 33%, para acotar un KPI basado en lo aquí indicado.

Finalmente, teniendo en cuenta el objetivo general del proyecto, concerniente a la Esperanza de vida, se definió un KPI para comparar esta medida por país respecto al comportamiento promedio de los demás países de la región.

En resumen, se definieron los siguientes KPIs para medir y entender mejor el comportamiento de la esperanza de vida de los países:

1. Expectativa de vida sobre el promedio, objetivo: superior al promedio
2. PIB per cápita, objetivo: Mayor a USD 12.535 alto, entre USD 12.535 y USD 1.036 medio y menor a USD 1.036 bajo.
3. Mortalidad infantil, objetivo: Menor a 25 muertes por cada 1000 niños.
4. Hipertensión, objetivo: Menor a 33% en la prevalencia en adultos.

## Power BI

Para la realización del análisis de la información se usó el programa Power BI, ya que el mismo presenta herramientas de conexión con Azure que facilita el procesamiento de los datos provenientes de SQL.

Se realizaron los siguientes pasos para disponibilizar la información en el programa:

- Conexión a SQL Server a las Tablas DWH Countries, DWH Series y XXX
- Creación en Power Query de la tabla Regions
- Anulación de la dinamización de las columnas correspondientes a las series en la tabla XXX e inclusión de la información de región.
- Verificación del modelo relacional

![1666756143556](image/README/1666756143556.png)

Una vez realizados los anteriores pasos, se elaboró el Dashboard para el análisis de la información. Este consta de una portada con vínculos a las demás páginas, una página denominada "Principal" en donde se puede explorar la data de todas las regiones y 5 hojas más correspondientes a las diferentes regiones definidas para el análisis.

- Portada

![1666766441753](image/README/1666766441753.png)

- Principal

![1666767611685](image/README/1666767611685.png)

- Región

![1666767718339](image/README/1666767718339.png)

## Análisis

...
