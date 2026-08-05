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
    │                       segment_fertilizantes_granulados.jpg,
    │                       segment_biofertilizantes.jpg
    ├── products/         → product_1.jpg … product_4.jpg
    └── backgrounds/      → bg_section_1.jpg, bg_section_2.jpg
```
Cada subcarpeta trae un archivo `COLOCAR_AQUI...txt` que indica el nombre exacto que debe
tener la imagen final. Bórralo cuando coloques la foto real.

## Cambios respecto a la versión anterior
- **Se eliminó por completo la acuicultura** — segmento, tarjeta, imagen de referencia y
  cualquier mención en el copy.
- **Se eliminó el enfoque en ganadería/avicultura y nutrición animal** de la versión anterior,
  para no diluir el nuevo enfoque.
- **Nuevo posicionamiento:** ADITMEX **no vende fertilizantes** — provee las materias primas
  funcionales que fabricantes y mezcladores de fertilizantes usan para (1) mejorar la
  **eficiencia** de su fórmula y (2) **personalizarla** para cada cliente o cultivo. Esto me
  lo confirmaste directamente, así que ya no es una suposición.

## De dónde sale el contenido técnico
Sigo sin tener fichas técnicas de ADITMEX específicas para fertilizantes. Para no inventar
nada, la página traduce sus **categorías reales de producto** (espesantes, acidulantes,
derivados del maíz, aceites naturales, derivados de ácidos grasos, glicoles, conservadores)
hacia funciones de eficiencia y personalización de fertilizantes que son de uso real y
conocido en la industria:

| Categoría real de ADITMEX | Función en fertilizantes |
|---|---|
| Espesantes (goma xantana, guar, CMC) | Estabilidad/suspensión en fertilizantes líquidos |
| Derivados del maíz (almidón) | Aglutinante/recubrimiento en fertilizantes granulados |
| Acidulantes (ácido cítrico) | Ajuste de pH para disponibilidad de nutrientes |
| Aceites naturales / derivados de ácidos grasos | Adyuvantes que mejoran adherencia foliar |
| Glicoles | Solventes/vehículos en formulaciones líquidas |
| Conservadores | Estabilidad de biofertilizantes/orgánicos frente a deterioro microbiano |

Evito deliberadamente **dosis numéricas específicas**, porque dependen de la formulación base
de cada fabricante — algo que corresponde a su equipo técnico definir, no algo que yo deba
inventar. Donde el uso requiere criterio de un especialista (p. ej. glicoles como vehículo),
lo señalo explícitamente en el texto ("consulte con su equipo de formulación").

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
