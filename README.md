
**Análisis de datos del sistema Citi Bike - Nueva York**

**Resumen del Proyecto**

Este repositorio contiene un proyecto completo de análisis de datos sobre el uso del sistema de bicicletas compartidas "Citi Bike", en la ciudad de Nueva York. El objetivo principal es analizar los patrones de uso, el comportamiento de los diferentes tipos de usuarios y las zonas de mayor demanda a través de un conjunto de procedimientos que abarcan desde la limpieza y transformación hasta la visualización y la creación de un dashboard operativo.

-> Para un análisis detallado de los hallazgos y conclusiones, por favor, consulte el **Informe completo del análisis.**

**Estructura del Repositorio**

/data/: 

Contiene los datasets utilizados.
    /datos brutos/
    /processed/: 
        (trips_final_for_analysis.csv) Dataset final y limpio utilizado para el análisis y el dashboard.
        (trips_cleaned_and_merged.csv) como punto de control intermedio en el proceso de limpieza de datos.
        (trips_raw_combined.csv) combinación en un único fichero de los archivos .csv


/notebooks/: Contiene los cuadernos de Jupyter Notebook con todo el proceso en Python.

    01-Exploracion_Inicial.ipynb: Carga y combinación de los datos brutos.

    02-Limpieza_y_Union.ipynb: Proceso completo de limpieza, transformación y enriquecimiento de los datos.

    03-Analisis_Exploratorio.ipynb: Análisis exploratorio, estadístico y visualización de los datos.

/dashboard/: Contiene el dashboard operativo final.

    Dashboard_CitiBike.xlsx: Archivo de Excel con las tablas dinámicas, gráficos y slicers interactivos.

/images/: Contiene las imágenes utilizadas en el informe completo del análisis.

INFORME_ANALISIS.md: El informe detallado con todos los hallazgos, interpretaciones y recomendaciones del proyecto.

**Cómo Utilizar**

Dataset:
Los archivos que contiene los datos brutos son demasiado grandes para ser incluido en este repositorio.

🔗 **Puedes descargarlo desde el siguiente enlace:** [Descargar Dataset](https://drive.google.com/drive/folders/1eYg0GjoU0vn4PW7DkdBGfIgYvUYH4rei?usp=drive_link)

Una vez descargado, colócalo en la carpeta principal del proyecto para que el código pueda encontrarlo y funcionar correctamente.

Análisis en Python: 
Para replicar el análisis, se recomienda ejecutar los notebooks en el orden numérico establecido.

Dashboard: 
El archivo de Excel que contiene el Dashboard, al igual que ocurre con los datos brutos, es demasiado grande para incluirlo en este repositorio.

🔗 **Puedes descargarlo desde el siguiente enlace:** [Descargar Dashboard](https://drive.google.com/drive/folders/1eYg0GjoU0vn4PW7DkdBGfIgYvUYH4rei?usp=drive_link)

Aquí encontrarás el entregable final interactivo que contiene un resumen visual de las conclusiones más importantes.

**Herramientas utilizadas**

Lenguaje: Python 

**Librerías Principales:** 

Pandas, NumPy, Matplotlib, Seaborn

**Dashboarding:** 

Microsoft Excel

