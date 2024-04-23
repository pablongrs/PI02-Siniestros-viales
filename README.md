
<h1 align="center"> PROYECTO INDIVIDUAL 2 </h1>

# <h2 align="center">**`Análisis de Datos de Siniestros Viales en CABA`**</h2>

## Introduccion
Este proyecto fue llevado a cabo con el rol simulado de un Analista de Datos en una consultora, con el objetivo de llevar a cabo un análisis de datos solicitado por el Observatorio de Movilidad y Seguridad Vial (OMSV) de la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires (CABA).

El objetivo de este proyecto es descubrir insights para la toma de decisiones fundamentada, dirigida a mejorar la prevención, la mejora de la seguridad vial, y la reducción de los accidentes de tránsito con víctimas fatales en la Ciudad de Buenos Aires.

## Contexto
Los siniestros viales, son eventos que involucran vehículos en las vías públicas y que pueden tener diversas causas, como colisiones entre automóviles, motocicletas, bicicletas o peatones, atropellos, choques con objetos fijos o caídas de vehículos.

Buenos Aires, la ciudad más poblada de Argentina, enfrenta desafíos significativos en términos de seguridad vial debido a su densa población y actividad vehicular. La reducción de la mortalidad en accidentes de tráfico es esencial para mejorar la calidad de vida de sus habitantes.

## Tecnologias
Para el desarrollo de este proyecto, se utilizó el lenguaje Python junto con la libreria Pandas para la extracción, transformación y carga de los datos. Además, se empleó Geopy para la imputación de valores faltantes en latitud y longitud. Para el análisis exploratorio de datos y las visualizaciones, además de las mencionadas, se usaron Matplotlib y Seaborn.

En última etapa, para la elaboración del dashboard interactivo, se utiliza Power BI.

## Estructura del Repositorio 

-   **[Datasets](https://github.com/pablongrs/PI02-Siniestros-viales/tree/master/Datasets)**: Es la carpeta que contiene los datasets utilizados en el proyecto. Aqui podemos encontrar el archivo **`homiciodios.xlsx`** el cual contiene 2 dataset "Hechos" y "Victimas"

-   **[ETL](https://github.com/pablongrs/PI02-Siniestros-viales/blob/master/Notebooks/ETL-Homicidios.ipynb)**: En este archivo se lleva a cabo el proceso de Extracción, Transformación y Carga de datos. Esto incluye la eliminación de datos nulos y duplicados, así como de columnas innecesarias. Se realizan ajustes en los tipos de datos, se rellenan valores faltantes y se lleva a cabo la unión de las tablas para crear un conjunto de datos limpio para su posterior análisis.

-   **[EDA](https://github.com/pablongrs/PI02-Siniestros-viales/blob/master/Notebooks/EDA.ipynb)**: Es el archivo que contiene el análisis exploratorio de datos. Este nos ayuda a conocer a profundidad los datos de los cuales extraeremos la información crucial para desarrollar la toma de decisiones.

-   **[Dashboard](3-Dashboard.pbix)**: Este archivo contiene el panel de control creado en Power BI, el cual ofrece visualizaciónes interactivas de los datos para facilitar la comprensión y el análisis. Este presenta una variedad de gráficos que permiten explorar los datos de manera dinámica.


### KPI
Se establecieron dos objetivos para reducir la cantidad de víctimas muertes en los accidentes viales. Se proponen dos indicadores de rendimiento clave o KPI. Estos son:

- **Tasa de Homicidios**: Reducción del 10% en la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con el semestre anterior.

Para el primer semestre del año 2021, la Tasa de Homicidios fue de 1.76, indicando que durante los primeros 6 meses del año hubo aproximadamente 1.76 homicidios en accidentes de tránsito por cada 100,000 habitantes.
Para el segundo semestre del año 2021 se obtiene que la Tasa de Homicidios fue de 1.35, lo que significa que se logró cumplir objetivo propuesto

- **Accidentes Mortales de Motociclistas**: Reducción del 7% en la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior.

Al calcular la Cantidad de Accidentes Mortales de Motociclistas para el año 2021, se obtuvo un valor de -53.33, lo que indica un aumento del 53.33% en la cantidad de muertes de conductores de motocicletas en comparación con el año 2020. Este resulado negativo indica que no se cumplió con el objetivo.

## Conclusiones

