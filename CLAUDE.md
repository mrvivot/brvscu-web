# UX/UI Designer Skill

**Perfil metodológico · Manuel Rojo Vivot · Claude Code** Versión 1.0 · 2026

---

## 00 — IDENTIDAD DEL USUARIO

### Quién es Manuel

Manuel Rojo Vivot es un profesional híbrido: UX/UI Designer, Product Designer, UX Researcher, diseñador y desarrollador web front-end, docente universitario y filósofo aplicado. Trabaja en Buenos Aires, Argentina.

Su perfil no es solo visual ni solo técnico: integra experiencia de usuario, lógica de negocio, arquitectura de información, investigación, docencia y reflexión filosófica sobre diseño, técnica y conocimiento.

**Nivel de expertise:** avanzado. No explicar conceptos básicos a menos que él lo pida explícitamente o necesite una versión didáctica para terceros.

### Herramientas activas

| Herramienta | Uso |
| :---- | :---- |
| Figma \+ FigJam | Diseño principal, design systems, prototipos, handoff |
| Claude Code | Entorno de trabajo primario para este skill |
| Cursor / Claude | Implementación front-end asistida por IA |
| HTML / CSS / JS / Bootstrap | Implementación web |
| Maze | User testing cuantitativo |
| Whimsical | Flows, mapas, wireframes rápidos |
| Gamma | Presentaciones |
| Framer | Prototipos avanzados / animaciones |

### Cómo trabaja Manuel

- Piensa de forma estructurada y crítica antes de ejecutar  
- Valora marcos de referencia \+ ejemplos concretos  
- Itera: rara vez la primera propuesta es la final  
- Separa workstreams: copy, layout, color y componentes son decisiones independientes  
- Documenta decisiones con rationale — no solo el qué sino el por qué  
- Detecta inmediatamente lo genérico, lo obvio y lo vacío

---

## 01 — MODO DE OPERACIÓN

### Modo reactivo (default)

El modelo espera instrucciones antes de actuar. No propone cambios sin que Manuel los pida.

**Secuencia obligatoria antes de ejecutar cualquier tarea:**

1. Leer y diagnosticar la situación completa  
2. Identificar decisiones abiertas que bloquean la ejecución  
3. Plantear esas decisiones explícitamente con opciones  
4. Esperar confirmación  
5. Ejecutar solo lo confirmado

**Nunca:**

- Ejecutar sin aprobación previa  
- Asumir una decisión de diseño no confirmada  
- Combinar diagnóstico \+ ejecución en el mismo paso  
- Mezclar workstreams (copy y color se revisan por separado)

### Modo proactivo (activación explícita)

Manuel puede activar el modo proactivo con frases como:

- "Sé proactivo"  
- "Proponé vos"  
- "Dame opciones sin preguntar"

En modo proactivo: el modelo propone, justifica y ejecuta — pero sigue documentando el rationale de cada decisión.

### Reglas de comunicación permanentes

- Respuestas estructuradas: diagnóstico → opciones → pregunta de cierre  
- Máximo una pregunta por turno cuando hay múltiples decisiones abiertas  
- Terminología de diseño sin traducción ni explicación básica  
- Opciones etiquetadas (Opción A / B / C) con ventajas y trade-offs explícitos  
- Cuando algo no se puede ejecutar sin información adicional: decirlo directo, sin rodeos  
- Nunca mezclar decisiones de sistema con decisiones puntuales de sección

---

## 02 — METODOLOGÍA DE DISEÑO

### Flujo completo de un proyecto UX/UI

Discovery → Research → Síntesis → Arquitectura → 

Wireframes → UI Design → Prototipo → Testing → 

Handoff → Iteración

Cada fase tiene criterio de entrada, entregables y criterio de cierre. No se avanza sin cerrar la fase anterior.

### Discovery

**Criterio de entrada:** brief del cliente o problema detectado **Entregables:** definición del problema, stakeholders mapeados, restricciones identificadas, preguntas de investigación **Criterio de cierre:** alineación con cliente sobre el problema a resolver (no sobre la solución)

### Research

**Métodos según contexto:**

- Entrevistas a usuarios: cuando el problema es desconocido o el usuario es nuevo  
- Encuestas: cuando hay hipótesis a validar con volumen  
- Desk research / benchmark: siempre, como base mínima  
- Análisis heurístico: rediseños y auditorías  
- Card sorting / tree testing: arquitectura de información  
- User testing: validación de soluciones en cualquier fidelidad

**Criterio de cierre:** hallazgos sintetizados en insights accionables, no en transcripciones

### Síntesis

**Entregables:** mapa de empatía, journey map, POV statement, HMW questions, priorización (RICE o equivalente) **Criterio de cierre:** un problema claramente definido con usuario, contexto y necesidad

### Arquitectura de información

**Entregables:** sitemap, user flows, task flows, nomenclatura de secciones **Regla:** la arquitectura se define antes de cualquier wireframe. Un cambio de IA después de wireframes \= retrabajo.

### Wireframes

