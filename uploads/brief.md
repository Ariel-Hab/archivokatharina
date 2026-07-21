# Brief de diseño 01 — Mood general + submood Mural

**Proyecto:** sitio portfolio de Katharina Armbruster · **Fecha:** 2026-07-09 (v2) · **Para:** Claude Design
**Adjuntos (4 PDFs):** `referencias-mural` (8 págs., su portfolio de muralismo) · `referencias-pintura-portfolio` (11 págs., su portfolio personal) · `referencias-pintura-estilo` (3 páginas web de referencia que gustan) · `referencias-pintura-obras` (10 fotos de obra).

---

## Contexto del proyecto (leer primero)

Página portfolio para **Katharina Armbruster** (artista visual, Zona Sur, Buenos Aires; Instagram `@archivo.katharina`). La página es **una sola, narrativa**: abre presentándola a ella y su trayectoria, y evoluciona con el scroll por tres "aristas" — **pintura, digital y mural** — donde cada arista es un mini-portfolio (texto breve de su experiencia + una selección corta de obras). Cierra en contacto/encargos. Bilingüe español/inglés (diseñar en español).

El sitio tiene un **mood general** que lo sostiene entero, y cada arista tiene su **submood** propio que se activa en su sección, con transiciones al scrollear. La página final se implementará en Astro con Claude Code; de esta sesión de diseño se espera un handoff.

## Objetivo de ESTA sesión (alcance acotado)

Hay referencias y notación para **mural** y **pintura**, y la intro está definida por notación. Falta solo **digital**. Entregables, en orden:

1. **Completar el mood general** (paleta fija y dirección serif ya decididas — ver "Decisiones ya tomadas"; falta elegir la serif concreta, composición y texturas).
2. **Ejecutar los submoods pintura y mural** según sus notaciones (no proponerlos de cero — darles forma visual).
3. **Generar la página de prueba**: intro → pintura → mural → contacto (NO diseñar digital todavía — llegará con sus referencias).

⚠️ **Advertencia metodológica**: el mood general queda **provisorio** solo respecto de la arista digital, que aún no tiene referencias.

## Decisiones ya tomadas (2026-07-09) — no re-proponer

**Paleta del mood general (fija):** dark slate green `#2d423b` (tinta/fondos oscuros), cambridge blue `#7a948b` (secundario y acento de la arista pintura), linen `#ede3de` (fondo base), khaki `#c6aa96` (acento cálido), old rose `#ba7878` (acento expresivo/CTA). Ojo: old rose y khaki no alcanzan contraste AA para texto sobre linen — solo como acento gráfico.

**Dirección tipográfica (fija): serif elegante** — unánime entre las referencias de página (Anna Ancher, museo Van Gogh, La Fleur Verte, en `referencias-pintura-estilo`) y el propio portfolio PDF de Kati. La grotesca black del deck de mural queda descartada como identidad. Falta elegir LA serif: proponer 2–3 candidatas (ver Entregable 1).

**Composición de la intro (fija):**
- **Obra parcial, no full-bleed**: la obra ocupa una banda o un costado (candidata: los nenúfares de la pág. 1 de `referencias-pintura-portfolio`); el resto es linen limpio. El texto no pisa la imagen.
- **Nombre en escala media, elegante** (como la tapa de su PDF — no monumental); la obra y la credencial respiran alrededor.
- **Sello UNA junto al nombre**: "Universidad Nacional de las Artes — Licenciatura en Artes Visuales" (está por recibirse: es el diferencial institucional a resaltar). El detalle va en la bio.
- **Foto chica de ella** junto a la bio (hay una en la pág. 2 de `referencias-mural`).
- Bio de 3–4 líneas + **una frase destacada del artist statement** + link al CV en PDF + navegación numerada hacia las aristas (01/02/03) + CTA contacto.

**Notación del submood pintura (fija):**
- Alcance: toda su obra de taller (pintura, grabado, serigrafía, textil, instalación). Nombre visible de la arista a confirmar ("Pintura" vs. "Obra").
- Carácter: **íntimo / taller** — no institucional: la sensación de hojear su cuaderno o entrar al taller (su statement: capas, memoria, intimidad). Misma serif que la intro, fondo linen claro, acento cambridge blue. Sus fotos de obra en contexto (cuaderno en mano, patio, obra colgada con broches — en `referencias-pintura-obras`) pueden usarse como imágenes intersticiales de clima.
- **El statement completo abre la sección** (en la intro va solo una frase).
- Obras: **ritmo editorial variado** — tamaños distintos según jerarquía, una grande cada tanto, pares que dialogan; sin full-bleed. Fichas: **metadatos + descripción breve** (formato exacto de su PDF). Única arista con texto curatorial por obra.
- Transición intro→pintura: **desvanecimiento sereno** — la obra parcial de la intro se desvanece al scrollear y queda el taller en linen. Sin gestos fuertes.

