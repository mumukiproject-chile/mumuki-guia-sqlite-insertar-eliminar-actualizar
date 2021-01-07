Recuerda que tienes la cláusula `WHERE` para poner una condición que filtre determinadas filas. 

Para seleccionar una fila en particular, tienes el ID que la distingue unívocamente. 

Acá tienes un ejemplo con un afiliado de la isapre que se mudó:

``` sql 
UPDATE afiliados SET domicilio = "Av. Rivadavia 27639" WHERE nro\_afiliado = 123987; 
```
