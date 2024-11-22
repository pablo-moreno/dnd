---
name: Esqueleto
tags:
  - type/enemy
alignment: Legal malvado
race: "[[Muerto viviente]]"
size: "[[Mediano]]"
aliases:
  - esqueleto
  - esqueletos
hit_points: 13
hit_dice: "`dice: 2d8 + 4`"
ca: "13"
---
> Es posible lograr que un esqueleto se levante insuflándole magia oscura. Estos monstruos  obedecen las invocaciones de los lanzadores de conjuros que los convocan desde cementerios pedregosos y campos de batalla, o se alzan en los lugares saturados de muerte y pérdida,  despertados por el estímulo de la magia nigromántica o la presencia de un mal que corrompe lo que toca.


## Características
| Característica                                                           | Nivel | Bonificador | Lanzar dado      |
| ------------------------------------------------------------------------ | ----- | ----------- | ---------------- |
| [[Dungeons and Dragons/Reglas/Estadisticas/Estadisticas/Fuerza\|Fuerza]] | 10    | 0           | `dice: 1d20 + 0` |
| [[Destreza]]                                                             | 14    | 2           | `dice: 1d20 + 2` |
| [[Constitución]]                                                         | 15    | 2           | `dice: 1d20 + 2` |
| [[Inteligencia]]                                                         | 6     | -2          | `dice: 1d20 - 2` |
| [[Sabiduría]]                                                            | 8     | -1          | `dice: 1d20 - 1` |
| [[Carisma]]                                                              | 5     | -3          | `dice: 1d20 - 3` |

[[Clase de Armadura]]: `=this.ca`
[[Puntos de golpe]]: `= this.hit_points` (`=this.hit_dice`)
[[Velocidad]]: 30

## Inmunidad a daño
- [[Veneno]]

## Inmunidad a estados
- [[Cansancio]]
- [[Envenenado]]

## Sentidos
- Visión en la oscuridad 60 pies
- [[Percepción pasiva]] 9

## Idiomas
- No puede hablar, pero entiende todos los idiomas que aprendió en vida

## Acciones
Espada corta. Ataque con arma cuerpo a cuerpo: +4 a impactar, alcance 5 pies, un objetivo. Impacto: 5 (`dice: 1d6 + 2`) de daño [[perforante]].
Arco corto. Ataque con arma a distancia: +4 a impactar, alcance 80/320 pies, un objetivo. Impacto: 5 (`dice: 1d6 + 2`) de daño [[perforante]].
## Desafío
1/4 - 50 [[PX]]


```statblock
name: Esqueleto
size: Mediano
type: No muerto
subtype: ""
alignment: Legal malvado
ac: 13
hp: 13
hit_dice: 2d8 + 4
speed: 30 ft.
stats:
  - 10
  - 14
  - 15
  - 6
  - 8
  - 5
damage_vulnerabilities: Contundente
damage_resistances: ""
damage_immunities: ""
condition_immunities: Envenenado
senses: Visión en la oscuridad 60 pies., Perceción pasiva 9
languages: No puede hablar
cr: 1/4
bestiary: true
actions:
  - name: Espada corta
    desc: "Ataque cuerpo a cuerpo: +4 al impactar, alcance 5 pies, un objetivo. Impacto: 5 (1d6 + 2) daño perforante."
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2
  - name: Arco corto
    desc: "Ataque con arma a distancia: +4 a impactar, alcance 80/320 pies, un objetivo. Impacto: 5 (1d6 + 2) de daño [[perforante]]"
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2

```


