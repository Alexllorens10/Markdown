# Markdown

Markdown es un lenguaje de marcado ligero, una forma de agregar formatos como encabezados, negritas, cursivas, listas... a un texto sin formato utilizando un editor de txto simple. Es decir, una forma rápida de coger apuntes con ordenador y pasarlos a limpio en un solo paso.

- Elementos de bloque
  - Párrafos
  - Saltos de línea
  - Encabecados
  - Cítas
  - Listas
  - Códigos de bloque
  - Líneas horizontales
- Elementos de línea
  - Énfasis
  - Links o enlaces
  - Código
  - Imágenes
- Otro elementos
  - Links automáticos
  - Omitir Markdown
  - Símbolos matemáticos

# Saltos de blque (=Párrafos)

Para generar un nuevo párrafo en Markdown simplemente separa el texto mediante una línea en blanco (pulsando dos veces INTRO). `Ejemplo:`

Lorem ipsum dolor sit amet , consectetur adipisicing elit. Eligendi voluptas harum nostrum, dolores iusto dolorum eveniet similique quos dolorem porro ducimos volupate, temporibus, reiciendis voluptatem modi explicabo ea. Eius, totam?

# Saltos de linea (=lineas de texto)

dadasdasdasd

# ENCABEZADOS

Las almuadillas o hastag `#` es el método utilizado en Markdown para crear encabezados. Debes usarlos añadiendo un por cada nivel y dejando un espacio en blanco.
`Ejemplo:`

## Encabezado 2

### Encabezado 3

#### Encabezado 4

##### Encabezado 5

###### Encabezado 6

# Líneas horizontales

# Enfatizar: negritas y/o cursivas

Para poner cursivas entre 1 asterisco Para poner negritas encierra entre 2 asteriscos Para poner negritas y cursiva encierra entre 3 asteriscos `Ejemplos:`

Lorem ipsum *dolor* sit **amet** , consectetur adipisicing elit. Eligendi voluptas harum nostrum, dolores iusto dolorum eveniet similique quos dolorem porro ducimos volupate, temporibus, reiciendis ***voluptatem modi explicabo*** ea. Eius, totam?

# Líneas horizontales

Para crearlas, en una línea en blanco deberás incluir `tres` de los siguientes elementos: 3 asteriscos, 3 guiones, o 3 guiones bajos. `Ejemplos:`

***

# Listas

Para crear listas desordenadas podemos utilizar 3 tipos de simbolos por cada item de la lista: Un asterisco `*`, un guión medio `-` o un símbolo más `+`. `Ejemplos:`

* Ítem 1
* Ítem 1
* Ítem 1

Para crear listas ordenadas debes utilizar la sitaxi de tipo: `1.`.

1. Ítem 1
2. Ítem 1
3. Ítem 1

Para generar listas anidadas (desordenadas u ordenadas) dentro de otras, simplemente trndrás que añadir `dos (o cuatro) espacios en blanco`. `Ejemplos:`

* Ítem 1
    * Ítem 12
        * Ítem 121
* Ítem 2
1. Ítem 1
    i. Ítem 12
        a. Ítem 121
2. Ítem 1

# Links o enlaces

Se crean escribiendo la palabra o texto enlazada entre `[]` corchetes, y el link en cuestión entre `()` paréntesis.

Sin texto enlazado la URL entre ángulos `< URL >`  Enlace de ejemplo como referencia: [3con14](https://3con14.es/), y al final del texto escribir la etiqueta seguida de dos puntos.

# Imágenes

Insertar una imagen con Markdown se realiza de una manera idéntica a insertar links. En este caso, debes añadir un símbolo de `!` exclamación al principio y el enlace que es la ubicación de la imagen.

![Primera moto](https://media.totmoto.com/product/yamaha-x-max-ie-125-abs-800x800.jpeg "Segunda moto")

![Texto alternativo](https://www.motofichas.com/images/cache/01-yamaha-xmax-125-250-momo-estudio-739-a.jpg "Título alternativo")

# Tablas

Markdown permite dibujar tablas mediante plecas `|`. Cada celda está separada por uno de estos caracteres. Para crear encabezados que se distingan vulnerablemente del resto del contenido, se subrayan las celdas correspondientes con guiones `-`. `Ejemplo:`

|Columna 1 | Columna 2 |
|--|--|
|uno|dos|
|tres|cuatro|
|cinco|seis|

# Línea de Código

Encerrando el código entre acentos graves `<html lang="es">`

# Bloque de Código

Para crear un bloque entero que contenga código lo único que tienes que hacer es encerrar dicho párrafo entre dos líneas formadas por tres `~` virguilillas o tres acentos grave. La otra manera de añadir código en Markdown es comenzar el párrafo con `cuatro espacios en blanco`. `Ejemplo:`

~~~ html
<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <title>Document</title>
</head>
~~~

# Omitir Markdown

Cómo escribir ciertos símblos como * o #, sin que Markdown los interprete para convertirlos en negritas,... Escribiendo justo delante del símbolo la barra invertida `\`. `Ejemplo:` Esto es un asterisco \*.

# Escritura matemática

En línea encerrando la fórmula entre signos de `$` En parrafos centrados, encerrando las fórmula entre dos signos de `$$`

* Fórmulas en línea: $(a+b)² = a² + b² + 2ab$
* Fórmulas centradas: 

$$a² - b² =(a + b) * (a - b)$$

* Radicales: 

$$\sqrt{a² - b²}$$

* Fracciones:
 
$$ x = \frac{-b ± \sqrt{b² - 4ac}}{2a} $$

* Paréntesis grandes: 

$$\left(\sqrt{x²}\right){²}$$

* Colores: 

$${\color{yellow}{A}}aBb123$$