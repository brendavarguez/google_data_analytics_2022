# Quiz 2: Pon a prueba tus conocimientos sobre SQL

### Q1. ¿Qué le dice que haga el asterisco (*) después de SELECT a la base de datos en esta consulta?

```
SELECT * FROM employee WHERE jobCode = 'FTE' AND LastName = 'James'
```

- Selecciona todos los datos que cumplan los criterios indicados en la consulta, luego multiplícalos
- Selecciona todos los datos que cumplan los criterios indicados en la consulta
- **Selecciona todas las columnas de la tabla de empleados**
- Selecciona la columna LastName de la tabla de empleados

&nbsp;

### Q2. En esta consulta, ¿el analista de datos desea recuperar datos de qué tabla? 

```
SELECT * FROM employee WHERE jobCode = 'FTE' AND LastName = 'James'
```

- LastName
- jobCode
- James
- **empleado**

> El analista de datos desea recuperar datos de la tabla de empleados.

&nbsp;

### Q3. En esta consulta, ¿qué se recuperará de la base de datos?

```
SELECT * FROM employee WHERE jobCode = 'FTE' AND LastName = 'James'
```

- Todos los datos de la tabla jobCode en los que jobCode es FTE y el apellido del empleado es cualquiera excepto James.
- Todos los datos de la tabla FTE en los que el apellido del empleado es James.
- Todos los datos de la tabla de empleados en los que jobCode es FTE y el apellido del empleado es cualquiera excepto James.
- **Todos los datos de la tabla de empleados en los que jobCode es FTE y el apellido es James.**

> Esta consulta seleccionará todos los datos de la tabla de empleados en los que jobCode es FTE y el apellido es James.

&nbsp;

### Q4. Estás trabajando con una tabla de una base de datos que contiene datos sobre músicos. La tabla se llama artist. Quieres revisar todas las columnas de la tabla.

Escribes la consulta en SQL a continuación. Agrega una cláusula FROM que recupere los datos de la tabla artist.

```
SELECT
*
FROM artist
```

¿Cuántas columnas hay en la tabla artist?

- **2**
- 5
- 8
- 9

> La cláusula FROM artist recuperará los datos de la tabla artist. La consulta completa es SELECT * FROM artist. La cláusula FROM especifica de qué tabla de la base de datos seleccionar los datos. En la tabla artist,hay dos columnas.

&nbsp;

### Q5. Estás trabajando con una tabla de base de datos que contiene datos sobre álbumes de música. Solo te interesan los datos relacionados con el álbum con el número de ID 277. Los números de ID de álbum se enumeran en la columna album_id de la tabla álbum.

Escribes la consulta en SQL a continuación. Agrega una cláusula WHERE que te muestre solo los datos sobre el álbum con número de ID 277.

```
SELECT
*
FROM
album
WHERE
    album_id = 277
```

¿Cuál es el nombre del álbum con número de ID 277? 

- Mozart: Música de cámara
- Beethoven: Sonatas para piano
- **Bach: Variaciones Goldberg**
- Vivaldi: Las cuatro estaciones

> La cláusula WHERE album_id = 277mostrará solo datos sobre el álbum con el número de ID 277. La consulta completa es SELECT * FROM album WHERE album_ID = 277. La cláusula WHERE filtra los resultados que cumplen con ciertas condiciones. La cláusula WHERE incluye el nombre de la columna, un signo de igual y el valor o los valores a incluir en la columna. El nombre del álbum con el número de ID 277 es Bach: Variaciones Goldberg.