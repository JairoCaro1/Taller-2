Universidad de los Andes
MINE-4101: Ciencia de Datos Aplicada
Taller 1: Inversiones inmobiliarias para alquiler vacacional
Integrantes:

Jairo Antonio Caro Vanegas
Entendimiento inicial de datos:

Desde el notebook Taller new york listing se genero el entedimiento del dataset listings donde se escogieron las variables de "price, room_type, number_of_reviews, neighbourhood_group_cleansed,minimum_nights", para los casos de las variables cuantitativas se calcularon los respectivos percentiles con el fin de eliminar la informacion que contara con outlayers de datos.

Estrategia de análisis:

Para la estrategia inicial de datos calcularemos la cantidad de reservas por apartamento para poder tener un mayor panorama de que tipos de apartamentos, sectores y de las clasificacions son mayormente reservados, con esto podremos tener una conclusion inicial de las mejores opciones de inversion por caracteristicas de apartamentos, luego generaremos unas recomendaciones con base en la reputacion previa del inmueble, para esto se genero un conteo de reseñas por apartamento, en este punto entraremos a validar si dependiendo del numero de reseñas los usuarios toman la decision de alquilar un departamento.

Con las tres fuentes de datos unidas se analizaran las principales cualidades a tener encuenta el la inversion como lo son zona, barrio, tipo de habitacion, numero de baño, caracteristicas principales, precio y minimo de noches, principalmente estas caracteristicas se analizaran en funcion del numero de alquileres por dia de este año y el proximo ya agendados.

Generacion de resultados:
El resumen del analisis de informacion quedo depositado en el archivo pdf "Analisis de inversion" que se encuntra en el repositorio

Dependencias:
Necesitaremos los datasets de listings,calendar y reviews para la ciudad de new york, por el tamaño del data set es necesario descargar los archivos de la imagen del siguiente link https://insideairbnb.com/get-the-data/ image

Instrucciones de ejecución:

Ejecutar el notebook Taller new york listing que nos generara el dataset limpio Listing_clean.csv
Ejecutar el notebook Taller new york calendar que nos generara el dataset booked_list.csv
Ejecutar el notebook Taller new york reviews que nos generara el dataset review_list.csv
Ejecutar el notebook Taller new york union analisis que nos generar el dataset recomendaciones.csv
