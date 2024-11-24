---
title: <% tp.file.title %>
creation date: <% tp.file.creation_date() %>
tags:
  - state/seedling
  - type/note
aliases:
---


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
