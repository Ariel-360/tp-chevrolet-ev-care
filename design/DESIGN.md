# DESIGN.md — Sistema de diseño "Chevrolet EV Care"
### Mínimo design system para alimentar Claude design / Figma / el HTML del TP

> Objetivo: que la presentación y los mockups (piezas, app EV Care, calendario de service) se vean
> **profesionales, sobrios y con identidad** — no genéricos. Los valores duros (color, tipografía, espaciado,
> motion) están en [`tokens.css`](tokens.css). Este documento explica **cómo usarlos**.

---

## 1 · Principios

1. **Sobrio y premium, no decorado.** Mucho espacio en blanco, jerarquía clara, pocas reglas bien aplicadas.
2. **Sin emojis.** Se reemplazan por un set de **iconos de línea** coherente (ver §4).
3. **El dorado se gana.** `--gold` es acento, no relleno: números clave, totales, la marca, el estado activo. El verde `--ev` marca todo lo de **posventa / EV / éxito** (es el color del ángulo).
4. **Movimiento mínimo y con intención.** Scroll suave + apariciones sutiles al entrar en viewport. Nada que rebote o distraiga. Respetar `prefers-reduced-motion`.
5. **Consistencia > cantidad.** Mismos radios, mismas sombras, misma escala tipográfica en todo.

---

## 2 · Color (uso)

| Token | Uso correcto | Evitar |
|---|---|---|
| `--ink` / `--ink-soft` | texto, headers de tabla, fondo de portada | usarlo como acento "divertido" |
| `--gold` | números KPI, total de presupuesto, marca, estado activo, bordes de énfasis | grandes áreas rellenas de dorado |
| `--ev` / `--ev-soft` | posventa, fidelización, "éxito", el Loyalty Loop, checks | texto largo en verde |
| `--blue` / `--violet` | datos secundarios, barras de Gantt | competir con el dorado |
| `--bg` / `--paper` / `--line` | fondo, tarjetas, divisores | sombras pesadas |

Contraste mínimo AA: texto sobre `--paper` usar `--ink`/`--ink-soft`; captions `--mute`.

---

## 3 · Tipografía

- **Pareja recomendada:** **Space Grotesk** (display geométrico, para h1/h2/kickers/números) + **Inter** (texto). Ambas en Google Fonts. Alternativas igualmente válidas: *Sora + Inter*, *Clash Display + Satoshi*, *Archivo + Inter*.
- **Cargar en el HTML** (en `<head>`):
  ```html
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@500;700&family=Inter:wght@400;500;700&display=swap" rel="stylesheet">
  ```
  > Para el **PDF offline** el fallback es el stack del sistema (ya definido en `tokens.css`). Si la entrega se imprime sin internet, conviene autohospedar las fuentes o aceptar el fallback.
- **Escala:** usar `--fs-300…900`. Kickers en mayúsculas, `letter-spacing:var(--tracking-kicker)`, color `--gold`.
- **Números** (KPIs, precios, seguidores): siempre en `--font-display`, peso 700 — dan sensación de "dato duro".

---

## 4 · Iconografía (reemplaza a los emojis)

**Estilo:** iconos de **línea**, trazo **1.75px**, esquinas redondeadas, `stroke:currentColor`, `fill:none`, viewBox `0 0 24 24`. Monocromo: heredan el color del contexto (`--ink` por defecto, `--gold` o `--ev` cuando son acento). Tamaño base 22–24px.

**Set mínimo a desarrollar** (cada emoji actual del HTML → su icono):

| Dónde (HTML actual) | Emoji a reemplazar | Icono propuesto |
|---|---|---|
| Secciones / pilares | 🎯 objetivo | diana / target |
| Capa MARCA | 🏛️ | edificio / columnas |
| Capa MODELO | 🚗 | auto de frente |
| Mercado | 📈 / 📊 | line-chart / bar-chart |
| Comunidad redes | 📱 | smartphone |
| Search | 🔎 | lupa |
| Influencers | 🤝 | handshake |
| CRM / Email | ✉️ | sobre |
| Posventa / agenda | 📅 | calendario |
| Rating de uso | ⭐ | estrella |
| Garantía / respaldo | (nuevo) | escudo (shield-check) |
| Carga / batería | (nuevo) | batería + rayo |
| Audiencias | 🏙️ 👨‍👩‍👧 🏢 | city / familia / building |
| Evidencia | 📸 | imagen / marco |
| Check listas | • | check en círculo (`--ev`) |

