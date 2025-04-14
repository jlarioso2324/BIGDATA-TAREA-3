# BIGDATA-TAREA-3
Descripción de la Solución

Este proyecto implementa un flujo de procesamiento de datos utilizando Apache Spark con Python (PySpark). La solución abarca las siguientes fases:

Configuración del Entorno Spark: Se inicializa una sesión Spark para habilitar el procesamiento distribuido de datos.
Importación de Datos: Se lee un archivo CSV desde un sistema de almacenamiento distribuido como HDFS.
Preprocesamiento de Datos:
Se eliminan entradas redundantes para garantizar la unicidad de los registros.
Se descartan filas con valores faltantes para mejorar la calidad del dataset.
Análisis Descriptivo: Se calculan métricas estadísticas esenciales sobre los datos preprocesados para entender su distribución y características.
Almacenamiento de Resultados: El dataset limpio se exporta a un archivo CSV en el sistema de archivos local para uso posterior.
