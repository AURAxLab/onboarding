# Agenda semanal - Práctica Kiany Morales Villavicencio (oct–nov 2026)

**Estudiante:** Kiany Morales Villavicencio  
**Encargado:** Alexander Barquero Elizondo (ABE)  
**Org:** AURAxLab  
**Lugar:** ECCI / CITIC, UCR  
**Horario:** lunes a viernes, 8:00–17:00  
**Periodo aproximado:** 5 octubre – 27 noviembre 2026 (8 semanas)

Hoja de ruta **semanal**. Detalle día a día solo donde ya está fijado (Compusoc, pickup EDUCON, taller del martes 6). Completá oraciones; no inventés URLs ni personas.

---

## 1. Propósito y cómo usarlo

### Propósito

1. **Despejar backlog de investigación de ABE** con entregables concretos, seguros y revisables (sin PII, sin reabrir decisiones cerradas).
2. **Aprendizaje de Kiany:** coding agents, métodos de investigación, herramientas (Antigravity, Git, higiene de cuota, matrices claim–fuente, protocolos de anotación).

### Cómo usarlo

- Revisá el bloque de la semana al **inicio** (lunes o primer check-in con ABE).
- En el **check-in semanal con ABE**, marcá qué entregables avanzaron, qué quedó bloqueado y qué necesita decisión suya.
- UI o código de producto solo **después** del ramp-up de agentes y con luz verde explícita de ABE.

### Pila de prioridades (núcleo)

| # | Proyecto | Enfoque típico |
|---|----------|----------------|
| 1 | **C5353 / NewCVAStudy** | Documentación segura, tablas, codebook, apoyo a backlog que ABE asigne |
| 2 | **cr-anonymizer** | Protocolo de anotación, práctica en texto scrubbed, métricas P/R/F1 |
| 3 | **MixedFeedback** | Matrices literarias / claim–fuente |

**Fuera de alcance:** AlquimIA / Colibría (proyecto muerto).  
**Aparcado:** OVARP (rebanada IA) — no se programa como núcleo; solo si ABE lo decide después.

No hay un track separado de “desarrollo de software practicante”.

### Ritmo con Compusoc (CI-0133 Computación y Sociedad, G3)

Kiany asiste con ABE. Patrón del calendario (America/Costa_Rica; pueden aparecer más fechas):

| Día | Bloque típico | Después |
|-----|---------------|---------|
| **Lunes** | Clase ~10:00–11:50 (a menudo consulta 9:00–10:00 y otra 13:30–15:00) | Tarde libre → lab si no hay consulta |
| **Jueves** | Clase ~09:00–11:50 | Tarde → lab |
| **Mar, mié, vie** | Lab de investigación (día completo, salvo excepciones) | — |

Fechas Compusoc ya vistas en calendario: lun **5, 19, 26 oct** y **2 nov**; jue **8, 15, 22, 29 oct** y **5 nov**. Verificar el calendario de ABE cada semana por altas/bajas.

---

## 2. Semanas 1–8

### Semana 1 · 5–9 octubre 2026

**Tema:** Herramientas, LexTALE, taller Antigravity y arranque read-only de C5353.

**Entregables para backlog de ABE**

- Notas de lectura HANDOFF / REGISTRO (solo lectura; sin reabrir decisiones).
- Esqueleto de tablas bilingües y codebook de 26 intents (estructura; sin inventar labels sin guía).
- Borrador de notas para guía de anotación de cr-anonymizer (preguntas abiertas para Daniel Shih).
- MixedFeedback solo si sobra tiempo (familiarización ligera).

**Aprendizaje**

- Cuentas Google + GitHub; Antigravity, Git, (opcional) VS Code + Copilot.
- LexTALE y criterio CVA C5353 (>80 EN; ≤80 ES).
- Coding agent, higiene de cuota, seguridad (sin secretos, sin PII, sin Salud / Health*).
- Codelab 1 *Primeros pasos*; Codelab 2 si hay cuota.

**Compusoc / ritmo (día a día solo aquí)**

- **Lun 5:** Compusoc ~10:00–11:50 (+ consultas posibles). **14:00** ABE recoge a Kiany en EDUCON. Recorrido del lugar, transporte para el martes, cuentas e instalación. Sin taller largo.
- **Mar 6:** Lab. LexTALE 8:00–9:00; taller agents + Antigravity 9:00–12:00; tarde Codelab 1 + bitácora + 10 prompts. Ver `taller-antigravity-2026-10-06.md` y `semana-1-tareas.md`.
- **Mié 7:** Lab (codelabs + C5353 read-only).
- **Jue 8:** Compusoc ~09:00–11:50; tarde lab.
- **Vie 9:** Lab. Recordatorio ~8:41 con José Daniel si faltan cuenta/máquina.

**Notas:** Daniel Shih (cr-anonymizer) aún sin fecha de reunión.

