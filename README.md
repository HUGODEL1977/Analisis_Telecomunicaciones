# Análisis_Datos_Telecomunicaciones.

<img width="521" alt="image" src="https://github.com/HUGODEL1977/Analisis_Telecomunicaciones/assets/128526281/b3b11607-fafb-4913-b82c-3cc00c4f7a5f">


 
# Análisis de Acceso a Internet y Telefonía Móvil en Argentina.


# Introducción


Este análisis exhaustivo se centra en el acceso a Internet y la telefonía móvil en Argentina. Exploramos detalladamente datos relacionados a Internet y la evolución de la telefonía móvil en el país. Los hallazgos se dividen en dos secciones: # Acceso a Internet con seis archivos y  # Telefonía Móvil con tres archivos, en estas dos secciones hay archivos cleaned o limpios que se cargan en el repositorio y con los que se trabajaron los EDA correspondientes, los archivos iniciales con los que se realizo el ETL, estaran en dos archivos de Google Drive, se dejan a continuacion : https://drive.google.com/drive/folders/10AR-QdZiqyQuLuqPIRBCV6aM899ZoYAI?usp=drive_link
               https://drive.google.com/drive/folders/1sUqQ9ughzbBPpQIj5I6vmWhSiyfUGhzy?usp=drive_link



# ACCESO A INTERNET

Datos y Rutas de Archivos


Para llevar a cabo el análisis del acceso a Internet, se recopilaron diversos conjuntos de datos. En esta sección, proporcionamos detalles sobre los datos y cómo acceder a ellos.


Resumen de Datos


En esta sección, ofrecemos una visión general de los datos clave. Esto incluye una descripción de las columnas más importantes y las primeras filas de datos para una comprensión inicial.


Evolución de Acceso a Internet


Hemos realizado un análisis temporal para visualizar la evolución del acceso a Internet en Argentina. Los resultados se presentan en gráficos que muestran la penetración de Internet en hogares y habitantes a lo largo del tiempo, destacando un crecimiento constante en penetracion y acceso de internet y su volumen de ingresos a lo largo de los años.


Detección de Valores Atípicos


Para garantizar la calidad de los datos, llevamos a cabo un proceso de detección de valores atípicos. Los resultados se presentan en gráficos de dispersión para resaltar observaciones inusuales.


Análisis de Correlación


En esta sección, realizamos un análisis de correlación entre las diversas tecnologías de acceso a Internet, identificando relaciones y tendencias significativas.


# KPI Propuesto


El KPI propuesto mide el aumento del acceso al servicio de Internet fijo para el próximo trimestre, por cada 100 hogares, por provincia. La fórmula para calcular el KPI es la siguiente:


KPI = ((NuevoAcceso - AccesoActual) / AccesoActual) * 100 Se calcula el valor del "Nuevo acceso" para el cuarto trimestre de 2022, aumentando en un 20% con base en el tercer trimestre de 2022.


Visualización


El análisis incluye una visualización que compara los accesos por cada 100 hogares en el tercer trimestre de 2022 y el cuarto trimestre de 2022 con el aumento propuesto. El gráfico muestra la penetración por provincia.


Resultados


Los resultados de este análisis son los siguientes:


Total de accesos por cada 100 hogares en el tercer trimestre de 2022: 1633. Total de accesos por cada 100 hogares en el cuarto trimestre de 2022 (con 20% de aumento): 1959.6.


Ejecución del Código El código proporcionado se puede ejecutar en un entorno de Python con las bibliotecas requeridas instaladas. Se aseguro que la ruta del archivo CSV sea correcta antes de ejecutar el código.


# TELEFONIA MOVIL


Datos y Resumen


El análisis de la telefonía móvil se basa en conjuntos de datos similares a los del acceso a Internet. Aquí proporcionamos un resumen de estos datos y su estructura.
Tasa de Crecimiento Anual (KPI)


Destacamos un indicador clave de desempeño (KPI) que calcula la tasa de crecimiento anual de los accesos operativos de telefonía móvil. Los resultados se presentan en gráficos de barras.


