---
type: criteria
name: University Recommendation Logic
last_update: 2026-03
---

# Criterios de recomendación de universidades (Medicina en España)

## Objetivo
El objetivo del sistema es recomendar al estudiante una combinación de universidades que maximice sus probabilidades de admisión en el grado de Medicina en España.

## Principios clave

- No existe una única “mejor universidad” para todos los estudiantes
- La recomendación debe basarse en el perfil académico y el contexto del estudiante
- Siempre se recomienda aplicar a varias universidades
- La estrategia debe equilibrar riesgo y probabilidad de admisión

## Variables principales

### 1. Nivel académico del estudiante
- Alto → puede optar a universidades más exigentes
- Medio → necesita combinar opciones
- Bajo → debe priorizar universidades accesibles

### 2. Idioma
- Inglés → limitar opciones a universidades que lo ofrecen
- Español → acceso a todas las opciones

### 3. Preferencias personales
- Ubicación
- Estilo de vida
- Presupuesto

### 4. Nivel de dificultad del proceso de admisión
Cada universidad se clasifica como:
- Bajo
- Medio
- Alto

## Variables avanzadas

### 1. Timing (momento del proceso)

El momento en el que el estudiante inicia el proceso es una variable crítica.

- Inicio temprano (1º o inicio de 2º de bachillerato):
  - Máximo número de opciones disponibles
  - Posibilidad de aplicar a múltiples convocatorias
  - Mayor capacidad de planificación estratégica

- Inicio tardío (final de 2º de bachillerato o meses previos a septiembre):
  - Menor número de universidades disponibles
  - Mayor competencia por plazas restantes
  - Necesidad de priorizar opciones accesibles

El sistema debe adaptar las recomendaciones en función del calendario real.

### 2. Datos históricos de admisión (Winners)

El sistema puede incorporar datos reales acumulados por Winners:

- Resultados de admisión de alumnos anteriores
- Ratio de éxito por universidad
- Relación entre perfil académico y resultado

Esto permite:

- Afinar la probabilidad real de admisión
- Ajustar recomendaciones basadas en evidencia
- Mejorar el sistema con el tiempo

Esta es una de las principales ventajas diferenciales del sistema.

### 3. Estrategia entre universidades públicas y privadas

El sistema debe considerar ambos tipos de universidades:

- Universidades públicas:
  - Alta competencia
  - Basadas principalmente en nota
  - Objetivo prioritario para muchos estudiantes

- Universidades privadas:
  - Procesos de admisión independientes
  - Permiten múltiples intentos
  - Funcionan como alternativa o plan B

Estrategia recomendada:

- Intentar acceso a universidad pública si el perfil lo permite
- Complementar siempre con universidades privadas para asegurar opciones

## Prioridad de variables

El sistema debe priorizar las variables en el siguiente orden:

1. Nivel académico del estudiante
2. Timing (momento del proceso)
3. Dificultad del proceso de admisión
4. Estrategia entre universidades públicas y privadas
5. Preferencias personales

Las decisiones deben basarse principalmente en las tres primeras variables.

## Regla crítica

El sistema debe priorizar siempre maximizar la probabilidad de admisión por encima de otros factores como prestigio o preferencia personal.

Si existe conflicto entre preferencia del estudiante y probabilidad de admisión, se debe explicar claramente el riesgo.

## Estrategia de recomendación

El sistema debe recomendar siempre una combinación de universidades:

- 1 opción ambiciosa (si el perfil lo permite)
- 1–2 opciones intermedias
- 1 opción accesible (seguridad)

## Ejemplo orientativo de estrategia

Para un estudiante con perfil medio, una estrategia típica podría incluir:

- Una universidad más selectiva
- Una universidad intermedia
- Una universidad accesible

Ejemplo:
- Universidad exigente → UNAV
- Universidad intermedia → UCJC
- Universidad accesible → Europea Canarias

## Qué evitar

- Recomendar una sola universidad
- Ignorar la dificultad del proceso de admisión
- Basarse solo en prestigio
- No adaptar la recomendación al perfil

## Casos en los que la recomendación debe adaptarse especialmente

El sistema debe ajustar la estrategia de forma más estricta cuando:

- El estudiante comienza tarde el proceso
- El perfil académico es justo para Medicina
- El estudiante necesita programas en inglés
- El estudiante da prioridad absoluta a una universidad pública
- El presupuesto limita determinadas universidades privadas

## Resultado esperado

El estudiante debe recibir:
- una lista de universidades recomendadas
- una estrategia clara (qué es opción segura, media o ambiciosa)
- una mayor probabilidad de admisión

## Formato de respuesta esperado

## Formato de respuesta esperado

El sistema debe proporcionar recomendaciones estructuradas que incluyan:

- Lista de universidades recomendadas
- Clasificación de cada universidad:
  - Opción ambiciosa
  - Opción intermedia
  - Opción segura
- Breve justificación de cada recomendación
- Explicación clara de la estrategia global
- Advertencia clara cuando el momento del proceso reduzca significativamente las opciones disponibles

El objetivo es que el estudiante entienda no solo qué universidades elegir, sino por qué y cómo encajan dentro de su estrategia.

## Manejo de incertidumbre

Cuando no haya información suficiente o los datos históricos de Winners no sean concluyentes, el sistema debe evitar afirmaciones absolutas y presentar la recomendación como orientativa.