**Prompt sugerido para Claude design:**
> "Generá un set de iconos de línea, trazo 1.75px, viewBox 24, esquinas redondeadas, stroke currentColor, fill none, estilo coherente y minimalista para una consultora de marketing automotriz EV: target, edificio, auto, line-chart, smartphone, lupa, handshake, sobre, calendario, estrella, shield-check, batería-con-rayo, city, familia, building, imagen, check-circle. Entregar como SVG inline optimizados."

**Logo:** ya existe un SVG inline en la portada (bowtie dorado + rayo EV). Reutilizarlo como marca del proyecto en piezas y apps.

---

## 5 · Espaciado, grilla y componentes

- **Ancho de contenido:** `--maxw` (1040px), centrado.
- **Ritmo vertical:** secciones separadas por `--sp-6`; padding interno de tarjeta `--sp-8`.
- **Radios:** tarjetas `--r-lg`, controles `--r-md`, pills `--r-pill`.
- **Sombras:** solo `--shadow-1` (tarjetas) y `--shadow-2` (elementos elevados / hover). Nada más pesado.
- **Componentes ya definidos en el HTML** (mantener y "vestir" con este sistema): nav sticky, section-card, card.kpi, tablas (header `--ink`), grilla FODA 2×2, funnel de 4 niveles (TOFU/MOFU/BOFU + Loyalty), Gantt 12 semanas, steps numerados, pill/note/warn.

---

## 6 · Motion (scroll suave + apariciones)

- **Scroll suave** entre secciones (ya está `scroll-behavior:smooth`; el nav ancla a cada sección).
- **Apariciones al entrar en viewport:** opacity 0→1 + translateY 12px→0, `--dur-slow var(--ease)`, una sola vez, con `IntersectionObserver`. Stagger leve entre tarjetas (60–80ms).
- **Hover:** elevar `--shadow-2` + translateY -2px en tarjetas clickeables, `--dur-fast`.
- **Regla:** nada de loops infinitos ni parallax agresivo. Sobrio.
- Siempre respetar `@media (prefers-reduced-motion: reduce)` (ya en `tokens.css`).

---

## 7 · Esqueletos de app a diseñar (Fase C — el corazón del ángulo)

Usar este sistema (color/tipo/iconos/motion) para los tres entregables visuales:

### 7.1 · App / micrositio "Calendario de service"
Agenda automática según el cronograma de fábrica. Pantallas: (1) próximo service con cuenta regresiva, (2) calendario mensual con turnos, (3) confirmación + recordatorio. Acento `--ev`. Icono base: calendario.

### 7.2 · App "EV Care / ID Care" (la estrella)
Onboarding + agenda + **"rating de uso"** + reportes. Pantallas: (1) home con score de salud del vehículo (anillo de progreso `--gold`/`--ev`), (2) reporte de uso (km, eficiencia, hábitos de carga — bar-chart), (3) agenda de service, (4) logros/gamificación (Loyalty loop). Tono: tablero limpio tipo fintech/health.

### 7.3 · Mockups de piezas (reemplazan los SVG placeholder de §7 del HTML)
Reel "Mito vs Realidad", post de posventa "EV Care", search ad, carrusel "5 cosas que tu eléctrico necesita". Formato vertical 1080×1350 / 1080×1920. Misma paleta y tipografía; el `--ev` para los CTA de posventa.

> Cuando estén listas, reemplazan los placeholders punteados del HTML (clase `.placeholder`).

---

## 8 · Cómo usar esto en Claude design / cloud design
1. Pasar `tokens.css` como base de variables.
2. Pedir el **set de iconos** (§4) primero — es lo que destraba quitar los emojis.
3. Diseñar las **apps** (§7) con esos tokens e iconos.
4. Aplicar la **tipografía** y el **motion** (§3, §6) al HTML para la versión "premium".
5. Exportar piezas y reemplazar los placeholders del HTML.
