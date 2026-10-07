---
title: "TIR · Tasa Interna de Rentabilidad"
tipo_pagina: concepto
tema: 7
aliases: [TIR, Tasa Interna de Rentabilidad, Tasa interna de retorno]
tags: [concepto, T07, problema]
---

**Tema:** [[T07]] · **Tipo:** problema · **Relacionado:** [[van]], [[payback]], [[seleccion-de-inversiones]]

## Qué es

Tipo de descuento que hace **VAN = 0**. Es la **rentabilidad anual** que obtiene el proyecto sobre el capital invertido.

$$0 = -A + \frac{FC_1}{(1+r)} + \frac{FC_2}{(1+r)^2}$$

**Criterio:** se acepta si **TIR > k** (coste del capital); entre varios proyectos, el de mayor TIR (con matices).

## Cómo se calcula en la PAU (dos años)

Cambio de variable $x = 1 + r$ y multiplicar por $x^2$:

$$A x^2 - FC_1 x - FC_2 = 0 \quad\Rightarrow\quad x = \frac{FC_1 + \sqrt{FC_1^2 + 4 A \cdot FC_2}}{2A}, \qquad r = x - 1$$

(Se toma la raíz positiva.) Truco: dividir antes por un factor común (miles) para manejar números pequeños.

Casos especiales:
- **Un único flujo** al final: $(1+r)^n = FC_n / A$ → [[O07-A6]] (barco), [[E13-B6]] (proyecto B).
- **Flujos proporcionales**: dos proyectos «uno el doble del otro» tienen la **misma TIR** → [[E09-B6]].
- Si la PAU **da la TIR** y pide interpretarla: [[E24-B6]].
- Si pide «a partir de qué tipo de descuento es aceptable»: es la TIR ([[O17-A6]]).

## Cómo lo pregunta la PAU

- Casi siempre junto al VAN del mismo proyecto: [[E10-B6]], [[O12-B5]], [[E12-B6]], [[O14-B5]], [[O15-A6]], [[E15-A5]], [[E16-A5]], [[E19-A6]], [[O23-A5]], [[E22-B5]], [[E25-P2]].
- Comparar dos proyectos solo por TIR: [[O11-A6]], [[E13-B6]], [[E04-B5]], [[E09-B6]].
- Definición teórica: [[O15-A2]].

## Errores típicos

- Plantear mal la ecuación (signos) o quedarse con la raíz negativa.
- Dar la TIR sin compararla con k.
- Creer que mayor TIR implica siempre mayor VAN: falla cuando los proyectos tienen **distinto tamaño** ([[E09-B6]], [[E24-B6]]).

## Preguntas

**21 preguntas** (más recientes primero):

- [[E25-P2]] (c1) · MUFFASA: IA o realidad aumentada; VAN, TIR y pay-back · *problema*
- [[E24-B6]] (b, c) · Sector dental: VAN y TIR de dos modelos de negocio · *problema*
- [[O23-A5]] (b) · VAN, TIR y pay-back con valor residual y cobros/pagos · *problema*
- [[E22-B5]] (b) · Maquinaria con valor residual: VAN, TIR y pay-back · *problema*
- [[E19-A6]] (c) · BKES: patinetes eléctricos, VAN y TIR · *problema*
- [[E18-B5]] (c) · Dos proyectos: pay-back engañoso, VAN y TIR · *problema*
- [[O18-A6]] (c) · Reforma de restaurante: pay-back, VAN y TIR · *problema*
- [[O17-A6]] (b) · VAN, tipo de descuento límite y pay-back · *problema*
- [[E16-A5]] (b) · DADOS, S.A.: VAN y TIR de nueva maquinaria · *problema*
- [[E15-A5]] (b) · AKMA, S.A.: VAN y TIR de un equipo a dos años · *problema*
- [[O15-A2]] (ii) · Inversión económica y TIR: conceptos · *teoria*
- [[O15-A6]] (b) · Alquiler de instalaciones: VAN y TIR con cobros y pagos · *problema*
- [[O14-B5]] (c) · VAN y TIR de un activo a dos años · *problema*
- [[E13-B6]] (b) · Proyectos A y B: VAN y TIR con cobros y pagos · *problema*
- [[E12-B6]] (b) · Inmovilizado con flujos constantes: VAN y TIR · *problema*
- [[O12-B5]] (c, d) · SUN: VAN y TIR de una inversión a dos años · *problema*
- [[O11-A6]] (b) · Pay-back y TIR de dos proyectos (año de 360 días) · *problema*
- [[E10-B6]] (b) · Proyecto JV: VAN y TIR · *problema*
- [[E09-B6]] (a, b) · TIR de dos proyectos proporcionales · *problema*
- [[O07-A6]] ("-") · Barco o fábrica de caramelos: rentabilidad (TIR) · *problema*
- [[E04-B5]] (a) · FIMERSA: TIR, pay-back e inconvenientes del pay-back · *problema*
