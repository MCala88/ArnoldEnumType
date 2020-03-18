# ArnoldEnumType

## Codigo creado por Miquel Calafell

Se trata de calcular el peso de una persona en los distintos planetas de nuestro Sistema Solar

-----
Peso_en_Superficie = tu_Masa * Gravedad_en_superficie
donde 
Gravedad_en_superficie = G * Masa_del_planeta / Radio_del_planeta_al_cuadrado
donde: 
G = 6.67300E-11
y 
tu_masa = tu_peso_en_la_Tierra / gravedad_superficial_tierra;
-----

Casos test - AssertJ Fluent Assertions

Aquí tienes los casos test que ha de satisfacer tu código:

https://github.com/dfleta/Java/blob/master/arnoldEnumTypeMaven/src/test/java/org/foobarspam/arnoldEnumType/test/ArnoldEnumTypeTest.java

Para utilizar estos casos test, has de incluir en el POM.xml del proyecto Maven o en el fichero build.gradle una dependencia adecuada a la librería de AssertJ. Búscala en el repo de Maven:
https://mvnrepository.com/

¿Cómo funcionan las Fluent Assertions?:
http://joel-costigliola.github.io/assertj/assertj-core-quick-start.html


Script principal - main
Programa la lógica para que, además de los casos test, satisfaga este script principal del programa:
https://github.com/dfleta/Java/blob/master/arnoldEnumTypeMaven/src/main/java/org/foobarspam/arnoldEnumType/main/ArnoldMain.java
