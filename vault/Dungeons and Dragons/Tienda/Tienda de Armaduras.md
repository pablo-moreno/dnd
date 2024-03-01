---
title: Tienda de Armaduras
creation date: 2024-02-21 01:57
tags:
  - state/seedling
  - type/note
aliases:
---


## Armadura Ligera

```dataview
table Clase_de_Armadura as "Clase de Armadura", Tipo_de_Armadura as "Tipo", Req.Fuerza, Sigilo, Peso, Precio as "Precio (po)"
from #armor/lig 
```

## Armadura Media

```dataview
table Clase_de_Armadura as "Clase de Armadura", Tipo_de_Armadura as "Tipo", Req.Fuerza, Sigilo, Peso, Precio as "Precio (po)"
from #armor/med  
```


## Armadura Pesada

```dataview
table Clase_de_Armadura as "Clase de Armadura", Tipo_de_Armadura as "Tipo", Req.Fuerza, Sigilo, Peso, Precio as "Precio (po)"
from #armor/pes  
```


## Escudos

```dataview
table Clase_de_Armadura as "Clase de Armadura", Tipo_de_Armadura as "Tipo", Req.Fuerza, Sigilo, Peso, Precio as "Precio (po)"
from #armor/esc  
```



## Conjunto de Ropa

```dataview
table Clase_de_Armadura as "Clase de Armadura", Tipo_de_Armadura as "Tipo", Req.Fuerza, Sigilo, Peso, Precio as "Precio (po)"
from #armor/ropa  
```


## Conjunto de Zapatos

```dataview
table Tipo_de_Armadura as "Tipo de Armadura", Peso, Precio as "Precio (po)"
from #armor/zap 
```

## Mochilas y Bolsas

### Bolsas para Objetos

```dataview
table Capacidad_Maxima as "Capacidad", Precio as "Precio (po)"
from "Dungeons and Dragons/Glosario/Objetos/Mochilas y Bolsas/Bolsas" 
```

### Mochilas

```dataview
table Capacidad_Maxima as "Capacidad", Bolsa_de_Objetos as "Bolsas", Peso, Precio as "Precio (po)"
from "Dungeons and Dragons/Glosario/Objetos/Mochilas y Bolsas/Mochilas"
```