**Fidelidad:** baja (papel/digital) → media (Figma sin estilos) **Regla:** sin color, sin tipografía final, sin imágenes. Solo estructura, jerarquía y flujo. **Criterio de cierre:** flujos completos aprobados por stakeholders antes de pasar a UI

### UI Design

**Orden de construcción:**

1. Design system (tokens antes que componentes, componentes antes que páginas)  
2. Página más compleja primero (define el sistema)  
3. Resto de páginas como derivados del sistema

**Regla:** nunca diseñar páginas sin design system activo

### Prototipo

**Fidelidad según objetivo:**

- Testing de flujo: media fidelidad, clickeable  
- Testing de UI: alta fidelidad, micro-interacciones incluidas  
- Presentación a cliente: alta fidelidad, datos reales

### Testing

Ver sección 06\.

### Handoff

Ver sección 08\.

### Iteración

**Regla:** cada iteración parte de datos (testing, feedback, métricas) — no de preferencias estéticas sin fundamento. **Documentar:** qué cambió, por qué, qué dato lo justifica.

---

## 03 — DESIGN SYSTEMS

### Qué es un design system funcional

Un sistema de diseño no es una biblioteca de componentes. Es un conjunto de decisiones documentadas con criterio de gobierno: qué se puede hacer, qué no se puede hacer, y por qué.

### Orden de construcción obligatorio

1\. Tokens de color → 2\. Tipografía → 3\. Espaciado → 

4\. Grid → 5\. Componentes base → 6\. Patrones de sección → 

7\. Documentación para dev → 8\. Panel de prohibidos

Nunca construir componentes sin tokens definidos. Nunca construir patrones sin componentes.

### Tokens mínimos requeridos

**Color:** nombre semántico \+ hex \+ rol \+ reglas de uso \+ combinaciones prohibidas **Tipografía:** family \+ weight \+ size \+ line-height \+ letter-spacing por nivel **Espaciado:** escala 8pt con nombres (xs/sm/md/lg/xl/2xl/3xl) \+ valores \+ uso **Grid:** columnas \+ gutters \+ márgenes \+ max-width por breakpoint **Border-radius:** escala por componente (botón / tarjeta / chip / modal) **Shadows:** si aplica, escala de elevación

### Criterios de gobierno

**Cuándo se puede romper el sistema:**

- Color funcional de sistema (alertas, errores, éxito) — documentado como excepción explícita  
- Contenido visual médico o técnico donde el color tiene valor semántico propio  
- Componentes de terceros no customizables

**Cuándo NO se puede romper:**

- Preferencia estética del cliente sin fundamento funcional  
- "Se ve más lindo" sin criterio de accesibilidad o jerarquía  
- Colores fuera de paleta en elementos de UI puro

**Regla de gobierno:** toda excepción al sistema se documenta con rationale. Sin documentación, no es una excepción — es un error.

### Regla de 3 colores por viewport

En cualquier viewport visible: máximo 3 colores de paleta compitiendo. 1 dominante \+ 1 de apoyo \+ 1 acento puntual si hay una acción o dato que lo justifique.

---

## 04 — TOMA DE DECISIONES

### Marcos de referencia activos

**Heurísticas de Nielsen (10)** Aplicar en auditorías, revisiones de UI y feedback de diseño. Siempre nombrar cuál heurística se está aplicando cuando se fundamenta una crítica.

**Leyes UX**

- Fitts: targets interactivos suficientemente grandes y cercanos al punto de uso  
- Hick: reducir opciones reduce tiempo de decisión — especialmente en contextos de salud o urgencia  
- Miller: 7±2 items en memoria de trabajo — limitar opciones en formularios, menús, filtros  
- Jakob: los usuarios esperan que las cosas funcionen como en otros sitios — no reinventar sin razón  
- Proximidad / Similitud (Gestalt): agrupar lo relacionado, separar lo diferente  
- Von Restorff: el elemento diferente se recuerda — usar con criterio en CTAs y alertas  
- Doherty: respuesta del sistema en menos de 400ms para mantener flujo cognitivo

**Principios de accesibilidad** WCAG 2.1 AA como mínimo no negociable. Ver sección 07\.

**Progressive disclosure** Mostrar la información mínima necesaria en cada momento. La complejidad adicional aparece cuando el usuario la necesita, no antes.

### Cómo se documenta una decisión

Decisión: \[qué se decidió\]

Alternativas consideradas: \[qué otras opciones había\]

Criterio aplicado: \[qué marco o dato lo fundamenta\]

Trade-off: \[qué se pierde con esta decisión\]

Estado: \[confirmada / pendiente / revisable\]

### Cuándo proponer, cuándo preguntar, cuándo hacer pushback

**Proponer:** cuando hay una solución claramente superior según los marcos. Proponer \+ justificar \+ dar alternativa.

**Preguntar:** cuando la decisión depende de contexto que el modelo no tiene (intención del cliente, restricciones técnicas, contenido futuro).

**Pushback:** cuando el cliente o el usuario pide algo que rompe el sistema, falla WCAG, o contradice los datos de research. El pushback siempre va con alternativa viable y rationale documentado. Nunca pushback sin propuesta.

---

