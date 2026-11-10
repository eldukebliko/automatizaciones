# Dirección visual — página de muestra «automatizaciones con IA» (04-nov-2026)

## Investigación (Dribbble, 04-nov-2026)
- `freelance portfolio landing page`: OViiO (nombre en degradado pastel + cifras grandes), Heloxone «Digital Value Studio»
  (naranja + negro + collage), OffDeck «Sultan» (beige + foto + tipografía contorneada). Todo muy «agencia».
- `terminal ui monospace website`: Mahid (página crema con tarjeta de terminal oscura, «shift manual ops into autonomous
  pipelines»), Morva/Sawala (verde sobre negro). Es exactamente el uniforme crema + tarjeta oscura: descartado.
- `audio plugin ui knob`: Mik Skuza (hardware oliva/naranja con contadores numéricos grandes «62 / 03»), Dmitriy Sysoev
  (panel blanco con etiquetas serigrafiadas), Julian Behrens (azul pálido con knobs).

## Direcciones consideradas
A. **Panel de instrumento** — la página como el frontal de un aparato de audio: fondo panel claro, etiquetas serigrafiadas
   en mayúsculas pequeñas, cifras reales en contadores tipo display, cadena de señal IN → PROCESO → OUT. ELEGIDA.
B. Terminal sobre papel crema — descartada (lista negra: crema + tarjeta oscura).
C. Collage editorial naranja/negro — descartada (look de agencia genérico, no habla del sujeto).

## Tokens (dirección A)
- Paleta: panel `#E9E7DF` · panel hundido `#DDDAD0` · tinta `#1B1A17` · oliva `#5F6B2E` · naranja `#E0601A` ·
  display ámbar `#F2A33A` sobre `#2A2721`.
- Tipografía: display **Big Shoulders Display** (condensada, industrial, para titulares y contadores) · cuerpo **IBM Plex Sans** ·
  utilidad **JetBrains Mono** (etiquetas serigrafiadas, comandos).
- Composición: una columna de 1080 px máx. dividida en «módulos» con borde fino y tornillos en las esquinas; cada módulo
  lleva su etiqueta serigrafiada arriba a la izquierda. Sin fondo negro.
- **Elemento firma:** la **cadena de señal** del hero: tres bloques (entrada → proceso → salida) unidos por «cables de patch»
  dibujados en SVG, con las cifras reales de Pablo en contadores ámbar (6 clips, 40 guiones, ≈20.000 líneas, 64 medios).
  No se ha usado en ningún otro proyecto de Pablo (Astra: cielo estrellado; videoclips: cut-out).

## Autocrítica
¿Lo habría hecho cualquier Claude sin ver Dribbble? No: el panel claro con serigrafía y contadores sale de los shots de
hardware, y la cadena de señal es una metáfora del oficio de Pablo (plugins), no un patrón de landing.

## Revisión 04-nov-2026 (Pablo: «es fea la página»; pide lo que venda más)
Dirección A descartada. Nueva dirección **«Blanca, persona y resultado»**, pensada para el comprador real (gestor,
dueño de estudio, director de academia, sin perfil técnico): compra confianza en una persona y un resultado que ve.
- Paleta: blanco `#FFFFFF` · gris suave `#F2F3F0` · tinta `#141414` · gris texto `#5B5E58` · **amarillo karaoke
  `#FFE000`** (el mismo de `render_karaoke.py`), solo en el elemento firma y en el botón.
- Tipografía: **Manrope** (display y cuerpo, pesos 400-800) · JetBrains Mono solo en etiquetas de precio.
- Composición: hero a dos columnas, foto real de Pablo a la izquierda y un teléfono a la derecha; después tres paquetes
  en tarjetas blancas; casos en una lista corta; reglas; contacto. Mucho aire, sin fondos oscuros, sin rejillas.
- **Elemento firma:** el **subtítulo karaoke vivo** dentro del teléfono: las palabras se iluminan en amarillo una a una,
  como en los clips reales que entrega. Es su producto, no una metáfora.
- Descartado: oscuro tipo Astra (aleja al gestor: parece producto tech) y cálido editorial (sin resultado visible).

