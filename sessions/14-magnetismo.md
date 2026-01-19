---
title: Magnetismo
subtitle: Campos magnéticos y biomagnetismo
subject: Semana 14
session:
  number: 14
  duration: TBD
  modality: Presencial
course: Física para Biotecnología
authors:
- name: Escuela de Física
keywords:
- Magnetismo
learning_objectives:
- Describir la fuerza magnética sobre partículas cargadas y corrientes.
- Explicar el origen del campo magnético producido por corrientes.
- Discutir ejemplos de magnetismo en sistemas biológicos.
activities: Principios físicos detrás de la Resonancia Magnética Nuclear (RMN).
evaluation:
- type: Formativa
  description: 'Mapa Mental Colaborativo: Aplicaciones del magnetismo en biotecnología
    y medicina.'
references:
- text: '[3] Ortuño, M. (2019). Física para las ciencias de la vida. Editorial Tébar
    Flores. https://elibro.net/es/lc/itcr/titulos/124788'
  pages: Secciones 15.1 a 15.8, pág. 267-280
---

![](https://img.shields.io/badge/-Magnetismo-lightgrey) ![](https://img.shields.io/badge/-Fuerza_magnética_sobre_una_partícula-lightgrey) ![](https://img.shields.io/badge/-Fuerza_magnética_sobre_una_corriente.-lightgrey) ![](https://img.shields.io/badge/-Campo_producido_por_una_corriente-lightgrey) ![](https://img.shields.io/badge/-Magnetograma-lightgrey) ![](https://img.shields.io/badge/-Magnetismo_en_los_seres_vivos-lightgrey)

:::{note} Objetivos
Al completar esta lección, serás capaz de:
1. Describir la fuerza magnética sobre partículas cargadas y corrientes.
2. Explicar el origen del campo magnético producido por corrientes.
3. Discutir ejemplos de magnetismo en sistemas biológicos.
:::

## Introducción

Aunque los organismos vivos no son "imanes" en el sentido tradicional, el magnetismo es crucial en la biotecnología moderna. Desde las bacterias que se orientan con el campo magnético terrestre hasta la poderosa Resonancia Magnética Nuclear para determinar estructuras de proteínas, el campo $\vec{B}$ es una herramienta de análisis indispensable.

## Campo magnético ($\vec{B}$)

Generado por cargas en movimiento (corrientes).
*   Unidad SI: **Tesla (T)**.
*   Referencia:
    *   Tierra: $\approx 50 \mu T$ (microteslas).
    *   Imán de refri: $\approx 5 mT$.
    *   Equipo MRI clínico: $1.5 - 3 T$.

## Fuerza magnética (Lorentz)

Una carga $q$ que se mueve a velocidad $v$ en un campo $B$ siente una fuerza perpendicular a ambos.

$$ \vec{F} = q (\vec{v} \times \vec{B}) $$
$$ F = |q| v B \sin(\theta) $$

*   Si $v$ es paralela a $B$, la fuerza es cero.
*   Esta fuerza encorva la trayectoria de las partículas cargadas.

## Espectrometría de masas

Herramienta "Gold Standard" en proteómica para identificar proteínas.
1.  Se ioniza la molécula ($q$).
2.  Se acelera ($v$).
3.  Se hace pasar por un campo magnético ($B$).
4.  La molécula se curva en un radio $r$.

$$ r = \frac{mv}{qB} $$

Midiendo el radio de curvatura, determinamos la relación masa/carga ($m/q$), la huella dactilar de la molécula.

:::{note} Cálculo de radio en Espectrometría
```{include} ../examples/14-radio-espectrometro.md
```
:::

## 🔬 Biomagnetismo

### Magnetotaxis
Ciertas bacterias (*Magnetospirillum*) sintetizan cristales de magnetita ($Fe_3O_4$) dentro de sus células. Estos actúan como brújulas microscópicas, permitiendo a la bacteria orientarse con el campo geomagnético para encontrar zonas óptimas de oxígeno en sedimentos.

### Seguridad en MRI
Los campos intensos de un MRI no dañan los tejidos biológicos (no son ionizantes), pero pueden convertir cualquier objeto ferromagnético (tijeras, implantes viejos) en proyectiles letales debido a la atracción magnética sobre el material.

## ✍️ Ejercicios propuestos

```{include} ../exercises/14-selector-velocidad.md
```



## 🧪 Actividades

Principios físicos detrás de la Resonancia Magnética Nuclear (RMN).


👉 [Ir a la actividad](../activities/14-fisica-rmn.md)

## 📝 Evaluación

- **Formativa**: Mapa Mental Colaborativo: Aplicaciones del magnetismo en biotecnología y medicina.


👉 [Ir a la evaluación](../evaluations/14-formativa-mapa-magnetismo.md)

## 📚 Referencias

- [3] Ortuño, M. (2019). Física para las ciencias de la vida. Editorial Tébar Flores. https://elibro.net/es/lc/itcr/titulos/124788, Secciones 15.1 a 15.8, pág. 267-280

