# Desafio del curso

## Escenario 1, pregunta 1-5

Acabas de empezar un nuevo trabajo como analista de datos. Trabajas para una cadena de farmacias de tamaño mediano con 38 tiendas en el suroeste de Estados Unidos. Tu supervisor comparte contigo un nuevo proyecto de análisis de datos.

Ella te explica que la farmacia está considerando suspender un producto de baño de burbujas llamado Splashtastic. Tu supervisor quiere que analices los datos de ventas y determines qué porcentaje de las ventas diarias totales de cada tienda proviene de ese producto. Luego, presentarás tus hallazgos a la gerencia.

Sabes que es importante seguir cada paso del proceso de análisis de datos: preguntar, preparar, procesar, analizar, compartir y actuar. Por lo tanto, empiezas por definir el problema y asegurarte de que entiendes completamente las expectativas de las partes interesadas.

Una de las preguntas que haces es dónde encontrar el conjunto de datos con el que trabajarás. Tu supervisor te explica que la base de datos de la empresa contiene toda la información que necesitas.

Luego, continúas con el paso de preparación. Accedes a la base de datos y escribes una consulta para recuperar los datos sobre Splashtastic. Observas que solo hay 38 filas de datos, que representan a las 38 tiendas de la empresa. Además, el conjunto de datos contiene cinco columnas: Número de tienda, Promedio de clientes diarios, Promedio de ventas diarias de Splashtastic (unidades), Promedio de ventas diarias de Splashtastic (dólares) y Promedio de ventas diarias totales (todos los productos).

&nbsp;

### Q1. Teniendo en cuenta el tamaño de tu conjunto de datos, decides que una hoja de cálculo será la mejor herramienta para tu proyecto. Debes proceder descargando los datos de la base de datos. Describe por qué es la mejor opción.

- Las hojas de cálculo son más eficaces cuando se trabaja con consultas.
- Solo las hojas de cálculo te permiten descargar y cargar datos.
- Las bases de datos no se pueden utilizar para el análisis.
- **Las hojas de cálculo funcionan bien para procesar y analizar un conjunto de datos pequeño, como el que estás usando.**

> Una hoja de cálculo es una opción inteligente cuando se trabaja con un conjunto de datos de 38 filas y cinco columnas.

&nbsp;

### Q2. Escenario 1, continuación.

Has descargado los datos de la base de datos de la empresa y los has importado a una hoja de cálculo. Para utilizar el conjunto de datos para este escenario, haz clic en el enlace a continuación y selecciona «Usar plantilla».

