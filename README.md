![HenryLogo](https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png)

​
# <h1 align="center">**`Proyecto Individual N°2`**

# <h1 align="center">**`DATATHON`**

<p align="center">
<img src="https://www.ibm.com/blogs/client-voices/wp-content/uploads/2019/09/Glinnt.jpg"   
>
</p>

​
¡Bienvenidos! Mi nombre es Matias Martinez y estoy cursando la etapa de Labs del Bootcamp de Henry. En este proyecto pondré en práctica mis habilidades en el campo del Machine Learning. Comenzaré con un análisis exploratorio de datos (EDA), para obtener consistencia en los mismos y lograr así predicciones precisas.

## **Introducción**

Un importante Centro de Salud me ha contratado con el fin de poder predecir si un paciente tendrá una estancia hospitalaria prolongada o no, utilizando la información contenida en el dataset asociado, la cual recaba una muestra histórica de sus pacientes, para poder administrar la demanda de camas en el hospital según la condición de los pacientes recientemente ingresados.
Para esto, se define que un paciente posee estancia hospitalaria prolongada si ha estado hospitalizado más de 8 días.


## **Objetivo del proyecto**

Crear un modelo de Machine Learning para poder predecir correctamente la estancia hospitalaria de los pacientes, basándonos en datos historicos de pacientes.

## **Resolución**

Comenzamos con la extracción de los datos a partir de los datasets provistos por Henry. Luego se llevó a cabo un Análisis Exploratorio de Datos (EDA), en el que se verificaron los valores nulos y duplicados, y se decidió eliminar ciertas variables consideradas prescindibles. Luego, se normalizaron los datos utilizando LabelEncoder.

Creamos y entrenamos el modelo de clasificación K-Nearest Neighborgs. 

Finalmente, implementamos el modelo entrenado para predecir el conjunto de datos "hospitalizaciones_test.csv" y se generó un archivo csv con los resultados.

## **Herramientas utilizadas**

+ Python.

    + Pandas.

    + sklearn.

    + Numpy.

    + Requests.

    + IO.
