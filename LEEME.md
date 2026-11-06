# Mi rutina

App instalable para iPhone con tu horario, entreno, comida, progreso de peso e idea del día.

## Archivos

- `index.html`: la app.
- `manifest.webmanifest`: nombre, icono y modo pantalla completa.
- `sw.js`: hace que funcione sin internet.
- `icons/`: iconos de la app.

## Publicarla gratis con GitHub Pages

1. Entra en github.com y crea una cuenta si no tienes.
2. Pulsa **New repository**, ponle de nombre `mi-rutina`, márcalo como **Public** y créalo.
3. En el repositorio, pulsa **uploading an existing file** y arrastra todos los archivos de esta carpeta, incluida la carpeta `icons`. Pulsa **Commit changes**.
4. Ve a **Settings > Pages**. En **Branch** elige `main` y la carpeta `/ (root)`, y pulsa **Save**.
5. Espera 1 o 2 minutos. Tu app estará en `https://TU-USUARIO.github.io/mi-rutina/`.

## Instalarla en el iPhone

1. Abre ese enlace en **Safari** (tiene que ser Safari).
2. Pulsa el botón de compartir y elige **Añadir a pantalla de inicio**.
3. Ábrela siempre desde el icono, no desde Safari, para que se vea a pantalla completa.

## Si cambias algo

Sube el archivo nuevo a GitHub y, en `sw.js`, cambia `mi-rutina-v1` por `mi-rutina-v2` (y así cada vez). Cierra y vuelve a abrir la app para ver los cambios.

## Importante

Tus datos (pesos, casillas marcadas, ideas guardadas) se guardan solo en tu iPhone. Si borras la app de la pantalla de inicio, se borran también.
