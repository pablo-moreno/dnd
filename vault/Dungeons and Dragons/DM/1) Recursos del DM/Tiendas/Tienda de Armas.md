---
title: Tienda de Armas
creation date: 2024-02-18 01:22
tags:
  - state/seedling
  - type/note
aliases:
---

## Armas Simples

### Cuerpo a Cuerpo

```dataview
table Dado_de_Daño as Daño, Tipo_de_Daño as "Tipo de Daño", Propiedades, Peso, Precio as "Precio (po)"
from #CaC_Simple 
```

### A Distancia

```dataview
table Dado_de_Daño as Daño, Tipo_de_Daño as "Tipo de Daño", Rango, Propiedades, Peso as "Peso (lb)", Precio as "Precio (po)"
from #Dist/Simple
sort Precio asc
```


## Armas Marciales

### Cuerpo a Cuerpo

```dataview
table Dado_de_Daño as Daño, Tipo_de_Daño as "Tipo de Daño", Propiedades, Peso, Precio as "Precio (po)"
from #CaC/Marcial 
```

### A Distancia

```dataview
table Dado_de_Daño as Daño, Tipo_de_Daño as "Tipo de Daño", Rango, Propiedades, Peso, Precio as "Precio (po)"
from #Dist/Marcial 
```


## Armas de Fuego

```dataview
table Dado_de_Daño as Daño, Tipo_de_Daño as "Tipo de Daño", Rango, Propiedades, Precio as "Precio (po)"
from #Dist/Fuego 
```



## Munición

### Flechas

```dataview
table Dado_de_Daño as Daño, Efecto, Peso, Precio as "Precio (po)"
from #mun/f  
```


### Virotes

```dataview
table Dado_de_Daño as Daño, Efecto, Peso, Precio as "Precio (po)"
from #mun/v  
```


### Balas

```dataview
table Dado_de_Daño as Daño, Efecto, Peso, Precio as "Precio (po)"
from #mun/b  
```


### Otros

```dataview
table Dado_de_Daño as Daño, Efecto, Peso, Precio as "Precio (po)"
from #mun/o  
```



