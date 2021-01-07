Uff, ¡qué alivio! Funcionó, y hasta hay un ID :scream:


Eso se debe a la forma en que se definió la tabla al crearla.

* Sabemos que el ID es sumamente necesario para identificar unívocamente a cada registro, así que le ordenamos a la tabla que ese campo se autogenere solo. :sunglasses:
* El resto de los campos no son tan relevantes, así que, como no les indicaste nada, quedaron en “NULL”. Esto no hubiese pasado con el título, porque... ¿qué serie o película no tiene título? :stuck\_out\_tongue\_winking\_eye: Y eso también se indica al crear la tabla: cuáles campos son opcionales (lo que se conoce como "nulleables") o no.

