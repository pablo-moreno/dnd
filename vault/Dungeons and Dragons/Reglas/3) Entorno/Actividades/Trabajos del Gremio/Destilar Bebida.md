---
title: Destilar Bebida
creation date: 2024-03-06 11:49
tags:
  - state/seedling
  - type/note
aliases: 
Salvación:
  - "[[Naturaleza]]"
  - "[[Dungeons and Dragons/Reglas/1) Estadisticas/Habilidades/Investigación|Investigación]]"
---
Puedes gastar tu acción semanal para crear Brebajes en la estancia. 

*Lista de Bebidas*
```dataview
table int_precio/10 as "Precio (po)", Cantidad
from #obj/beb  
```


Además, los Cerveceros pueden tener una bebida añejándose para aumentar su calidad cada semana que pase, lo que otorga un multiplicador a su precio de venta.

El cervecero podrá quedar añejándose 1 bebida a la semana por cada nivel de taberna. Esto no requiere de ninguna acción.


| Calidad    | Bonus de<br>Precio |
| ---------- | ------------------ |
| Común      | x2                 |
| Poco Común | x4                 |
| Raro       | x6                 |
| Muy Raro   | x8                 |
| Legendario | x12                |

