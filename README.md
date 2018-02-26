# smn_mex
consultas sql sistema meteorológico nacional mexicano

para hacer consultas como:
"promedio del máximo de días corridos sin lluvia por estación"
"días con temperatura mínima menor a 10 grados y precipitación mayor a 10 mm"
"conteo por año de días arriba de 35 grados"

se escoge una estacion o una lista, también se debe poder escoger un área dentro del territorio y que el programa selecciones las claves.

partiendo de esa lista el script entra a la url de cada estacion, procesa la informacion y la estructura en un data.frame,

La estructura de la función que se me ocurre:
consulta <- function(x, criterion){}
x = estacion o lista de estaciones,
criterion = criterio

y entre los parámetros escoger si se desea un conteo de los días corridos bajo dicho criterio
