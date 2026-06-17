# CLAUDE.md — Contexto maestro del proyecto
### TP Integrador 2026 · "Consultoría de Marketing Digital" · Grupo 31 · Chevrolet

> **Este archivo es la fuente de verdad del proyecto.** Cualquier sesión —ya sea de **Claude Code**
> (lo carga automáticamente) o de **Cowork / Claude app** (leerlo primero al abrir la carpeta)— debe
> empezar por acá para tener continuidad. Si algo cambia de forma estructural, se actualiza este archivo.
> El **registro de avances día a día** (bitácora) vive en [`BRIEF_TP_Grupo31.md`](BRIEF_TP_Grupo31.md).
>
> _Última actualización: 17/06/2026._

---

## 0 · Cómo trabajamos (protocolo de continuidad CC ⇄ Cowork)

- **Una sola carpeta, dos herramientas.** Claude Code y Cowork operan sobre la misma carpeta del proyecto.
- **Antes de tocar nada:** leer este `CLAUDE.md` (contexto estable) + la sección *Bitácora* del `BRIEF`.
- **Al terminar una tanda de trabajo:** anotar qué se hizo en la *Bitácora* del `BRIEF` (lo más reciente arriba)
  y, si cambió el plan o el estado de una fase, actualizar la sección correspondiente de este archivo.
- **División de responsabilidades sugerida:**
  - *Claude Code* → tareas de archivos/datos/automatización: capturas, edición del HTML, exportar PDF,
    extracción de tokens de diseño, scripts.
  - *Cowork / Claude app* → tareas conversacionales y de diseño visual: redacción de secciones, generación
    de piezas/mockups, diseño de los esqueletos de app (calendario, app EV Care).
- **Regla de oro:** no duplicar archivos maestros. El HTML es **uno solo**; el contexto es **este archivo**;
  la bitácora es **el BRIEF**.

---

## 1 · Qué es este trabajo (identidad del proyecto)

- **Materia:** Marketing Digital Táctico y Operativo — Tecnicatura Universitaria en Comercio Electrónico y
  Marketing Digital (UTN). Año lectivo 2026.
- **Consigna:** actuar como **agencia/consultora independiente** y entregar una **Propuesta de Asesoramiento de
  Marketing Digital a 3 meses (90 días)** para una marca líder de movilidad eléctrica en Argentina, con el fin de
  ganar *market share*. (No es un examen teórico: es un caso real de mercado — "El Pitch de Cliente").
- **Asignación Grupo 31:** Grupos 23–34 = **Chevrolet (Spark EV)** · **Enfoque obligatorio: fidelización y
  servicio de posventa.**
- **Modelo real 2026:** el oficial de la consigna dice "Spark EV", pero el modelo que Chevrolet vende en
  Argentina es el **Spark EUV** (102 CV, 42 kWh, 360 km, ~ARS 35,7 M, garantía 3 años/100.000 km). En el trabajo
  mantenemos el nombre asignado "Spark EV" en la carátula y aclaramos en el cuerpo que el modelo real es el EUV.
- **Horizonte:** 3 meses. **Entrega:** **18/06/2026 hasta 23:59 hs** (⚠️ es inminente).
- **Docente:** Mario Olivetto *(a confirmar — ver Decisiones abiertas)*.
- **Autoría:** la consigna asigna Grupo 31 (6 integrantes en el aula); el trabajo se viene desarrollando como
  **individual (autor: Ariel Lescano)**. La carátula debe listar *solo a quienes participaron* → ver
  *Decisiones abiertas*.

### La gran idea (ángulo del trabajo) — "Chevrolet EV Care"
Insight central: en Argentina la mayor barrera para comprar un EV **no es el precio ni la autonomía**, sino la
**desconfianza en la posventa** (no hay red de talleres desarrollada y es condición para mantener la garantía).
Chevrolet es la **única marca tradicional** del lote con red instalada → convertimos esa debilidad del mercado en
nuestra ventaja. **No vendemos un auto, vendemos tranquilidad de largo plazo.** Cuatro pilares: (1) EV Experience
Centers, (2) entrega con capacitación (Onboarding EV), (3) posventa inteligente con agenda de service, (4) loop de
fidelización por "rating de uso" (gamificación + CRM).

---

## 2 · La consigna oficial (requisitos que NO se negocian)

