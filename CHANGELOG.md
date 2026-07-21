# Changelog

Todas las novedades notables de **FontTest** se documentan en este archivo.

El formato se basa en [Keep a Changelog](https://keepachangelog.com/es-ES/1.1.0/)
y el proyecto sigue [Versionado Semántico](https://semver.org/lang/es/):
**X.Y.Z** = X cambios extremos/reworks · Y cambios medio-grandes/funciones · Z retoques, bugfixes, hotfixes.

## [1.1.1] - 2026-07-21
### Añadido
- **Japonés** (日本語) como 11.º idioma disponible, con su propio texto de ejemplo y pangrama (いろは).

[1.1.1]: https://github.com/SirAxelloid1460/FontTest/releases/tag/v1.1.1

## [1.1.0] - 2026-07-21
### Añadido
- **Localización a 10 idiomas** (los más hablados): inglés, chino simplificado, hindi, español, francés, árabe, bengalí, portugués, ruso y urdu. **Selector de idioma** en la cabecera.
- Soporte de escritura **RTL** (derecha a izquierda) para árabe y urdu.
- **Detección automática** del idioma del navegador y **memoria** de la preferencia elegida (localStorage).
- Cada idioma incluye su propio **texto de ejemplo** y **pangrama**.

### Cambiado
- Toda la interfaz y los mensajes (importación, errores, avisos de CORS) ahora son traducibles.

[1.1.0]: https://github.com/SirAxelloid1460/FontTest/releases/tag/v1.1.0

## [1.0.0] - 2026-07-21
### Añadido
- Previsualización de fuentes **.ttf / .otf / .woff / .woff2** en una app HTML única, 100 % offline y sin dependencias.
- Importar fuentes **arrastrando** o desde el selector de archivos. Admite **.zip**: se descomprime en memoria con el motor nativo del navegador (`DecompressionStream`) y carga todas las fuentes que contenga.
- Importar **desde un enlace** (requiere internet): archivo directo, **.zip**, **Google Fonts** / hojas CSS con `@font-face`, y páginas web (best-effort). El tipo se detecta por la **firma de bytes**, así que funcionan enlaces de descarga sin extensión.
- **Descargar** cada fuente cargada con un clic, reutilizando la copia en memoria (funciona incluso sin conexión). Icono de descarga en SVG.
- Controles de **tamaño, grosor, interletrado e interlineado**.
- Estilos: cursiva, subrayado, MAYÚSCULAS y colores de texto/fondo.
- Vistas: texto propio, pangrama, abecedario completo y escala de tamaños.
- Aviso claro cuando un sitio bloquea el acceso por **CORS**, indicando descargar el archivo/`.zip` e importarlo manualmente.
- Licencia **GNU General Public License v3**.

[1.0.0]: https://github.com/SirAxelloid1460/FontTest/releases/tag/v1.0.0
