# Analisis de las startups unicornio en el mundo.

En los últimos años, se ha visto un aumento en el número de startups que han alcanzado la valoración de unicornio, es decir, han alcanzado un valor de mercado de mil millones de dólares o más. A medida que este fenómeno continúa creciendo, se hace cada vez más importante entender los factores que contribuyen al éxito de estas startups. En este análisis EDA, se explorará un conjunto de datos que contiene información sobre las startups unicornio en todo el mundo, con el objetivo de identificar patrones y tendencias que puedan ayudar a entender los factores clave detrás del éxito de estas empresas emergentes. A través de este análisis, esperamos descubrir información valiosa para emprendedores, inversores y otros interesados en el mundo de las startups y la innovación empresarial.

------

## Data

He usado un dataset de Kaggle de las [startup que han llegado a convertirse en unicornio](https://www.kaggle.com/datasets/uzairrehman/world-wide-unicorn-startups) en todo el mundo y el conjunto de datos contiene las siguientes características:


- Company: Compañia que ha conseguido convertirse en unicornio. 
- Valuation: Valor de la compañia.
- Date: Fecha en la que se convirtio unicornio.
- Country: País al que pertenece la compañia.
- City: Ciudad a la que pertenece la compañia.
- Industry: Industria a la que pertenece la compañia.
- Investors: Inversores.
- Year: Año en el que convirtio en unicornio. 
- Month: Meses en el que convirtio en unicornio. 
- Day: Día en el que se convirtió en unicornio. 

-----

## Hipótesis

-  A partir del año 2020 se observa una tendencia positiva en el número de startups que alcanzan el estatus de unicornio. 
- Hay una relación entre la ubicación geográfica y el éxito de una startup
- Existen diferencias en la valoración promedio de las startups unicornio según el país en la que se encuentran.
- Existen ciudades específicas donde se concentra una cantidad significativa de startups unicornio.
- Hay patrones estacionales en el momento en que las startups alcanzan el estatus de unicornio

Para probar las anteriores hipotesis utilicé las siguientes librerias:


<img src = 'fotos readme/librerias.png'>



Junto a las siguientes pruebas estadísticas: 
- D'Agostino-Pearson: Para ver si mis datos seguian una distribución normal o no.
- Chi cuadrado: Nos permite evaluar si hay una relación significativa entre las variables.
- Kruskall-Wallis: Para determinar si hay evidencia de estacionalidad en la cantidad de empresas unicornio registradas por mes en los datos que se tienen.


-----
## Resultados


- Confirmamos una tendencia muy positiva del surgimiento de unicornios sobretodo a partir del 2020

<img src = 'fotos readme/hipotesis1.png'> 

- Los países líderes son Estados Unidos, China e India. (Exitosas = por encima de la mediana del valor. No exitosa = por debajo de la mediana)

<img src = 'fotos readme/hipotesis2.png'>

- La Inteligencia Artificial, Automoción y Transporte, y Fintech son las industrias con más unicórnios y las que más valor tienen. 

<img src = 'fotos readme/industrias.png'>

- San Francisco, Nueva York, Beijing y Londres son las ciudades más interesantes a la hora de invertir en este tipo de compañias.

<img src = 'fotos readme/hipotesis4.png'>

- Suecia es el país donde, en promedio, los unicornios tienen un mayor valor. 

<img src = 'fotos readme/hipotesis3.png'>

- No hay un "momento perfecto" para invertir. Es decir, no se observan patrones estacionales en el nacimiento de los unicornios. 

<img src = 'fotos readme/hipotesis5.png'>