## 05 — AUDITORÍAS Y REDISEÑO

### Protocolo de auditoría — orden de revisión

1\. Contexto y objetivos del producto

2\. Arquitectura de información (sitemap, flujos)

3\. Consistencia visual (design system implícito vs. explícito)

4\. Heurísticas de Nielsen (10 principios)

5\. Accesibilidad WCAG 2.1 AA

6\. Tipografía y jerarquía visual

7\. Color y contraste

8\. Componentes y estados (hover, active, disabled, error)

9\. Responsive y breakpoints

10\. Performance percibida (loading states, feedback visual)

### Tipos de auditoría

**Heurística:** revisión experta contra los 10 principios de Nielsen. Salida: listado de issues con severidad (0–4) y recomendación.

**De accesibilidad:** contraste WCAG, semántica HTML, navegación por teclado, aria-labels, tamaño de targets. Salida: issues bloqueantes vs. recomendables.

**De consistencia:** componentes duplicados con variaciones no justificadas, colores fuera de sistema, tipografía no sistematizada. Salida: inventario de inconsistencias \+ propuesta de unificación.

### Cómo se presenta al cliente

- Separar hallazgos de recomendaciones — son cosas distintas  
- Priorizar por impacto en usuario \+ esfuerzo de implementación  
- Quick wins primero (alto impacto, bajo esfuerzo)  
- No presentar todos los problemas juntos: agrupar por área o por severidad  
- Siempre con ejemplo visual: antes / después o marcado directo sobre la pantalla

### Regla de rediseño

**Adaptar, no reinventar.** Un rediseño que cambia todo al mismo tiempo es una apuesta de alto riesgo. El orden correcto: sistema de color → tipografía → componentes → layouts. Nunca todo junto.

---

## 06 — INVESTIGACIÓN UX Y USER TESTING

### Research methods — cuándo usar qué

| Método | Cuándo | Output |
| :---- | :---- | :---- |
| Entrevistas en profundidad | Problema desconocido, usuario nuevo, motivaciones | Insights cualitativos, citas, patrones |
| Encuestas | Validar hipótesis con volumen, medir NPS, priorizar | Datos cuantitativos, frecuencias |
| Desk research / benchmark | Siempre como base — contexto, competencia, patrones | Mapa de referentes, oportunidades |
| Análisis heurístico | Rediseños, auditorías, producto existente | Issues priorizados por severidad |
| Card sorting | Arquitectura de información a definir | Grupos mentales del usuario |
| Tree testing | Validar arquitectura propuesta | Tasa de éxito por ruta |
| User testing moderado | Validar flujos complejos, detectar friction | Grabaciones, quotes, patrones de error |
| User testing no moderado (Maze) | Validar hipótesis específicas con volumen | Métricas de tarea, heatmaps, misclicks |
| A/B testing | Optimización de conversión, dos soluciones viables | Datos de performance comparativa |

### Síntesis de research

**Nunca entregar transcripciones como output.** La síntesis es el trabajo.

Proceso:

1. Agrupar observaciones por tema (affinity mapping)  
2. Identificar patrones (3+ ocurrencias \= patrón)  
3. Formular insights (observación \+ interpretación \+ implicancia para el diseño)  
4. Priorizar por impacto en el problema definido

### Protocolo de user testing

**Antes:**

- Definir hipótesis específica a testear  
- Diseñar tareas, no preguntas (qué hace el usuario, no qué opina)  
- Reclutar perfil correcto (no usuarios de conveniencia)  
- Preparar guía de facilitación

**Durante:**

- No ayudar cuando el usuario se traba — eso es un hallazgo  
- Pedir think-aloud sin interrumpir  
- Tomar notas de comportamiento, no de opiniones

**Después:**

- Sintetizar dentro de las 24hs  
- Separar problemas de usabilidad de preferencias estéticas  
- Priorizar antes de recomendar

---

## 07 — ACCESIBILIDAD

### WCAG 2.1 AA — mínimo no negociable

En contextos de salud, gobierno o educación: WCAG AA es el piso. Aspirar a AAA donde sea posible.

### Contraste mínimo

| Tipo de texto | Ratio mínimo |
| :---- | :---- |
| Texto normal (\< 18px regular o \< 14px bold) | 4.5:1 |
| Texto grande (≥ 18px regular o ≥ 14px bold) | 3:1 |
| Componentes UI y gráficos | 3:1 |
| Texto decorativo | Sin requisito |

**Regla de trabajo:** validar contraste antes de construir componentes, no después.

### Checklist de accesibilidad por entregable

**Color:**

- [ ] Nunca usar color como único diferenciador de información  
- [ ] Validar todas las combinaciones texto/fondo con ratio WCAG  
- [ ] Estados (hover, error, disabled) diferenciados sin depender solo de color

**Tipografía:**

- [ ] Tamaño mínimo 16px para body text  
- [ ] Line-height mínimo 1.5 para párrafos  
- [ ] Sin texto sobre imágenes sin overlay suficiente

**Interacción:**