---

### Semana 2 · 12–16 octubre 2026

**Tema:** Fluidez con agents + familiarización profunda de NewCVAStudy (documentación segura).

**Entregables para backlog de ABE**

- Notas consolidadas HANDOFF / REGISTRO (dudas listadas; sin “arreglar” procesos cerrados).
- Avance del esqueleto tablas bilingües / codebook (columnas acordadas con ABE).
- Higiene documental segura y sin PII según lo que ABE indique (índices, checklists de figuras, nombres de archivo).
- Bitácora semanal: qué aprendió del agent y qué bloquea.

**Aprendizaje**

- Cerrar Codelab 1/2; práctica diaria token-light (un cambio pequeño, revisar diff).
- Documentar dudas sin reabrir decisiones; distinguir scrubbed vs sensible.

**Compusoc / ritmo**

- **Lun 12:** sin Compusoc visto en calendario (confirmar); lab o según ABE.
- **Mar 13 / mié 14 / vie 16:** lab.
- **Jue 15:** Compusoc ~09:00–11:50; tarde lab.

**Notas:** No Abstract rewrite. No datos crudos de participantes.

---

### Semana 3 · 19–23 octubre 2026

**Tema:** Apoyo a tareas C5353 que ABE asigne (tablas, figuras, inventario exploratorio).

**Entregables para backlog de ABE**

- Tablas o checklists de figuras según asignación explícita.
- Inventario de claims **etiquetado como exploratorio** (no como hallazgos finales).
- Lista borrador: ítems del backlog que ella puede tocar vs solo ABE.
- Actualización breve del codebook / tablas si ABE lo pide.

**Aprendizaje**

- Lectura crítica; trazabilidad claim → fuente; etiquetar incertidumbre.
- Agents solo en sandbox o archivos autorizados.

**Compusoc / ritmo**

- **Lun 19:** Compusoc ~10:00–11:50 (+ consultas posibles); resto lab.
- **Mar 20 / mié 21 / vie 23:** lab C5353.
- **Jue 22:** Compusoc ~09:00–11:50; tarde lab.

**Notas:** No reabrir decisiones cerradas. No reescribir Abstract salvo pedido explícito. Sin UI/código.

---

### Semana 4 · 26–30 octubre 2026

**Tema:** cr-anonymizer: protocolo de anotación y práctica en texto scrubbed.

**Entregables para backlog de ABE**

- Notas de protocolo refinadas **después** de reunión con Daniel Shih (si ya ocurrió; si no, borrador de preguntas).
- Práctica gold-sample solo sobre texto scrubbed (sin PII real).
- Ejemplos scrubbed o ficticios de “qué se anota / qué no”.
- Lista de dudas del protocolo para ABE / Daniel.

**Aprendizaje**

- Anotación, gold sample, acuerdo entre anotadores (intro).
- Separar protocolo (reglas) de implementación (código).

**Compusoc / ritmo**

- **Lun 26:** Compusoc ~10:00–11:50; resto lab.
- **Mar 27 / mié 28 / vie 30:** lab cr-anonymizer (+ cierre menor C5353 si ABE lo pide).
- **Jue 29:** Compusoc ~09:00–11:50; tarde lab.

**Notas:** Si Daniel Shih no tiene fecha, documentar el bloqueo en el check-in.

---

### Semana 5 · 2–6 noviembre 2026

**Tema:** Métricas cr-anonymizer (P/R/F1) + inicio matriz lit MixedFeedback.

**Entregables para backlog de ABE**

- Ejercicios P/R/F1 sobre muestras scrubbed o tablas de práctica (TP/FP/FN según guía de ABE).
- Primer esqueleto de matriz literaria MixedFeedback (claims ↔ fuentes).
- Notas de métricas o datos scrubbed que faltan.

**Aprendizaje**

- Interpretar precisión, recall y F1.
- Mapear claim–fuente sin inventar citas.

**Compusoc / ritmo**

- **Lun 2:** Compusoc ~10:00–11:50; resto lab.
- **Mar 3 / mié 4 / vie 6:** lab (métricas + MixedFeedback).
- **Jue 5:** Compusoc ~09:00–11:50; tarde lab.

**Notas:** C5353 solo mantenimiento / tareas puntuales que ABE reabra.

---

### Semana 6 · 9–13 noviembre 2026

**Tema:** Matrices claim–fuente MixedFeedback (profundizar).

**Entregables para backlog de ABE**

- Matrices claim–fuente MixedFeedback avanzadas (más celdas, fuentes verificables, dudas marcadas).
- Bitácora: qué del backlog de ABE quedó cerrado esta semana.
- Cierre de huecos de cr-anonymizer si ABE lo prioriza.

**Aprendizaje**

- Rigor en trazabilidad bibliográfica / claim.
- Vocabulario de evaluación solo si ABE lo introduce.

