---
title: "Valoración de existencias (FIFO y PMP)"
tipo_pagina: concepto
tema: 5
aliases: [Valoración de existencias, FIFO, PMP, Precio medio ponderado, LIFO, Ficha de almacén]
tags: [concepto, T05, problema]
---

**Tema:** [[T05]] · **Tipo:** problema · **Relacionado:** [[gestion-de-inventarios]], [[patrimonio-y-masas-patrimoniales]], [[balance-de-situacion]]

## Qué es

Cuando hay compras a distintos precios, hay que decidir a qué precio salen las unidades vendidas y, por tanto, a cuánto se valoran las **existencias finales**.

- **FIFO** (*first in, first out*): salen primero las más **antiguas**; en el almacén quedan las **últimas** compradas.
- **PMP** (precio medio ponderado): todas las unidades se valoran al promedio ponderado:
  $$PMP = \frac{\sum \text{unidades} \times \text{precio}}{\sum \text{unidades}}$$
  Si hay ventas **intercaladas** entre compras, el PMP se **recalcula tras cada entrada** ([[O11-A5]]).
- **LIFO** (último en entrar, primero en salir): **no admitido** por el PGC desde 2008; solo cae en 2004 y 2007.

**Con inflación** (precios crecientes), FIFO da el **mayor** valor de existencias finales ([[O04-A4]], [[O07-B4]]); si la última compra es la más barata, ocurre al revés ([[O19-B6]]).

## Procedimiento PAU

1. Unidades finales = existencias iniciales + compras − ventas.
2. FIFO: «consumir» los lotes más antiguos con las ventas; valorar lo que queda.
3. PMP: calcular el precio medio (ojo con el orden cronológico) y multiplicar por las unidades finales.
4. El **precio de venta no interviene** en la valoración (es un distractor).

## Cómo lo pregunta la PAU

- Un producto, FIFO y PMP: [[E13-A6]], [[O17-B6]], [[E18-A5]], [[O19-B6]], [[O21-B5]], [[E21-A5]], [[O22-B5]], [[E23-B5]].
- **Dos productos** a la vez: [[O20-A6]], [[O24-B6]], [[E24-A6]].
- Venta intercalada: [[O11-A5]].
- **Trampa** de unidades: se venden todas las de un modelo ([[O24-B6]]).

> [!note] Ha caído casi todos los años entre 2017 y 2024; **no ha aparecido en el modelo de 4 preguntas** (2025-2026).

## Errores típicos

- Usar un PMP global cuando hay una venta antes de la última compra.
- Redondear el PMP a dos decimales antes de multiplicar (las oficiales lo hacen: [[O21-B5]], [[E24-A6]]).
- Valorar con el precio de venta.

## Preguntas

**14 preguntas** (más recientes primero):

- [[E24-A6]] (a, b) · FRESÓPOLIS: fresas y garbanzos por PMP y FIFO · *problema*
- [[O24-B6]] (a, b) · DJ MUSIC: mesas de mezclas por FIFO y PMP · *problema*
- [[E23-B5]] (a, b, c) · 2-WHEELS: patinetes por FIFO y PMP · *problema*
- [[O22-B5]] (a, b, c) · BIO-LIVE: aceite de oliva por FIFO y PMP · *problema*
- [[E21-A5]] (a, b) · RECORD: videocámaras por FIFO y PMP · *problema*
- [[O21-B5]] (a, b) · Envases de vidrio: FIFO y PMP · *problema*
- [[O20-A6]] (a, b) · YZM: vino tinto por FIFO y vino blanco por PMP · *problema*
- [[O19-B6]] (a, b) · Estuches escolares: PMP y FIFO con compra barata en agosto · *problema*
- [[E18-A5]] (a, b) · Existencias de otoño: FIFO y PMP con dos ventas · *problema*
- [[O17-B6]] (a, b, c) · LEDLUX: bombillas por FIFO y PMP · *problema*
- [[E13-A6]] (a, b) · PERFILES: existencias de estuches por FIFO y PMP · *problema*
- [[O11-A5]] (a, b) · GADI: existencias de bicicletas por PMP y FIFO · *problema*
- [[O07-B4]] ("-") · PMP, FIFO y LIFO con inflación · *teoria*
- [[O04-A4]] ("-") · PMP, FIFO y LIFO con inflación · *teoria*
