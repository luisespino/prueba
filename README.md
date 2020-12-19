# Fase 2


Administrador de almacenamiento

Cambio de motor de una base de datos

índices
- creación de llaves foráneas
- creación de índices únicos
- creación de índices

codificación
- ascii
- iso 8859-1
- utf8

checksum
- md5
- sha256

compresion
- compress y decompress en sentencias sql
- compress y decompress backup
- definir una base de datos comprimida (varchar, text)

cifrado
- base de datos cifrada
- backup cifrado

grafos
- diagrama de estructura de datos

Para mayor detalle ver este [enlace](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.172.3370&rep=rep1&type=pdf).

- diagrama de dependencias




Parser de SQL

La segunda fase del proyecto, en cuanto al parser de SQL, consiste en agregar los siguientes componentes:

Índices
Agregar al parser la administración de índices, la especificación está en el capítulo 11 de la documentación de PostgreSQL [Indexes](https://www.postgresql.org/docs/13/indexes.html)

PL/pgSQL
Agregar al parser el lenguaje procedural, la especificación están en el capítulo 42 de la documentación de PostgreSQL [PL/pgSQL — SQL Procedural Language](https://www.postgresql.org/docs/13/plpgsql.html)

Traducción, optimización y ejecución de código
La ejecución del lenguaje PL/pgSQL se realizará mediante la traducción hacia un lenguaje intermedio basado en Python que cumpla con las características del código de tres direcciones. El código generado debe ejecutarse desde Python para mostrar los resultados al cliente.







Administrador de la base de datos






