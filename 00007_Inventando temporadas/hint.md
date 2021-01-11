Recuerda que tienes la cláusula `WHERE` para poner una condición que filtre determinadas filas. 

Para seleccionar una fila en particular, tienes el ID que la distingue unívocamente. 

Aquí tienes un ejemplo con un afiliado de la isapre que se mudó:

``` sql 
UPDATE afiliados SET domicilio = "Av. Providencia 1576" WHERE nro_afiliado = 123987; 
```
