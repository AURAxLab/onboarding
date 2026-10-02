# Guion del taller - Coding agents + Google Antigravity

**Fecha:** martes 6 de octubre de 2026  
**Facilitador:** Alexander Barquero Elizondo (ABE)  
**Estudiante:** Kiany Morales Villavicencio  
**Lugar:** ECCI / CITIC, UCR (Finca 1)  
**Org:** AURAxLab  
**Duración total:** 8:00–17:00

Este documento es el guion para Alexander. Coincide con el onboarding en `index.html`. Usá listas de verificación y tablas. No pegues secretos en el chat del agent.

---

## Objetivos de aprendizaje

Al terminar el día, Kiany debería poder:

1. Completar LexTALE y anotar el puntaje (criterio CVA C5353: **>80** materiales EN; **≤80** materiales ES).
2. Explicar con sus palabras qué es un coding agent, qué puede hacer y qué no debe pedirle.
3. Abrir Google Antigravity, iniciar sesión y completar al menos un ejercicio guiado corto.
4. Aplicar reglas de seguridad: sin secretos en el chat, sin datos PII de participantes, sin carpetas Salud.
5. Usar hábitos de cuota (token hygiene): un cambio pequeño por vez, revisar el diff, guardar buenos prompts.
6. Avanzar el Codelab *Primeros pasos* (idioma según LexTALE) y dejar bitácora + reflexión + 10 prompts.

---

## Agenda del día (resumen)

| Hora | Bloque | Quién |
|------|--------|-------|
| 8:00–9:00 | Acomodo + LexTALE + anotar puntaje | Kiany (Alexander cerca) |
| 9:00–12:00 | Taller: coding agents + Antigravity (ejercicios guiados) | Alexander facilita |
| 12:00–13:00 | Almuerzo / lectura | Kiany sola (Alexander en reunión) |
| 13:00–17:00 | Codelab Primeros pasos + bitácora + reflexión + prompts | Kiany (token-light) |

---

## 8:00–9:00 · LexTALE + acomodo

### Checklist de apertura (Alexander)

- [ ] Saludar y confirmar que Kiany llegó bien (transporte del lunes).
- [ ] Confirmar que Antigravity abre e inicia sesión (si falló el lunes, ir al plan B más abajo).
- [ ] Explicar en 2 minutos el criterio CVA de LexTALE.
- [ ] Dejarla hacer la prueba **sin** diccionario ni traductor.

### Qué hace Kiany