**Fuente autoritativa:** `Trabajo Práctico Integrador 2026.pdf` y su transcripción
`Trabajo Práctico Integrador 2026 – Consultoría de Marketing Digital.md`.

### 2.1 · Los 5 pasos obligatorios (estructura de la propuesta)
1. **Análisis Situacional** — auditoría digital de la marca y su competencia · mercado/tendencias de uso ·
   benchmarking · FODA · objetivos.
2. **Estrategia Táctica** — canales · segmentación de audiencias · embudo de conversión.
3. **Plan Operativo** — calendario / Gantt · presupuesto.
4. **Plan de Contenidos** — propuesta creativa de piezas (Social Media · Influencers · Search).
5. **Presupuesto y KPI** — distribución de la inversión + métricas de éxito para el cliente.

### 2.2 · Requisitos formales
- **Carátula obligatoria:** institución (UTN), carrera/materia, año (2026), título del TP, número de grupo,
  marca/modelo asignado, **nombre y apellido de todos los que participaron**, nombre del docente.
- **Identificación interna:** marca y modelo, objetivo general (máx. 3 líneas), índice de secciones.
- **Formato del archivo:** PDF. Si es **interactivo/web → PDF explicativo + enlace funcional**. ← *es nuestro caso.*
- **Legibilidad:** secciones tituladas en orden lógico, tipografías y jerarquías consistentes, redacción formal sin
  errores, gráficos/tablas rotulados.
- **Evidencia visual obligatoria:** capturas de auditoría y benchmarking · esquema del embudo · calendario/Gantt
  legible · ejemplos visuales de piezas · tabla de presupuesto · tabla de KPI.
- **Extensión:** 12–25 páginas/diapositivas.
- **Nomenclatura del archivo:** `TP_Integrador_MarketingMTyO_Grupo31_Chevrolet.pdf`.
- **Entrega:** la hace un solo integrante; todos los que participaron figuran en la carátula.

