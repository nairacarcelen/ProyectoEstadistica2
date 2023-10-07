# ProyectoEstadistica2

**DICCIONARIO DE CODIGOS**
#**Tabla de datos 1 = *Padron Electoral 2020***

Esta tabla hace referencia al Padron Electoral 2020 sobre los ciudadanos aptos para votar en el Plebiscito Nacional Chileno sobre Constitución Política en el año 2020. Esta tabla refuerza nuestras variables independientes porcentaje de los votantes jóvenes y votantes femeninas aptas para votar dentro del padrón electoral. Esta tabla corresponde a la pagina oficial del Servicio Electoral de Chile (SERVEL). Si bien esta tabla hace referencia a cantidades, trabajaremos en base a los datos porcentuales que podamos inferir a partir de esta información.

Comuna = Nombre de comunas por region 

Edad = Edad de ciudadados y ciudadanas aptos para votar

Rango_edad = Rango de edad de ciudadanos y ciudadanas aptos para votar 

Region = Nombre de la region 

Sexo = Sexo biologico de los y las ciudadanos y ciudadanas aptos para votar

Cedula = Cantidad de ciudadanos y ciudadanas aptos para votar por rango de edad y/o de acuerdo al sexo



##**Tabla de datos 2 = *2020_PlebiscitoConstitucionPolitica2*** --> Resultados del Plebiscito Constitucional 2020

Esta tabla hace referencia a los resultados del Plebiscito Constitucional del año 2020. Esta tabla refuerza nuestra variable dependiente de porcentaje de votos a favor del “apruebo” por comuna durante el Plebiscito Nacional Chileno sobre Constitución Política en el año 2020. Si bien esta tabla hace referencia a cantidades, trabajaremos en base a los datos porcentuales que podamos inferir a partir de esta información. Esta tabla corresponde a la pagina oficial del Servicio Electoral de Chile (SERVEL). Asimismo, teniendo en cuenta que no ha sido procesada, esta tabla contiene columnas que no trabajaremos pero que no hemos eliminado ya que poseen relacion directa con los datos que sí necesitamos como, por ejemplo, el numero de votos por cada opcion en las diferentes comunas. Las variables que no trabajaremos seran: Circunscripcion electoral, Local y Mesa. 

Codigo de la Region = Las regiones de Chile estan codificadas del 1 al 16, asi tambien se encuentran en la base de datos

Region = Nombre de la region

Comuna = Nombre de comunas por region 

Circunscripcion electoral =  Distrito electoral o distrito legislativo que es una subdivisión territorial para llevar a cabo el proceso electoral

Local = Local de votacion

Mesa = Numero de mesa de votacion 

Numero de voto codificada (Num_voto_cod) = Variable de eleccion de voto donde 1 es "Apruebo" y 2 es "Rechazo"

Opcion de voto (Op_voto) = Opcion de voto en donde se tienen las opciones "Apruebo", "Rechazo", "Voto Nulo", "Voto Blanco"

Cantidad de votos (Cant_votos) = Cantidad de votos por mesa de votacion

Seleccion = Resultado final de eleccion por mesa de votacion



###**Tabla de datos 3 = *2017_12_Presidencial_2V*** --> Resultados de la eleccion presidencial 2017

Esta tabla hace referencia a los resultados de la eleccion presidencial en segunda vuelta del 2017, en donde se enfrentaron Sebastián Piñera y Alejandro Guillier y fue Piñera quien se llevo el triunfo electoral. Ahora bien, esta tabla refuerza nuestra variable independiente de ganador de la ultima eleccion por comuna, la cual nos ayudará a entender si existe alguna correlacion entre el resultado de la ultima eleccion y el resultado del plebiscito 2020 por cada comuna. Esta tabla corresponde a la pagina oficial del Servicio Electoral de Chile (SERVEL). Asimismo, teniendo en cuenta que no ha sido procesada, esta tabla contiene columnas que no trabajaremos pero que no hemos eliminado ya que poseen relacion directa con los datos que si necesitamos como, por ejemplo, el numero de votos por cada opcion en las diferentes comunas. Las variables que no trabajaremos seran: Circunscripcion electoral, Local y Mesa. 

Codigo de la Region = Las regiones de Chile estan codificadas del 1 al 16, asi tambien se encuentran en la base de datos

Region = Nombre de la region

Comuna = Nombre de comunas por region 

Circunscripcion electoral = Distrito electoral o distrito legislativo que es una subdivisión territorial para llevar a cabo el proceso electoral

Local = Local de votacion

Mesa = Numero de mesa de votacion 

Numero de voto codificada (Num_voto_cod) = Variable de eleccion de voto donde 1 es "Apruebo" y 2 es "Rechazo"

Opcion de voto (Op_voto) = Opcion de voto en donde se tienen las opciones "Apruebo", "Rechazo", "Voto Nulo", "Voto Blanco"

Cantidad de votos (Cant_votos) = Cantidad de votos por mesa de votacion



####**Tabla de datos 4 = *Indice de Desarrollo por Comuna***

Region = Nombre de la region

Comuna = Nombre de la comuna por region 

IDC = Indice de desarrollo por comuna



#####**Tabla de datos 5 = *Cantidad_de_Votantes_por_edad_y_sexo_por_comuna_Plebiscito_Nacional***

Esta tabla hace referencia a la cantidad de votantes por edad y sexo por comuna en el Plebiscito Constitucional 2020. Esta tabla refuerza nuestras variables independientes porcentaje de los ciudadanos jóvenes y ciudadanas femeninas aptas para votar dentro del padrón electoral, pues se podra hacer una correlacion entre los ciudadanos aptos y la cantidad final de personas que acudieron a votar. Finalmente, esto podra reforzar nuestro eje de investigacion: Factores que influyeron en el voto a favor del “apruebo” durante el Plebiscito Nacional Chileno sobre Constitución Política en el año 2020. Si bien esta tabla hace referencia a cantidades, trabajaremos en base a los datos porcentuales que podamos inferir a partir de esta información.

Region = Nombre de la region

Comuna = Nombre de comunas por region 

Sexo = Sexo biologico de los y las ciudadanos y ciudadanas que acudieron a votar de acuerdo a la comuna de residencia

Rango etario = Rango de edad de los y las votantes

Total = Total de votantes segun el sexo y edad 


