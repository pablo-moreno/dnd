---
name: Sin título
tags:
  - type/enemy
alignment: 
race: Bestia
size: Pequeño
aliases:
  - ciempiés gigante
  - ciempiés gigantes
hit_points: 4
hit_dice: "`dice: 1d6 + 1`"
---
## Características
| Característica                                                           | Nivel | Bonificador | Lanzar dado      |
| ------------------------------------------------------------------------ | ----- | ----------- | ---------------- |
| [[Dungeons and Dragons/Reglas/Estadisticas/Estadisticas/Fuerza\|Fuerza]] | 5     | -3          | `dice: 1d20 -3`  |
| [[Destreza]]                                                             | 14    | 2           | `dice: 1d20 + 2` |
| [[Constitución]]                                                         | 12    | 1           | `dice: 1d20 + 1` |
| [[Inteligencia]]                                                         | 1     | -5          | `dice: 1d20 -5`  |
| [[Sabiduría]]                                                            | 7     | -2          | `dice: 1d20 - 2` |
| [[Carisma]]                                                              | 3     | -4          | `dice: 1d20 - 4` |

[[Clase de Armadura]]: 13
[[Puntos de golpe]]: `= this.hit_points` (`=this.hit_dice`)
[[Velocidad]]: 30
Trepar: 30 pies


## Sentidos
- Visión ciega 30 pies
- Percepción pasiva 8
## Acciones
**Mordisco**. Ataque con arma cuerpo a cuerpo: +4 a impactar, alcance 5 pies, una criatura. Impacto: 4 (`1d4 + 2`) de daño [[perforante]], y el objetivo debe superar una tirada de salvación de [[Constitución]] CD 11 o sufrirá 10 (`dice: 3d6`) de daño de veneno. Si el veneno reduce al objetivo a 0 puntos de golpe, este estará estable pero envenenado durante 1 hora, incluso tras recuperar puntos de golpe. Además, mientras esté envenenado (por este veneno) también estará paralizado.
## Desafío
1/4 - 50 [[PX]]
