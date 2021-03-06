Cable-Carrier-RepRap
====================

Small cable carrier for Prusa Iteration 3 (print it yourself!)
--------------------------------------------------------------

I'm sorry, it's In Spanish ... I'll translate later


![](http://i30.photobucket.com/albums/c343/rafatorresc/efb934ee-ae60-44f1-a96b-42c1645e2461_zps2c6e53f4.png)

# Cable Carrier for RepRap 3D Printers --- Cadena Portacables para impresoras RepRap

Es una cadena portacables de pequeño tamaño para utilizar en una Prusa Iteration 3. 
El marco no deja mucho espacio para pasar a la cadena, de modo que he diseñado esta 
con un radio de giro de unos 40 mm.

Hay dos tipos de eeslabones: Abiertos y cerrados. Por lo que he probado, los abiertos 
funcionan muy bien y son más fáciles de montar que los cerrados. Con los cerrados es 
mas dificil que se abra la cadena.

La idea de hacer un eslabón abierto es tener la posibilidad de añadir un cable o quitar
un cable sin tener que desmontar toda la cadena. No se si funcionará, pero no se pierde 
nada pues ambos funcionan bien.

<center>
**Realmente, el eslabón cerrado punciona mucho mejor que el abierto y es el que os recomiendo utilizar.**</center>

Por el momento dejo los STL para que se prueben y me podais mandar sugerencias.

Nota: A sugerencia de alguien, os dejo también el fichero "fuente" en freecad. Para 
cambiar las dimensiones hay que abrir los sketches, y cambiar los valores de 
las restricciones. Quizás he abusado un poco de la geometría, pero ... es tan fácil ;)

 **El autor, *osease yo*, no me hago responsable de los problemas 
derivados del uso o abuso de la información, ficheros o diseños publicaods por mi.** 

Se prudente en el uso.

Si los datos no se ajustan a la realidad imprusada es posible que necesites calibrar TU impresora ;)




## Datos más técnicos:

Licencia GPL (creo que v2, no lo recuerdo bien)

Datos aproximados 
 - Anchura de la cadena:   16mm
 - Altura de la cadena: 10 mm
 - Hueco para cables de 7 mm x 6 mm = 42 - 1 mm2
 - Ángulo de giro por eslabón:  40º
 - Longitud de cadena por eslabón: 10 mm (para calcular los eslabones que necesiteis.
 - Anchura de giro de 180º: 42 mm aprox.

 
 
## Impresión 
 
Si las piezas se cogen bien al cristal (o kapton o dm o lo que sea que uses como soporte), es *recomendable* imprimir los eslabones sin usar Brim ni Raft.

![](http://i30.photobucket.com/albums/c343/rafatorresc/Mobile%20Uploads/20140622_121259_zpstpk6inaj.jpg)
Foto: Impresión de 9 eslabones donde se observa que no uso Brim para sujección.

Para ayudar a la adhesión del eslabón a la mesa, he añadido superficies en zonas que no molestan y que se pueden retirar con facilidad. Con estas superficies es más facil imprimir sin usar Brim.

![](http://i30.photobucket.com/albums/c343/rafatorresc/Mobile%20Uploads/20140622_121600_zpsbwobwf7k.jpg)
Foto: Cadena montada con los eslabones recién impresos, sin limar ni ajustar.

Para el caso de tener que usar Brim, he achaflanado las aristas donde pudieran haber 
interferencia con los restos del Brim y con el "efecto" de la primera capa (que suele ser 
más ancha). 

En principio no debería funcionar mal sin retoques adicionales. Y si no es así, coged la 
lima y saneais los eslabones en las zonas achaflanadas. Es posible que algunos errores 
de impresión impidan a la cadena ponerse completamente recta.... *lima*.

## Sujección a motor NEMA17

Podeis imprimir las piezas Abrazadera y EslabonFijo para hacer el anclaje del final de la cadena a un motor de dimensiones NEMA17.

Necesitareis un tornillo M3x5mm, arandela y tuerca M3. La tuerca se aloja en el interior de la abrazadera y la arandela y el tornillo en la parte superior del eslabonFijo. Enroscais, orientais el eslabón en la dirección que querais y fijais con un poco de apriete al tornillo.

En la parte inferior de la abrazadera encontrareis dos salientes. Si necesitais fijar la abrazadera con más fuerza podeis probar a colocar una abrazadera de nylon (de las que usamos para agrupar cables, fijar lm8uu, etc) en estas pestañas y tirar hasta obtener la fijación deseada. Esto no lo he probado aun pero pronto lo haré.


## Desarrollo posterior

Proximamente espero tener tiempo para el diseño de los anclajes:
  - a motor [hecho]
  - al soporte de aluminio de la hotbed. [muy MUY pronto, casi acabado]
  - a la base del lateral del marco de aluminio. [pronto]
  - al extremo izquierdo del eje X [pronto]
 
Os ruego que hagais comentarios y sugerencias para hacer evolucionar el diseño y que sea 
de la máxima utilidad para todos.
 
 Espero que os sea de utilidad.
 
 Saludos!

 Rafa
