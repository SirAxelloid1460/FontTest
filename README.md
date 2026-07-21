# 🔤 FontTest — versión web (GitHub Pages)

App para **probar fuentes** `.ttf`, `.otf`, `.woff` y `.woff2` directamente en el navegador.
Un único `index.html` estático, sin build ni dependencias.

- **Repositorio:** <https://github.com/SirAxelloid1460/FontTest>
- **App en vivo:** <https://siraxelloid1460.github.io/FontTest/>
- **Novedades:** ver [CHANGELOG.md](CHANGELOG.md)

## Publicar en GitHub Pages

1. Sube el contenido de esta carpeta (`index.html`, `.nojekyll`, `README.md`, `LICENSE`) a la raíz de la rama `main` del repo `FontTest`.
2. En el repo: **Settings → Pages**.
3. En *Build and deployment* → *Source*: **Deploy from a branch**.
4. Elige la rama `main` y la carpeta `/ (root)`. Guarda.
5. En 1-2 minutos la app estará en:
   <https://siraxelloid1460.github.io/FontTest/>

El archivo `.nojekyll` evita que GitHub procese el sitio con Jekyll (no es necesario para un HTML, pero es buena práctica).

## Notas al servir por HTTPS

- Al importar **desde un enlace**, usa siempre URLs `https://` (una página `https` bloquea recursos `http` por *mixed content*).
- El límite de **CORS** sigue igual: algunos sitios (fontspace, itch.io…) no permiten leer sus páginas/descargas.
  En ese caso, descarga el archivo o `.zip` e **impórtalo** arrastrándolo (los `.zip` se cargan solos).
- Todo el procesamiento es en el navegador del visitante; las fuentes no se suben a ningún servidor.

## Licencia

Copyright (C) 2026 SirAxelloid1460

**GNU General Public License v3** (o posterior). Software libre, SIN GARANTÍA.
Ver el archivo [LICENSE](LICENSE) o <https://www.gnu.org/licenses/>.