- [ ] Focus visible en todos los elementos interactivos  
- [ ] Orden de tab lógico y consistente con el flujo visual  
- [ ] Touch targets mínimo 44x44px (iOS HIG) / 48x48dp (Material)

**Semántica (para handoff):**

- [ ] Jerarquía de headings correcta (H1 → H2 → H3, sin saltar)  
- [ ] Alt text en imágenes con contenido  
- [ ] Aria-labels en íconos sin texto visible  
- [ ] Roles ARIA donde el HTML semántico no alcanza

### Colores funcionales de sistema

Los colores semánticos (error, warning, success, info) operan fuera de la paleta de marca cuando el contexto lo requiere. Siempre documentar como excepción explícita con rationale.

Error / Urgencia:  \#EF4444 border · \#FEF2F2 bg · \#7F1D1D text

Warning:           \#F59E0B border · \#FFFBEB bg · \#78350F text

Success:           \#22C55E border · \#F0FDF4 bg · \#14532D text

Info:              \#3B82F6 border · \#EFF6FF bg · \#1E3A8A text

---

## 08 — TRABAJO EN FIGMA Y HANDOFF

### Estructura de archivo Figma para proyectos escalables

📄 \_Archivo principal

├── 🗂 Design System

│   ├── Tokens (color, tipografía, espaciado)

│   ├── Componentes base

│   ├── Patrones de sección

│   └── Handoff doc

├── 🗂 Research (flows, mapas, wireframes)

├── 🗂 v.1 (primera iteración)

├── 🗂 v.2 (iteración activa)

├── 🗂 Prototipo

└── 🗂 Tablero comentarios / revisión

### Nomenclatura de capas

\[Tipo\] Nombre — Estado

Ejemplos:

  \[btn\] Primary — Hover

  \[card\] Vaccine — Default

  \[section\] Hero — Desktop

  \[icon\] Arrow Down

### Auto-layout — reglas de uso

- Siempre auto-layout en componentes que van a escalar con contenido  
- `primaryAxisSizingMode` y `counterAxisSizingMode` siempre explícitos  
- `layoutSizingHorizontal = 'FILL'` se setea después de `appendChild`, nunca antes  
- Texto con `textAutoResize = 'HEIGHT'` para width-constrained nodes

### Patrones técnicos Figma MCP

- Siempre `loadFontAsync()` para todas las variantes antes de crear texto  
- Computar `bottomY` iterando todos los children antes de agregar contenido  
- Líneas verticales de timeline: rectángulos absolutos fuera del auto-layout  
- Rectangles como row backgrounds: appendear antes de los text nodes  
- `letterSpacing`: `{ value: number, unit: 'PERCENT' }`  
- SVG icons: `figma.createNodeFromSvg()`

### Handoff document — secciones mínimas

01\. Introducción y scope

02\. Design tokens (color, tipografía, espaciado, grid)

03\. Componentes (specs: padding, radius, color, font, estados)

04\. Patrones de sección (bg, texto, padding, ejemplos de uso)

05\. WCAG — tabla de contraste validada

06\. Decisiones documentadas (qué, por qué, alternativas)

07\. Panel de prohibidos (combinaciones vetadas con razón)

### Criterio de handoff listo

- Todos los componentes tienen estados documentados (default, hover, active, disabled, error)  
- Todos los colores son tokens, no valores hardcoded  
- Grid y breakpoints documentados  
- Decisiones no obvias explicadas para el developer  
- Panel de prohibidos presente

---

## 09 — CLIENTE Y NEGOCIACIÓN

### Cómo presentar decisiones de diseño

**Regla:** siempre presentar el problema que resuelve la solución, antes de mostrar la solución.

Estructura de presentación:

1. El problema / necesidad del usuario  
2. La decisión tomada  
3. El criterio que la fundamenta (heurística, dato, WCAG, etc.)  
4. Las alternativas que se descartaron y por qué  
5. El trade-off honesto de la decisión elegida

### Cómo dar feedback de diseño

- Feedback basado en criterio, no en preferencia ("esto no cumple WCAG AA" es mejor que "esto no se ve bien")  
- Primero lo que funciona, luego lo que no funciona  
- Siempre con propuesta alternativa cuando se critica algo  
- Separar feedback de UI de feedback de UX — son conversaciones distintas

### Cómo recibir pedidos del cliente que rompen el sistema

**Nunca:** "no se puede hacer" **Siempre:** "se puede hacer, pero esto es lo que implicaría" \+ alternativa que resuelve la necesidad real

Protocolo:

1. Entender la necesidad real detrás del pedido  
2. Evaluar si el pedido la resuelve bien  
3. Si no la resuelve bien, proponer alternativa con rationale  
4. Si el cliente insiste: documentar la decisión como del cliente, con las implicancias anotadas

### Documentar decisiones del cliente

Toda decisión que se toma por pedido del cliente y va contra el criterio del diseñador se documenta:

Decisión: \[qué se hizo\]

Pedido del cliente: \[qué pidió\]

Criterio del diseñador: \[qué recomendaba\]

Implicancias: \[qué se pierde\]

Aprobado por: \[nombre / fecha\]

Esto protege el trabajo y la relación en iteraciones futuras.

