# PROMPTS para Claude design — Mockups y esqueletos de app
### Fase C · TP Chevrolet EV Care · Grupo 31

> Prompts listos para copiar y pegar en Claude design. Basados en el design system
> ([`DESIGN.md`](DESIGN.md) + [`tokens.css`](tokens.css)). Cuando las piezas estén listas, reemplazan los
> placeholders punteados del **§7 del HTML** (clase `.placeholder`) y se enlazan las apps.

---

## 📷 Qué foto usar (la tengo en la carpeta del proyecto)

- **Foto recomendada del Spark EUV:** `ea64583d6e6fc5fa0cf4b6127e1f14a1e2e40178.jpg` (Spark EUV azul, 3/4 frontal,
  ciudad al atardecer). Alternativas: `spark.avif`, `chevrolet-ar-bloque-retail-spark-euv-desktop.avif`.
- **Subir la foto en:** Reel "Mito vs Realidad" (A), Post posventa (B), Carrusel (D).
- **NO necesita foto:** Search ad (C) — es un anuncio de Google, puro texto.

---

## ⚙️ Preámbulo de estilo (pegar al inicio de CADA prompt)

```
Diseñá con este design system (marca "Chevrolet EV Care"):
- Colores: dorado #C9A227 (acento/marca), verde eléctrico #19A974 (posventa/EV/éxito),
  negro #0E0E0E (texto/fondos oscuros), gris #2b2b2b, fondo #F6F6F4, blanco, líneas #E4E4E4.
- Tipografía: títulos y números en "Space Grotesk" (geométrica); texto en "Inter".
- Iconos: de línea, trazo fino, monocromos. SIN EMOJIS, sin clipart.
- Estilo: sobrio, premium, mucho espacio en blanco, tipo consultora/fintech.
- Logo: moño Chevrolet dorado con un rayo verde (EV).
```

---

## 7.1 · App "Calendario de Service" (3 pantallas)

```
Diseñá 3 pantallas de app móvil "EV Care · Agenda de Service" (1080×2160 c/u, lado a lado, marco de iPhone):
1) PRÓXIMO SERVICE: card grande con cuenta regresiva ("Faltan 18 días"), modelo "Spark EUV",
   km actuales, barra de progreso verde hacia el próximo service, botón "Confirmar turno".
   Header con logo + "Hola, Ariel".
2) CALENDARIO MENSUAL: vista de mes; días con turno disponible en verde, el seleccionado en dorado;
   lista de horarios abajo.
3) CONFIRMACIÓN: check verde grande, "Turno confirmado", fecha/hora, concesionario,
   nota "Te avisamos 48 hs antes", botón "Agregar al calendario".
Iconos de línea (calendario, auto, campana). Acento principal verde #19A974.
```

---

## 7.2 · App "EV Care / ID Care" (4 pantallas — la estrella)

```
Diseñá 4 pantallas de la app "Chevrolet EV Care" (1080×2160 c/u, lado a lado, estilo tablero fintech/health):
1) HOME / SCORE: anillo de progreso grande (tipo Apple Watch) "Salud del vehículo 92",
   combinando dorado y verde; 3 mini-cards debajo (Autonomía, Batería, Próximo service).
2) RATING DE USO: reporte mensual con bar-chart de eficiencia (km/kWh por semana),
   métricas (km recorridos, hábitos de carga) y un "Rating de uso" con medalla/estrellas.
3) AGENDA DE SERVICE: línea de tiempo de mantenimientos (hechos en verde, próximo en dorado), botón "Agendar".
4) LOGROS (Loyalty loop): tarjetas de logros desbloqueados (carga eficiente, conducción suave),
   puntos canjeables y referidos.
Números en Space Grotesk. Iconos de línea. Sin emojis.
```

---

## 7.3 · Piezas / mockups (Social · Influencers · Search)

```
A) REEL "Mito vs Realidad" (1080×1920 vertical) — [subir la foto del Spark azul]:
   Fondo: foto del Spark EUV. Texto grande arriba "¿Y si se rompe?"; abajo en verde "Lo arreglamos nosotros."
   Etiqueta "MITO vs REALIDAD", logo EV Care, botón play. Tipografía Space Grotesk, acento verde.

B) POST POSVENTA "EV Care" (1080×1350) — [subir la foto del Spark]:
   Header dorado "EV CARE · Tu auto, siempre al día". 3 filas con icono de línea:
   "Agendá tu service online", "Reporte de uso mensual", "Rating de tu vehículo". Foto del Spark abajo.

C) SEARCH AD (1080×1080, SIN foto):
   Mockup de anuncio de Google. Etiqueta "Patrocinado". Título azul "Chevrolet Spark EUV | Service Oficial",
   URL verde "chevrolet.com.ar/ev-care", descripción "El eléctrico con la red de posventa más grande del país.
   Agendá tu test drive." + extensiones (Test drive · Garantía · Concesionarios).

D) CARRUSEL "5 cosas que tu eléctrico necesita" (1080×1350, 6 slides) — [foto del Spark en portada]:
   Slide 1 portada con foto + título; slides 2–6 cada uno un tip con icono de línea y número grande;
   slide final CTA "Agendá en EV Care". Paleta de marca.
```

---

## ➡️ Próximo paso (cuando estén las piezas)
1. Exportar cada pieza/pantalla como PNG.
2. Guardarlas en una carpeta (sugerido `design/piezas/`).
3. Avisar a Claude Code → reemplaza los placeholders SVG del **§7 del HTML** por las piezas finales y enlaza las apps.

> Alternativa: los **esqueletos de app (7.1 y 7.2)** se pueden construir directamente en **HTML/SVG** desde Claude Code
> (quedan exactos al design system y editables), en lugar de generarlos en Claude design.
