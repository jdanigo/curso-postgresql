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
