# Proceso ETL
Este es un script sencillo donde se puede evidenciar como es el proceso de extraccion, transformación y carga utilizando el lenguaje de programacion Python.

Este script es bastante util en el momento de trabajar con grandes cantidades de datos.

El proceso inicia extrayendo los datos de las empresas mas  cotizadas en la bolsa de nueva york, el objetivo del proceso etl es recolectar la informacion y se pide cambiar la divisa en la cual esta representada cada empresa, inicialmente con dolar americano US yse pide convertirlo a libra esterlina GBP, ademas de que los datos esten limpios y no tengan valores nulos y faltantes.

El archivo de entrada es de formato json y tendra el nombre de "jsonfile".

Los archivos de salida se llamaran "archivo_destino" en formato csv y "archivo registro" en formato txt los cuales contentran los datos transformados y elk registro del proceso ETL.


