---
title: Energía mecánica
subtitle: Trabajo, energía mecánica y potencia
subject: Semana 6
session:
  number: 6
  duration: TBD
  modality: Presencial
course: Física para Biotecnología
authors:
- name: Escuela de Física
keywords:
- Energía
- mecánica
learning_objectives:
- Calcular el trabajo realizado por una fuerza constante en un desplazamiento.
- Relacionar el trabajo con el cambio en la energía cinética.
- Explicar el concepto de energía potencial y sus diferentes formas.
- Aplicar el principio de conservación de la energía mecánica a sistemas físicos.
- Definir y calcular la potencia mecánica en procesos físicos.
activities: 'Molecu-olimpiadas: Calcular el trabajo y potencia de motores moleculares
  (Kinesina/Miosina) vs motores macroscópicos.'
evaluation:
- type: Sumativa
  description: 'Problemario: Cálculo de gasto energético en procesos biológicos.'
references:
- text: '[1] Wilson, J., Buffa, A., & Lou, B. (2007). Física (6.ª ed.). Pearson-Prentice
    Hall.'
  pages: Secciones 7.1 a 7.4, pág. 217-231
---

![](https://img.shields.io/badge/-Energía_mecánica-lightgrey) ![](https://img.shields.io/badge/-trabajo-lightgrey) ![](https://img.shields.io/badge/-energía_cinética-lightgrey) ![](https://img.shields.io/badge/-energía_potencial-lightgrey) ![](https://img.shields.io/badge/-conservación_de_la_energía-lightgrey) ![](https://img.shields.io/badge/-potencia-lightgrey)

:::{note} Objetivos
Al completar esta lección, serás capaz de:
1. Calcular el trabajo realizado por una fuerza constante en un desplazamiento.
2. Relacionar el trabajo con el cambio en la energía cinética.
3. Explicar el concepto de energía potencial y sus diferentes formas.
4. Aplicar el principio de conservación de la energía mecánica a sistemas físicos.
5. Definir y calcular la potencia mecánica en procesos físicos.
:::

## Introducción

En biología, todo proceso requiere energía: desde la división celular hasta la contracción muscular. La física nos proporciona el marco riguroso para cuantificar estos procesos. Veremos que la quema de calorías, el transporte activo y la síntesis de proteínas siguen las mismas leyes de conservación que una montaña rusa.

## Trabajo mecánico ($W$)

En física, realizamos trabajo solo cuando aplicamos una fuerza que causa un desplazamiento.

$$ W = F \cdot d \cdot \cos(\theta) $$

*   $F$: Magnitud de la fuerza.
*   $d$: Desplazamiento.
*   $\theta$: Ángulo entre la fuerza y el desplazamiento.

:::{important} Unidades
La unidad de trabajo y energía es el **Joule (J)**.
$$1 \text{ J} = 1 \text{ N}\cdot\text{m}.$$
En biología celular, a menudo usamos $k_B T$ (energía térmica) o unidades derivadas de calorías.
:::

## Energía cinética ($K$)

Es la energía asociada al movimiento.

$$ K = \frac{1}{2} m v^2 $$

*   **Aplicación**: Una ultracentrífuga imparte una enorme energía cinética a las partículas para separarlas. El rotor, al girar a altas velocidades, posee una gran cantidad de energía rotacional.

### Teorema Trabajo-Energía
El trabajo neto realizado sobre un objeto es igual al cambio en su energía cinética.
$$ W_{neto} = \Delta K = K_f - K_i $$

## Energía potencial ($U$)

Es energía almacenada debido a la posición o configuración.

1.  **Potencial gravitatoria**: $U_g = mgy$. (Importante en macroescala y circulación de fluidos).
2.  **Potencial elástica**: $U_e = \frac{1}{2} k x^2$. (Relevante para proteínas elásticas como la titina o la deformación celular).
3.  **Potencial química/eléctrica**: Aunque se ven en otros capítulos, siguen la misma lógica: energía almacenada en enlaces o gradientes.

## Conservación de la energía mecánica

En un sistema aislado donde solo actúan fuerzas conservativas (como la gravedad o fuerzas elásticas ideales):

$$ E_{total} = K + U = \text{constante} $$
$$ K_i + U_i = K_f + U_f $$

### Paisajes de energía (energy landscapes)
En el plegamiento de proteínas, visualizamos "embudos de energía". La proteína busca naturalmente el estado de menor energía potencial (conformación nativa). Aunque termodinámico, el principio es análogo a una bola rodando hacia el fondo de un valle.

## Potencia ($P$)

La rapidez con la que se realiza trabajo.

$$ P = \frac{W}{\Delta t} $$

*   **Unidad**: Watt (W).
*   **Ejemplo**: Un motor molecular como la miosina realiza trabajo muy rápido en escalas de tiempo pequeñas, generando una potencia específica alta.

---

## 🔬 Ejemplo aplicado: Motores moleculares

:::{note} Motores moleculares y trabajo
```{include} ../examples/05-motores-moleculares.md
```
:::

## ✍️ Ejercicios propuestos

```{include} ../exercises/06-calculo-protocolo.md
```



## 🧪 Actividades

Molecu-olimpiadas: Calcular el trabajo y potencia de motores moleculares (Kinesina/Miosina) vs motores macroscópicos.


👉 [Ir a la actividad](../activities/06-molecu-olimpiadas.md)

## 📝 Evaluación

- **Sumativa**: Problemario: Cálculo de gasto energético en procesos biológicos.


👉 [Ir a la evaluación](../evaluations/06-sumativa-problemario-energia.md)

## 📚 Referencias

- [1] Wilson, J., Buffa, A., & Lou, B. (2007). Física (6.ª ed.). Pearson-Prentice Hall., Secciones 7.1 a 7.4, pág. 217-231

