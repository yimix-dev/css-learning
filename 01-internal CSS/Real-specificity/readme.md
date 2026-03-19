# Real specificity

la especificicidad es el mecanicmo central de la resolcuion de conflictos en CSS para decidir que regla gana cuando muchas apuntan a un mismo elemento

## que problema resuleve?

cuando muchas reglas aplcian cambios a un mismo elmento, la especificidad entra en el juego para decidir atra vez e difernetes criterios cual va a ganar.

## definicion tecnica

Especificidad es el peso numérico asignado a un selector CSS que determina su prioridad frente a otros selectores que apuntan al mismo elemento.

Este peso se calcula contando ciertos tipos de selectores.

El navegador compara esos valores y la regla con mayor especificidad gana.

## comportamiento por defecto

si 2 reglas tienen exactamente el mismo peso se aplicara la ultima regla que fue escrita

tambien si no se añade una regla que cambie un valor predeterminado el navegador aplica uno por defecto a eso se le conoce como (user agent)