[Desafío del curso - Escenario 1](https://docs.google.com/spreadsheets/d/1pIiGuiZ8SZ2xNfXHEIIb5gpX1NNOuKAUbaqtmPh1GUY/template/preview?resourcekey=0-p4GIOWHIaC6wZTvc9HZzyA#gid=0)

Ahora es el momento de procesar los datos. Como sabes, este paso implica encontrar y eliminar errores e inexactitudes que pueden interferir con tus resultados. **Al limpiar los datos, observas que falta información sobre Splashtastic en la fila 16. No estás seguro de cómo proceder, así que lo mejor es pedirle orientación a tu supervisor. **

- **Verdadero**
- Falso

> Lo mejor es pedirle orientación a tu supervisor. Hacer preguntas te ayuda a aprender y evitar errores.

&nbsp;

### Q3. Escenario 1, continuación

Una vez que hayas encontrado la información faltante, analiza tu conjunto de datos.

Durante el análisis, debes crear una nueva columna F. En la parte superior de la columna, agrega el atributo Porcentaje promedio de ventas totales - Splashtastic. Selecciona la definición correcta para un atributo.

- **Característica o calidad de los datos que se utilizan para etiquetar una columna**
- Un título o un subtítulo
- Observación de datos dentro de una columna
- Todas las características de algo contenido en una tabla

> Un atributo es una característica o calidad de los datos que se utilizan para etiquetar una columna.

&nbsp;

### Q4. Escenario 1, continuación

A continuación, determina el promedio total de ventas diarias de los últimos 12 meses en todas las tiendas. El rango que contiene estas ventas es E2:E39. Identifica la forma correcta de escribir tu función.

- =PROMEDIO(E2+E39)
- =PROMEDIO(E2,E39)
- =PROMEDIO(E2-E39)
- **=PROMEDIO(E2:E39)**

> La función comienza con un signo igual (=) y el rango es de E2 a E39.

&nbsp;

### Q5. Escenario 1, continuación

Has llegado a la fase compartir del proceso de análisis de datos. Implica crear una visualización de datos para resaltar los conocimientos de ventas de Splashtastic que has descubierto.

- **Verdadero**
- Falso

> La fase compartir implica crear visualizaciones de datos, preparar la presentación y comunicar tus resultados a las partes interesadas.

&nbsp;

## Escenario 2, preguntas 6-10

Has trabajado para la Sociedad Dental Nacional (NDS), sin fines de lucro, como analista de datos junior durante unos dos meses. La misión de la NDS es ayudar a sus miembros a mejorar la salud bucal de sus pacientes. Los miembros de la NDS son dentistas, higienistas y personal de apoyo en consultorios dentales.

A la NDS le apasiona la salud de los pacientes. Parte de esto implica programar automáticamente citas de seguimiento después del reemplazo de corona, la cirugía dental de emergencia y los procedimientos de extracción. La NDS considera que el seguimiento es un paso importante para garantizar la recuperación del paciente y minimizar la infección.

Desafortunadamente, muchos pacientes no se presentan a estas citas, por lo que la NDS quiere crear una campaña para ayudar a sus miembros a aprender cómo animar a sus pacientes a que tomen en serio las citas de seguimiento. Si tiene éxito, esto ayudará a la NDS a lograr su misión de promover la salud bucal de todos los pacientes.

Tu supervisor acaba de enviarte un correo electrónico diciendo que te va muy bien en el equipo y quiere darte alguna responsabilidad adicional. Describe el problema de que muchos pacientes no acuden a las citas de seguimiento. Se te encarga analizar los datos sobre este problema y presentar tus hallazgos mediante visualizaciones de datos.

Un miembro de la NDS con tres consultorios dentales en Colorado ofrece compartir sus datos sobre las citas perdidas. Por lo tanto, tu supervisor utiliza una consulta de base de datos para acceder al conjunto de datos del grupo dental. La consulta le indica a la base de datos que recupere toda la información de los paciente de los tres consultorios dentales del miembro, ubicados en el código postal 81137.

&nbsp;

### Q6. La tabla es tabla_datos_dentales y el nombre de la columna es código_postal. Has escrito la siguiente consulta, pero has recibido un error al ejecutarla. ¿Cuál es la cláusula que corrige esta consulta?

```
SELECT *
FROM dental_data_table
WHERE dental_data_table = 81137
```

- **DÓNDE código_postal = 81137**
- DÓNDE = 81137
- DÓNDE_zip_code = 81137
- DÓNDE zip_code 81137

> La sintaxis correcta es DÓNDE código_postal = 81137. DÓNDE indica dónde buscar información. El nombre de la columna es código_postal. Y se pide a la base de datos que devuelva solo los registros que coincidan con el código postal 81137.

&nbsp;

### Q7. Escenario 2, continuación

El conjunto de datos que el supervisor recuperó e importó en una hoja de cálculo incluye una lista de pacientes, su información demográfica, tipos de procedimientos dentales y si asistieron a su cita de seguimiento. Para utilizar el conjunto de datos para este escenario, haz clic en el enlace a continuación y selecciona «Usar plantilla».

[Desafío del curso - Escenario 2](https://docs.google.com/spreadsheets/d/1tXJvXgUP58iYYSW6tBfiGMD5lJFOgHXvHx2EdDOCxnA/template/preview?resourcekey=0-Ha_b6RzKHJFYElJN20NOyg#gid=0)

La información demográfica del paciente incluye datos como edad, sexo y domicilio. ¿En qué podría interferir el hecho de que el conjunto de datos incluya personas que viven en el mismo código postal?

- Fórmulas o funciones de las hojas de cálculo
- Visualización de datos
- **Equidad**
- Procedimientos dentales futuros

> Como analista de datos, es tu responsabilidad asegurarte de que tu análisis sea justo. Aunque muchos códigos postales reflejan poblaciones diversas, una mejor opción sería incluir datos sobre personas que viven en varios códigos postales.

&nbsp;

### Q8. Escenario 2, continuación

A medida que revisas el conjunto de datos, observas que hay una cantidad desproporcionada de personas de edad avanzada. Por lo tanto, investigas más a fondo y descubres que este código postal representa una comunidad rural en Colorado con unos 800 residentes. Además, hay un gran centro de vida asistida en la zona. Casi 300 de los residentes del código postal 81137 viven en el centro.

Reconoces que es una cantidad considerable, por lo que quieres saber si la edad tiene un efecto en la probabilidad de que un paciente asista a una cita de seguimiento con el dentista. Analizas los datos y el análisis revela que las personas de edad avanzada tienden a pasar por alto los seguimientos más que las personas jóvenes.

Por lo tanto, investigas un poco en línea y descubre que las personas mayores de 60 años tienen un 50% más de probabilidades de faltar a las citas con el dentista. A veces esto se debe a que tienen ingresos fijos. Además, muchas personas de edad avanzada carecen de transporte para ir y volver de las citas.

Con este nuevo conocimiento, le escribes un correo electrónico a tu supervisor expresando tus inquietudes sobre el conjunto de datos. Tu supervisor está de acuerdo con tus preocupaciones, pero también está impresionado con lo que has aprendido y piensa que tus hallazgos podrían ser muy importantes para el proyecto. Te pide que cambies la tarea empresarial. Ahora, la campaña de la NDS tratará de educar a los consultorios dentales sobre los desafíos a los que se enfrentan las personas de edad avanzada y encontrar formas de ayudarles a acceder a una atención dental de calidad.

&nbsp;

Cambiar la tarea empresarial implica definir la nueva pregunta o problema a resolver.

- **Verdadero**
- Falso

> Una tarea empresarial es la pregunta o las respuestas de análisis de datos a los problemas para una empresa.

&nbsp;

### Q9. Escenario 2, continuación

Continúa con tu análisis. Al final, tus hallazgos respaldan lo que descubriste durante tu investigación en línea: A medida que las personas envejecen, es menos probable que asistan a las citas dentales de seguimiento.

Pero aún no has terminado. Sabes que los datos se deben combinarse con la información humana para llegar a una verdadera toma de decisiones basada en datos. Por lo tanto, el siguiente paso es compartir esta información con personas familiarizadas con el problema. Te ayudarán a verificar los resultados de tu análisis de datos.

**Completa el espacio en blanco: Las personas que están familiarizadas con un problema y que ayudan a verificar los resultados del análisis de datos son _____ . **

- **expertos en la materia**
- científicos de datos
- clientes
- las partes interesadas

> Los expertos en la materia examinan los resultados del análisis de datos para identificar cualquier inconsistencia, dar sentido a las áreas grises y, finalmente, validar las decisiones tomadas.

&nbsp;

### Q10. Escenario 2, continuación

Los expertos en la materia quedan impresionados por tu análisis. El equipo acepta pasar al siguiente paso: la visualización de datos. Sabes que es importante que las partes interesadas de la NDS comprendan rápida y fácilmente que es menos probable que las personas de edad avanzada asistan a las citas dentales de seguimiento importantes. Esto les ayudará a crear una campaña eficaz para los miembros.

Es hora de crear tu presentación para las partes interesadas. Incluirá una visualización de datos que demuestra la tendencia de que es menos probable que las personas asistan a las citas de seguimiento a medida que envejecen. Para ello, un gráfico circular será más eficaz.

- **Falso**
- Verdadero

> Un gráfico circular se utiliza para representar las proporciones de ciertas categorías de datos en comparación con el conjunto. Un gráfico de líneas sería eficaz para hacer un seguimiento de las tendencias a lo largo del tiempo, como las personas que asisten a menos citas a medida que envejecen.
