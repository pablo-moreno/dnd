```leaflet
image: [[Costa de la Espada.jpg]]
id: costa_de_la_Espada
defaultZoom: 2
minZoom: 1
maxZoom: 10
unit: pies
recenter: true
bounds: [[0, 0], [150, 200]]
scale: 1
```

## Midiendo distancias
Para poder medir correctamente la distancia entre dos puntos tenemos que establecer el campo `bounds` correctamente. Este campo nos indica los límites del mapa.

### Cómo calcular los límites del mapa

Si tenemos un mapa de cuadrículas lo tenemos sencillo. 

Si una cuadrícula son 5 pies, tendremos que contar el número de cuadrículas de ancho y de alto y multiplicar esos valores por los pies de la cuadrícula, en este caso 5.

Por ejemplo:

30 de alto x 5 pies = 150 de alto
40 de ancho x 5 pies = 200 de ancho.

Nos daría por tanto unas `bounds` límites de `[150, 200]`, siendo el primer valor el alto y el segundo el ancho.

Teniendo en cuenta que el punto de partida de las `bounds` es `[0, 0]`, el valor que tendremos que establecer es `[[0, 0], [150, 200]]`
