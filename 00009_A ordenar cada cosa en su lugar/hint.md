Si no te diste cuenta de cómo hacerlo, acá te mostramos cómo agregamos a nuestra base de datos de afiliados todas las personas cuyo nombre empieza con A, ordenados por RUT: 

``` sql INSERT INTO afiliados (a_nombre, a_rut, a_direccion) SELECT p_nombre, p_rut, p_domicilio FROM personas WHERE nombre LIKE "A%" ORDER BY p_rut; ```
