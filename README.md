# ADITMEX — Landing Page Premium (Eficiencia y personalización de fertilizantes)

## Qué contiene esta carpeta
```
aditmex-landing-agro/
├── index.html                     ← página completa (HTML + CSS + JS embebidos)
├── PROMPTS_IMAGENES.md             ← lista de imágenes + prompts para generarlas
├── README.md                       ← este archivo
└── assets/images/
    ├── hero/            → hero_main.jpg
    ├── segments/         → segment_fertilizantes_liquidos.jpg,
    │                       segment_nutricion_vegetal.jpg,
    │                       segment_aceites_esenciales.jpg,
    │                       segment_biofertilizantes.jpg
    ├── products/         → product_1.jpg … product_5.jpg
    └── backgrounds/      → bg_section_1.jpg, bg_section_2.jpg
```
Cada subcarpeta trae un archivo `COLOCAR_AQUI...txt` que indica el nombre exacto que debe
tener la imagen final. Bórralo cuando coloques la foto real.

## Cambios respecto a la versión anterior
- Se eliminó por completo la acuicultura, ganadería/avicultura y cualquier framing de
  nutrición animal.
- **Se incorporó contenido verificado** a partir de dos documentos que compartiste:
  `DOC-20260724-WA0077.md` (posicionamiento de ADITMEX en nutrición vegetal e insumos
  agrícolas) y `productos_quimicos_para_industria_agro.md` (productos químicos específicos
  con **proveeduría ya identificada** y clientela confirmada).
- Se agregaron 2 pestañas nuevas al portafolio técnico — **Nutrición vegetal y fertirriego**
  (urea, sulfato de amonio, ácido fosfórico, sulfato de zinc, sulfato de magnesio, EDTA) y
  **Aceites esenciales y bioinsumos** (naranja, ajo, mostaza, y referencia a neem, citronela,
  canela, clavo, orégano y tomillo) — y una quinta, **Coadyuvantes y tratamiento** (ácido
  cítrico, glicerina, propilenglicol, sosa cáustica, hipoclorito de sodio).
- Los segmentos (`#segmentos`) se reorganizaron para reflejar estos mismos tres ejes.
- Estabilidad/suspensión (goma xantana, guar, CMC) y recubrimiento/aglutinación (almidón de
  maíz) se mantuvieron tal cual, ya que confirmaste que también aplican.

## De dónde sale el contenido técnico
A diferencia de la primera versión — donde tuve que traducir categorías genéricas de ADITMEX
hacia posibles usos agropecuarios sin certeza — este contenido nuevo proviene de **productos
reales con proveeduría confirmada** según los documentos que compartiste. Es un nivel de
certeza distinto y más alto que el resto de la página.

Sigo evitando **dosis numéricas específicas** (g/L, %, kg/ha), porque esas cifras dependen del
cultivo, la etapa fenológica y la formulación base de cada cliente — algo que corresponde
definir a un agrónomo o al equipo técnico de quien fabrica el producto final, no algo que yo
deba inventar. Donde el documento fuente da un dato objetivo verificable (como el 46% de
nitrógeno de la urea), sí lo incluí, porque es una especificación del insumo en sí, no una
recomendación de dosificación.

No incluí productos de "Protección del cultivo" (insecticidas, fungicidas, herbicidas de
síntesis) mencionados en `DOC-20260724-WA0077.md` como categoría de mercado, porque ese
documento los describe como oportunidad de posicionamiento, no como inventario confirmado de
ADITMEX — a diferencia de los productos químicos del segundo documento, que sí vienen con
clientela y aplicaciones específicas ya validadas.

**Recomendación:** antes de publicar, pide a tu equipo técnico que revise cada afirmación de
la sección de productos y la ajuste o respalde con fichas técnicas propias si ya las tienes.

## Dirección de diseño
Mismo sistema visual que las demás landing pages de ADITMEX, para mantener consistencia de
marca: azul corporativo estimado (`#0B3556` / `#2E6F9E`), teal (`#1B8A7A`) y acento ámbar para
CTA (`#E8862B`) — ⚠️ *paleta estimada, no verificada contra el sitio real* (ver nota al inicio
del `<style>` en `index.html`). Tipografía Fraunces + Manrope + IBM Plex Mono, con las mismas
"fichas técnicas" en formato mono como elemento de autoridad.

## Persuasión aplicada (sin nombrarla como tal)
- **Honestidad como diferenciador:** el propio hero dice "no vendemos fertilizantes" —
  posiciona a ADITMEX como aliado técnico, no competidor, lo cual reduce fricción de entrada
  con fabricantes que temen ser desplazados por su proveedor de insumos.
- **Autoridad:** años de trayectoria, marcas aliadas globales, lenguaje técnico preciso.
- **Prueba social implícita:** cita del "equipo técnico ADITMEX" en la franja de confianza.
- **Reciprocidad:** asesoría técnica ofrecida antes de pedir la cotización.
- **Urgencia suave:** "respuesta en menos de 24 horas" y encabezados orientados a que la
  producción no se detenga.
- **Autoridad por especificidad:** los chips de categoría técnica (`Categoría: Espesantes`,
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
