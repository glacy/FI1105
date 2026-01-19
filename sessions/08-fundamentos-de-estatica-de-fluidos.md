---
title: Fundamentos de estática de fluidos
subtitle: Densidad, presión y principio de Arquímedes
subject: Semana 8
session:
  number: 8
  duration: TBD
  modality: Presencial
course: Física para Biotecnología
authors:
- name: Escuela de Física
keywords:
- Fundamentos
- estática
- fluidos
learning_objectives:
- Definir los conceptos de esfuerzo y esfuerzo de deformación
- Explicar la relación profundidad y presión
- Describir el principio de Pascal y su uso en aplicaciones prácticas
- Relacionar la fuerza de flotabilidad con el principio de Arquímedes
- Describir el origen de la tensión superficial
activities: 'Reto del densímetro casero: Construir un densímetro para medir concentración
  de azúcar en soluciones de fermentación.'
evaluation:
- type: Formativa
  description: 'Demostración práctica: Medición correcta de densidades y tensión superficial
    (checklist).'
references:
- text: '[1] Wilson, J., Buffa, A., & Lou, B. (2007). Física (6.ª ed.). Pearson-Prentice
    Hall.'
  pages: Secciones 9.1 a 9.3 y 9.5, pág. 297-319; 324-328
- text: '[2] Jou Mirabent, D. (2009). Física para ciencias de la vida (2.ª ed.). McGraw-Hill
    España. https://elibro.net/es/lc/itcr/titulos/50165'
  pages: Secciones 3.1 a 3.4 p 89-97
---

![](https://img.shields.io/badge/-Fundamentos_de_estática_de_fluidos-lightgrey) ![](https://img.shields.io/badge/-Densidad-lightgrey) ![](https://img.shields.io/badge/-Presión_y_profundidad-lightgrey) ![](https://img.shields.io/badge/-Principio_de_Arquímedes_(flotación)-lightgrey) ![](https://img.shields.io/badge/-Principio_de_Pascal-lightgrey) ![](https://img.shields.io/badge/-Tensión_superficial_y_capilaridad-lightgrey)

:::{note} Objetivos
Al completar esta lección, serás capaz de:
1. Definir los conceptos de esfuerzo y esfuerzo de deformación
2. Explicar la relación profundidad y presión
3. Describir el principio de Pascal y su uso en aplicaciones prácticas
4. Relacionar la fuerza de flotabilidad con el principio de Arquímedes
5. Describir el origen de la tensión superficial
:::

## Introducción

La vida es fundamentalmente acuática. El citoplasma, la sangre, el medio de cultivo de un biorreactor... todos son fluidos. Entender cómo se comportan los líquidos en reposo (estática) es el primer paso para dominar bioprocesos, desde calcular la presión en el fondo de un tanque de fermentación hasta diseñar separaciones por densidad.

## Densidad ($\rho$)

Masa por unidad de volumen.
$$ \rho = \frac{m}{V} $$
*   Agua: $\approx 1000 \text{ kg/m}^3$ o $1 \text{ g/cm}^3$.
*   **Importancia**: La separación celular por centrifugación en gradiente (Ficoll, Sacarosa) se basa puramente en diferencias de densidad ($\rho_\text{celula}$ vs $\rho_\text{medio}$).

## Presión ($p$)

Fuerza ejercida perpendicularmente sobre una superficie.
$$ p = \frac{F}{A} $$
*   Unidad SI: **Pascal (Pa)** ($1 \text{ Pa} = 1 \text{ N/m}^2$).
*   Otras: atm, mmHg, psi.

### Presión hidrostática
La presión aumenta con la profundidad debido al peso del fluido sobre ella.
$$ p = p_0 + \rho g h $$
*   $p_0$: Presión superficie (atm).
*   $h$: Profundidad.

En un tanque de fermentación de 10 metros de altura, la presión en el fondo es significativamente mayor que en la superficie ($P_\text{fondo} \approx 2 \text{ atm}$). Esto afecta la solubilidad de gases ($O_2, CO_2$) y debe considerarse para el metabolismo celular.

:::{note} Presión en fondo de biorreactor
```{include} ../examples/08-presion-biorreactor.md
```
:::

## Principio de Pascal

*Un cambio en la presión aplicada a un fluido incompresible encerrado se transmite sin disminución a cada punto del fluido y a las paredes del recipiente.*
*   Aplicación: Sistemas hidráulicos y regulación de presión osmótica (conceptualmente similar en transmisión de fuerzas en vacuolas).

## Principio de Arquímedes y flotación

*Todo cuerpo sumergido parcial o totalmente en un fluido experimenta una fuerza de empuje hacia arriba igual al peso del fluido desplazado.*

$$ F_\text{empuje} = \rho_\text{fluido} \cdot V_\text{desplazado} \cdot g $$

### Condición de Flotabilidad
*   Si $\rho_\text{objeto} < \rho_\text{fluido}$: El objeto flota.
*   Si $\rho_\text{objeto} > \rho_\text{fluido}$: El objeto se hunde.
*   Si $\rho_\text{objeto} == \rho_\text{fluido}$: flotabilidad neutra (se queda donde está).

### 🔬 Aplicación: Centrifugación Isopícnica
En este método, se crea un gradiente de densidad en el tubo. Las partículas (ADN, orgánulos) viajan hasta encontrar la zona donde su densidad coincide exactamente con la del medio ($\rho_\text{particula} = \rho_\text{medio}$). Allí, la fuerza de empuje cancela la fuerza centrífuga y la partícula se detiene ("flota" en equilibrio).

## Tensión superficial ($\gamma$)

Las moléculas en la superficie de un líquido sienten una atracción neta hacia el interior, creando una "película" tensa.
*   Causa: Fuerzas de cohesión (puentes de hidrógeno en agua).
*   **Biotech**:
    *   Formación de gotas en microfluídica.
    *   Surfactantes pulmonares y detergentes para lisis celular (rompen la tensión superficial y las membranas).
    *   Capilaridad: Ascenso de líquidos en tubos finos (o en el xilema de plantas).

## ✍️ Ejercicios propuestos

```{include} ../exercises/08-biorreactor-flotacion.md
```



## 🧪 Actividades

Reto del densímetro casero: Construir un densímetro para medir concentración de azúcar en soluciones de fermentación.


👉 [Ir a la actividad](../activities/08-densimetro-casero.md)

## 📝 Evaluación

- **Formativa**: Demostración práctica: Medición correcta de densidades y tensión superficial (checklist).


👉 [Ir a la evaluación](../evaluations/08-formativa-densidad.md)

## 📚 Referencias

- [1] Wilson, J., Buffa, A., & Lou, B. (2007). Física (6.ª ed.). Pearson-Prentice Hall., Secciones 9.1 a 9.3 y 9.5, pág. 297-319; 324-328
- [2] Jou Mirabent, D. (2009). Física para ciencias de la vida (2.ª ed.). McGraw-Hill España. https://elibro.net/es/lc/itcr/titulos/50165, Secciones 3.1 a 3.4 p 89-97