**Compusoc / ritmo**

- Confirmar en calendario Compusoc de nov (puede haber más lun/jue). Patrón: lun/jue clase; mar/mié/vie lab.
- Prioridad de lab: MixedFeedback.

**Notas:** OVARP sigue aparcado. Sin UI.

---

### Semana 7 · 16–20 noviembre 2026

**Tema:** Consolidar MixedFeedback + backlog C5353 / anonymizer que ABE reabra; UI solo con luz verde.

**Entregables para backlog de ABE**

- Paquete revisable MixedFeedback (matriz(ces) + notas de gaps).
- Tareas de cierre de C5353 o cr-anonymizer que ABE asigne.
- Si ABE autoriza UI/código: cambios pequeños, diff revisable, nunca secretos ni PII.

**Aprendizaje**

- Pedir revisión antes de ampliar alcance.
- Si hay UI: diffs pequeños y revisión humana.

**Compusoc / ritmo**

- Confirmar lun/jue Compusoc en calendario; resto lab de consolidación.

**Notas:** No programar OVARP ni AlquimIA. Si ABE libera OVARP esa semana, tratarlo como excepción explícita.

---

### Semana 8 · 23–27 noviembre 2026

**Tema:** Cierre, consolidación y handoff para el siguiente practicante.

**Entregables para backlog de ABE**

- Índice de entregables semanas 1–7 (hecho / parcial / bloqueado).
- **Bitácora final** (aprendizajes, bloqueos, recomendaciones).
- **Documento de handoff** (qué leer primero, normas de seguridad, estado por proyecto).
- **Lista de gaps** para ABE (decisiones pendientes, scrubbed faltante, ítems no tocados a propósito).

**Aprendizaje**

- Handoff usable vale más que trabajo sin contexto.
- Autoevaluación breve frente a las dos metas (backlog + aprendizaje).

**Compusoc / ritmo**

- Confirmar Compusoc; resto lab de cierre. Sin frentes nuevos salvo pedido de ABE.

---

## 3. Vista rápida

| Semana | Fechas | Enfoque | Compusoc visto |
|--------|--------|---------|----------------|
| 1 | 5–9 oct | Tools + LexTALE + Antigravity + C5353 read-only | Lun 5 (+ EDUCON 14:00), jue 8 |
| 2 | 12–16 oct | Fluidez agents + NewCVAStudy profundo | Jue 15 |
| 3 | 19–23 oct | Tareas C5353 asignadas por ABE | Lun 19, jue 22 |
| 4 | 26–30 oct | cr-anonymizer protocolo + gold scrubbed | Lun 26, jue 29 |
| 5 | 2–6 nov | P/R/F1 + MixedFeedback lit start | Lun 2, jue 5 |
| 6 | 9–13 nov | MixedFeedback claim–fuente | Confirmar calendario |
| 7 | 16–20 nov | Consolidar núcleo; UI solo si ABE OK | Confirmar calendario |
| 8 | 23–27 nov | Bitácora final, handoff, gaps | Confirmar calendario |

---

## 4. Decisiones abiertas (requieren ABE)

1. **Calendario Compusoc nov (semanas 6–8):** confirmar lun/jue adicionales en Google Calendar.
2. **Reunión Daniel Shih:** cuándo y qué debe llevar Kiany.
3. **Backlog C5353 seguro:** qué puede tocar ella vs solo ABE (Abstract, decisiones cerradas, PII = solo ABE).
4. **Luz verde UI/código:** si/cuándo y en qué repo/sandbox.
5. **OVARP:** seguir aparcado o liberar una rebanada concreta (por defecto: no).

---

## 5. Normas permanentes

1. No secretos en el chat del agent.
2. No datos personales de participantes.
3. No abrir carpetas Salud / Health*.
4. No force-push, no borrar repos, no subir secretos.
5. Un cambio pequeño por vez; siempre revisar el diff.
6. Si el agent propone algo raro: parar y preguntar a Alexander.
7. No reabrir decisiones cerradas de C5353 / NewCVAStudy salvo instrucción explícita de ABE.

---

## 6. Contactos

- **Alexander Barquero Elizondo** · encargado · alexander.barqueroelizondo@ucr.ac.cr · ext. 8000  
- **José Daniel** · cuenta / computadora / permisos de install  
- **Daniel Shih** · referente reunión cr-anonymizer  
- Dudas MEP: Rosibel Arguello Segura · ext. 6099  

---

## 7. Archivos relacionados

| Archivo | Uso |
|---------|-----|
| `semana-1-tareas.md` | Detalle día a día Semana 1 |
| `taller-antigravity-2026-10-06.md` | Guion del taller mar 6 (ABE) |
| `index.html` | Onboarding imprimible |

---

*AURAxLab · Agenda semanal oct–nov 2026 · Kiany Morales Villavicencio · Anclada a Compusoc lun/jue*
