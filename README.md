# TFE-Arte-Rupestre
Código fuente y metadatos del Trabajo Fin de Estudios de la Maestría en IA
## Contenido del Repositorio
* **`TFE_ArteRupestrescrapper.ipynb`**: Cuaderno de Google Colab para la extracción y raspado web automatizado de las imágenes del catálogo.
* **`TFE_Clustering_Arte_RupestreV1.ipynb`**: Cuaderno con el pipeline de Visión Artificial (CLAHE + Filtro Bilateral), extracción de características (ResNet50), reducción dimensional (PCA) y agrupamiento (K-Means y DBSCAN).
* **`datos_idearq.json`**: Estructura de metadatos crudos recopilados durante el web scraping.
* **`CLASIFICACION DEL ARTERUPESTRE.xlsx`**: Matriz de homologación de descriptores tipológicos y control de consistencia de los 1,787 registros analizados.
* **`RESULTADO_FINAL_CRUZADO_KMEANS.xlsx`**: Resultados de la asignación de clústeres por muestra y yacimiento generados por el modelo K-Means ($K=5$).
* **`RESULTADO_FINAL_CRUZADO_DBSCAN.xlsx`**: Resultados de la asignación de clústeres y detección de ruido geográfico generados por el modelo DBSCAN.
* **`requirements.txt`**: Archivo de especificación de librerías y dependencias necesarias para la réplica del entorno de ejecución.