## Segunda pasada (04-nov-2026, publicada)
Pablo aprobó la dirección blanca y pidió «modernizar y mejorar los mockups». Cambios: teléfono con isla, barra de progreso
animada, contador «clip N de 7» sincronizado con la línea de tiempo, silueta con luz de escena, onda de audio, iconos
laterales y pie tipo reel; línea de tiempo con el clip activo resaltado; mockups de bandeja (remitentes, hora, etiquetas),
informe (KPIs, barras, lectura) y agente (chat con etiquetas reglas/memoria/Notion); sección «Una semana, antes y después»
(marcada como ejemplo, no dato de cliente); cabecera fija con botón; chips de confianza (Astra, Mytel, UOC, Barcelona).
Rechazada antes: dirección «panel de instrumento» (Pablo: «es fea»).

## Tercera pasada (04-nov-2026, publicada)
Pablo, como consumidor: «es muy tostón, necesito atajos» y «el subtítulo no está centrado». Cambios: bloque «¿Qué te trae
aquí?» con 4 atajos por problema (vídeo, correo, informe, agentes) que saltan a su paquete; cabecera con anclas cortas;
se eliminan las secciones «Para quién», «Antes/después» y «Cuatro reglas» (el antes/después pasa a una línea dentro de
cada paquete y las reglas a chips bajo «Cómo funciona»); casos en una frase; subtítulo centrado a todo el ancho; la
silueta CSS se sustituye por `clip-bg.jpg`, un fotograma real de un clip entregado en jul-2026 desenfocado (sigma 70,
irreconocible) que se usa también en los mini-clips y en la línea de tiempo. Error corregido: la clase `sc` del header
(scroll) chocaba con la clase `sc` de las tarjetas de atajo; ahora `scrolled`.

## Cuarta pasada (10-nov-2026, publicada)
Pablo: «no llama mucho la atención, ni queda claro, ni es un paso a paso que el cliente entienda y vea cómo nos
necesita para ganar más dinero ahorrándose». Misma dirección blanca (aprobada); cambia el hilo de venta:
- Hero: «Tu equipo pierde horas cada semana en tareas que ya se hacen solas». CTA principal → calculadora.
- **Segundo elemento firma: la calculadora de horas** (`#calculadora`). El cliente elige su caso (4 pestañas, que también
  fijan los 4 atajos), mueve horas/semana y coste/hora, y un panel amarillo le dice: cuánto le cuesta hoy al mes, precio
  del paquete, horas que vuelven, lo que le queda cada mes y en qué semana recupera la instalación. Supuesto explícito:
  una persona sigue dedicando 1 de cada 5 horas a revisar. Si no compensa, lo dice en blanco («te lo diría igual en la
  llamada»): honestidad como argumento de venta.
- **Paso a paso con fechas** (`#pasos`): Hoy 15 min → Mañana precio por escrito + 3 clips gratis → Días 2-5 instalado →
  Semana 2 la persona pasa de hacer a revisar → Mes 2 solo cuota. Cada paso con «tú / yo».
- Paquetes: la línea Antes/Después pasa a tres filas HOY / CON ESTO / GANAS. Se elimina la sección «Cómo funciona»
  (absorbida por el paso a paso); las 4 reglas van a «Casos».
- Corregido: `.packs` con `minmax(0,1fr)` (una tarjeta ensanchaba la rejilla); calculadora y pasos sin animación de
  aparición (un salto por ancla los dejaba invisibles un instante).

## Quinta pasada (10-nov-2026, publicada)
Pablo: «le falta hacer más servicios por el cliente, gestionarle todos los buzones, mejorarle el SEO…» y «la videollamada
de ejemplo queda muy cutre blurreada». Cambios:
- `reel-bg.jpg` sustituye a `clip-bg.jpg`: fotograma real de Pablo a cámara (toma en bruto de su Escritorio, segundo 60,
  recorte 9:16 a 405×720, sin letras ni nada musical a la vista). Pendiente: su vídeo de 3 min cara a cámara lo sustituirá.
- Nueva sección `#servicios` «Lo de arriba es lo más pedido. Esto es el menú entero»: 5 grupos por resultado (que te
  encuentren · que te contesten · que publiques sin trabajar · que decidas con datos · tu equipo con IA), 14 líneas con
  precio en mono a la derecha. Enlace desde los atajos («Ver el menú entero») y desde la cabecera («Todo el menú»).
- SEO: 4 ofertas más en el JSON-LD (buzones 650, SEO 350, recordatorios 300, web 900), 2 preguntas nuevas en FAQ (HTML y
  schema), meta description nueva, `llms.txt` con el menú, sitemap con fecha.
- Quitada del todo la animación de aparición `.rv` (al entrar por un ancla en móvil la sección quedaba en blanco).
