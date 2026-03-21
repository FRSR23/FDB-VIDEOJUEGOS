# FDB-VIDEOJUEGOS-GIT
Propósito: tener una base de datos organizada, eficiente y útil para poder mostrar información sobre distintos títulos de videojuegos.
<br>
Motivación: aprender como crear y como funciona una base de datos mediante la implementación de una, dejando de lado lo académico también me gustan los videojuegos y es por eso que elegí convertir mi eso en el punto principal de mi DB.
<br>

DIAGRAMA DE MODELO ENTIDAD-RELACIÓN
![alt text](https://github.com/FRSR23/FDB-VIDEOJUEGOS/blob/main/Diagrama%20E-R.png)

DIAGRAMA UML
![alt text](https://github.com/FRSR23/FDB-VIDEOJUEGOS/blob/main/Diagrama%20de%20UML.png)
<br>

**Cambios**
<br>
Diagrama E-R: se modificaron los errores en la cardinalidad, se agregaron propiedades como los ID a las entidades.
<br>
Diagrama UML: se modifico la organización de los FK y algunas direcciones de las tablas para que tuviera mas coherencia. 

**Formas Normales Aplicadas**
<br>
1FN: se aplico para tener datos atómicos (genero, plataforma, desarrollador).
<br>
2FN: se aplico para separar las entidades y evitar que toda la información vaya a la entidad de videojuego.
<br>
3FN: cada atributo de cada entidad depende de su propia PK, por ejemplo, Pais_origen depende de DESARROLLADOR  y el patron se repite por el diagrama. 
<br><br>
**Diccionarios**
<br><br>
![alt text](https://github.com/FRSR23/FDB-VIDEOJUEGOS/blob/main/DICCIONARIO_PART_1.jpg)
<br><br>
![alt text](https://github.com/FRSR23/FDB-VIDEOJUEGOS/blob/main/DICCIONARIOS_PART_2.jpg)