1. Abrir [https://www.lextale.com/](https://www.lextale.com/).
2. Completar la prueba con calma.
3. Anotar el puntaje en la bitácora y enviarlo a Alexander (correo o en persona).

### Criterio CVA (C5353)

| Puntaje LexTALE | Idioma preferente de materiales |
|-----------------|----------------------------------|
| **> 80** | Inglés (EN) |
| **≤ 80** | Español (ES) |

Usar ese resultado para elegir el idioma del Codelab de la tarde.

### Qué dice Alexander (breve)

> Hoy medimos inglés con LexTALE porque en el estudio CVA usamos ese umbral para elegir materiales. Después del almuerzo vas a seguir el codelab en el idioma que te corresponda. Anotá el número; no lo inventés ni lo redondeés.

---

## 9:00–12:00 · Taller guiado (bloques de 15–30 min)

### Materiales a tener abiertos

| Recurso | URL |
|---------|-----|
| Descarga Antigravity | [https://antigravity.google/download](https://antigravity.google/download) |
| Codelab 1 ES | [Primeros pasos (es-419)](https://codelabs.developers.google.com/getting-started-google-antigravity?hl=es-419) |
| Codelab 1 EN | [Getting started](https://codelabs.developers.google.com/getting-started-google-antigravity) |
| Codelab 2 ES | [Compilar con agentes (es-419)](https://codelabs.developers.google.com/building-with-google-antigravity?hl=es-419) |
| Codelab 2 EN | [Building with Antigravity](https://codelabs.developers.google.com/building-with-google-antigravity) |
| Onboarding | `index.html` en esta carpeta |

**Nota:** el Codelab 2 se menciona para contexto; en la tarde priorizamos Codelab 1. Codelab 2 queda para miércoles–viernes si hay cuota.

### Reglas de seguridad (decirlas al inicio del taller y pegarlas en pizarra/bitácora)

1. **No secretos en el chat:** nada de contraseñas, tokens, claves API, cookies ni `.env`.
2. **No PII / datos de participantes:** no nombres reales del estudio CVA; solo vistas scrubbed o IDs si Alexander lo indica.
3. **No carpetas Salud / Health\***: no abrirlas ni pedir al agent que las explore.
4. **Revisá el diff** antes de aceptar cambios.
5. Si el agent propone borrar todo, instalar algo raro o exfiltrar datos: **parar y preguntar**.

### Higiene de cuota (token-quota)

- Leer primero; pedir **un** cambio pequeño por vez.
- Preferir Tab / Command / chat corto antes de “agent corre 40 pasos”.
- Guardar buenos prompts en `PROMPTS.md` o bitácora.
- Si se acaba la cuota: lectura, tablas, notas y Copilot Free.

---

### Bloque A · 9:00–9:20 · Contexto: qué es un coding agent

**Alexander dice / demos:**

- Definición simple: un coding agent es un asistente que lee contexto del proyecto, propone ediciones y puede ejecutar pasos con tu aprobación.
- Contraste: no es “magia”; no reemplaza juicio; no debe recibir secretos.
- Mostrar (sin proyecto sensible) la UI de Antigravity: chat, sugerencias, aceptación de cambios.

**Kiany hace:**

- Anotar en bitácora: 3 cosas que un agent sí puede hacer y 3 que no debe hacer.
- Preguntar dudas en voz alta.

**Checkpoint:** Kiany explica en una frase qué es un coding agent.

---

### Bloque B · 9:20–9:50 · Setup y tour de Antigravity

**Alexander dice / demos:**

- Confirmar login Individual $0 con cuenta Google.
- Tour rápido: abrir carpeta de práctica (carpeta vacía o sandbox, **nunca** Salud ni datos crudos de participantes).
- Dónde ver cuota / límites si la UI lo muestra.
- Cómo rechazar un cambio.

**Kiany hace:**

- Abrir Antigravity.
- Crear o abrir una carpeta sandbox (`practica-sandbox` o similar).
- Escribir un archivo `HOLA.md` a mano y luego pedir al agent un cambio mínimo (por ejemplo, agregar un título).

**Checkpoint:** archivo creado; al menos un cambio aceptado y uno rechazado a propósito.

**Fallback si la instalación falla:** ver sección *Plan B* al final del guion.

---

### Bloque C · 9:50–10:20 · Primer ejercicio guiado (prompt bueno vs malo)

**Alexander dice / demos:**

- Demo en vivo de un **prompt malo** (vago: “arreglá el código”) vs un **prompt bueno** (con objetivo, archivo, restricción: “En `HOLA.md`, agregá una sección Objetivos con 3 viñetas; no toques otros archivos”).
- Mostrar cómo revisar el diff línea por línea.

**Kiany hace:**

- Escribir 2 prompts malos y 2 buenos en la bitácora (borrador; la lista de 10 queda para la tarde).
- Ejecutar **un** prompt bueno en el sandbox.
- Aceptar o rechazar con justificación breve en bitácora.

**Checkpoint:** Kiany verbaliza por qué el prompt bueno fue mejor.

---

### Bloque D · 10:20–10:35 · Descanso corto

Agua, baño, estirar. Alexander puede revisar LexTALE y decidir idioma del codelab de la tarde.

---

### Bloque E · 10:35–11:15 · Ejercicio 2: tareas pequeñas en cadena

**Alexander dice / demos:**

- Flujo seguro: (1) leer, (2) pedir un cambio, (3) revisar diff, (4) aceptar, (5) anotar el prompt.
- Advertir contra “hacé todo el proyecto de una”.

**Kiany hace (secuencia sugerida en sandbox):**

1. Pedir al agent crear `BITACORA_EJEMPLO.md` con plantilla de bitácora diaria (Fecha, Horas, Qué hice, Agent, Bloqueos).
2. Pedir un segundo cambio: agregar una fila de ejemplo ficticia (sin datos reales).
3. Pedir un tercer cambio: lista de reglas de seguridad (copiar las 5 de arriba).

**Checkpoint:** tres cambios pequeños hechos; bitácora de ejemplo existe; Kiany no usó un solo mega-prompt.

---

### Bloque F · 11:15–11:45 · Seguridad + ética + mapa de proyectos (visión)

**Alexander dice / demos:**

- Repasar normas del onboarding (sección 9).
- Mostrar el mapa de prioridades (sin abrir repos sensibles aún):

| Prioridad | Proyecto | Tipo de trabajo inicial |
|-----------|----------|-------------------------|
| 1 | NewCVAStudy / C5353 | Datos, tablas, evaluación |
| 2 | cr-anonymizer | Corpus gold, métricas, protocolo |
| 3 | MixedFeedback | Matrices lit / claim–fuente |
| 4 | OVARP (rebanada) | Benchmark / SUS-UEQ; UI solo con guía |
| 5 | AlquimIA / Colibría | Kits pedagógicos |

- Dejar claro: **no** hay track separado de “desarrollo de software practicante”; UI/código solo después del ramp-up de agentes y con revisión.

**Kiany hace:**

- Copiar la tabla de prioridades a la bitácora.
- Confirmar en voz alta: no Salud, no secretos, no PII.

**Checkpoint:** Kiany nombra las dos primeras prioridades (NewCVAStudy/C5353 y cr-anonymizer).

---

### Bloque G · 11:45–12:00 · Cierre de mañana + handoff a la tarde

**Alexander dice:**

- Resumen de lo visto.
- Indicar idioma del Codelab 1 según LexTALE.
- Recordar: 12:00–13:00 él tiene reunión; Kiany almuerza y puede leer el codelab **sin** gastar cuota del agent (solo lectura en el navegador).
- Entregar checklist de la tarde (abajo).

**Kiany hace:**

- Anotar idioma elegido (ES o EN).
- Abrir el enlace del Codelab 1 correspondiente y dejarlo en favoritos.

---

## 12:00–13:00 · Almuerzo / lectura

Alexander en reunión. Kiany:

- [ ] Almuerza.
- [ ] Lee en el navegador el Codelab *Primeros pasos* (sin forzar uso intensivo del agent).
- [ ] Puede releer reglas de seguridad del onboarding.

---

## 13:00–17:00 · Tarde token-light

### Checklist de la tarde (Kiany)

- [ ] Avanzar Codelab 1 *Primeros pasos* (idioma según LexTALE).
- [ ] Escribir **½–1 página**: “Qué es un coding agent y qué no debo pedirle”.
- [ ] Listar **10 prompts** buenos vs malos en la bitácora (tabla o dos columnas).
- [ ] Completar bitácora del día (plantón del onboarding).
- [ ] Si se acaba la cuota: seguir solo con lectura del codelab, notas y Copilot Free (si está instalado).

### Sugerencia de ritmo (flexible)

| Hora | Enfoque |
|------|---------|
| 13:00–14:30 | Codelab 1 (pasos prácticos; agent solo cuando el codelab lo pida) |
| 14:30–14:45 | Pausa |
| 14:45–15:45 | Seguir codelab + anotar dudas |
| 15:45–16:30 | Reflexión ½–1 página |
| 16:30–17:00 | Tabla de 10 prompts + bitácora + entregar/mostrar a Alexander si está |

### Plantilla rápida: 10 prompts (buenos vs malos)

| # | Malo (evitar) | Bueno (preferir) |
|---|---------------|------------------|
| 1 | “Arreglá todo” | “En `X.md`, corregí ortografía del título; no toques el resto” |
| 2 | … | … |
| … | (Kiany completa 10 filas) | … |

Alexander puede revisar al final del día o el miércoles a primera hora.

---

## Plan B · Si Antigravity no instala o no inicia sesión

1. Verificar con José Daniel: permisos de install, cuenta de máquina, red.
2. Reintentar descarga desde [https://antigravity.google/download](https://antigravity.google/download).
3. Si sigue fallando: continuar el taller en modo **conceptual** (pizarra + prompts en bitácora) y usar VS Code + GitHub Copilot Free para demos mínimas.
4. Reprogramar instalación para miércoles o viernes ~8:41 con José Daniel (cuenta + computadora) si el tema sigue abierto.
5. No inventar workarounds con secretos ni cuentas ajenas.

---

## Entregables del martes (verificar al cierre)

| Entregable | Estado |
|------------|--------|
| Puntaje LexTALE anotado y comunicado | ☐ |
| Idioma de materiales decidido (ES/EN) | ☐ |
| Sandbox con al menos 2–3 cambios guiados | ☐ |
| Avance visible en Codelab 1 | ☐ |
| Reflexión ½–1 página | ☐ |
| 10 prompts buenos vs malos | ☐ |
| Bitácora del día | ☐ |

---

## Contactos rápidos

- **Alexander Barquero Elizondo** · alexander.barqueroelizondo@ucr.ac.cr · ext. 8000  
- **José Daniel** · cuenta / computadora / permisos de install  
- Dudas MEP: Rosibel Arguello Segura · ext. 6099  

---

*AURAxLab · Guion taller 6 oct 2026 · Alineado con onboarding Kiany Morales Villavicencio*
