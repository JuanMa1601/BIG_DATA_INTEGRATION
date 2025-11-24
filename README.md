#Word Count Analysis - Big Data Integration

##Descripción del Proyecto
Este proyecto implementa un contador de palabras utilizando Apache Spark como parte de la
actividad práctica de la materia Big Data Integration de la Universidad Nacional Abierta y a
Distancia (UNAD).

##Objetivo
Implementar un programa en PySpark que realice el conteo de palabras específicas en un archivo
de texto, aplicando técnicas de procesamiento distribuido para el análisis de datos masivos.

#Resultados Obtenidos
El análisis del archivo Anexo1-Aplication.txt arrojó los siguientes resultados:

Palabra	Conteo
Recognition	4
Vision	66
** Recognition** (con espacio)	4

##Tecnologías Utilizadas
- Apache Spark 3.4.0
- PySpark (Python API for Spark)
- Hadoop HDFS (para almacenamiento distribuido)
- Python 3.10

##Estructura del Proyecto

bigdata-integration-wordcount/
│
├── word_count_spark.py          # Código principal en PySpark
├── Anexo1-Aplication.txt        # Archivo de datos de entrada
├── word_count_results.html      # Resultados en formato HTML
├── README.md                    # Este archivo
└── requirements.txt             # Dependencias del proyecto

##Ejecución del Proyecto
Prerrequisitos

## Instalar PySpark
pip install pyspark

## Verificar instalación de Hadoop
hadoop version

Ejecutar el contador de palabras

## Ejecutar con Spark
spark-submit word_count_spark.py

## O ejecutar directamente con Python
python3 word_count_spark.py

Características del Código
- Procesamiento distribuido con RDDs de Spark
- Conteo específico de palabras requeridas
- Generación automática de reporte HTML
- Manejo de errores y validación de archivos
- Configuración optimizada para entorno local

##Metodología
- Carga de datos: Lectura del archivo de texto en un RDD
- Transformación: División y limpieza de palabras
- Filtrado: Conteo específico de palabras objetivo
- Agregación: Conteo general de todas las palabras
- Exportación: Generación de reporte en HTML

##Autor
Juan Meriño Mercado
Estudiante de Especialización en Ciencia de Datos y Analítica
Universidad Nacional Abierta y a Distancia (UNAD)

##Curso
Big Data Integration - Código 203008077
Vicerrectoría Académica y de Investigación

##Licencia
Este proyecto es parte de los requisitos académicos de la UNAD y se distribuye con fines educativos.

##Enlaces Relacionados
Apache Spark Documentation
PySpark API Reference
UNAD - Universidad Nacional Abierta y a Distancia

##Contacto
Para más información sobre este proyecto, puedes contactar al autor a través de los canales institucionales de la UNAD.

Última actualización: Noviembre 2025
