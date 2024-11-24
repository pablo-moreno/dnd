---
title: Imbuir Objeto
creation date: 2024-03-05 22:48
tags:
  - state/seedling
  - type/note
aliases: 
Nivel de Clase: 2
Mejora de Habilidad:
---
Has obtenido la capacidad inyectar ciertas infusiones mágicas en objetos mundanos para convertirlos en objetos mágicos.

**Infusiones Conocidas**
Cuando obtengas este rasgo, elige cuatro infusiones de artífice que aprender de la sección "Infusiones de artífice", situada al final de la descripción de la clase.
Podrás elegir más infusiones cuando llegues a determinados niveles en esta clase, tal y como se muestra en la columna "Infusiones conocidas" de la tabla del artífice.
Además, cada vez que subas un nivel en esta clase, podrás sustituir una de las infusiones de artífice que ya conoces por otra nueva.

**Imbuir un Objeto**
Tras finalizar un descanso largo, puedes tocar un objeto no mágico e imbuirlo de una de tus infusiones de artífice para convertirlo en un objeto mágico. Las infusiones solo funcionan en algunos tipos de objetos, tal y como se especifica en la descripción de cada infusión. Si el objeto requiere sintonización, puedes sintonizarte con él en el momento de imbuirlo. 
Si decides sintonizarte con el objeto más adelante, deberás hacerlo con el proceso habitual de sintonización.

Tu infusión permanecerá en un objeto de forma indefinida, pero, si mueres, la infusión se desvanece tras una cantidad de días igual a tu modificador por Inteligencia (mínimo de 1 día). La infusión también se desvanecerá si sustituyes el conocimiento de dicha infusión.

Puedes imbuir más de un objeto no mágico tras un descanso largo. E l número máximo de objetos aparece en la columna "Objetos imbuidos" de la tabla del artífice.
Tienes que tocar cada uno de los objetos y las infusiones solo pueden estar en un objeto cada vez. Además, ningún objeto admite más de una infusión a la vez. Si intentas  superar tu máxima cantidad de infusiones, la más antigua se acaba y luego se aplica la nueva.

Si una infusión acaba en un objeto que contenga otras cosas, como una bolsa de contención, su contenido aparecerá en su espacio y alrededor de este sin sufrir daños.

Infusiones de Artífice
Las infusiones de artífice son procesos extraordinarios que convierten rápidamente un objeto no mágico en un objeto mágico. La descripción de cada una de las siguientes infusiones indica el tipo de objeto que puede recibirla, además de si el objeto mágico resultante requiere sintonización.

Para algunas infusiones, es necesario un nivel de artífice mínimo. No podrás aprender a preparar dichas infusiones hasta que no hayas alcanzado ese nivel.
A menos que su descripción indique lo contrario, solo puedes aprender cada infusión una vez


*Lista de Infusiones*

```dataview

table Nivel as "Nivel Requerido", Objeto as "Objeto Necesario"
from #art/inf 
sort Nivel

```