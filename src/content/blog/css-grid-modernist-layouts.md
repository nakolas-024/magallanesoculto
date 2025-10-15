---
title: "(NOTICIA DE EJEMPLO) El Diseño de la Corrupción: Cómo se 'Construyen' los Sobreprecios en Obras Públicas"
date: "2025-10-08"
description: "Un análisis técnico de cómo las licitaciones de obras públicas en Magallanes se diseñan para favorecer a ciertos contratistas a través de especificaciones ambiguas y sobreprecios ocultos."
excerpt: "No es solo un sobreprecio, es un diseño. Magallanes Oculto accedió a las bases técnicas de tres proyectos recientes y encontró un patrón sistemático para inflar costos y limitar la competencia, todo a la vista de los fiscalizadores."
categories: ["Corrupción", "Infraestructura", "Investigación"]
tags: ["Obras Públicas", "Licitaciones", "Sobreprecios", "Fraude al Fisco"]
---

# El Diseño de la Corrupción: Cómo se 'Construyen' los Sobreprecios en Obras Públicas

Los arquitectos modernistas trabajaban con cálculos matemáticos precisos para lograr la funcionalidad. Hoy, en la administración pública de Magallanes, esa misma precisión se utiliza para diseñar licitaciones, no para servir al público, sino para asegurar que el dinero termine en los bolsillos correctos.

## La Licitación como Diseño Filosófico

Antes de analizar una sola línea de presupuesto, debemos entender que una licitación es más que un documento: es una declaración de intenciones. En teoría, representa:

- **Orden sobre el caos** en la asignación de fondos.
- **Pensamiento sistemático** para el bien común.
- **Competencia democrática** entre empresas.

En la práctica, se ha convertido en una herramienta para implementar principios muy distintos.

## Montando un Sistema de Sobreprecios

Empecemos con una estructura básica de costos extraídos de la licitación para la "Plaza Cívica de Puerto Williams":

// Extracto del Presupuesto Oficial - Partida "Obras Exteriores"

:root {
--costo-real-banca: 80000;         /* 80,000 CLP /
--costo-licitado-banca: 450000;     / 450,000 CLP */

--costo-real-luminaria: 120000;     /* 120,000 CLP /
--costo-licitado-luminaria: 780000; / 780,000 CLP */

--costo-real-m2-baldosa: 15000;     /* 15,000 CLP /
--costo-licitado-m2-baldosa: 55000; / 55,000 CLP */
}


Este sistema asegura que cada ítem del presupuesto esté inflado de manera intencional y sistemática. No hay errores, hay un diseño.

## Un Diseño "A Medida"

Analicemos cómo se estructura una adjudicación para que solo un proponente pueda ganar de manera "legítima":

// Extracto de las Bases Técnicas - Requisitos del Proponente

.empresa-ganadora {
display: grid;
grid-template-columns: repeat(12, 1fr);

/* Requisito 1: Experiencia Específica /
/ Debe acreditar experiencia en "construcción de piletas ornamentales
sobre 2,500 metros de altura", un requisito irrelevante para
una plaza a nivel del mar. */
grid-column: 1 / -1;

/* Requisito 2: Equipo Mínimo Inusual /
/ Se exige maquinaria específica (ej. "Hormigonera autopropulsada
modelo X-2000"), que casualmente solo posee un proveedor local. */
grid-column: 4 / 10;

/* Requisito 3: Capital Acreditado Desproporcionado /
/ Se pide un capital comprobado que excede en 5 veces el valor
del contrato, eliminando a todas las Pymes competentes. */
grid-column: 10 / -1;
}


## El Equilibrio Asimétrico: La Comisión Evaluadora

Una comisión evaluadora imparcial debería ser simétrica en su juicio. Lo que encontramos es un equilibrio diseñado para inclinarse siempre hacia un lado.

// Composición de la Comisión Evaluadora "Plaza Cívica"

.comision-evaluadora {
display: grid;
grid-template-columns: 2fr 1fr 1fr 3fr; /* Poder de voto desigual */
}

/* El miembro con más peso en la decisión final (2fr) es un
"asesor externo" contratado por trato directo por la misma
unidad que licita el proyecto. */
.evaluador-clave {
grid-column: 1 / 3;
}

/* Los otros dos miembros (1fr, 1fr) son funcionarios de menor
rango con poca experiencia en el área técnica a evaluar. */
.evaluador-secundario-1 { grid-column: 3; }
.evaluador-secundario-2 { grid-column: 4; }


## El Modernismo Responsivo a la Corrupción

Los diseñadores de estos esquemas se adaptan a la fiscalización de Contraloría, pero sus principios se mantienen:

```css
@media (min-width: 768px) {
  /* Si Contraloría observa un requisito, se "flexibiliza" en el papel,
     pero se mantiene la barrera en los criterios de evaluación. */
  .requisito-observado {
    grid-column: span 12; /* Parece abierto a todos */
    opacity: 1; /* Es visible y parece justo */
  }
  
  .criterio-evaluacion-subjetivo {
    /* "Innovación de la propuesta": 40% del puntaje */
    /* Este criterio sin definición objetiva permite a la comisión 
       justificar cualquier resultado. */
    grid-column: span 12;
    font-weight: 900; /* Tiene el mayor peso */
  }
}
Conclusión: La Licitación como Liberación (de fondos públicos)
Los arquitectos de la corrupción ven el sistema de compras públicas no como una restricción, sino como una liberación: una forma de liberar fondos del escrutinio y dirigirlos con precisión matemática.

Al entender la "sintaxis" de estos documentos y los "principios de diseño" que los rigen, podemos empezar a fiscalizar de manera efectiva. No basta con mirar el precio final; hay que deconstruir el proceso, línea por línea, para encontrar la belleza funcional de un esquema corrupto.

El código de la corrupción está escrito en documentos públicos. Solo hay que aprender a leerlo.