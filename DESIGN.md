# DESIGN.md · Club Pioneros del Norte

Fuente visual única para la web (`sitio-web/`) y el CRM (`crm/`). Inspirado en el sistema editorial deportivo de Nike: la foto y los titulares enormes hablan; la interfaz es blanco, negro y un gris. El naranja del club es el único color.

## Color
| Rol | Valor | Uso |
|---|---|---|
| Tinta | `#111111` | Texto, botón principal (píldora negra), filtros activos, navegación activa |
| Lienzo | `#ffffff` | Fondo de todo |
| Nube | `#f5f5f5` | Campos de formulario, botón secundario, bloques de apoyo |
| Línea | `#cacacb` / `#e5e5e5` | Divisores de 1 px. No hay sombras. |
| Apagado | `#6b6b6d` | Texto secundario (≥4.5:1 sobre blanco y nube) |
| Naranja club | `#ff6e01` | Rellenos: bloque de campaña, categoría encontrada, barras, botón de WhatsApp. Texto encima siempre en tinta. |
| Naranja texto | `#b84700` | Naranja cuando es texto sobre blanco (4.9:1) |
| Rojo / verde | `#d30005` / `#007d48` | Solo para estados: deuda, vencido, pagado, asistió |

Nunca texto blanco sobre naranja (no llega a 3:1).

## Tipografía (autoalojada en `fonts/`)
- **Anton**, mayúsculas, interlínea 0.9: titulares de campaña (web, máx. 6rem) y títulos de página del CRM. Nunca para párrafos.
- **Archivo** 400/500/600/700: todo lo demás. Títulos de sección en 500, 1.6–2rem, en frase normal (no mayúsculas).
- Números en tablas y montos: `font-variant-numeric: tabular-nums`.

## Forma
- Botones, filtros y chips: píldora (radio 30px). Principal negro; secundario nube; sobre foto, blanco.
- Tarjetas, tablas y bloques: esquinas rectas, borde de 1 px o fondo nube. Sin sombras.
- Campos: fondo nube, radio 12px; al enfocar, fondo blanco y borde tinta de 1.5px.
- Ritmo de 8 px; secciones de la web separadas 56–96 px.

## Web
Portada con fotos a todo el ancho y titular en Anton blanco; buscador de categoría con píldoras de año y resultado en bloque naranja; «Más que baloncesto» como campaña naranja; uniformes como tarjeta de producto (foto en nube, nombre, detalle, precio); cierre sobre foto con botón naranja de WhatsApp.

## CRM
Mismo sistema en claro. Barra lateral blanca con la sección activa en píldora negra; en el celular, barra inferior de 5 pestañas. Burbujas de chat: contacto en nube, Claude en naranja suave, personal del club en negro.

## No hacer
Etiquetas pequeñas encima de los títulos, degradados decorativos, sombras, bordes de color a la izquierda, emojis como íconos, fuentes de sistema como titular.
