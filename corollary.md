¡Excelente! :smirk: Logramos sacar lo mejor del contenido... y de nosotros también. :blush:

En esta lección vimos:

* Cómo insertar nuevos datos en la tabla. 
* Cómo tomar datos de una tabla para insertarlos en otra. 
* Que se puede insertar información solo en los campos obligatorios, dejando vacíos los nulleables y autocompletando los que se generan solos, como las _PK_.
* Que se puede eliminar todo lo que queramos, usando las mismas condiciones que poníamos en las consultas. 
* Que podemos actualizar/modificar ciertos campos de registros que nos interesan. 
* Cómo ordenar y limitar la cantidad de resultados que se muestran. Y de yapa, una forma de resolver el "top 5" en otros motores:

 ``` sql 
 SELECT * FROM afiliados ORDER BY cuota DESC LIMIT 5; 
 ```

Pero te dejamos entrever que no existe una única tabla en el mundo, sino que puede haber varias, y hasta _relacionarse_ entre sí como tú con tus amigos: tienen cosas en común y pueden compartir información.

Veamos en la próxima lección de qué estamos hablando. :grimacing: 