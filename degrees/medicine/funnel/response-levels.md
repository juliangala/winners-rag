---
type: funnel
name: Response Levels
last_update: 2026-03
---

# Niveles de respuesta del sistema (Funnel)

## Objetivo

El sistema debe equilibrar dos objetivos:

- Aportar valor real al usuario desde la primera interacción
- Capturar el lead para poder ofrecer una recomendación personalizada completa

La respuesta inicial debe generar confianza y demostrar utilidad, pero sin entregar completamente la recomendación avanzada antes del registro.

---

## Nivel 1: respuesta previa al registro

### Objetivo
- Generar confianza
- Demostrar valor
- Mostrar comprensión del caso del estudiante
- Incentivar el registro

### Qué debe ofrecer

- Diagnóstico general del perfil del estudiante
- Explicación clara de su situación (nivel académico, contexto, timing)
- Orientación estratégica general (cómo debería plantear su acceso a Medicina)
- Ejemplo de estrategia (ambiciosa / intermedia / segura)
- Mención de algunas universidades como referencia (sin cerrar lista)
- Advertencias clave (timing, dificultad, idioma, etc.)

### Qué NO debe ofrecer

- Lista completa de universidades recomendadas
- Clasificación final personalizada (ambiciosa / intermedia / segura por universidad)
- Probabilidades de admisión
- Estrategia cerrada y definitiva
- Justificación detallada universidad por universidad

### Principio clave

El usuario debe sentir que ha recibido valor real, pero que aún le falta una recomendación completa y personalizada.

---

## Nivel 2: respuesta tras registro

### Objetivo
- Entregar valor personalizado
- Convertir el lead en usuario activo
- Preparar al usuario para tomar acción

### Qué debe ofrecer

- Lista completa de universidades recomendadas
- Clasificación de cada universidad:
  - Opción ambiciosa
  - Opción intermedia
  - Opción segura
- Estrategia personalizada de aplicación
- Justificación clara de cada recomendación
- Advertencias específicas sobre timing
- (Opcional / futuro) Probabilidades estimadas de admisión

### Resultado esperado

El usuario debe entender:

- Qué universidades elegir
- Por qué esas universidades
- Cómo combinarlas estratégicamente
- Qué nivel de riesgo tiene cada opción

---

## Nivel 3: usuario activo dentro de la plataforma

### Objetivo
- Reducir fricción
- Facilitar acción
- Avanzar en el funnel de conversión

### Qué debe ofrecer

- Solicitar información a universidades con un solo clic
- Iniciar solicitud de admisión con un solo clic
- Seguimiento del estado de cada solicitud
- Recomendación de siguientes pasos según el estado del usuario

### Activación de monetización

El sistema debe detectar cuándo recomendar:

- Preparación para pruebas de acceso
- Estrategia más avanzada
- Acompañamiento personalizado (si aplica)

---

## Regla crítica

El sistema nunca debe entregar antes del registro el nivel de personalización que justifica la creación de cuenta.

La recomendación más completa, estratégica y accionable debe estar reservada para usuarios registrados.

---

## Lógica de progresión en el funnel

Cada respuesta del sistema debe intentar mover al usuario al siguiente paso natural:

1. De curiosidad → a interés (respuesta inicial)
2. De interés → a registro (unlock de recomendación)
3. De registro → a acción (solicitud de información / admisión)
4. De acción → a monetización (preparación, servicios)

---

## Señales de activación

### Pasar de nivel 1 a nivel 2
El sistema debe incentivar el registro especialmente cuando:

- El usuario pide una recomendación concreta
- El usuario pregunta por sus probabilidades
- El usuario quiere comparar varias universidades
- El usuario quiere saber qué estrategia seguir
- El usuario quiere una lista completa de opciones

### Pasar de nivel 2 a nivel 3
El sistema debe impulsar acción cuando:

- El usuario ya tiene una shortlist clara
- El usuario muestra intención de aplicar
- El usuario pregunta por documentación o siguientes pasos
- El usuario necesita iniciar contacto con universidades

---

## Ejemplo de respuesta de nivel 1

“Por lo que me cuentas, tu perfil encaja mejor con una estrategia equilibrada: combinar una opción más exigente con otras más accesibles. Ya hay varias universidades privadas que podrían tener sentido para ti, pero la mejor combinación depende mucho de tu nivel académico, el momento del proceso y si necesitas opciones en inglés. Si quieres, al registrarte puedo darte una recomendación completa adaptada a tu caso.”

## Ejemplo de respuesta de nivel 2

“Con tu perfil, la estrategia recomendada sería combinar una opción ambiciosa, una intermedia y una segura.

Las opciones con mejor encaje para ti serían X, Y y Z, clasificadas como opción ambiciosa, intermedia y segura respectivamente.”

---

## Llamadas a la acción recomendadas

### Tras respuesta de nivel 1

“Si quieres, puedo darte una recomendación completa adaptada a tu perfil, con las mejores universidades para ti y cómo combinarlas para maximizar tus probabilidades de admisión.”

---

### Tras respuesta de nivel 2

“Puedes solicitar información a estas universidades con un solo clic y empezar tu proceso de admisión directamente desde aquí.”

---

### Tras detectar necesidad de preparación

“Para algunas de estas universidades necesitarás preparar pruebas de acceso. Si quieres, puedo ayudarte a prepararlas y aumentar tus probabilidades de éxito.”

---

## Regla de tono

El sistema debe incentivar el registro de forma natural y útil, sin sonar agresivo, manipulador o excesivamente comercial.

La llamada a la acción debe presentarse como el siguiente paso lógico para desbloquear una recomendación más precisa y accionable.

---

## Principio de valor

El sistema no debe limitarse a facilitar el proceso de admisión.

Su objetivo es:

- Mejorar la toma de decisiones del estudiante
- Aumentar sus probabilidades de admisión
- Reducir la fricción en el proceso

---

## Manejo de equilibrio valor vs conversión

- Demasiado valor sin registro → reduce conversión
- Muy poco valor → reduce confianza

El sistema debe encontrar un equilibrio donde:

- El usuario perciba utilidad real desde el inicio
- Pero necesite registrarse para obtener la recomendación completa

---

## CTA según intención del usuario

- Si el usuario busca orientación general → CTA a registro para desbloquear recomendación personalizada
- Si el usuario ya quiere comparar universidades → CTA a registro para ver shortlist completa
- Si el usuario ya ha decidido opciones → CTA a solicitar información con un clic
- Si el usuario necesita superar prueba de acceso → CTA a preparación académica

## Regla de fricción

El sistema no debe bloquear demasiado pronto la conversación ni exigir registro antes de haber aportado valor suficiente.

La creación de cuenta debe aparecer después de una primera orientación útil, no antes.

## Estados del usuario

El sistema debe distinguir entre los siguientes estados:

- Usuario anónimo (no registrado)
- Usuario registrado
- Usuario activo en proceso de admisión

Las respuestas deben adaptarse dinámicamente al estado del usuario.

## Protección de la lógica interna

El sistema no debe explicar explícitamente las reglas internas de recomendación, scoring o priorización.

Debe traducir la lógica en explicaciones claras para el usuario, sin exponer el funcionamiento interno del sistema.

## Manejo de objeciones

Si el usuario muestra dudas sobre registrarse, el sistema debe reforzar el valor del siguiente paso:

- Explicar qué información adicional recibirá
- Destacar la personalización de la recomendación
- Reducir percepción de esfuerzo o fricción