---
name: Bandido
tags:
  - type/enemy
alignment: Cualquiera no legal
race: "[[Humanoide]]"
size: "[[Mediano]]"
aliases:
  - Pirata
  - piratas
  - bandido
  - bandidos
---
> Los **bandidos** se unen en bandas que, en ocasiones, están dirigidas por matones, veteranos o lanzadores de conjuros. No todos los bandidos son malvados, pues la tiranía, sequías, enfermedades o hambrunas pueden obligar a gente honesta a llevar una vida de bandidaje. 
> 
> Los **piratas** son los bandidos del mar. Pueden ser tanto filibusteros a los que solo les importan las riquezas y el asesinato como corsarios con una sanción de la corona para atacar y saquear a los navíos de las naciones enemigas.
## Características
| Característica | Nivel | Bonificador | Lanzar dado |
| ---- | ---- | ---- | ---- |
| [[Fuerza]] | 11 | 0 | `dice: 1d20 + 0` |
| [[Destreza]] | 12 | 1 | `dice: 1d20 + 1` |
| [[Constitución]] | 12 | 1 | `dice: 1d20 + 1` |
| [[Inteligencia]] | 10 | 0 | `dice: 1d20 + 0` |
| [[Sabiduría]] | 10 | 0 | `dice: 1d20 + 0` |
| [[Carisma]] | 10 | 0 | `dice: 1d20 + 0` |

[[Clase de Armadura]]: 12 ([[Armadura de cuero]])
[[Puntos de golpe]]: 11 (`dice: 2d8 + 2`)
[[Velocidad]]: 30
## Sentidos
- [[Percepción pasiva]] 10

## Idiomas
- [[Idioma común]]

## Acciones
- **Cimitarra**. Ataque con arma cuerpo a cuerpo: +3 a impactar, alcance 5 pies, un objetivo. Impacto: 4 (`dice: 1d6 + 1`) de [[daño cortante]].
- **Ballesta ligera**. Ataque con arma a distancia: +3 a impactar, alcance 80/320 pies, un objetivo. Impacto: 5 (`dice: 1d8 + 1`) de [[daño perforante]].
## Desafío
1/8 - 25 [[PX]]


```statblock
name: Bandido
size: Mediano
type: Humanoide
subtype: Cualquier raza
alignment: Cualquiera no legal
ac: 12
hp: 11
hit_dice: 2d8 + 2
speed: 30 ft.
stats:
  - 11
  - 12
  - 12
  - 10
  - 10
  - 10
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Perception 10
languages: any one language (usually Common)
cr: 1/8
bestiary: true
dice: true
actions:
  - name: Cimitarra
    desc: "Ataque con arma cuerpo a cuerpo: +3 al impactar, alcance 5 pies, objetivo. Impacto: 4 (1d6 + 1) de daño cortante."
    attack_bonus: 3
    damage_dice: 1d6
    damage_bonus: 1
  - name: Ballesta ligera
    desc: "Ataque con arma a distancia: +3 a impactar, rango de 80  a 320 pies, un objetivo. Impacto: 5 (1d8 + 1) de daño perforante."
    attack_bonus: 3
    damage_dice: 1d8
    damage_bonus: 1

```

