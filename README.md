# Barcelona Alimenta
**Dashboard de acceso a alimentación sostenible y de proximidad en los barrios de Barcelona**

**Enfoque:** Barcelona y área metropolitana · **Tema:** alimentación urbana
**Asignatura:** Gestión de Proyectos (UAB 2026/27) · **Grupo:** 8 — Oriol Carbó Molera (1795282) · Xavier Vara Anido (1795681) · Hèctor Villanueva Azuara (1790820) · Pol Raurich Barba (1795396)

---

## 1. Reto

No todos los barrios de Barcelona tienen el mismo acceso a alimentos frescos, de proximidad y sostenibles (mercados municipales, huertos urbanos, puntos de venta de proximidad). Esa desigualdad se cruza con la renta y la densidad de población, y hoy no existe una visión sencilla y pública que permita verla barrio a barrio.

**Pregunta guía:** ¿qué barrios tienen menos acceso a una alimentación sostenible y de proximidad, y qué proyectos urbanos podrían reducir esa brecha dentro de un modelo de ciudad justa, circular y regenerativa?

## 2. Objetivos y finalidad

**Objetivo general:** diseñar y planificar un proyecto que haga visible y ayude a reducir las desigualdades de acceso a alimentación sostenible y de proximidad en Barcelona, apoyado en datos abiertos.

**Objetivos específicos**
1. Mapear la oferta de alimentación de proximidad por barrio (mercados, huertos urbanos y otros puntos relevantes) con datos de Open Data BCN.
2. Cruzar esa oferta con población y renta para construir un indicador de acceso por barrio.
3. Identificar los barrios prioritarios y proponer 2 o 3 intervenciones concretas (por ejemplo, nuevos huertos comunitarios, circuitos cortos de venta o mercados itinerantes).
4. Publicar un dashboard online como prototipo que comunique los resultados a la ciudadanía y a los responsables públicos.
5. Completar el diseño de gestión del proyecto: plan, costes, riesgos, impacto, stakeholders y gobernanza.

**Finalidad:** contribuir a una transformación urbana inteligente, sostenible, circular y justa, y demostrar coherencia entre el reto, las actividades, los recursos, los impactos y los riesgos.

## 3. Criterios mínimos de éxito

- [ ] Enfoque, tema y reto definidos y recogidos en este README.
- [ ] Propuesta escrita completa: reto, plan de gestión, costes, riesgos, impacto, stakeholders y gobernanza.
- [ ] Prototipo: dashboard online publicado en GitHub Pages, con al menos 3 indicadores por barrio, un mapa y una página «Sobre» con fuentes, método y licencia.
- [ ] WBS, PERT y Gantt elaborados; tablero Kanban actualizado semanalmente.
- [ ] Matriz de riesgos y Teoría del Cambio con indicadores de impacto.
- [ ] Presentación oral defendida por todo el grupo.
- [ ] Uso de IA declarado, con análisis y reflexión propios del grupo.

## 4. Roles

| Persona | Rol principal | Responsabilidades | Apoyo en |
|---|---|---|---|
| Oriol Carbó Molera | Coordinación y planificación | Repositorio, README, WBS, PERT, Gantt, tablero Kanban, reuniones y entregas | Redacción de la propuesta |
| Xavier Vara Anido | Impacto, costes y redacción | Costes y financiación, matriz de riesgos, Teoría del Cambio, indicadores y propuesta escrita | Análisis de datos |
| Hèctor Villanueva Azuara | Datos y prototipo | Datasets de Open Data BCN, limpieza, dashboard, GitHub Pages y `sobre.html` | Presentación oral |
| Pol Raurich Barba | Stakeholders y comunicación | Mapa de actores, gobernanza, estrategia de comunicación y guion de la presentación oral | Diseño visual del dashboard |

Todos los miembros revisan los entregables y participan en la presentación oral. La matriz RACI inicial está en [`docs/plan.md`](docs/plan.md) y se revisa en la tarea E.

## 5. Planificación

- Plan, tareas, PERT y Gantt: [`docs/plan.md`](docs/plan.md)
- Tablero de tareas: GitHub Projects del repositorio (Board y Roadmap) https://github.com/users/hectorvillanuevaazuara-dot/projects/1.

## 6. Estructura del repositorio

Estructura prevista: `index.html`, `sobre.html` y `data/` se añadirán cuando se desarrolle el prototipo (tareas L y M).

```
barcelona-alimenta/
├─ README.md
├─ index.html          (dashboard, raíz del sitio)
├─ sobre.html          (fuentes, método y licencia)
├─ docs/
│  └─ plan.md
└─ data/
```

## 7. Datos y licencias

Fuente principal: Open Data BCN (Ajuntament de Barcelona), con licencia Creative Commons Attribution 4.0. Datasets previstos (localizados en el portal; falta validar su uso en la tarea B):

- Mercados municipales de la ciudad de Barcelona (CSV, actualización semanal)
- Huertos urbanos de la ciudad de Barcelona (CSV y JSON)
- Renta disponible de los hogares por persona, por secciones censales (CSV); habrá que agregarla a barrios
- Población por barrio (pendiente de seleccionar el dataset concreto)

Los datasets definitivos y su fecha de actualización se documentarán en `sobre.html`. Licencia del repositorio: CC BY 4.0.

## 8. Uso de herramientas de IA

Se emplean herramientas de IA como apoyo (exploración de datos, generación de código del dashboard, revisión). El análisis, la interpretación y las decisiones son del grupo, y cada uso significativo se documenta.
