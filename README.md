<p align='center'>
<img src ="https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png">
<p>

<h1 align='center'>
 <b>PROYECTO INDIVIDUAL Nº2</b>
</h1>
 
# <h1 align="center">**`Mercado bursátil`**</h1>

# <h1 align="center">**`By: JAVIER HORACIO VILCA MARTINEZ`**</h1>


<p align='center'>
<img src = 'https://www.ifcmarkets.com/uploads/image/moverv_thumbs/2ded1b3bb8299ab33d4edb004ff8086202018feb.png' height = 400>
<p>


# <h2 align="center">**` Análisis Exploratorio de los datos`(_Exploratory Data Analysis = EDA_)`**</h2>



Se busco una lista de las empresas que pertenecen al mercado bursátil que pertenecen a SP500 para luego poder descargar los datos de la empresas desde el año 2000 hasta la fecha, para posterior tratamiento de los datos con los mismo se hizo un análisis de Open-Close y Volumen que nos permite tener  una expectativa de las empresas que mejor números tuvieron, en base a eso se selecciono a las 5 empresas mejor posicionadas por el análisis, descargamos los datos de las empresas seleccionadas y creamos un DataFrame integrando las mismas.
Genere un resumen de estadísticas descriptivas del datasets mediante el uso   del comando describe () de la librería de pandas la cual muestra valores como ser la mediana, varianza, valor mínimo, valor máximo, quartiles y cantidad de datos.
Realice el análisis univariados de los valores de apertura y cierre de las acciones de cada empresa mediante el uso de la librería matplotlib, del cual podemos observar la frecuencia con que valores cierran y abren en cada día.
Los análisis bivariados de correlación entre variables numéricas de los datos de apertura, cierre, volumen y cierre mediante el uso de las librerías matplotlib, seaborn obtenemos la correlación entre las variables numéricas y/o categóricas.
Para la búsqueda de Outliers se usaron tres métodos:
1.	Uso de Boxplot: Podemos utilizar un boxplot para visualizar los valores atípicos de un conjunto de datos, los valores atípicos se identifican como puntos fuera de los bigotes (whiskers) del boxplot.
2.	Método Z-score: Podemos utilizar el Z-score para detectar valores atípicos en nuestro DataFrame, los valores atípicos son aquellos puntos de datos cuyo valor absoluto del Z-score es mayor que 3.
3.	Método de intercuartil: El método de intercuartil se basa en el rango intercuartil (IQR) para detectar valores atípicos, los mismos se identifican como aquellos puntos de datos que están por debajo de Q1 – 1.5*IQR o por encima de Q3 + 1.5 *IQR
Se puede observar que los valores outliers de cada empresa son muy pocos.


 # <h2 align="center">**`Dashboard`**</h2>
 


El dashboard fue desarrollado usando Power BI en el cual podemos observar la relación entre los diferentes cambios  en la acciones respecto del tiempo, se pueden observar las variaciones que existen en las acciones entre el precio de apertura y el precio de cierre mediante el cual a través de los años podemos concluir en que ocasiones el precio de las acciones pierden valor y se observa que la empresa:
1.	GWW(W. W. Grainger) en el año 2003 tuvo una pequeña caída en el precio junto a los años 2018, 2021 . 
2.	NVR(NVR, Inc.) en el año 2018 tuvo una perdida importante del valor de las acciones.
3.	AZO(AutoZone) en el año 2015, 2018 su caída del precio no fue grande en el año 2020 ahí si podemos observar un gran descenso del precio de la acción.
4.	MTD(Mettler Toledo) en el año 2018 es su única caída del precio de las acciones.
5.	ORLY(O'Reilly Auto Parts) en el año 2017, 2020 y en la actualidad esta teniendo una baja en el precio de las acciones