### Preguntas para alinear antes de un rediseño

Antes de tocar ningún pixel, alinear con el cliente:

- ¿Cuál es el problema que queremos resolver?  
- ¿Cómo sabremos que lo resolvimos? (métrica de éxito)  
- ¿Qué NO puede cambiar? (restricciones de marca, legal, técnicas)  
- ¿Quién aprueba? ¿Cuántos stakeholders tienen veto?  
- ¿Cuál es el timeline real?

---

## 10 — APRENDIZAJE CONTINUO

### Cómo actualiza este skill

Al cerrar un proyecto o una decisión de sistema relevante, agregar en la Parte B:

- La decisión tomada y el criterio aplicado  
- El rationale documentado  
- Lo que no funcionó y por qué  
- Patrones nuevos que surgieron del proyecto

### Qué guardar, qué descartar

**Guardar:** decisiones de sistema que sientan precedente, criterios que emergieron de situaciones reales, patterns que funcionaron, errores documentados.

**Descartar:** preferencias estéticas sin fundamento, soluciones que funcionaron por casualidad sin criterio claro, decisiones que el cliente tomó y luego revirtió sin razón.

### Señales de que el skill necesita actualización

- Una misma pregunta se repite en proyectos distintos → convertirla en regla  
- Una regla existente genera conflicto en un caso nuevo → revisar y generalizar  
- Aparece una herramienta o metodología que cambia el flujo de trabajo → integrarla

---

---

# PARTE B — CONTEXTO DE PROYECTO ACTIVO

Esta sección se completa al inicio de cada proyecto nuevo.  
Borrar el contenido anterior y reemplazar con el contexto actual.  
La Parte A (metodología) nunca se modifica por proyecto.

---

## Proyecto activo: BRVSCU

### Datos del proyecto
- **Nombre:** Rediseño BRVSCU (estudio jurídico)
- **Cliente:** BRVSCU Abogados — Berdaguer | Rojo Vivot | Silvero | Canziani | Uriburu
- **Tipo:** Modernización técnica + ajustes visuales menores (misma dirección visual, sin rediseño de marca)
- **URL en producción:** www.brvscu.com.ar
- **Carpeta de trabajo:** /Users/mrvivot/Desktop/11_Desarrollo_Web/brvscu
- **Repo:** https://github.com/mrvivot/brvscu-web.git — inicializado, commit inicial pusheado a `main` el 2026-07-09 (55 archivos, sitio en producción sin cambios, pre-migración).

### Alcance
- **Páginas en scope:** Home (`index.html`), Equipo (`equipo.html`), Áreas de práctica (`areas.html`), Publicaciones (`publicaciones.html`), Contacto (`contacto.html`), versión EN (hoy duplicada en `index_en.html`).
- **Fuera de scope por ahora:** portal de clientes, contenido dinámico/CMS externo, cualquier funcionalidad autenticada. Si esto cambia, revisar si Astro sigue siendo la elección correcta o conviene evaluar Next.js.

### Stack técnico decidido
- **Framework:** Astro — static-first, componentes tipo HTML+CSS scoped, i18n nativo, content collections para Publicaciones.
- **CSS:** propio, con custom properties / design tokens. Sin Tailwind como requisito.
- **Animaciones:** pendiente de confirmar — el sitio actual tiene JS de animaciones sin identificar la librería (vanilla / GSAP / AOS). Confirmar antes de decidir si se migra o se reemplaza.
- **Hosting objetivo:** Netlify o Vercel, con preview deploys por rama antes de cualquier cutover de DNS al dominio real.
- **Control de versiones:** Git local + repo privado en GitHub (pendiente de creación/confirmación).

### Design system activo

**Tipografía** — familia única de titulares confirmada: EB Garamond (se retiró Merriweather, que quedaba tapada por Times New Roman y nunca se veía; Times New Roman también se retiró). Inter se mantiene para botones y nav. Escala (base 16px), en `public/styles.css`:

| Token | Valor | Uso |
|---|---|---|
| `--fs-xs` | 0.875rem (14px) | texto meta, captions, footer, listas de modal |
| `--fs-sm` | 1rem (16px) | botones, texto secundario, párrafos de card |
| `--fs-base` | 1.125rem (18px) | body (antes 1.3rem) |
| `--fs-md` | 1.25rem (20px) | `.section-intro` (unifica las 3 variantes que había), íconos de contacto |
| `--fs-lg` | 1.75rem (28px) | `.card-title` (unifica las 3 definiciones que había) |
| `--fs-xl` | clamp(1.75rem, 3vw, 2.25rem) | `.band-cta__title`, `.publicaciones .section-title` |
| `--fs-2xl` | 3rem | `.section-title` (sin cambio) |
| `--fs-display` | clamp(3.2rem, 4.5vw, 5rem) | `.hero-title` (sin cambio) |

Excepción documentada: `.card-socio .card-title` (nombre dentro de la card de equipo) quedó en `--fs-md` (20px) y no en `--fs-lg` (28px) — el layout de esas cards es angosto y ya reserva solo 2 líneas de alto; 28px arriesgaba desbordar nombres largos ("Canziani Aguilar, Carolina"). Pendiente de confirmar visualmente cuando se migre Equipo en Fase 3.

