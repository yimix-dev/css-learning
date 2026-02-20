# Conexión de CSS

## CSS externo (<link>)

CSS externo es un documento aparte de el html que se conecta desde la cabeza del docmuneto con un <link> para definir apariencia y separar contenido de presentacion visual.

## CSS interno (<style>)

CSS interno es escribir CSS dentro del HTML mediante la etiqueta <style>, aplicando estilos solo a ese documento y sin posibilidad real de reutilización.

## CSS en línea (style="")

Es usar atributos de CSS desde le HTML aplicnado cambios solamente a ese elemento

## cual usar y por que

El estandar y profesional es el CSS externo, es el que mejor escala y funciona.

## Prioridad entre las formas

En igualdad de condiciones la jeraquia es CSS Inline > CSS interno > CSS externo, siendo el estilo en linea el que prevalece ante los demas.

## Dónde colocar el <link> y por qué

Tiene que ir ubicado en el head del docuemnto HTML porque el navegador necesita parsear el CSS antes de mostrar el contenido y asi evitar el efecto FOUC (Flash of Unstyled Content)

## Errores comunes al conectar CSS

La mayoría de errores al conectar CSS no son fallos del lenguaje, sino errores de rutas, nombres o estructura del proyecto.
