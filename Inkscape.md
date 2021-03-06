
                                                   20 de Octubre del 2021

# Índice


[Imágenes](#imágenes)

[Formatos Comunes](#formatos-comunes)

[Imágenes Vectoriales](#imágenes-vectoriales)

[Formatos](#formatos)

[Ejercicio Vectoración](#ejercicio-vectoración)

[Ejercicio Rasteración](#ejercicio-rasteración)

[Propiedades de las formas](#propiedades-de-las-formas)

[Ejercicio de alineación](#ejercicio-de-alineación)

[Operaciones booleanas con formas](#operaciones-booleanas-con-formas)

[Como ajustar el lienzo en Inkscape](#como-ajustar-el-lienzo-en-inkscape)

[Editor de texto](#editor-de-texto)
# Imágenes 

Las imágenes se guardan digitalmente de dos maneras:

- Por un lado (Ráster) podemos hacer una matriz de puntos (Mapa de bits) y a  cada punto le asignamos un color (Píxel) 

Tres colores primarios aditivos : Rojo, Verde y Marrón o mejor conocido como RGB(Red,Green,Brown)

Otra forma de colores primarios es llamada: CMYK(Cyan,Magenta,Yellow,Black)

Propiedades de una imagen Ráster:

*Resolución*. Un mapa de bits tiene un tamaño concreto de A x B

La resoulción se puede expresar de diferentes formas:

-> Nº total de píxeles. Normalmente MP (Megapíxeles), esto es el número que resulta de A x B en millones de píxeles

-> Lineas horizontales. En vídeo se utiliza la cantidad de líneas horizontales, normalmente se asume una proporción concreta entre A y B, por ejemplo 4/3(TV)
o 16/9(Cine)

Las líneas horizontales suelen ser :

240p --> (240 píxeles de alto)

480p --> 480 píxeles de alto

720p --> 720 píxeles de alto

1080p --> HD(1080 píxeles de alto)

2k --> 2048 píxeles de alto 

4k --> 4096 píxeles de alto


-> Un archivo puede expresar su resolución dicendo A x B

 - Por ejemplo una imagen de 350 x250 píxeles. Se utiliza cuando hablamos de archivos concretos.

NO CONFUNDIR con la resolución de impresión, medida en puntos por pulgad (ppp) o (dpi) dots per inch.


- Espacios de color 

 - Sistemas para detallar los colores :

 - RGB (Red, Green, Blue) para pantallas

 - CMYK (Cyan, Magenta, Yellow, Black) para imprimir

 - Colores indexados -> Toma hasta 256 colores y se usan solo esos --> GIFs

- Canal (como los 3 canales de RGB) de transparencia. Este canal de llama alfa (α). Los PNG pueden tenerlos, los GIFs o los JPG no.

### FORMATOS COMUNES 

- JPG ( y JPEG) --> Tiene congresión

![](https://github.com/Tabrih/1er-Trimestre/blob/main/DEATH_NOTE_L_wallpaper.jpg)

- GIF --> Color indexado. Se puede animar

![](https://c.tenor.com/ZX95mDnlodwAAAAd/the-rock-sus-eye.gif)

- PNG --> No tiene compresión. Admite alfa

![](https://github.com/Tabrih/1er-Trimestre/blob/main/Astronauta.png)

- TIFF --> Sin compresión

Otros particulures:

- PSO

- RAW (Foto sin comprimir)

Imagen Ráster está hecha de píxeles y tiene formatos los .JPG .GIF .PNG.

## IMÁGENES VECTORIALES

Se define la imagen como un conjunto de formas (Líneas, Puntos,etc) Cada una de estas formas está definida matemáticamente.

Por ejemplo un círculo se define como un relleno. 

Forma = Círculo

Radio = 30 píxeles

Borde = 1 ancho, color rosa

### FORMATOS 

- .svg (Scalable vector graphic)

- .eps

Específicos

- DWG (Autocad)

- DXF (AutoCad)

- 3DM (Rhinoceros)

- AI (Ilustrator)

Formato mezcla Ráster y vectorial

- PDF = Portable Document Format

Rasterizamos una imagen, cuando pasamos de una imagen vectorial a una imagen ráster (mapa de bits).

Vectorizar es pasar de un mapa de bits (Imagen Ráster) a formato vectorial.

Las imágenes vectoriales están formadas de formas.

### Ejercicio Vectorización

Vamos a tomar la imagen del cuadro del león de Rosa Bonheur.

Esta es la imagen rásterizada original.

![](https://github.com/Tabrih/1er-Trimestre/blob/main/El%20Cid.jpg)

[Fuente](https://www.museodelprado.es/coleccion/obra-de-arte/el-cid/19984271-9cb6-476d-8655-f012e1fec1bf)

Abrimos Inkscape

Lo primero es decidir si el programa hará una o más pasadas. Con una única pasada SIEMPRE obtendremos una imagen en blanco y negro(Que podremos colorear después).

Una única pasada tenemos:

- Corte de luminosidad -> Junta todos los píxeles más oscuras que un umbral.

- Detección de bordes -> Revisa el contrate entre píxeles

Varias pasadas nos permite hacer una imagen vectorial más compleja, con varios grises o colores. Esto necesita más capacidad de proceso.

Después de importar el león, vamos a ajustr el lienzo, para ello vamos a propiedades de documento --> En tamaño, vamos a ajustar página o contenido
selecionamos la imagen y pulsamos el botón Ajustar página a contenido o selección

- Vectorizamos el león con las siguientes características

   - Múltiples pasadas  - Colores   - 8 pasadas

- Borramos el original 

- Guardamos como León 1.svg

- Subimos al Github

![León 1](https://github.com/Tabrih/1er-Trimestre/blob/main/Le%C3%B3n%201.svg)

Para realizar esta imagen la vectorizé en Inkscape con múltiples pasadas --> colores --> 8 pasadas y obtuvé este resultado.

![León 2](https://github.com/Tabrih/1er-Trimestre/blob/main/Le%C3%B3n%202.svg)

Para realizar esta imagen la vectorizé en Inkscape e invertí los colores, obteniendo un león blanco con fondo negro y viceversa. Luego les cambié los colores y se quedó así.

![León 3](https://github.com/Tabrih/1er-Trimestre/blob/main/Le%C3%B3n%203.svg)

Para realizar esta imagen la vectorizé en Inkscape varias veces, tanto una verde como una negra, las sobrepusé y me quedó así. Me gusta, la verdad.

[Imagen propia]



                                                      27 de Octubre de 2021


### Ejercicio Rasterización

![León 1](https://github.com/Tabrih/1er-Trimestre/blob/main/Im%C3%A1genes/Le%C3%B3n%201.png)

He rasterizado esta imagen a 16x21 píxeles y se ve muy pequeña.


![León 2](https://github.com/Tabrih/1er-Trimestre/blob/main/Im%C3%A1genes/Le%C3%B3n%202.png)

He rasterizado esta imagen a 160x211 píxeles, se ve mucho más grande que la anterior.

![León 3](https://github.com/Tabrih/1er-Trimestre/blob/main/Im%C3%A1genes/Le%C3%B3n%203.png)



![León 4](https://github.com/Tabrih/1er-Trimestre/blob/main/Im%C3%A1genes/Le%C3%B3n%204.png)



![León 5](https://github.com/Tabrih/1er-Trimestre/blob/main/Im%C3%A1genes/Le%C3%B3n%205.png)


# Propiedades de las formas

- Leon1.svg

- Desagruparlo -> Varias formas -> Cambiar las propiedades de las formas

3 ELEMENTOS 
- Relleno "Pincel"
- Trazo (Línea)
- Estilo de trazo(Línea)

LEÓN 1

![León.svg](https://github.com/Tabrih/1er-Trimestre/blob/main/Im%C3%A1genes/Le%C3%B3n%201.svg%20Relleno%20con%20borde.svg)

RGBA 

Mezcla de los colores primarios aditivos : Rojo (Red), Verde (Green) y Azul (Blue).


HSL (Hue,Saturation,Light)

Tono/Saturación

Este sistema mezcla lo siguiente: 
- Un de tono de color en la rueda cromática ( Hue, tono de color en inglés) 
- Un canal de nivel de saturación cromática que va de gris al color (Saturation) 
- Un canal de luminosidad de color (Light)
- Un canal de transparencia(Alfa)

CMYK 

Este sistema mezcla los tres color primarios substractivos ( Cyan,Magenta ,Amarillo) y un canal de negro.

RGBa  [1e 3a 5666] --> Byte de color en modo RGB (Hexadecimal)
       R  G  B A
       
### Ejercicio de alineación

Alineación vertical y horizontal:
![](https://github.com/Tabrih/1er-Trimestre/blob/main/Im%C3%A1genes/Underground.svg)

Alineación con un solo objeto, en este caso el triángulo:
![](https://github.com/Tabrih/1er-Trimestre/blob/main/Im%C3%A1genes/Mitsubichi.svg)


# Operaciones booleanas con formas

Proceso de como crear un logo:

Creamos un círculo con la tabla de creación de la izquierda en Inkscape:

![](https://github.com/Tabrih/1er-Trimestre/blob/main/Im%C3%A1genes/Proceso%20logo%201.png)

Creamos un rectángulo con la tabla de creación de la izquierda en Inkscape:

![](https://github.com/Tabrih/1er-Trimestre/blob/main/Imágenes/Procesologo2.png)

Creamos un triángulo sobre la esquina del rectángulo con la tabla de creación de la izquierda en Inkscape:

![](https://github.com/Tabrih/1er-Trimestre/blob/main/Im%C3%A1genes/Proceso%20logo%203.png)

Seleccionamos el rectángulo y el triángulo, vamos al apartado trayecto y clickamos en diferencia:

![](https://github.com/Tabrih/1er-Trimestre/blob/main/Im%C3%A1genes/Captura%20de%20pantalla%20de%202021-10-27%2013-06-38.png)

Seleccionamos el rectángulo y nos vamos a la flechas de arriba a la izquierda en Inkscape y elegimos la de reflejar los objetos seleccionados verticalmente:

![](https://github.com/Tabrih/1er-Trimestre/blob/main/Im%C3%A1genes/Captura%20de%20pantalla%20de%202021-10-27%2013-09-27.png)

Hacemos click derecho sobre el rectángulo y seleccionamos la opción de duplicar. Al hacer esto procedemos a mover ambos rectángulos en el círculo:

![](https://github.com/Tabrih/1er-Trimestre/blob/main/Im%C3%A1genes/Captura%20de%20pantalla%20de%202021-10-27%2013-10-00.png)

Seleccionamos el rectángulo de la parte de arriba junto al círculo y de nuevo vamos al apartado de trayecto y clickamos en diferencia:

![](https://github.com/Tabrih/1er-Trimestre/blob/main/Im%C3%A1genes/Captura%20de%20pantalla%20de%202021-10-27%2013-10-21.png)

Hacemos lo mismo con el rectángulo de la parte inferior y finalmente obtenemos el logo, en este caso el de la empresa Fagor:

![](https://github.com/Tabrih/1er-Trimestre/blob/main/Im%C3%A1genes/Captura%20de%20pantalla%20de%202021-10-27%2013-10-28.png)

## Como ajustar el lienzo en Inkscape

Primero nos vamos al apartado de la parte superior izquierda de Inkscape llamada Archivo y seleccionamos propiedades del documento, también podemos usar un atajo y usar las teclas Control + SHift + D para ajustar el lienzo de Inkscape:

![](https://github.com/Tabrih/1er-Trimestre/blob/main/Im%C3%A1genes/Captura%20de%20pantalla%20de%202021-10-27%2013-40-32.png)

Elegimos cualquier imagen, en este caso he elegido el cuadro de Rosa Bonheur, El Cid:

![](https://github.com/Tabrih/1er-Trimestre/blob/main/Im%C3%A1genes/Captura%20de%20pantalla%20de%202021-10-27%2013-43-50.png)

Cuando tenemos la imagen que nos guste, vamos a la parte superior, específicamente al apartado edición, y, en este, seleccionamos ajustar la página a la selección, o más rápidamente podemos usar el atajo de Mayús + Control + R:

![](https://github.com/Tabrih/1er-Trimestre/blob/main/Im%C3%A1genes/Captura%20de%20pantalla%20de%202021-10-27%2013-43-57.png)

 Y así tendriamos la imagen ajustada al lienzo.


                                                  16 de Noviembre de 2021


# Editor de texto

Línea de texto
Caja de texto

Sans Serial → Normal
- bold → negrita
- Italic→ Cursiva
- bold Italic → negrita crusivo

Tamaño en Puntos (En impresión)
 - Subtítulo 14-20 pts
 - Texto para leer en A4: 12 pts
 - Texto pequeño: 8-10 pts
 - Letra pequeña del contrato con Satanás 4-6 pts
 
Super Script = Super Índice

Este tipo de escritura es el de las potencias.

Subscript = Sub Índice

Este tipo de escritura es de notación científica.

Espacio entre letras (Interletrado o Kerning)


