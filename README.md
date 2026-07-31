# ADITMEX — Landing Page Premium (Sector Agropecuario)

## Qué contiene esta carpeta
```
aditmex-landing-agro/
├── index.html                     ← página completa (HTML + CSS + JS embebidos)
├── PROMPTS_IMAGENES.md             ← lista de imágenes + prompts para generarlas
├── README.md                       ← este archivo
└── assets/images/
    ├── hero/            → hero_main.jpg
    ├── segments/         → segment_alimento_balanceado.jpg, segment_ganaderia_avicultura.jpg,
    │                       segment_agroindustria_poscosecha.jpg, segment_acuicultura.jpg
    ├── products/         → product_1.jpg … product_4.jpg
    └── backgrounds/      → bg_section_1.jpg, bg_section_2.jpg
```
Cada subcarpeta trae un archivo `COLOCAR_AQUI...txt` que indica el nombre exacto que debe
tener la imagen final. Bórralo cuando coloques la foto real.

## De dónde sale el contenido técnico
No cuento con fichas técnicas específicas de ADITMEX para el sector agropecuario (los
documentos que compartiste son de panificación, aceite de naranja y aditivos para
mermeladas/salsas). Para no inventar datos que no puedo verificar, esta página:

- Usa las **categorías reales de producto de ADITMEX** (conservadores, edulcorantes,
  espesantes, aromáticos, aceites naturales, glicoles, acidulantes, derivados del maíz,
  derivados de ácidos grasos) confirmadas en su ficha pública de proveedor.
- Reaplica ingredientes que **sí conozco con certeza** por tus documentos (propionato de
  calcio, sorbato de potasio, benzoato de sodio, ácido ascórbico, ácido cítrico, gomas
  xantana/guar, CMC, almidón de maíz, aceite esencial de naranja) hacia funciones
  agropecuarias donde esas mismas funciones químicas son de uso real y conocido en la
  industria (conservación de forraje/granos, premezclas, agua de bebida, palatabilidad).
- Evita deliberadamente **dosis numéricas específicas** para el sector agropecuario, porque
  esas cifras sí dependen de la especie, la etapa productiva y la formulación — algo que
  debe confirmar tu propio equipo técnico o un nutriólogo, no algo que yo deba inventar.
- Menciona el propilenglicol (categoría "Glicoles") como ejemplo de uso conocido en ganado
  lechero en transición, con nota explícita de "consulte con su nutriólogo" para no dar
  una recomendación técnica que no me corresponde dar.

**Recomendación:** antes de publicar, pide a tu equipo técnico que revise cada afirmación
de la sección de productos y la ajuste o la respalde con tus propias fichas técnicas del
sector agropecuario si ya las tienes.

## Dirección de diseño
Mismo sistema visual que la versión de panificación, para mantener consistencia de marca
entre landing pages: azul corporativo estimado (`#0B3556` / `#2E6F9E`), teal (`#1B8A7A`) y
acento ámbar para CTA (`#E8862B`) — ⚠️ *paleta estimada, no verificada contra el sitio real*
(ver nota al inicio del `<style>` en `index.html`). Tipografía Fraunces + Manrope + IBM Plex
Mono, con las mismas "fichas técnicas" en formato mono como elemento de autoridad.

## Persuasión aplicada (sin nombrarla como tal)
- **Autoridad:** años de trayectoria, marcas aliadas globales, lenguaje técnico preciso.
- **Prueba social implícita:** cita del "equipo técnico ADITMEX" en la franja de confianza.
- **Reciprocidad:** asesoría técnica ofrecida antes de pedir la cotización.
- **Urgencia suave:** "respuesta en menos de 24 horas" y encabezados orientados a que el
  ciclo productivo no se detenga.
- **Autoridad por especificidad:** los chips de categoría técnica (`Categoría: Conservadores`,
  `Categoría: Glicoles`, etc.) funcionan como señal de rigor sin necesidad de superlativos.

## Cómo integrar las imágenes finales
1. Genera cada imagen con el prompt correspondiente en `PROMPTS_IMAGENES.md`.
2. Guárdala con el nombre exacto indicado, dentro de la subcarpeta señalada.
3. Abre `index.html` en el navegador — no se requiere tocar el código.

## Personalización rápida
- **Colores:** centralizados en `:root` al inicio del `<style>`.
- **Textos:** cada sección está comentada (`<!-- SECCIÓN -->`) para ubicarla rápido.
- **WhatsApp/correo:** el botón final usa `ventas@aditmex.com.mx` y
  `+52 443 514 5662`, tomados del sitio público de ADITMEX.
