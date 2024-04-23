
<h1 align="center"> PROYECTO INDIVIDUAL 2 </h1>

# <h2 align="center">**`Análisis de Datos de Siniestros Viales en CABA`**</h2>

## Introduccion
Este proyecto fue llevado a cabo con el rol simulado de un Analista de Datos en una consultora, con el objetivo de llevar a cabo un análisis de datos solicitado por el Observatorio de Movilidad y Seguridad Vial (OMSV) de la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires (CABA).

El objetivo de este proyecto es descubrir insights para la toma de decisiones fundamentada, dirigida a mejorar la prevención, la mejora de la seguridad vial, y la reducción de los accidentes de tránsito con víctimas fatales en la Ciudad de Buenos Aires.

## Contexto
Los siniestros viales, son eventos que involucran vehículos en las vías públicas y que pueden tener diversas causas, como colisiones entre automóviles, motocicletas, bicicletas o peatones, atropellos, choques con objetos fijos o caídas de vehículos.

Buenos Aires, la ciudad más poblada de Argentina, enfrenta desafíos significativos en términos de seguridad vial debido a su densa población y actividad vehicular. La reducción de la mortalidad en accidentes de tráfico es esencial para mejorar la calidad de vida de sus habitantes.

## Estructura del Repositorio 

-   **[Datasets](https://github.com/pablongrs/PI02-Siniestros-viales/tree/master/Datasets)**: Es la carpeta que contiene los datasets utilizados en el proyecto. Aqui podemos encontrar el archivo **`homiciodios.xlsx`** el cual contiene 2 dataset "Hechos" y "Victimas"

-   **[ETL](https://github.com/pablongrs/PI02-Siniestros-viales/blob/master/Notebooks/ETL-Homicidios.ipynb)**: En este archivo se lleva a cabo el proceso de Extracción, Transformación y Carga de datos. Esto incluye la eliminación de datos nulos y duplicados, así como de columnas innecesarias. Se realizan ajustes en los tipos de datos, se rellenan valores faltantes y se lleva a cabo la unión de las tablas para crear un conjunto de datos limpio para su posterior análisis.

-   **[EDA](https://github.com/pablongrs/PI02-Siniestros-viales/blob/master/Notebooks/EDA.ipynb)**: Es el archivo que contiene el análisis exploratorio de datos. Este nos ayuda a conocer a profundidad los datos de los cuales extraeremos la información crucial para desarrollar la toma de decisiones.

-   **[Dashboard](3-Dashboard.pbix)**: Este archivo contiene el panel de control creado en Power BI, el cual ofrece visualizaciónes interactivas de los datos para facilitar la comprensión y el análisis. Este presenta una variedad de gráficosque permiten explorar los datos de manera dinámica.

## Tecnologias
Para el desarrollo de este proyecto, se utilizó el lenguaje Python junto con la libreria Pandas para la extracción, transformación y carga de los datos. Además, se empleó Geopy para la imputación de valores faltantes en longitud y latitud. Y para el análisis exploratorio de datos y las visualizaciones, además de las mencionadas, se usaron Matplotlib y Seaborn.

En última etapa, para la elaboración del dashboard interactivo, se utiliza Power BI.

