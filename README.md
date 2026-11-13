# TALE Sinaloa 2026 — Sitio web

Sitio estático hecho con HTML5, CSS y JavaScript puro. No requiere instalación, compilación ni dependencias externas.

## IMPORTANTE: estructura necesaria para evitar el error 404

Al subir el sitio, **`index.html` debe quedar directamente en la raíz de la rama/carpeta que publica GitHub Pages**. No debe quedar dentro de otra carpeta llamada `TALE-Sinaloa-2026`.

La estructura correcta del repositorio es:

```text
repositorio/
├── index.html
├── proyecto.html
├── identidad.html
├── galeria.html
├── 404.html
├── styles.css
├── script.js
├── .nojekyll
├── assets/
│   ├── logo-tale-circular.png
│   ├── logo-tale-horizontal.png
│   ├── identidad-visual-tale.png
│   └── nebula-bg.webp
└── README.md
```

## Publicar en GitHub Pages

1. Descarga y **descomprime** el ZIP en tu computadora.
2. Abre la carpeta descomprimida. Selecciona todo lo que está dentro: `index.html`, las páginas `.html`, `styles.css`, `script.js`, `assets/`, `.nojekyll` y `README.md`.
3. Sube esos elementos a la **raíz del repositorio**. Al entrar al repositorio en GitHub, debes ver `index.html` al mismo nivel que `styles.css`, no una carpeta que contenga todos los archivos.
4. En GitHub abre **Settings → Pages**.
5. En **Build and deployment**, selecciona **Deploy from a branch**.
6. Selecciona la rama `main` y la carpeta `/(root)`. Pulsa **Save**.
7. Abre la URL que aparece en **Settings → Pages**. No abras la dirección del repositorio (`github.com/...`), porque esa es la página de código, no el sitio publicado.
8. En **Actions**, comprueba que el despliegue de Pages haya terminado correctamente.

### Dirección del sitio

- Repositorio de usuario (por ejemplo, `usuario.github.io`): `https://usuario.github.io/`
- Repositorio de proyecto (por ejemplo, `TALE-Sinaloa-2026`): `https://usuario.github.io/TALE-Sinaloa-2026/`

GitHub muestra la dirección exacta en **Settings → Pages**. Sustituye `usuario` y el nombre del repositorio por los tuyos.

## Si todavía aparece 404

- Confirma que `index.html` está en la raíz de la rama publicada y que el nombre está escrito exactamente en minúsculas.
- Confirma que Pages publica desde la misma rama donde subiste los archivos (`main`) y desde `/(root)`.
- Confirma que el despliegue más reciente en **Actions** terminó sin errores.
- Usa la URL indicada en **Settings → Pages** y añade la ruta del repositorio cuando sea un sitio de proyecto.

## Contenido

- `index.html`: portada principal.
- `proyecto.html`: presentación del concepto TALE.
- `identidad.html`: identidad visual, colores, usos y especificaciones.
- `galeria.html`: imágenes originales y descargas.
- `404.html`: página personalizada para rutas inexistentes.
- `styles.css`: diseño adaptable, fondo y animaciones.
- `script.js`: menú móvil.
- `assets/`: logotipos, lámina de identidad y fondo espacial.

Conserva la estructura y los nombres de los archivos: las páginas utilizan rutas relativas para funcionar tanto en un sitio de usuario como en un repositorio de proyecto.