### 2.3 · Rúbrica (10 criterios, 1 punto c/u)
Carátula completa · Análisis situacional completo · Coherencia objetivos–diagnóstico · Estrategia táctica ·
Plan operativo (Gantt) · Plan de contenidos visual · Presupuesto distribuido · KPI alineados · Consistencia
integral · Profesionalismo y creatividad. *(Criterios transversales del PDF: consistencia, creatividad —"ideas
disruptivas"—, profesionalismo —"están vendiendo una idea").*

### 2.4 · Unidad de IA (aplicarla visiblemente suma en creatividad)
El curso dedica varias slides a **IA aplicada al marketing**: generación/optimización/personalización de contenido,
**chatbot 24/7**, automatización (caso Spotify), optimización de pauta y anuncios dinámicos, keywords. Herramientas
citadas por la cátedra: **Clipdrop, Fliki.ai, Studio D-ID**, y el marco de *prompting* (Rol/objetivo · Requerimiento
· Atributo). → En la propuesta, el **chatbot "Chevy Asistente EV"** y la personalización por "rating de uso" son
nuestro uso concreto de IA; además, las piezas/mockups pueden generarse con IA y mencionarlo.

---

## 3 · Estado actual del proyecto (qué ya existe en la carpeta)

| Componente | Archivo / carpeta | Estado |
|---|---|---|
| **Presentación (entregable)** | `TP_Integrador_MarketingMTyO_Grupo31_Chevrolet.html` | ✅ Borrador integral con las 8 secciones. Falta: insertar capturas reales, piezas finales, exportar a PDF. |
| **Brief / bitácora** | `BRIEF_TP_Grupo31.md` | ✅ Documento de trabajo vivo (datos verificados, tracker, bitácora). |
| **Consigna oficial** | `Trabajo Práctico Integrador 2026.pdf` + `.md` | ✅ Referencia (no se edita). |
| **Evidencias de benchmarking** | `Evidencias/` (5 marcas × 8 categorías) | ✅ **56 capturas** recortadas (1920×864, sin barra de navegador) + `README.md` con datos. |
| **Originales full-screen** | `Evidencias_originales_fullscreen/` | ✅ Respaldo de las 56 capturas sin recortar (se puede borrar si no se necesita). |
| **Capturas viejas (Cowork previo)** | `01 - capturas evidencia redes/` | ⚠️ Material temprano y parcial (BYD, Jetour). **Reemplazado** por `Evidencias/`. Conservar o archivar. |

### 3.1 · Datos clave ya capturados (resumen — detalle en `Evidencias/README.md`)
| Marca | IG seg. | TikTok (likes) | YouTube (videos) | SimilarWeb |
|---|--:|--:|--:|--:|
| **Chevrolet** | 225 K | 210,8 K (1,5 M) | 113 K (256) | 745,8 K/mes · Arg #918 |
| **BAIC** | **285 K** | 9.107 (33,6 K) | 1,76 K (41) | ~48,6 K/mes · Arg #7.816 |
| **BYD** | 19 K | 29,9 K (144,3 K) | 389 (18) | 9,4 M/mes (dominio global) |
| **Jetour** | 14,7 K | 400 (1.364) | 60 (34) | ~31 K/mes · Arg #14.837 |
| **JMEV** | 9.132 | 1.124 (14,4 K) | 19 (33) | ~8 K/mes · Arg #34.958 |

**Hallazgos para el ángulo EV Care:** Chevrolet lidera la huella madura (TikTok/YouTube/tráfico web 100% argentino);
**BAIC sorprende en Instagram (285 K, supera a Chevrolet)** → vigilar en FODA; Jetour/JMEV con huella incipiente →
su barrera es confianza + posventa (ventaja Chevrolet); en Google Maps, la ficha de Car One (Chevrolet) muestra chips
de reseñas "estafadores (23)/desastre (22)" → **evidencia de que la posventa es el campo de batalla real**.

---

## 4 · El entregable y el flujo de exportación

- **Qué se entrega:** **un PDF** (12–25 pág.) que funciona como *informe explicativo* **+ el enlace funcional a la
  presentación HTML**. El HTML es la pieza "interactiva/web"; el PDF la acompaña según pide la consigna.
- **Cómo se genera el PDF:** abrir el HTML en el navegador → *Imprimir* → *Guardar como PDF* (el `@media print` del
  HTML ya oculta el `nav` y limpia sombras/márgenes). Nombre de salida: `TP_Integrador_MarketingMTyO_Grupo31_Chevrolet.pdf`.
- **Enlace funcional:** para el "link a la presentación" se puede publicar el HTML (p. ej. GitHub Pages / Netlify /
  un hosting simple) y poner esa URL en la portada del PDF. *(Decisión pendiente: dónde se hostea.)*
- **Antes de exportar:** quitar/duplicar la sección `#interno` ("Anexo de trabajo · NO forma parte de la entrega") —
  no debe ir en el PDF final. Verificar que la extensión quede dentro de 12–25 páginas.

---

## 5 · Sistema de diseño (tokens actuales del HTML) — base para "cloud design"

> Esto es lo que el usuario quiere **extraer** más adelante para trabajar el diseño de las piezas y los esqueletos de
> app en herramientas de diseño asistido por IA ("cloud design" / frontend-design). Acá queda documentado para no
> tener que volver a leer el CSS.

### 5.1 · Paleta (CSS variables, en `:root` del HTML)
| Token | HEX | Uso |
|---|---|---|
| `--gold` | `#C9A227` | **Color de marca primario** (dorado Chevrolet) — acentos, números de sección, totales |
| `--gold-soft` | `#E7CE7A` | dorado suave (degradés, bordes) |
| `--ink` | `#0E0E0E` | negro principal (texto, headers de tabla, portada) |
| `--ink-soft` | `#2b2b2b` | gris muy oscuro (texto secundario) |
| `--ev` | `#19A974` | **verde "eléctrico"** — acento EV / posventa / éxito |
| `--ev-soft` | `#D8F3E7` | verde pálido (notas, pills) |
| `--blue` | `#1f6fbf` | azul secundario (Search, barras Gantt) |
| violeta Gantt | `#8a5cc4` | etapa "conversión" |
| `--paper` `#ffffff` · `--bg` `#f6f6f4` · `--line` `#e4e4e4` · `--mute` `#6b6b6b` | neutros (fondo, líneas, texto apagado) |

### 5.2 · Tipografía
- **Actual:** stack del sistema (`-apple-system, "Segoe UI", Roboto, Helvetica, Arial`). Base 16px, line-height 1.6.
- **Para versión "profesional":** conviene migrar a una pareja con personalidad (p. ej. un display geométrico para
  títulos + una sans neutra para texto). *Decidir y aplicar en la fase de diseño.*

### 5.3 · Componentes ya definidos en el HTML (reutilizables)
`nav` sticky · `section` tipo card · `card.kpi` (números grandes) · tablas con header oscuro · grilla **FODA** (2×2) ·
**embudo/funnel** de 4 niveles (TOFU/MOFU/BOFU + Loyalty Loop) · **Gantt** de 12 semanas · `steps` numerados (los 4
pilares) · `pill` / `note` / `warn` · `placeholder` (marcos punteados dorados para piezas pendientes).

### 5.4 · Logo
Hay un **SVG inline** en la portada: moño (bowtie) estilo Chevrolet en `--gold` + rayo EV en `--ev`. Reutilizable
como marca del proyecto en piezas y apps.

---

## 6 · Roadmap de implementación (fases)

### Fase A — Completar la información del informe *(prioridad por la entrega 18/06)*
- [x] Confirmar **Decisiones abiertas** (§8): autoría grupo/individual, docente, presupuesto, hosting del link.
- [x] Completar celdas faltantes del benchmarking: garantía BAIC y Jetour; unidades patentadas JMEV/Jetour/BAIC
      (ACARA/ADEFA).
- [ ] Validar metas numéricas (900 leads, 60 ventas, CPL) anclándolas a un % del mercado real.

### Fase B — Integrar las evidencias visuales en la presentación *(ver mapa en §7)*
- [x] Reemplazar los 2 `placeholder` "📸 Capa MARCA / 📸 Capa MODELO" de la sección 1.3 por capturas reales.
- [x] Insertar capturas de benchmarking (auditoría) con su rótulo (capa + fuente) — criterio 2 de la rúbrica.

### Fase C — Diseño profesional + esqueletos de app y mockups *(lo que el usuario llama "cloud design")*
- [ ] **Extraer** el sistema de diseño (§5) a un archivo de tokens reutilizable (p. ej. `design/tokens.css` o un
      `design/DESIGN.md`) para alimentar las herramientas de diseño.
- [ ] Diseñar los **esqueletos (skeletons) de aplicación**:
  - [ ] **App / micrositio de Calendario de service** (agenda automática por cronograma de fábrica).
  - [ ] **App "EV Care" / "ID Care"** (onboarding + agenda + "rating de uso" + reportes) — el corazón del ángulo.
  - [ ] Resto de **mockups de piezas** (Reel "Mito vs Realidad", post posventa, search ad, carrusel) que hoy son
        SVG placeholder en la sección 7 → reemplazar por piezas finales.
- [ ] Aplicar tipografía/diseño "premium" al HTML manteniendo la paleta.

### Fase D — Cierre y exportación
- [ ] Quitar la sección `#interno` del HTML para el PDF.
- [ ] Verificar extensión 12–25 págs. y coherencia integral (cadena Diagnóstico→Objetivos→Tácticas→Presupuesto→KPI).
- [ ] Exportar PDF + publicar HTML + poner el link en la portada del PDF.

---

## 7 · Mapa: dónde va cada captura/evidencia dentro de la presentación

Las 56 capturas de `Evidencias/` alimentan principalmente la **Sección 1 (Análisis Situacional)** del HTML.
Estructura de carpetas por marca: `01_Web · 02_Modelo · 03_Instagram · 04_TikTok · 05_YouTube · 06_Google_Search ·
07_Google_Maps · 08_Similarweb`.

| Captura (categoría) | Capa | Sección del HTML donde va |
|---|---|---|
| `01_Web` (web oficial marca) | 🏛️ MARCA | 1.3 / 1.4 — auditoría de marca (placeholder "Capa MARCA") |
| `03_Instagram`, `04_TikTok`, `05_YouTube` | 🏛️ MARCA | 1.4 — respaldan la tabla de seguidores/comunidad |
| `08_Similarweb` (tráfico) | 🏛️ MARCA | 1.4 — tráfico del sitio corporativo |
| `07_Google_Maps` (reseñas concesionario) | 🏛️ MARCA | 1.4 / FODA — evidencia de posventa (estrellas + reseñas) |
| `02_Modelo` (web del modelo) | 🚗 MODELO | 1.3 / 1.5 — auditoría del modelo (placeholder "Capa MODELO") |
| `06_Google_Search` (marca, modelo, auto eléctrico, ads) | 🚗 MODELO | 1.5 — keywords/anuncios; prueba de pauta en Search |

**Cómo insertarlas en el HTML:** usar rutas **relativas**, p. ej.
`<img src="Evidencias/Chevrolet_Spark_EUV/03_Instagram/instagram_home.png" alt="..." style="width:100%;border-radius:10px">`.
Al imprimir el HTML a PDF **desde la carpeta**, las imágenes relativas se incrustan sin problema. **Rotular cada
captura** con su capa (marca/modelo) y la fuente (criterio de la rúbrica). Para no inflar la extensión, priorizar
**Chevrolet + el principal rival (BYD)** y resumir el resto en una grilla/contact-sheet.

> Nota sobre el formato de las capturas: están recortadas a 1920×864 mostrando solo el contenido de la página (sin
> barra del navegador ni barra de tareas), aptas para insertar directo. Hay respaldo full-screen en
> `Evidencias_originales_fullscreen/` por si se necesita la versión con URL visible como "prueba de sesión real".

---

## 8 · Decisiones (resueltas y pendientes)

**Resueltas (17/06/2026):**
1. **Autoría:** ✅ **Individual** — carátula solo con **Ariel Lescano**.
2. **Docente:** ✅ **Mario Olivetto**.
3. **Nombre del modelo:** ✅ usar **"Spark EUV"** en toda la presentación (ya aplicado al HTML). Se mantiene la
   aclaración en §1.2 de que es el modelo real 2026.
4. **Presupuesto:** ✅ **ARS 36.000.000** (cifra de referencia confirmada).

**Pendientes:**
5. **Hosting del enlace funcional:** dónde se publica el HTML para tener la URL que va en el PDF.
6. **Ciudades del despliegue:** hoy CABA, Córdoba, Rosario, Mendoza + **Bahía Blanca** (reemplaza a La Plata). Confirmar.
7. **Datos faltantes (Fase A):** garantía BAIC y Jetour; unidades patentadas JMEV/Jetour/BAIC (ACARA/ADEFA); validar
   metas numéricas (900 leads, 60 ventas) anclándolas a un % del mercado.

**Estrategia de evidencias (Fase B) — definida:** no se vuelca toda la evidencia en el cuerpo. Se usa un esquema de
3 niveles para no recargar la visual principal: (a) **montajes comparativos** (1 imagen por categoría con las 5 marcas
lado a lado) embebidos inline como el visual del benchmarking; (b) **2–3 capturas individuales** de alto impacto
(ej. reseñas posventa de Chevrolet, los 285 K de IG de BAIC); (c) **anexo de evidencias** al final / carpeta
`Evidencias/` referenciada para el detalle completo. Los montajes se generan a `Evidencias/_comparativas/`.

---

## 9 · Mapa rápido de archivos

```
Trabajo Práctico Integrador 2026 Consultoría de Marketing Digital/
├── CLAUDE.md                      ← ESTE archivo (contexto maestro, leer primero)
├── BRIEF_TP_Grupo31.md            ← bitácora viva + datos verificados + tracker
├── TP_Integrador_MarketingMTyO_Grupo31_Chevrolet.html   ← entregable (presentación)
├── Trabajo Práctico Integrador 2026.pdf                 ← consigna oficial (no editar)
├── Trabajo Práctico Integrador 2026 – Consultoría…​.md   ← transcripción de la consigna
├── Evidencias/                    ← 56 capturas (5 marcas × 8 categorías) + README.md
│   └── <Marca>/<01_Web…08_Similarweb>/*.png
├── Evidencias_originales_fullscreen/   ← respaldo full-screen de las capturas
└── 01 - capturas evidencia redes/      ← capturas viejas (parcial, reemplazado)
```

---

_Para continuar: leé §6 (Roadmap) y §8 (Decisiones abiertas), confirmá lo pendiente y seguimos por la fase que
corresponda. La prioridad inmediata, por la fecha de entrega, es Fase A + Fase B (información y evidencias en la
presentación); el diseño fino de apps/piezas (Fase C) es lo que se trabajará con "cloud design"._
