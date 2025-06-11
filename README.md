# Trabajo Práctico N.º 4 - Gramáticas de cláusulas definidas en Prolog

**Nombre:** Coral Tolazzi  
**Materia:** Procesamiento del Lenguaje Natural  
**Tema:** Lenguajes y Autómatas - Gramáticas  
**Profesora:** Yanina Ximena Scudero  
**Cuatrimestre:** 1.º Cuatrimestre del 2025  
**Instituto:** Instituto Tecnológico Beltrán

## Descripción

Este trabajo práctico consiste en el desarrollo de una gramática utilizando cláusulas definidas en Prolog (DCG) para generar y validar oraciones simples. Se construye una base de conocimiento con estructuras gramaticales como sintagmas nominales y verbales, respetando género y número, y se generan árboles sintácticos a partir de consultas.

## ⚙️ Funcionalidades

- Implementación de gramáticas en Prolog con DCG.
- Representación de estructuras gramaticales con argumentos de género y número.
- Construcción de árboles sintácticos para oraciones válidas.
- Consultas que permiten verificar oraciones o mostrar su análisis sintáctico.

## Componentes principales

- Reglas gramaticales:
  - `o/1`: oración compuesta por sintagma nominal + sintagma verbal.
  - `sn/3`: sintagma nominal con determinante y sustantivo.
  - `sv/2`: sintagma verbal con verbo intransitivo o transitivo.
- Predicados para:
  - Determinantes: género (m/f) y número (sg/pl).
  - Sustantivos: género y número.
  - Verbos: transitivos e intransitivos, con número.
- Consultas de ejemplo:
  - `phrase(o(_), [la, empleada, trabaja])`: verifica validez.
  - `phrase(o(O), Oracion)`: construye árbol sintáctico.

## Conclusión

Este trabajo permite aplicar gramáticas formales al procesamiento del lenguaje natural usando Prolog, generando estructuras sintácticas y validando oraciones con precisión. Fortalece la comprensión de las DCG y su aplicación en entornos lógicos.
