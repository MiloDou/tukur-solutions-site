---
name: Tukur Solutions
description: Tecnología con sensibilidad artística y dirección humana.
colors:
  paper: "#f4f2eb"
  paper-strong: "#fffefa"
  ink: "#182230"
  muted: "#596575"
  accent: "#2858cc"
  accent-deep: "#1d4299"
  sand: "#e2e7f0"
  line: "#cfd5df"
typography:
  display:
    fontFamily: "Manrope, sans-serif"
    fontSize: "clamp(48px, 6.5vw, 88px)"
    fontWeight: 700
    lineHeight: 0.99
    letterSpacing: "-0.035em"
  headline:
    fontFamily: "Manrope, sans-serif"
    fontSize: "clamp(36px, 5vw, 62px)"
    fontWeight: 700
    lineHeight: 1.04
    letterSpacing: "-0.04em"
  title:
    fontFamily: "Manrope, sans-serif"
    fontSize: "clamp(20px, 2.1vw, 26px)"
    fontWeight: 700
    lineHeight: 1.15
  body:
    fontFamily: "Manrope, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.75
  label:
    fontFamily: "Manrope, sans-serif"
    fontSize: "13px"
    fontWeight: 500
    lineHeight: 1.5
components:
  button-primary:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.paper-strong}"
    typography: "{typography.label}"
    padding: "13px 18px"
  button-primary-hover:
    backgroundColor: "{colors.accent-deep}"
    textColor: "{colors.paper-strong}"
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    padding: "13px 18px"
  contact-panel:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper-strong}"
---

# Sistema de diseño: Tukur Solutions

## Overview

**Creative North Star: "El taller del búho"**

Tukur se presenta como un espacio donde una persona observa, interpreta, decide y diseña antes de construir con tecnología. La página combina la precisión de un estudio digital con la sensibilidad de un taller artístico. El búho original es la firma; el engranaje y las líneas de conexión muestran el proceso sin convertir la marca en una estética genérica de IA.

La identidad usa mucho espacio, una jerarquía editorial clara y una paleta corta. Las expresiones de cada cliente pueden ser distintas entre sí; el marco de Tukur conserva siempre su propia voz. La referencia editorial de Awesome DESIGN.md para Mistral.ai orientó la jerarquía, el ritmo y el uso selectivo del acento; sus colores, tipografías y elementos de marca no forman parte de Tukur.

**Características clave:**

- Logo original de búho y engranaje, sin redibujar ni recolorear.
- Marfil cálido, tinta azul oscuro y un único acento cobalto.
- Manrope en todos los textos, con pesos asignados por función.
- Composición editorial de bordes rectos, líneas finas y círculos como motivo secundario.
- Movimiento lento que explica la relación entre criterio humano y construcción tecnológica.

## Colors

El marfil da aire al contenido; la tinta sostiene la lectura; el cobalto dirige la atención hacia ideas y acciones importantes.

### Primary

- **Cobalto** (`{colors.accent}`, `#2858cc`): CTA principal, palabras clave del hero, trazos del engranaje, puntos de conexión y estados de foco.
- **Cobalto profundo** (`{colors.accent-deep}`, `#1d4299`): hover, enlaces y etiquetas que necesitan contraste sobre superficies claras.

### Neutral

- **Marfil base** (`{colors.paper}`, `#f4f2eb`): fondo principal.
- **Marfil luminoso** (`{colors.paper-strong}`, `#fffefa`): secciones de respiro, superficies puntuales y texto de botones azules o paneles oscuros.
- **Tinta** (`{colors.ink}`, `#182230`): títulos, texto principal y panel final de contacto.
- **Gris de lectura** (`{colors.muted}`, `#596575`): párrafos secundarios y metadatos legibles.
- **Azul niebla** (`{colors.sand}`, `#e2e7f0`): superficie secundaria de apoyo, especialmente alrededor de imágenes de proyectos.
- **Línea** (`{colors.line}`, `#cfd5df`): divisores, bordes y estructura de las retículas.

**Regla de acento:** el cobalto debe señalar decisiones, acciones o conexiones. No llenar paneles enteros de azul solo para que parezcan tecnológicos.

**Regla de proyectos:** los colores de FIPQ y Witchu pueden aparecer dentro de sus capturas o piezas visuales y en los detalles que describen el caso. No pasan a la navegación, los botones ni las demás secciones de Tukur.

## Typography

**Familia única:** Manrope, con `sans-serif` como respaldo. Su geometría limpia sostiene el carácter tecnológico; el ritmo, la escala y el espacio permiten la expresión artística sin agregar otra fuente.

### Jerarquía

- **Texto que acompaña al logo y títulos:** Manrope Semibold `600` o Bold `700`. Las letras ya integradas en el PNG original se conservan intactas. El titular principal usa `700`, `clamp(48px, 6.5vw, 88px)`, una interlínea de `0.99` y un interletrado de `-0.035em`.
- **Encabezados de sección:** Manrope `700`, aproximadamente `clamp(36px, 5vw, 62px)`, interlínea `1.04`.
- **Títulos de servicio y proyecto:** Manrope `600` o `700`, de `20px` a `26px` según la jerarquía.
- **Textos y párrafos:** Manrope Regular `400`, normalmente de `14px` a `19px`, con interlínea generosa cercana a `1.75`. Evitar renglones demasiado largos.
- **Botones y etiquetas:** Manrope Medium `500`, con tamaño que siga siendo legible. Las mayúsculas se reservan para etiquetas breves; los párrafos se escriben en caja normal.

**Regla de peso:** los pesos de la línea anterior son la guía de marca definida por el usuario. Los botones y etiquetas del sitio usan `500`; los títulos y el texto junto al logo usan `600` o `700`.

