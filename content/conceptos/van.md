---
title: "VAN · Valor Actual Neto"
tipo_pagina: concepto
tema: 7
aliases: [VAN, Valor Actual Neto]
tags: [concepto, T07, problema]
---

**Tema:** [[T07]] · **Tipo:** problema (a veces teoría) · **Relacionado:** [[tir]], [[payback]], [[seleccion-de-inversiones]], [[inversion-concepto-y-tipos]]

> [!tip] El concepto **más preguntado** de toda la serie junto con el balance. Cae casi todos los años, normalmente en el mismo problema que la TIR o el pay-back.

## Qué es

Método **dinámico** de selección de inversiones: actualiza al momento inicial todos los flujos netos de caja que genera el proyecto, usando como tipo de descuento el **coste del capital** (k), y les resta el desembolso inicial. Mide la **riqueza que crea** el proyecto en euros de hoy.

$$VAN = -A + \frac{FC_1}{(1+k)} + \frac{FC_2}{(1+k)^2} + \dots + \frac{FC_n + VR}{(1+k)^n}$$

- **A**: desembolso inicial. **FC<sub>t</sub>**: flujo neto de caja del año t = cobros − pagos (no ingresos − gastos). **VR**: valor residual, se suma al flujo del último año. **k**: tipo de descuento.

**Criterio de decisión**
- VAN > 0 → el proyecto es **aceptable** (recupera la inversión y además gana más que k).
- VAN = 0 → indiferente (rinde exactamente k; k = TIR).
- VAN < 0 → **rechazar**.
- Entre varios proyectos: el de **mayor VAN**.

**Variables que influyen** (preguntado en [[E16-B2]]): desembolso inicial, flujos de caja, tipo de descuento, duración y valor residual. A mayor k, menor VAN.

## Cómo lo pregunta la PAU

1. **Calcular el VAN de dos proyectos y elegir** — el formato estrella: [[O08-A5]], [[E08-A6]], [[O10-A6]], [[E14-A6]], [[E20-B6]], [[O21-A5]], [[E23-A6]], [[E24-B6]], [[E25-P2]], [[O26-P2]].
2. **VAN + TIR del mismo proyecto** y comprobar que coinciden: [[E10-B6]], [[O12-B5]], [[E12-B6]], [[O14-B5]], [[O15-A6]], [[E15-A5]], [[E16-A5]], [[E19-A6]].
3. **Conflicto VAN vs. pay-back** (el pay-back elige uno y el VAN otro): [[O03-A5]], [[E18-B5]], [[E20-B6]], [[O17-A6]], [[E23-A6]] (empate en pay-back), [[O26-P2]].
4. **Flujos dados como cobros y pagos** (hay que restarlos antes): [[E13-B6]], [[O15-A6]], [[O23-A5]], [[E24-B6]], [[E25-P2]].
5. **Valor residual** al final: [[E22-B5]], [[O23-A5]], [[O26-P2]].
6. **Variantes poco habituales**: desembolso desconocido X ([[O13-A5]]); proyecto que ni siquiera recupera lo invertido ([[O06-A5]], [[E06-B6]], [[E05-B6]]); planteamiento a 5 años sin calcular ([[E07-B5]]); **tres años** con flujos en % del anterior ([[O26-P2]], primera vez en 2026).

## Errores típicos

- Usar ingresos − gastos (o el beneficio) en lugar de **cobros − pagos**.
- Olvidar restar el desembolso inicial o elevar mal los exponentes.
- Actualizar el valor residual con otro exponente o «olvidarlo».
- Concluir solo con el número: la PAU puntúa la **justificación** («VAN > 0, luego crea valor…»).
- Comparar proyectos con distinto desembolso sin comentarlo (en la PAU basta con elegir el de mayor VAN, pero se puede añadir el VAN por euro invertido).

## Preguntas

**34 preguntas** (más recientes primero):

- [[O26-P2]] (a, b) · RORRET: robótica o automatización; VAN, pay-back e inversión económica/financiera · *problema*
- [[E25-P2]] (a, b) · MUFFASA: IA o realidad aumentada; VAN, TIR y pay-back · *problema*
- [[E24-B6]] (a) · Sector dental: VAN y TIR de dos modelos de negocio · *problema*
- [[E23-A6]] (a) · Automoción: VAN y pay-back de dos proyectos · *problema*
- [[O23-A5]] (a) · VAN, TIR y pay-back con valor residual y cobros/pagos · *problema*
- [[E22-B5]] (a) · Maquinaria con valor residual: VAN, TIR y pay-back · *problema*
- [[O21-A5]] (a) · Ropa deportiva en EE. UU.: VAN y pay-back · *problema*
- [[E20-B6]] (a) · OHMIUM CARS: VAN y pay-back de dos alternativas · *problema*
- [[E19-A6]] (a, b) · BKES: patinetes eléctricos, VAN y TIR · *problema*
- [[E18-B5]] (b) · Dos proyectos: pay-back engañoso, VAN y TIR · *problema*
- [[O18-A6]] (b) · Reforma de restaurante: pay-back, VAN y TIR · *problema*
- [[O17-A6]] (a) · VAN, tipo de descuento límite y pay-back · *problema*
- [[E16-A5]] (a) · DADOS, S.A.: VAN y TIR de nueva maquinaria · *problema*
- [[E16-B2]] ("-") · Cuatro variables financieras que influyen en el VAN · *teoria*
- [[E15-A5]] (a, c) · AKMA, S.A.: VAN y TIR de un equipo a dos años · *problema*
- [[O15-A6]] (a, c) · Alquiler de instalaciones: VAN y TIR con cobros y pagos · *problema*
- [[E14-A6]] (a, b) · Calzado que diversifica: VAN de dos proyectos · *problema*
- [[O14-B5]] (a, b) · VAN y TIR de un activo a dos años · *problema*
- [[E13-B6]] (a) · Proyectos A y B: VAN y TIR con cobros y pagos · *problema*
- [[O13-A5]] (a, b) · VAN con desembolso desconocido X · *problema*
- [[E12-B6]] (a) · Inmovilizado con flujos constantes: VAN y TIR · *problema*
- [[O12-B5]] (a, b) · SUN: VAN y TIR de una inversión a dos años · *problema*
- [[E11-A6]] (b) · Pay-back y VAN de dos proyectos · *problema*
- [[E10-B6]] (a) · Proyecto JV: VAN y TIR · *problema*
- [[O10-A6]] (a, b, c) · VAN de dos inversiones a dos años · *problema*
- [[O09-B6]] (b, c) · Proyectos H y Z: pay-back, VAN y decisión · *problema*
- [[E08-A6]] (a, b) · Tarrasa o Mérida: VAN de dos localizaciones · *problema*
- [[O08-A5]] (b) · Dos proyectos: plazo de recuperación y VAN · *problema*
- [[E07-B5]] (c) · Pay-back a cinco años: ¿es lógica la elección? Expresión del VAN · *problema*
- [[E06-B6]] (a) · ARDILLA, S.A.: VAN y plazo de recuperación de un proyecto no rentable · *problema*
- [[O06-A5]] (a) · PIEDRASA: VAN y plazo de recuperación de un proyecto que no se recupera · *problema*
- [[E05-B6]] (a) · ARDONA, S.A.: VAN y plazo de recuperación de un proyecto no rentable · *problema*
- [[O04-A5]] ("-") · ¿Es rentable una inversión a dos años? (VAN) · *problema*
- [[O03-A5]] (b) · Proyectos H y Z: pay-back frente a VAN · *problema*