# KPI: Tasa de Crecimiento Anual de los Accesos Operativos


Este repositorio presenta un KPI propuesto por el alumno Henry Hugo Hernan Delgado Osorio, llamado "Tasa de Crecimiento Anual de los Accesos Operativos". Este KPI proporciona una idea de cómo han evolucionado los accesos operativos año tras año.


# Descripción


El KPI "Tasa de Crecimiento Anual de los Accesos Operativos" se calcula siguiendo un proceso que implica:


1.	Agrupar los datos por año.


2.	Calcular la suma total del "Total de accesos operativos" para cada año.


3.	Calcular la tasa de crecimiento anual utilizando la fórmula:
   

TasadeCrecimientoAnual = ((AccesosOperativosdelActual - AccesosOperativosdelAñoAnterior) / AccesosOperativosdelAñoAnterior) * 100 Los resultados se muestran en forma de una serie de tiempo que indica la tasa de crecimiento anual de los accesos operativos durante varios años.


Ejecución del Código


El código necesario para calcular la Tasa de Crecimiento Anual se encuentra en el archivo proporcionado.


Resultados Los resultados del cálculo de la Tasa de Crecimiento Anual se presentan en una serie de tiempo que muestra la evolución de los accesos operativos año tras año.


Los resultados se presentan en porcentaje y proporcionan información valiosa sobre la tendencia de crecimiento.


A continuación, se muestra un ejemplo de los resultados:


Año 2014 -7.143718 

2015 -1.493263 

2016 3.394120 

2017 -0.340904 

2018 -5.029213 

2019 -3.818550 

2020 18.968461 

2021 -15.282524 

2022 3.056367

Name: Total de accesos operativos


Visualización


Además de los resultados numéricos, se incluye una visualización que representa la Tasa de Crecimiento Anual en un gráfico de barras. Este gráfico proporciona una representación visual de la evolución de los accesos operativos año tras año.


Evolución de la Telefonía Móvil


Exploramos la evolución de los accesos pospago y prepago a lo largo de varios años, identificando una tendencia inversa.


Correlación en Telefonía Móvil


Realizamos un análisis de correlación en los datos de telefonía móvil, enfocándonos en las relaciones entre los accesos pospago, prepago y operativos.


Mapa de Calor de Correlación


Para una visualización efectiva, presentamos un mapa de calor que revela la correlación entre las diferentes variables de telefonía móvil.


# Conclusiones


En resumen, este análisis de datos destaca una tendencia constante en el acceso a Internet y la telefonía móvil en Argentina. Hemos identificado correlaciones significativas y detectado valores atípicos que proporcionan información valiosa para comprender el panorama de las telecomunicaciones en el país.


# Tecnologías Utilizadas


Este proyecto de análisis se realizó utilizando tecnologías clave, como Python, Pandas para el manejo de datos, Matplotlib para visualizaciones y Jupyter Notebook para el desarrollo. Los datos utilizados son de dominio público y se emplearon únicamente con fines de análisis e ilustración.



# Requisitos


Para ejecutar este análisis, nos aseguramos de tener las siguientes bibliotecas instaladas:


import pandas as pd


import numpy as


import seaborn as sns


import matplotlib.pyplot as plt


# Disclaimer


De parte del equipo de Henry se quiere aclarar y remarcar que los fines de los proyectos propuestos son exclusivamente pedagógicos, con el objetivo de realizar proyectos que simulen un entorno laboral, en el cual se trabajen diversas temáticas ajustadas a la realidad. No reflejan necesariamente la filosofía y valores de la organización. Además, Henry no alienta ni tampoco recomienda a los alumnos y/o cualquier persona leyendo los repositorios (y entregas de proyectos) que tomen acciones en base a los datos que pudieran o no haber recabado. Toda la información expuesta y resultados obtenidos en los proyectos nunca deben ser tomados en cuenta para la toma real de decisiones (especialmente en la temática de finanzas, salud, política, etc


Hugo Hernan Delgado Osorio


correo electronico: hugohernandelgadoo@gmail.com


GITHUB HUGODEL1977

