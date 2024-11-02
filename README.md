
## Enunciado
Magneto quiere reclutar la mayor cantidad de mutantes para poder luchar contra los X-Mens.

Te ha contratado a ti para que desarrolles un proyecto que detecte si un humano es mutante basándose en su secuencia de ADN.

Para eso te ha pedido crear un programa con un método o función con la siguiente firma:

```java
 boolean isMutant(String[] dna);
```

En donde recibirás como parámetro un array de Strings que representan cada fila de una tabla de (NxN) con la secuencia del ADN. Las letras de los Strings solo pueden ser: (A,T,C,G), las cuales representa cada base nitrogenada del ADN.

Sabrás si un humano es mutante, si encuentras **más de una secuencia de cuatro letras iguales**, de forma oblicua, horizontal o vertical.
## Instrucciones de cómo ejecutar el programa o la API

En este repositorio se encuentra el proyecto completo con lo requerido en el informe. A continuación se dará instrucciones de como ejecutar el proyecto en distintas situaciones:

#### Local:
 Se debe ejecutar el archivo `MutantDetectorApplication` que funciona como el `main` de nuestra aplicación.
 Consola de H2 usamos `http://localhost:8080/h2-console/`
 Swagger `http://localhost:8080/swagger-ui/index.html`


#### En Render
Crear servidor en render, indicar que se hace con Docker y deployar el servicio