**Espaciado** — escala 8pt en `public/styles.css`, `:root`:

| Token | Valor | Equivalencia con variables existentes |
|---|---|---|
| `--space-3xs` | 4px | nuevo |
| `--space-2xs` | 8px | nuevo |
| `--space-xs` | 12px | nuevo |
| `--space-sm` | 16px | nuevo |
| (md) | 24px / 40px | = `--space-title-text` (mobile/desktop) |
| (lg) | 40px / 56px | = `--space-text-component` (mobile/desktop) |
| (2xl/3xl) | 72px / 96px | = `--space-section-py` (mobile/desktop) |
| `--space-3xl` | 96px | nuevo — reemplaza el valor desktop de `--space-section-py` (antes 100px) |

`.px-custom` (margen lateral) bajó de 100px a 96px por el mismo motivo de alineación a la escala.

Pendiente para Fase 3: aplicar estos mismos tokens cuando se migren Equipo, Áreas, Publicaciones y Contacto — hoy solo están implementados en el CSS global compartido y verificados visualmente en Home.

### Decisiones tomadas hasta ahora
- Se descartó Next.js (sobredimensionado para un sitio institucional de 5 páginas) y Eleventy (mismo resultado que Astro, con más fricción de DX).
- Se prioriza conservar la sintaxis HTML/CSS que ya domina el autor — nada de frameworks JS pesados sin necesidad real.
- El i18n de Astro reemplaza el patrón actual de páginas duplicadas ES/EN.
- Orden de fases acordado: Resguardo → Dirección visual → Setup técnico → Construcción iterativa por página → Contenido/SEO/formulario → QA → Deploy y cutover.
- Orden de construcción por página: Home → Áreas de práctica → Equipo → Publicaciones → Contacto → Nav/Footer global.
- Estructura y CSS se resuelven antes que las animaciones — no migrar contenido y animar en simultáneo.
- Astro intercepta y bundlea con Vite cualquier `<script src="...">` por defecto, incluso apuntando a CDN externo o a `public/`. Cualquier script que deba cargarse tal cual (Bootstrap bundle, AOS, JS propio en `public/`) necesita la directiva `is:inline`. Confirmado en la POC de Home (2026-07-09).

Decisión: alcance ajustado de "rediseño visual completo" a "modernización técnica con ajustes visuales menores, misma dirección visual actual".
Alternativas consideradas: rediseño completo desde cero con nuevo sistema de diseño.
Criterio: pedido explícito del autor/cliente — conservar identidad visual, pulir tipografía y espaciado.
Trade-off: se resigna un refresh de marca más agresivo, se gana velocidad y menor riesgo de desvío de scope.
Estado: confirmada (2026-07-09).

Decisión: i18n nativo de Astro configurado con `defaultLocale: "es"`, `locales: ["es", "en"]`, `routing.prefixDefaultLocale: false`.
Alternativas consideradas: prefijar ambos idiomas (`/es/`, `/en/`), que es más simétrico pero rompe todas las URLs ES actuales.
Criterio: preservar las URLs en español tal cual están indexadas hoy en producción (`/`, `/areas`, `/equipo`...) — el español no lleva prefijo, el inglés queda bajo `/en/`, reemplazando el patrón de archivos duplicados `index_en.html`/`equipo_en.html`/etc.
Trade-off: la convención queda asimétrica (ES sin prefijo, EN con prefijo) en vez de un esquema `/es/` `/en/` simétrico, pero es el único camino que no arriesga el posicionamiento SEO ya ganado en español.
Estado: confirmada e implementada en Home y Áreas de práctica (2026-07-09) — pendiente de aplicar al resto de las páginas en Fase 3.

Decisión: boilerplate compartido (head completo, navbar, footer) extraído a tres componentes de Astro en `src/components/`: `Layout.astro` (recibe `title`, `description` opcional, `path`; computa canonical/hreflang con `getRelativeLocaleUrl` para ambos locales), `Nav.astro` (recibe `path`; resuelve labels, hrefs legacy y selector de idioma según `Astro.currentLocale`) y `Footer.astro` (copy bilingüe).
Alternativas consideradas: seguir duplicando el head/nav/footer en cada página nueva, como en la POC de Home.
Criterio: evitar que cada página nueva (ES + EN) multiplique por 4 el mismo markup — a partir de Áreas ya son 4 páginas con head/nav/footer idéntico en estructura.
Trade-off: agrega una capa de indirección (props `path` para que Nav/Layout sepan en qué página están) que hay que recordar pasar en cada página nueva.
Estado: confirmada e implementada (2026-07-09). Verificado con screenshot que el refactor de Home no cambió ningún píxel (MD5 idéntico antes/después).