## Layout

El contenido ocupa hasta `1240px` y se centra. El margen lateral es de `32px` en escritorio, `22px` hasta `820px` y `20px` hasta `760px`. Las secciones se separan con líneas finas y un espacio vertical de `clamp(70px, 9vw, 118px)`; en móvil el espacio ronda `68px`.

El hero usa dos columnas para equilibrar mensaje y logo; en móvil se apilan. La comparación entre inteligencia natural y artificial es de dos columnas en escritorio y una en móvil. Los servicios pasan de tres columnas a una; los casos pasan de dos a una. En todos los tamaños, el contenido debe leerse en el mismo orden lógico: propuesta, filosofía, servicios, proceso, trabajos y contacto.

La página combina márgenes amplios con bloques densos de información útil. No comprimir los proyectos hasta convertirlos en miniaturas: cada caso necesita suficiente espacio para mostrar el trabajo real, explicar el aporte de Tukur y ofrecer un enlace claro al resultado publicado.

## Elevation & Depth

La página es principalmente plana. Los divisores y los cambios entre marfil y tinta crean estructura. La navegación móvil, las etiquetas y el control de movimiento se separan con bordes y superficies; el logo recibe un halo cobalto y un `drop-shadow` externo para destacarlo sin modificar los píxeles del archivo.

El panel de contacto usa tinta oscura como cierre visual. Los círculos tenues de su fondo y los anillos alrededor del búho aportan profundidad sin competir con el mensaje ni con el botón de contacto.

## Shapes

Los botones, tarjetas y paneles tienen esquinas rectas. Los contornos finos y las separaciones lineales expresan orden. Los círculos pertenecen al universo del búho, el engranaje, el halo y los puntos de conexión; son un motivo con significado, no una decoración para repetir en cada elemento.

El activo oficial es [`assets/tukur-logo-original.png`](assets/tukur-logo-original.png), PNG RGBA transparente de `422 × 497`, idéntico al archivo original del workspace. Mantener su proporción y área de seguridad visual. Se permite cambiar el color del entorno y añadir luz mediante CSS alrededor del logo; no estirar, recortar, redibujar, sustituir letras, recolorear ni añadir elementos dentro del propio PNG.

## Components

### Botones y enlaces

- **Primario:** recto, cobalto con texto marfil, alto mínimo de `48px` y relleno actual de `13px 18px`. En hover pasa a cobalto profundo; el movimiento de `-2px` es breve y secundario.
- **Secundario:** superficie clara, borde fino y tinta. En hover cambia borde y texto hacia cobalto profundo.
- **Enlace editorial:** subrayado visible, texto cobalto profundo y flecha ascendente cuando conduce al contacto o a una página publicada.
- **Foco:** contorno de `3px` en cobalto, separado `4px` del elemento. Conservar al menos `44 × 44px` de área operable para controles táctiles.

### Navegación

Barra superior pegajosa con logo a la izquierda, enlaces directos a secciones y un CTA de contacto. En móvil los enlaces se muestran en un panel vertical controlado por un botón de menú con estado accesible; Escape lo cierra. La navegación debe ayudar a encontrar servicios, proyectos y contacto de inmediato.

### Comparación de inteligencias

Dos bloques simétricos con un trazo de conexión. La inteligencia natural comprende, analiza, decide y diseña; la artificial ayuda a explorar y construir bajo dirección humana. La ilustración puede animarse, pero el texto siempre debe explicar la idea por sí solo.

### Servicios y proceso

Los divisores ordenan los servicios sin añadir iconos genéricos. Cada servicio dice qué problema ayuda a resolver. La numeración se reserva para los tres pasos del proceso: escuchar, definir y construir con el cliente.

### Casos de trabajo

Cada caso debe mostrar una imagen reconocible del proyecto publicado, su nombre, el problema que resolvía, el aporte concreto de Tukur y un enlace al sitio. Las capturas son evidencia de trabajo, no decoración. Si se usa una composición editorial adicional, distinguirla de una captura real. No atribuir resultados, métricas ni tareas que el proyecto no documente.

### Escenario del logo y movimiento

El logo es el punto focal; el engranaje gira lentamente (`52s` por vuelta) y una señal recorre la conexión (`5.5s`). Las transiciones de interacción duran cerca de `0.2s`. Mantener el control visible para reducir animaciones y respetar `prefers-reduced-motion`. El movimiento comunica colaboración y proceso; nunca condiciona la lectura ni el acceso a contenido.

## Do's and Don'ts

### Do

- **Do** usar el PNG original transparente y darle presencia con espacio, escala y luz externa.
- **Do** mantener la secuencia marfil → información clara → trabajo real → panel de contacto oscuro.
- **Do** aplicar Manrope con los pesos de marca: `600/700` títulos, `400` párrafos y `500` botones y etiquetas.
- **Do** reservar el cobalto para llamadas a la acción, enlaces, foco y conexiones visuales.
- **Do** mostrar el aporte de Tukur junto al trabajo de cada cliente, con crédito preciso.
- **Do** permitir que la experiencia funcione sin animación y con teclado.

### Don't

- **Don't** modificar la forma, color, letras o proporción del logo.
- **Don't** tomar los colores de un cliente como colores generales de Tukur.
- **Don't** añadir degradados, vidrio, brillos o chips decorativos que desplacen el trabajo y el mensaje.
- **Don't** usar ilustraciones genéricas de IA para representar el criterio humano.
- **Don't** usar mayúsculas en párrafos ni etiquetas diminutas para sostener el estilo editorial.
- **Don't** presentar automatización, datos o resultados como capacidades comprobadas por un caso si no hay evidencia pública de ese trabajo.
