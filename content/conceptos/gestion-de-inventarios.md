---
title: "Gestión de inventarios · Modelo de Wilson"
tipo_pagina: concepto
tema: 5
aliases: [Gestión de inventarios, Modelo de Wilson, Pedido óptimo, Costes de inventario]
tags: [concepto, T05, problema, fuera-de-temario]
---

**Tema:** [[T05]] · **Tipo:** problema y teoría · **Relacionado:** [[valoracion-de-existencias]]

> [!warning] **Fuera del temario LOMLOE actual.** Solo cae en 2003-2004. Se conserva por completitud histórica.

## Qué es

Costes asociados a las existencias:
- **De adquisición** (precio de compra).
- **De pedido o reaprovisionamiento** (tramitar cada pedido): el total anual **baja** si se piden lotes más grandes (menos pedidos).
- **De almacenamiento o mantenimiento** (espacio, seguros, coste financiero): **suben** con el tamaño del pedido (más stock medio).
- **De ruptura** (quedarse sin existencias).

**Modelo de Wilson** (lote económico): pedido que minimiza pedido + almacenamiento.

$$Q^* = \sqrt{\frac{2 \cdot D \cdot K}{g}}$$

(D = demanda anual; K = coste por pedido; g = coste de mantener una unidad un año.) Coste anual = $\frac{D}{Q^*}K + \left(\frac{Q^*}{2} + SS\right) g$ (+ coste de compra $D \cdot p$ si se pide el total). En el óptimo, coste de pedidos = coste de almacenamiento (sin stock de seguridad).

## Cómo lo pregunta la PAU

[[O03-B3]] (teoría de los costes), [[O04-B6]] (FUTURU, Q* = 30), [[E04-A6]] (Mar del Norte, con stock de seguridad).

## Preguntas

**3 preguntas** (más recientes primero):

- [[E04-A6]] ("-") · Mar del Norte: pedido óptimo (Wilson) y coste del inventario · *problema*
- [[O04-B6]] ("-") · FUTURU, S.L.: modelo de Wilson (pedido óptimo) · *problema*
- [[O03-B3]] ("-") · Costes de los inventarios según el tamaño del pedido · *teoria*
