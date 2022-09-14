# Pruebas en Laravel


#### Paso 1
Se corren lao test de prueba, hay dos maneras para hacerlo. Pero elegimos la siguiente:
![](https://github.com/RafArenas/Capturas-Pruebas-Laravel/blob/master/documentation/paso%201.PNG?raw=true)

#### Paso 2
Creamos un nuevo fichero de test con el siguiente comando:
![](https://github.com/RafArenas/Capturas-Pruebas-Laravel/blob/master/documentation/paso%202.PNG?raw=true)

![](https://github.com/RafArenas/Capturas-Pruebas-Laravel/blob/master/documentation/paso%202.1.PNG?raw=true)

#### Paso 3
Repetimos el paso 1 y verificamos que todo sale OK
![](https://github.com/RafArenas/Capturas-Pruebas-Laravel/blob/master/documentation/paso%203.PNG?raw=true)

#### Paso 4
Camiamos lo siguiente en el fichero UserTest y vemos que nos arroja un error
![](https://github.com/RafArenas/Capturas-Pruebas-Laravel/blob/master/documentation/paso%204.PNG?raw=true)

![](https://github.com/RafArenas/Capturas-Pruebas-Laravel/blob/master/documentation/paso%204.1.PNG?raw=true)

## Pruebas Unitarias

#### Paso 1
Ahora usamos el siguiente comando para crear una prueba unitaria:
![](https://github.com/RafArenas/Capturas-Pruebas-Laravel/blob/master/documentation/Pruebas%20unitarias%201.PNG?raw=true)

#### Paso 2
Volvemos a correr las pruebas de la siguiente manera y vemos el error que arroja por la modifiación dentro del fichero UserTest:
![](https://github.com/RafArenas/Capturas-Pruebas-Laravel/blob/master/documentation/Pruebas%20unitarias%202.PNG?raw=true)

#### Paso 3
Modificamos de nuevo el fichero UserTest ubicado en el directorio Feature dentro de la carpeta tests y volvemos a correr las pruebas obteniendo el siguiente resultado:
![](https://github.com/RafArenas/Capturas-Pruebas-Laravel/blob/master/documentation/Pruebas%20unitarias%202.1.PNG?raw=true)

![](https://github.com/RafArenas/Capturas-Pruebas-Laravel/blob/master/documentation/Pruebas%20unitarias%202.2.PNG?raw=true)

## Ahora realizamos otros ejercicios

#### Paso 1
Vamos a crear una UI con el siguiente comando:
![](https://github.com/RafArenas/Capturas-Pruebas-Laravel/blob/master/documentation/UI%201.PNG?raw=true)

#### Paso 2
Seguimos creando una interfaz de autenticación reactiva con el siguiente comando:
![](https://github.com/RafArenas/Capturas-Pruebas-Laravel/blob/master/documentation/UI%202.PNG?raw=true)

#### Paso 3
Por recomendación corremos el siguiente comando desde la terminal de windows CMD:
![](https://github.com/RafArenas/Capturas-Pruebas-Laravel/blob/master/documentation/UI%203.PNG?raw=true)

![](https://github.com/RafArenas/Capturas-Pruebas-Laravel/blob/master/documentation/UI%203.1.PNG?raw=true)

#### Paso 4 
Creamos la base de datos desde phpMyAdmin asi:
![](https://github.com/RafArenas/Capturas-Pruebas-Laravel/blob/master/documentation/UI%204.PNG?raw=true)

Después ubicamos el fichero .env y modificamos el nombre de la base de datos para que sea igual al que tenemos en phpMyAdmin, luego corremos las migraciones hacia la BD:
![](https://github.com/RafArenas/Capturas-Pruebas-Laravel/blob/master/documentation/UI%204.1.PNG?raw=true)

![](https://github.com/RafArenas/Capturas-Pruebas-Laravel/blob/master/documentation/UI%204.2.PNG?raw=true)

#### Paso 5
Ubicamos el directorio Unit, y abrimos el fichero UserTest:
![](https://github.com/RafArenas/Capturas-Pruebas-Laravel/blob/master/documentation/UI%205.PNG?raw=true)

#### Paso 6
Modificamos la función que había en el fichero, quedando asi:
![](https://github.com/RafArenas/Capturas-Pruebas-Laravel/blob/master/documentation/UI%206.PNG?raw=true)

#### Paso 7
Agregamos la siguiente línea al use:
![](https://github.com/RafArenas/Capturas-Pruebas-Laravel/blob/master/documentation/UI%207.PNG?raw=true)

#### Paso 8
Corremos el test de la siguiente forma:
![](https://github.com/RafArenas/Capturas-Pruebas-Laravel/blob/master/documentation/UI%208.PNG?raw=true)

##### Para descargar este repositorio
[Test-Laravel](http://https://github.com/RafArenas/Test-Laravel.git "Test-Laravel")
