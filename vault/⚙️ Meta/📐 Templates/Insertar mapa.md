
```leaflet
image: [[Costa de la Espada.jpg]]
id: costa_de_la_Espada
defaultZoom: 1
minZoom: 1
maxZoom: 10
unit: millas
recenter: true
bounds: [[0, 0], [472.02, 714.28]]
scale: 4
width: 100%
```

## Midiendo distancias
Para poder medir correctamente la distancia entre dos puntos tenemos que establecer el campo `bounds` correctamente. Este campo nos indica los límites del mapa.

### Cómo calcular los límites del mapa

#### Con cuadrículas

Si tenemos un mapa de cuadrículas lo tenemos sencillo. 

Si una cuadrícula son 5 pies, tendremos que contar el número de cuadrículas de ancho y de alto y multiplicar esos valores por los pies de la cuadrícula, en este caso 5.

Por ejemplo:

30 de alto * 5 pies = 150 de alto
40 de ancho * 5 pies = 200 de ancho.

Nos daría por tanto unas `bounds` límites de `[150, 200]`, siendo el primer valor el alto y el segundo el ancho.

Teniendo en cuenta que el punto de partida de las `bounds` es `[0, 0]`, el valor que tendremos que establecer es `[[0, 0], [150, 200]]`

#### Con distancias de referencia

Para medir mapas sin cuadrículas pero con distancias de referencia será un poco más complicado, pero no mucho.

Necesitamos: 

- La referencia de distancia en la leyenda
- El tamaño de la imagen

Utilizando alguna herramienta de edición de imagen, podemos obtener el número de pixeles por unidad de medida.

![[Midiendo distancias de referencia.png]]

En este caso concreto, 126px equivalen a 100 millas, por lo tanto 1 milla equivale a 1,26px. 

Dicho de otro modo, 1px equivale a (1 / 1,26 ~=) 0,793 millas

![[Ancho y alto de mapa.png]]

Si la imagen tiene, por ejemplo, `3600px * 2329px` sabemos que la distancia total que cubre el mapa es de  `(2329px * 0,793m/px) * (3600px * 0,793m/px)` = `[1888.1, 2857.14]`

![[Distancia ajustada correctamente.png]]

Puede darse el caso de que la imagen se haga muy grande, pero no hay problema, pues tenemos la propiedad `scale`.

Con esta propiedad, podemos escalar las distancias mientras hacemos más pequeña la imagen del mapa.

Para ello, dividiremos el resultado de las `bounds` entre un valor que podamos manejar fácilmente (2, 4, 5) y ese mismo valor se lo estableceremos a la propiedad `scale`.

En el ejemplo que estamos viendo, si tenemos `[1888.1, 2857.14]` y lo dividimos entre 4 nos queda `[472.02, 714.28]` como `bounds` límites y el valor de `scale` sería 4.

Para medir distancias en el mapa, mantén pulsado alt y haz click en el punto de inicio y en el de fin, se pueden establecer puntos intermedios para calcular distancias irregulares.

![[Distancia entre dos localizaciones.png]]
Aquí podemos ver, por tanto, que la distancia entre Warlock's Crypt y Trollclaw Ford en línea recta es de 148,4 millas.

