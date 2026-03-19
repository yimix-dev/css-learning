## cascada

La cascada es el sistema de resolucion de conflictos de CSS
cuando muchas reglas estan aplicando estilos a un mimso elemento la cascada elige cual gana
la cascada resuelve con el criterio de 3 reglas que deciden el resultado final: !important, id> Clase> Etiqueta, la ultima regla gana

### !important

es un nivel especial de prioridad que se activa con !important, esta permite forzar una regla que contenga el !important sobre otras reglas. la desventaja es que si se abusa de !important se puede romper la estructura CSS, por eso profesionalmente se evita

### especificidad

la especificidad es un sistema de peso numerico donde entre mayor sea el numero mayor sera la especificidad, como modelo mental podemos decir que el peso aprximado es:
inline style = 1000
ID = 100
clase = 10
etiqueta = 1

### orden de aparicion

si dos reglas tienen exactamente el mismo peso, se mostrara el cambio de la ulitma regla que se añadio, es decir la ultima en ser escritra en el CSS es la que se sobrepondra osbre las demas con el mismo peso.

#### tambien se toma en cuenta:

navegador (user agent)
usuario
autor (CSS)