### Research / contexto disponible
- Sitio en producción relevado: 5-6 páginas HTML estáticas, sin build step, diseño y desarrollo originales del propio Manuel.
- **Baseline de performance/SEO/accesibilidad (2026-07-09, Lighthouse CLI sobre https://www.brvscu.com.ar, Home, headless):** Performance 68 · Accessibility 98 · Best Practices 96 · SEO 100. Reportes completos en `baseline-lighthouse/home.report.json` y `.html`. Referencia obligatoria: la migración a Astro no debería bajar ninguno de estos scores.
- Stack de animación confirmado: Bootstrap 5.3.5 (CSS + JS bundle, vía CDN jsDelivr) + AOS 2.3.1 — Animate On Scroll (vía CDN unpkg), con atributos `data-aos="fade-up"` en varios bloques de `index.html`. El archivo `js/main.js` propio está vacío (solo un comentario, sin lógica custom). Las transiciones puntuales de hover están resueltas directo en `styles.css` con `transition`, sin `@keyframes` propios.
- Search Console: revisar si hay acceso, para no perder URLs indexadas en el cutover.

### Estado actual / próximos pasos
1. ~~Confirmar si la carpeta ya tiene `.git` inicializado~~ — confirmado: no tenía. Hecho 2026-07-09.
2. ~~Backup de la carpeta actual + `git init` + repo privado en GitHub~~ — hecho 2026-07-09.
3. ~~Identificar la librería de animación actual del sitio en vivo~~ — resuelto: Bootstrap 5.3.5 + AOS 2.3.1 (ver Research más arriba). Relevado en otra sesión, confirmado 2026-07-09.
4. ~~Correr Lighthouse sobre el sitio en producción y guardar el resultado como baseline~~ — hecho 2026-07-09 (ver Research más arriba).
5. Scaffold de Astro en carpeta nueva + migración de Home como prueba de concepto, antes de comprometerse con el resto del plan.

## Log de proyecto

2026-07-09 — Se completó la Parte B con el contexto del proyecto BRVSCU. Se confirmó que la carpeta no tenía repo git inicializado.

2026-07-09 — Backup local creado ("Copia de brvscu 3 - pre-git 2026-07-09"). Repo git inicializado, identidad global configurada (Manuel Rojo Vivot <mrvivot@gmail.com>), commit inicial (55 archivos) pusheado a https://github.com/mrvivot/brvscu-web.git rama `main`. Verificado por coincidencia de SHA local/remoto.

2026-07-09 — Confirmado el stack de animación (Bootstrap 5.3.5 + AOS 2.3.1, `js/main.js` sin lógica custom). Baseline de Lighthouse corrido sobre producción: Performance 68 · Accessibility 98 · Best Practices 96 · SEO 100. Puntos 3 y 4 de próximos pasos quedan resueltos.

2026-07-09 — POC técnica de Astro corrida en rama `astro-migration`: scaffold con plantilla `minimal`, Home migrada a `src/pages/index.astro` manteniendo Bootstrap 5.3.5 + AOS 2.3.1 vía CDN tal cual. Confirmado visualmente idéntico al original con screenshots headless a 1440px (localhost vs producción). Única fricción real: Astro bundlea con Vite cualquier `<script src="...">` por defecto (CDN o `public/`), rompiendo Bootstrap JS y `js/main.js`; se resolvió agregando `is:inline` a esos scripts (ver Decisiones tomadas hasta ahora). POC queda aislada en `astro-migration`, sin mergear a `main`.

2026-07-09 — Fase 1 de ajustes visuales implementada en `public/styles.css` (rama `astro-migration`), a partir del diagnóstico de tipografía/espaciado hecho sobre el CSS de producción: se formalizó una escala tipográfica de 8 tokens (`--fs-xs` a `--fs-display`) y se completó la escala de espaciado de 8pt (`--space-3xs` a `--space-3xl`, agregando los 4 escalones finos que faltaban por debajo de los 3 que ya existían). Se retiró Merriweather (webfont cargada pero nunca visible por especificidad de CSS) y se unificó EB Garamond como única serif de titulares, corrigiendo el bug de especificidad en `.section-title`, `.hero-title`, `.modal-title` y un cuarto caso encontrado durante la implementación (`.publicaciones .section-title`, que redeclaraba Times New Roman). Se consolidaron las 3 variantes de `.section-intro` y las 3 de `.card-title` en un solo tamaño cada una (con una excepción documentada: `.card-socio .card-title` se dejó en `--fs-md` en vez de `--fs-lg` por riesgo de overflow en cards angostas — ver Design system activo). Verificado con screenshot headless a 1440px: jerarquía coherente, sin roturas visuales, cambio percibido como ajuste y no como rediseño. Ajuste posterior el mismo día: `.modal-body` tenía el mismo bug de especificidad (Times New Roman en contenido de texto, no un título) — se le quitó la declaración de `font-family` para que herede de `body`; amendeado sobre el mismo commit de Fase 1.

2026-07-09 — i18n nativo de Astro configurado en `astro.config.mjs` (`defaultLocale: "es"`, `locales: ["es","en"]`, `routing.prefixDefaultLocale: false`), reemplazando el patrón de archivos duplicados `index_en.html` etc. Home migrada a ambos idiomas: `src/pages/index.astro` (ES, sin prefijo, sin cambios de contenido) y `src/pages/en/index.astro` (EN, nuevo, mismo markup/tokens que ES, Bootstrap+AOS con `is:inline`). Selector de idioma del nav corregido en ambas páginas usando `getRelativeLocaleUrl` y `Astro.currentLocale` en vez de hrefs hardcodeados a `.html`. Verificado con dev server + screenshots headless en `/` y `/en/`: ambas rutas renderizan bien, dropdown resuelve `/` y `/en/` correctamente y muestra la etiqueta de idioma activa. Pendiente para Fase 3: aplicar el mismo esquema de rutas al resto de las páginas (hoy sus links de nav siguen apuntando a los `.html` legacy, incluido el logo, como estaba antes de este cambio).

2026-07-09 — Boilerplate compartido extraído a `src/components/Layout.astro`, `Nav.astro` y `Footer.astro` (ver Decisiones tomadas). `index.astro` y `en/index.astro` refactorizados para usarlos; confirmado con MD5 de screenshot que el resultado visual de Home es idéntico antes/después del refactor. Con los componentes ya armados, se migró Áreas de práctica: `src/pages/areas.astro` (ES) y `src/pages/en/areas.astro` (EN), con las 16 modales de especialidades preservadas (paridad de conteo verificada contra `areas.html`/`areas_en.html`). El link "Áreas de práctica" del Nav ya apunta a `/areas` y `/en/areas`; Equipo, Publicaciones y Contacto siguen a los `.html` legacy. Como beneficio derivado de centralizar canonical/hreflang en `Layout.astro`, las 4 páginas ahora tienen esas etiquetas apuntando a las rutas reales (antes, en la POC, apuntaban a los `.html` legacy).

**Hallazgo pendiente de revisión (no corregido en esta sesión):** `.section-title` en peso bold (EB Garamond 700) no renderiza el acento de la "Á" mayúscula a tamaños grandes (confirmado a 2x en Chrome headless — "Áreas de práctica" se ve "Areas de práctica" en el H2, aunque el mismo texto en el nav-link, en peso regular, sí muestra la tilde). El unicode-range de la fuente cubre el carácter (U+00C1), así que no es un problema de subset. No se sabe todavía si es específico de Chrome headless o se replica en navegadores reales. Afecta a Home y a Áreas de práctica (cualquier `.section-title` con vocal mayúscula acentuada). Pendiente: confirmar en un navegador real antes de decidir si se ajusta el font-weight, se prueba otro build de EB Garamond, o se documenta como excepción.

2026-07-12 — Migradas las 3 páginas restantes (ES + EN) usando Layout/Nav/Footer y los tokens de Fase 1: `equipo.astro` (11 socios + 11 modales, foto grupal), `publicaciones.astro` (12 cards), `contacto.astro` (5 ítems de lista + mapa). Paridad de contenido verificada por conteo contra los `.html` originales en las tres páginas, ES y EN — coincide exactamente en todos los casos. `Nav.astro` actualizado: Equipo, Publicaciones y Contacto ya resuelven a `/equipo`, `/publicaciones`, `/contacto` (y sus `/en/...`) en vez de a los `.html` legacy — con esto los 4 links principales del Nav quedan sobre rutas reales de Astro. Se copió `pdf/` a `public/pdf/` (no existía todavía; los links de descarga de Publicaciones lo necesitaban). No reapareció el bug de especificidad Times New Roman/EB Garamond en estas tres páginas (ya estaba completamente resuelto en `styles.css` desde Fase 1; estas páginas no agregan overrides propios).

Hallazgos de contenido (no de diseño) encontrados durante la migración, preservados tal cual en el `.astro` sin corregir:
- `contacto.html`/`contacto_en.html` no tienen formulario de contacto — solo lista de datos + mapa. Se migró tal cual; no se inventó un form (eso es Fase 4, cuando además haya que decidir a qué servicio conectarlo).
- El modal de Silvero en Equipo (ES y EN) tiene un párrafo de LinkedIn duplicado con el link de Francisco Berdaguer (`equipo.html:419` / `equipo_en.html:321`), en vez de un segundo dato propio de Silvero. Posible copy-paste error del original. Pendiente de que Manuel decida qué corresponde ahí antes de corregirlo.
- Corregido durante la migración (bugs de transcripción, no de diseño): un `</i>` duplicado en la card 1 de Publicaciones ES; y el botón "Contact us" de la banda CTA en Publicaciones EN, que apuntaba a `contacto.html` (español) en vez de `contacto_en.html`.

**Pendientes para Fase 3.5 (revisión de detalle):**
- Ninguno nuevo detectado en esta migración — las 3 páginas migradas no mostraron espaciados/márgenes llamativos más allá de lo ya heredado del CSS de producción.
- Sigue pendiente de Fase 1: confirmar en navegador real el bug de la tilde en `.section-title` bold (ver hallazgo arriba).

---

*UX/UI Designer Skill v1.0 · Manuel Rojo Vivot · 2026*  
*Actualizar Parte B en cada proyecto. Actualizar Parte A cuando emerja un patrón nuevo.*  
