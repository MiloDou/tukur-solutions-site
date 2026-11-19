# Tukur Solutions — sitio de marca

Sitio estático responsive, hecho en HTML, CSS y JavaScript sin dependencias de compilación. La dirección visual usa una paleta formal de marfil y cobalto, Manrope y el PNG transparente original del logo, sin alterarlo. Las reglas de marca están en `DESIGN.md`.

## Vista previa local

Abrí `index.html` en un navegador. Para probarlo con un servidor local, desde esta carpeta ejecutá:

```sh
python3 -m http.server 8000
```

Después visitá `http://localhost:8000`.

## Publicar con Cloudflare Pages desde GitHub

1. Subí esta carpeta a un repositorio propio.
2. En Cloudflare, abrí **Workers & Pages → Create → Pages → Connect to Git** y seleccioná el repositorio.
3. Para este sitio estático, dejá vacíos el comando de compilación y la carpeta de salida en la raíz del proyecto.
4. Cloudflare asignará una dirección `*.pages.dev`; luego podés agregar tu dominio en **Custom domains**.

## Portafolio

Las tarjetas de FIPQ y Witchu muestran capturas reales y optimizadas de las páginas públicas. El aporte y la entrega de cada proyecto están visibles antes de abrir los detalles. Los colores propios de cada proyecto aparecen dentro de su captura; la interfaz de Tukur mantiene su paleta de marfil y cobalto.

La oferta principal publicada se concentra en sitios web, portafolios y dirección digital. Las necesidades de automatización, integraciones y análisis de datos se evalúan según alcance y equipo, como expresa el cuestionario de Tukur.

## Antes de anunciarlo como sitio oficial

- Elegir el dominio oficial. En cuanto exista, agregar en el `<head>` de `index.html` una URL absoluta para `rel="canonical"`, `og:url` y `og:image` (y `twitter:image` si se usa una imagen social). El título, la descripción, el tipo de página y el idioma social ya están preparados.
