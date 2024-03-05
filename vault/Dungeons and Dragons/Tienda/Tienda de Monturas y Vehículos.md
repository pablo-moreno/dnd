---
title: Tienda de Monturas y Vehículos
creation date: 2024-02-21 01:59
tags:
  - state/seedling
  - type/note
aliases:
---

## Montura 

```dataview
table Capacidad_de_Carga as "Capacidad de Carga", velocidad as "Velocidad", Precio as "Precio (po)"
from #obj/mon 
```
## Embarcaciones

### Barco
```dataview
table Precio as "Precio (po)", Velocidad as "Vel(mph)", Vpt as "Vtp(p)", Tripulación as "Trip.", Pasajeros as "Pas.", Equipaje as "Cg.(ton)", CA, HP, Huecos_Armas as "Arm."
from #obj/bar 
```

### Armas de Embarcación

```dataview
table Precio as "Precio (po)", Rango, ca as "CA", HP, Dado_de_Daño as "Daño", Bon_Daño as "Bon. Daño"
from #bar/arm 
```


### Mejoras de Embarcación

```dataview
table Precio as "Precio (po)", Tiempo, Debuff
from #bar/mej 
```

## Arreos, Guarniciones y Vehículos de Tiro

```dataview
table Peso, Precio as "Precio (po)"
from #object/gua 
```