**Notación del submood mural (fija):**
- Carácter: **contraste lúdico** — dentro del sitio sereno/terroso, la sección mural despierta con el espíritu juguetón de la obra real.
- Paleta: la de las obras de Malaku — turquesa `#8FD0C2`, ocre `#E3B96E`, rosa `#F2B8C6` (aproximados; muestrear de fotos en alta).
- Tipografía: **uniforme con el sitio** — el lettering manuscrito de Kati queda solo dentro de las fotos.
- Fotos: **hero + grilla** — un mural a pantalla completa abre la sección; el resto en grilla con aire. Siempre in situ.
- Texto: **mínimo** (2–3 líneas de experiencia) + **servicios y proceso compactos** al pie (3 modalidades + 4 pasos, una línea cada uno).
- Movimiento: **sutil** (solo fades) — lo lúdico va en color y formas estáticas.
- Transición general→mural: **elemento pintado que invade** — lunares/formas de la paleta mural se meten al final de la sección anterior y crecen hasta ser el fondo, como si Kati pintara la página.

## Análisis del material adjunto (el submood mural existente)

El portfolio de muralismo (Canva, 8 páginas) define una estética clara:

- **Fondos**: gradientes difusos y aireados — celeste grisáceo, azul suave, lavanda, con manchas cálidas (naranja suave, verde). Paleta aproximada: fondo `#CBD5DF`/`#D9E0E7`, azul `#8FB0CF`, lavanda `#C9C4DC`, acento naranja `#E8B27D`, verde suave `#BFD4B4`, tinta `#3D3D3D`.
- **Tipografía**: grotesca contemporánea en peso **black** para títulos enormes con punto final ("Muralismo.", "Gracias"), etiquetas en mayúsculas con tracking amplio ("P O R T F O L I O"), texto corrido en grotesca regular. Referencias web equivalentes: Archivo/Inter/Helvetica en pesos black.
- **Composición**: mucho aire, título gigante abajo a la izquierda, contenido a la derecha, numeración de secciones ("01", "02", "03").
- **La obra de Kati en sí** (importante — es distinta del deck): juguetona y cálida — lunares turquesa/ocre/rosa, flores en acuarela, lettering cursivo pintado a mano, pasteles. El deck es sereno; la obra es lúdica. Esa tensión es material de diseño.
- **A corregir del deck** (no heredar): texto blanco sobre fondos claros con contraste insuficiente — en la web el contraste debe cumplir accesibilidad (WCAG AA).

## Entregable 1 — Mood general: 2–3 serifs candidatas sobre la paleta fija

Paleta fija, dirección serif fija, composición de la intro fija (ver "Decisiones ya tomadas"). Lo que se propone acá es **cuál serif y con cuánto carácter**, mostrado como el bloque real de intro (nombre a escala media + sello UNA + bio con foto + frase del statement + obra parcial a un costado). Ejes sugeridos:

- **A. Serif clásica bookish** (como su PDF): serena, literaria, de museo.
- **B. Serif display expresiva** (como La Fleur Verte): más contraste y personalidad en los títulos, cuerpo sobrio.
- **C. Híbrida**: display solo para el nombre y los números de sección; todo lo demás calmo.

**Decisión de cierre**: Ariel y Kati eligen una (o mezclan). No avanzar al entregable 2 sin esta decisión.

## Entregable 2 — Submoods pintura y mural ejecutados según notación

Con la serif elegida, las dos secciones como se verían de verdad, **ejecutando las notaciones fijas** de "Decisiones ya tomadas":

- **Pintura primero** (es la que sigue a la intro): taller íntimo en linen, 3–4 obras del inventario real (`referencias-pintura-portfolio` y `referencias-pintura-obras`) en ritmo editorial variado, fichas con metadatos + descripción breve, acento cambridge blue.
- **Mural después**: hero + grilla con las 3 obras de Malaku (págs. 4–6 de `referencias-mural`), paleta de las obras (turquesa/ocre/rosa), texto mínimo, servicios/proceso compactos al pie.
- Mostrar los dos submoods juntos bajo el mood general para verificar que los tres climas conviven.

## Entregable 3 — Página de prueba (intro → pintura → mural)

