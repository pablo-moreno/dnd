---
name: Estirge
tags:
  - type/enemy
alignment: 
race: Bestia
size: "[[Diminuto]]"
aliases:
  - estirge
  - estirges
hit_points: 2
hit_dice: "`dice: 1d4`"
---
> Estas horribles criaturas voladoras parecen un cruce entre un murciélago enorme y un mosquito gigante. Sus patas terminan en pinzas afiladas y su larga probóscide azota el aire en busca de su próxima comida. Las estirges se alimentan de la sangre de seres vivos, pegándose a ellos y  drenándolos poco a poco. Aunque no son un peligro cuando son pocos, una bandada de estirges puede representar una amenaza formidable, ya que estas criaturas tienen la oportunidad de volver a adherirse a sus debilitadas víctimas en cuanto estas consiguen quitárselas de encima. 

**Chupar sangre**. Las estirges atacan posándose sobre su víctima, encontrando un punto vulnerable y clavando su probóscide en la carne mientras sujetan al objetivo mediante sus pinzas. Una vez se han saciado, se separan y alejan volando, para digerir su comida.
## Características
| Característica                                                           | Nivel | Bonificador | Lanzar dado      |
| ------------------------------------------------------------------------ | ----- | ----------- | ---------------- |
| [[Dungeons and Dragons/Reglas/Estadisticas/Estadisticas/Fuerza\|Fuerza]] | 4     | -3          | `dice: 1d20 - 3` |
| [[Destreza]]                                                             | 16    | 3           | `dice: 1d20 + 3` |
| [[Constitución]]                                                         | 11    | 0           | `dice: 1d20 + 0` |
| [[Inteligencia]]                                                         | 2     | -4          | `dice: 1d20 - 4` |
| [[Sabiduría]]                                                            | 8     | -1          | `dice: 1d20 - 1` |
| [[Carisma]]                                                              | 6     | -2          | `dice: 1d20 -2`  |

[[Clase de Armadura]]: 14
[[Puntos de golpe]]: `= this.hit_points` (`=this.hit_dice`)
[[Velocidad]]: 10
[[Volar]]: 40


## Sentidos
- Visión en la oscuridad 60 pies
- [[Percepción pasiva]] 9

## Acciones
**Chupar sangre**. Ataque con arma cuerpo a cuerpo: +5 a impactar, alcance 5 pies, un objetivo. Impacto: 5 (`dice: 1d4 + 3`) de daño [[perforante]], y la estirge se engancha al objetivo. Esta no atacará mientras esté enganchada. En lugar de eso, al inicio de cada uno de los turnos de la estirge, el objetivo perderá 5 (`dice: 1d4 + 3`) puntos de golpe debido a la pérdida de sangre. La estirge puede desengancharse utilizando 5 pies de su movimiento. Lo hará tras chupar 10 puntos de golpe en forma de sangre de su objetivo o cuando este muera. Cualquier criatura, incluyendo el objetivo, puede usar una acción para desenganchar a la estirge.
## Desafío

1/8 - 25 [[PX]]
