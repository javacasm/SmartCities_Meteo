# SmartCities_Meteo

## Estación meteorológica y medida de calidad del aire

Medirá los parámetros atmosféricos (temperatura, humedad, ...) y de Calidad de aire (partículas, gases, etc. )

Estará conectada a Internet permitiendo enviar los datos y recabar predicciones del tiempo

Incluirá los siguientes sensores
* Luz
* Temperatura
* Humedad
* Lluvia
* Nivel de contaminación
* Gases nocivos (CO, NOx,...)


## Maqueta:  Estación meteorológica y de calidad del aire
* Medida de temperatura, humedad
* Calidad de aire
* Gases


## Ejemplos

### Lectura de datos meteo

Se leen los datos de un sensor BME280 y se muestran por la pantalla lcd

![](./imagenes/4_Meteo_BME280_bb.png)

Ejemplo: SmartCities/Meteo/Datos_Meteo

### Publicación Web de Datos Meteo

Se leen los datos de un sensor BME280 y se muestran por la pantalla lcd

El propio Arduino crea una página web donde se muestran los datos

Tendremos que acceder la ip de arduino desde un navegador

http://192.168.1.nArduino/arduino/Webserver

![](./imagenes/4_Meteo_BME280_bb.png)

Ejemplo: SmartCities/Meteo/Publicacion_datos

### Publicación de datos en ThingSpeak

![](./imagenes/4_Meteo_BME280_bb.png)

Se leen los datos de un sensor BME280 y se publican en [ThingSpeak](https://github.com/javacasm/SmartCities_Comunes/blob/master/ThingSpeak.md)

Ejemplo: SmartCities/Meteo/Publicacion_thinkspeak
