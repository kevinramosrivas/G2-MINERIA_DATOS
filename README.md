# G2-MINERIA_DATOS
## Proyecto final del curso de Mineria de datos - VIII ciclo UNMSM

### Integrantes del equipo
* Blas Ruiz, Luis Aaron
* Huarhuachi Ortega, Andrea Mariana
* Ramos Rivas, Kevin Keyler
* Rojas Villanueva, Paula Elianne
* Torres Talaverano, Luz Elena

### Conjunto de datos usado

[Datos sísmicos brindados por el IGP] (https://ultimosismo.igp.gob.pe/descargar-datos-sismicos)

### Objetivo del proyecto

 El objetivo se centra en aplicar métodos de segmentación de datos o clustering a un conjunto de datos con información de sismos en Perú para analizar características comunes en los agrupamientos resultantes y poder utilizar estos resultados con fines predictivos de vulnerabilidad.

### Conjunto de datos posterior al preprocesamiento
[Dataset preprocesado](https://github.com/KevinRamosRivas/G2-MINERIA_DATOS/blob/main/IGP_Datos-Sismicos_Consolidados_V3.csv)


### Instrucciones para el uso del sistema

El sistema se encuentra dividido en 3 partes

* Preprocesamiento
  Se hace uso de 2 datasets que nos provee el IGP, estos seran la data de entrada para esta primera parte
* Clustering con Kmeans y Kmedoids
  Se hara uso de el dataset consolidado y preprocesado que se genero en el paso anterior
  Se genera producto de este paso, 4 dataset 2 dataset para pruebas y 2 para entrenamiento
* Modelos de predicción
  Se hace uso de los 4 dataset que se generaron en el paso anterior


Para usar el sistema solo sera necesario cargar en el primer paso los datasets correspondientes a preprocesar, en los demas pasos no sera necesario cargar los datasets ya que estos se encuntran alojados en este repositorio de (github)[https://github.com/KevinRamosRivas/G2-MINERIA_DATOS.git] y se descargan autoamticamente de ahi.
