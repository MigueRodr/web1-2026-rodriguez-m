# Declaración de uso de IA — Misión 01

## Herramientas que usé

Usé ChatGPT/Codex como asistente de aprendizaje y para obtener una primera propuesta
de estructura HTML. No copié el resultado sin leerlo: revisé cada elemento antes de
incluirlo en la práctica.

## Qué le pedí

Pedí una guía y una plantilla para crear una ficha de personaje de videojuego sin
CSS. La página debía incluir una imagen con texto alternativo, una tabla de
estadísticas, una lista de habilidades, una historia en varios párrafos y un
formulario con etiquetas asociadas a sus campos.

## Qué me devolvió

El asistente propuso un documento HTML con `header`, `main`, `section`, `article` y
`footer`. También propuso una tabla con encabezados, una lista no ordenada y campos
de formulario enlazados con elementos `label` mediante los atributos `for` e `id`.

## Qué estaba mal o incompleto

La primera propuesta usaba la carpeta `mision-01`, pero este repositorio exige la
convención `practica-NN-nombre`. Además, no puede incluir una fotografía real del
personaje por sí sola: debo añadir el archivo local `assets/tilin.jpg` y ajustar
el texto alternativo para que describa esa imagen exacta.

## Qué corregí y por qué

Organicé la entrega en `practica-01-ficha`, que coincide con la convención del
repositorio. Dejé el formulario con etiquetas explícitas, añadí un `caption` a la
tabla y mantuve una jerarquía de encabezados sin saltos: un `h1` seguido de varios
`h2`. Antes de entregar revisaré el resultado en W3C y Lighthouse, y registraré aquí
cualquier corrección adicional que encuentre.

Después pedí adaptar el contenido al personaje viral Tilín. Cambié el título, las
estadísticas, las habilidades, los párrafos de historia y los textos del formulario.
También cambié la ruta de imagen a `assets/tilin.jpg`. Debo reemplazar el texto
alternativo si la fotografía que elija no muestra a Tilín bailando con traje de
colores.

## Qué escribí yo desde cero

Debo elegir y guardar la imagen local de Tilín, comprobar que el texto alternativo
corresponda a ella y realizar las validaciones finales. También revisaré que no se
agregue CSS a esta misión.

## Reflexión

La IA fue útil para recordar la estructura semántica y los requisitos de
accesibilidad, pero necesito comprobarlos en el navegador y con los validadores. La
declaración me permite distinguir la propuesta inicial de las decisiones y pruebas
que haré personalmente.
