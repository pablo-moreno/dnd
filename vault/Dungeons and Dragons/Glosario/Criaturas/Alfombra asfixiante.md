---
name: Alfombra asfixiante
tags:
  - type/enemy
alignment: 
race: "[[Autómata]]"
size: "[[Grande]]"
aliases:
  - alfombra
hit_dice: "`dice: 6d10`"
hit_points: 33
---
> Muchos héroes descuidados y aspirantes a ladrón llegan hasta el umbral de la morada de su enemigo con los ojos y los oídos abiertos en busca de trampas, solo para ver truncada prematuramente su aventura cuando las alfombras bajo sus pies se animan y le asfixian hasta la muerte. Una alfombra asfixiante puede tener diversas formas, desde una moqueta  delicadamente tejida digna de una reina hasta una tosca estera en la choza de un campesino. Las criaturas capaces de detectar magia pueden sentir el aura mágica falsa de la alfombra.
> 
> En ocasiones, una alfombra asfixiante parece una alfombra voladora o algún objeto mágico beneficioso. Sin embargo, cualquier personaje que se detenga o se siente en la alfombra, o que intente pronunciar una palabra de mando, quedará atrapado por la alfombra, que se enrollará firmemente alrededor de la víctima.
## Características
| Característica   | Nivel | Bonificador | Lanzar dado      |
| ---------------- | ----- | ----------- | ---------------- |
| [[Fuerza]]       | 17    | 3           | `dice: 1d20 + 3` |
| [[Destreza]]     | 14    | 2           | `dice: 1d20 + 2` |
| [[Constitución]] | 10    | 0           | `dice: 1d20`     |
| [[Inteligencia]] | 1     | -5          | `dice: 1d20 - 5` |
| [[Sabiduría]]    | 3     | -4          | `dice: 1d20 - 4` |
| [[Carisma]]      | 1     | -5          | `dice: 1d20 - 5` |

[[Clase de Armadura]]: 12
[[Puntos de golpe]]: `=this.hit_points` (`= this.hit_dice`)
[[Velocidad]]: 10
## Inmunidad a daño
- [[Psíquico]]
- [[Veneno]]
## Inmunidad a estados
- [[Asustado]]
- [[Cegado]]
- [[Ensordecido]]
- [[Envenenado]]
- [[Hechizado]]
- [[Paralizado]]
- [[Petrificado]]
## Sentidos
- Visión ciega 60 pies (ciego más allá de este radio)
- [[Percepción pasiva]] 6

## Pasivas

**Susceptibilidad a la Antimagia**. La alfombra estará [[Incapacitado|incapacitada]] mientras se encuentre en el área cubierta por un campo antimagia. Si es el objetivo de disipar magia, la alfombra deberá tener éxito en una tirada de salvación de Constitución con [[CD]] igual a la salvación de conjuros del lanzador o estará inconsciente durante 1 minuto. 

**Transferir Daño**. Mientras esté agarrando a una criatura, la alfombra solo recibe la mitad del daño que se le inflija. La otra mitad del daño lo recibe la criatura agarrada. 

**Apariencia Falsa**. Mientras permanezca estática, la alfombra asfixiante es indistinguible de una alfombra normal y corriente.
## Acciones
**Asfixiar**. Ataque con arma cuerpo a cuerpo: +5 a impactar, alcance 5 pies, una criatura Mediana o más pequeña. Impacto: La criatura es agarrada (CD 13 para escapar). Hasta que el agarre finalice, el objetivo también estará apresado, cegado y corre el riesgo de asfixiarse, y la alfombra no puede envolver a otro objetivo. Además, al principio de cada uno de los turnos de la criatura, esta recibirá 10 (`dice: 2d6 + 3`) de daño [[contundente]]. 
## Desafío
2 - 450 [[PX]]