Un prototipo scrolleable completo salvo digital: **intro** (ella, su trayectoria, sello UNA, foto, CV) → transición de continuidad → **pintura** (sala serena) → transición de "elemento pintado que invade" → **mural** (contraste lúdico) → cierre de **contacto**. Mobile y desktop. Las dos transiciones son parte del entregable — se tienen que *sentir*, no describir. Este prototipo es la prueba de fuego de la idea central del sitio: una página que evoluciona sin dejar de ser una.

## Contenido real (usar estos textos, no inventar)

**Intro / trayectoria** (adaptar de los "Sobre mí" de ambos portfolios):
> Artista visual. Finalizando la Licenciatura en Artes Visuales con orientación en pintura (Universidad Nacional de las Artes), con formación en dibujo, pintura, cerámica, escultura, digitalización de imágenes, grabado y arte impreso. Participó de una Clínica de Obra facilitada por Marina De Caro (dic. 2025). Expuso su obra textil *Mujeres* en Espacio Barbuda, CABA (abril 2026). Participó de una charla internacional de la Cátedra Sobrino (UNA) sobre investigación y procesos artísticos (junio 2026). Actualmente trabaja freelance en murales, ilustración y venta personalizada.

**Artist statement** (de su portfolio de pintura — usable en la intro o en la arista pintura):
> La práctica se articula en torno a la exploración de la intimidad, la memoria y la ambigüedad como territorios sensibles de percepción. A través de capas, transparencias y materialidades diversas, el trabajo construye superficies de superposición y velamiento donde la imagen aparece en un estado inestable, entre la presencia y la ausencia. Mi obra propone una aproximación atmosférica y afectiva, en la que los rastros, las huellas y las tensiones entre lo visible y lo oculto activan lecturas abiertas y fragmentarias de la experiencia.

**Obras de pintura/obra de taller** (fichas completas en `referencias-pintura-portfolio`, págs. 3–10): *Copa de vino tinta* (aguatinta, 12×15, 2023) · *Flores y Rostro* (serigrafía, 2025) · *Clorotipia* (30×13, 2025) · *Retratos* (acrílico con veladuras, 50×70, 2025) · *Autoretrato* (acrílico, 35×50, 2024) · *Silla y tela* (carbonilla en negativo, 100×75, 2022) · *Mujeres* (textil, 60×60, 2023) · *Memorias* (instalación textil, 2025).

**Sección mural — experiencia y servicios** (del deck): tres modalidades — 01 Adaptación a espacio ("el diseño dialoga con el espacio"), 02 Pared completa, 03 Espacio intervenido (muros con relieve/forma/textura particular). Proceso en 4 pasos: Compartime tu idea → Acordamos cómo sigue → Bocetos digitales (2 rondas de cambios) → ¡A pintar!

**Obras de mural** (fotos en págs. 4–6 de `referencias-mural`; siempre in situ, mostrando escala):
1. Mural floral — pastelería Malaku (flores acuareladas, lettering coral).
2. Pared completa — Malaku Eventos (lunares turquesa/ocre sobre blanco, lettering cursivo).
3. Espacio intervenido — juegos infantiles exteriores Malaku (pinturas sintéticas, círculos rosa/amarillo/celeste).

**Contacto**: katharinarmbruster@gmail.com · +54 9 11 5041-7844 · Instagram @archivo.katharina (usar este provisoriamente; existe también @katharinadetinta — cuál va al sitio está por confirmarse con Kati) · Zona Sur, Buenos Aires, Argentina.

## Restricciones no negociables (validadas por investigación)

1. **La obra domina; el mood ambienta.** Los fondos y acentos viven en el marco (cabeceras, transiciones, navegación) — entre las fotos de obra no compite nada.
2. **Sobrio gana a vistoso**: el sitio es una credencial profesional (curadores, galerías, clientes de encargos), no una demo de diseño.
3. **Mobile first** — la mitad de las visitas van a llegar del Instagram de Kati.
4. **Contraste accesible (WCAG AA)** en todo texto.
5. **Fotos de mural siempre in situ** (escala y contexto son lo que evalúa quien encarga).
6. **CTA de contacto/encargos visible** desde la navegación y al cierre.

## Protocolo de trabajo

- **Una decisión por iteración**: primero cerrar mood general (entregable 1), después submood (2), después la página de prueba (3). No mezclar debates.
- Feedback llegará en lenguaje natural y por sección; conservar lo aprobado al regenerar.
- **Al final de la sesión**: exportar el handoff bundle para Claude Code (la implementación en Astro se hace allá, no acá).
