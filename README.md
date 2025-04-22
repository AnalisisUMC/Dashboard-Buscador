# Dashboard-Buscador
Código en Shiny para generar un buscador de los productos generados por la UMC a partir de palabras clave
# Librerias requeridas
- library(foreign)       # Permite importar y exportar datos en formatos de otros programas como SPSS, SAS, Stata, etc.
- library(haven)         # Proporciona funciones para leer y escribir archivos en formatos como SAS, SPSS y Stata.
- library(openxlsx)      # Permite leer, escribir y manipular archivos de Excel (.xlsx) sin necesidad de Java.
- library(readxl)        # Ofrece funciones para leer archivos Excel (.xls y .xlsx).
- library(tidyverse)     # Conjunto de librerías para la manipulación y visualización de datos (incluye dplyr, ggplot2, tidyr, entre otros).
- library(ggplot2)       # Librería para crear gráficos en R basada en la gramática de gráficos, excelente para visualizaciones personalizadas.
- library(fst)           # Facilita la lectura y escritura de datos en un formato binario eficiente para grandes volúmenes de datos.
- library(ggpubr)        # Extiende ggplot2 para crear gráficos complejos y presentables, añadiendo funciones como exportar y personalizar.
- library(flexdashboard) # Permite crear paneles interactivos con R Markdown, ideal para la presentación de análisis de datos.
- library(shiny)         # Framework para construir aplicaciones web interactivas utilizando R.
- library(DT)            # Crea tablas interactivas utilizando la tecnología JavaScript DataTables.
- library(shinydashboard) # Facilita la creación de dashboards interactivos con Shiny, proporcionando un diseño visual atractivo y funcional.
- library(stringr)       # Proporciona funciones útiles para manipular y trabajar con cadenas de texto.

# Descripción
El dashboard presenta un buscador de investigaciones que se alimenta de una base de datos que incluye los documentos elaborados por la UMC entre los años 2013 y 2024. Incluye documentos de las colecciones de Aportes Metodológicos, Estudios breves, Estudios especiales, Evaluaciones y Factores Asociados y Zoom educativo. Para esto, se generaron palabras clave para cada documento a partir de distintos criterios. Entre ellos: Año de publicación, Población, Pruebas, Diseño, Variables, Evaluación, Fuente de datos y Responsables. 
En la primera pestaña, se selecciona o se escribe la palabra clave de interés. Luego, se presiona el botón "Buscar". 

![image](https://github.com/user-attachments/assets/bfd510f9-36e2-481c-ae67-4967f776e06b)

En la segunda pestaña, aparece el listado de documentos que incluyen dichas palabras clave. 

![image](https://github.com/user-attachments/assets/a72df1c4-b208-4896-bd84-139e52f8ae13)
