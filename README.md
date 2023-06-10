# Curso de PostgreSQL

## Comandos DQL

- SELECT -> Se utiliza para recuperar datos de una o varias tablas
- FROM -> Especifica la tabla o tablas desde las cuales se deben extraer los datos
- WHERE -> Permite aplicar condiciones para filtrar los datos basándose en criterios de evaluación específicos
- GROUP BY -> Se utiliza para agrupar los datos basándose en una o varias columnas
- HAVING -> Permite aplicar condiciones a los grupos creados mediante GROUP BY
- ORDER BY -> Ordena los resultados en función de una o varias columnas.


## Comandos DML

- INSERT -> Se utiliza para insertar nuevos registros en una tabla.
- UPDATE -> Se utiliza para actualizar datos existentes de una tabla, permite actualizar todos los registros o alguno en específico en función a la clausula WHERE.
- DELETE -> Se utiliza para eliminar una o varias filas de una tabla, obedeciendo a la clausula WHERE, si no está presente, eliminará todos los registros.
- MERGE -> Combina operaciones de tipo INSERT, UPDATE, DELETE en una sola sentencia.

## Comandos DDL

- CREATE -> Crea una nueva tabla, vista, índice o sinónimo.
- ALTER -> Modifica la estructura de una tabla existente, como agregar, mofificar o eliminar columnas.
- DROP -> Elmina una tabla, vista, índice o sinónimo.
- TRUNCATE -> Elimina todos los datos de una tabla, pero conserva la estructura de la tabla.
- RENAME -> Cambia el nombre de una tabla o de una columna existente.

## Comandos DCL

- GRANT -> Otorga privilegios a los usuarios sobre objetos de la base de datos.
- REVOKE -> Revoca los privilegios otorgados anteriormente.

## Comandos TCL

- COMMIT -> Confirma los cambios realizados en una transacción y los guarda de forma permanente en la base de datos
- ROLLBACK -> Descarta todos los cambios realizados en una transacción y los devuelve al estado anterior a la transacción
- SAVEPOINT ->  Crea un punto de guardado dentro de una transacción, lo que permite realizar un ROLLBACK parcial hasta ese punto, sin deshacer toda la operación
- RELEASE SAVEPOINT -> Elimina un punto de guardado creado previamente con SAVEPOIN. Después de haber ejecutado este comando no se podrá realizar un ROLLBACK parcial hasta ese punto.

# Tipos de Datos en PostgreSQL

- INTEGER -> Entero de 32 bits
- BIGINT -> Entero de 64 bits
- DECIMAL -> Numero decimal de precisión variable
- JSON -> Es un tipo de dato usado especialmente en postgresaql, para almacenar datos de formato JSON de forma eficiente en la base de datos.
- SERIAL -> En realidad no es un tipo, es un alias, que genera una secuencia de forma automática, su tipo real es un entero (INT) , pero se usa en postgresql para declarar que un campo es de valor autoincrementable.
- BOOLEAN -> Valor booleano (verdadero o falso)
- TEXT -> Cadena de texto de longitud variable
- VARCHAR -> Cadena de texto variable con longitud máxima especificada
- DATE -> FECHA
- TIMESTAMP -> FECHA Y HORA
- GEOMETRY -> Datos de geometria (puntos, líneas, polígonos etc)
- BYTEA -> Datos binarios de longitud variable
