---
title: Tienda de Magia
creation date: 2024-02-21 01:57
tags:
  - state/seedling
  - type/note
aliases:
---

## Pociones

```dataview
table Efecto, Rareza, Precio as "Precio (po)"
from #om/poc 
```

## Pergaminos

```dataview
table Peso, Precio as "Precio (po)"
from x
```


## Focos de Conjuro

### Elemento Mágico

```dataview
table Peso, Precio as "Precio (po)"
from #Foco/EM
```

### Foco Druídico

```dataview
table Peso, Precio as "Precio (po)"
from #Foco/FD 
```


### Símbolo Sagrado

```dataview
table Peso, Precio as "Precio (po)"
from #Foco/SS 
```




## Venenos

(Verter: 5p, Lanzar: 20p + Bon. Fuerza, R: 5p)

```dataview
table Efecto, Aplicación, Condición, Precio as "Precio (po)"
from #om/ven 
```






