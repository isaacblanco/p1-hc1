# P1 HTML & CSS I - Disturbed

## Refereces

## Requirements

[Node.js](http://nodejs.org/) >= 14.15.x

## Features

- Usa [Parcel v2](https://parceljs.org).

### Stylesheets

- [Sass/SCSS](https://sass-lang.com) compilación de estilos y minificación con [`cssnano`](https://github.com/cssnano/cssnano) (`@parcel/optimizer-cssnano`).

### HTML

- Minificación del html con [`htmlnano`](https://github.com/posthtml/htmlnano) (`@parcel/optimizer-htmlnano`).
- [PostHTML](https://github.com/posthtml/posthtml) incluye:
  - Incluye HTML parciales con [`posthtml-include`](https://github.com/posthtml/posthtml-include). De esta forma puedo reclicar partes en archivos mas pequeños.

### Scripts

- Permite Javascript modernos (ES201x/ES8/ES7/ES6…) desde [Babel](https://babeljs.io/).

### Imagenes

- Transformaciones con [`@parcel/transformer-image`](https://parceljs.org/recipes/image/) (basedo en [`sharp`](https://sharp.pixelplumbing.com/)).

### Comandos

| Comando         | Descripción                                                                                                                             |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| `npm run dev`   | Lanza el servidor para desarrollo, abriendo el navegador en local. Se compilan los ficheros de `src`.                                   |
| `npm run build` | Realiza la compilación minificando los ficheros. El resultado se va a la carpeta `dist/`. Dicha carpeta es la que se publica en la web. |
| `npm run clean` | Borra el contenido `/dist` y la cache.                                                                                                  |
| `npm run test`  | Muestra si todo esta funcionando.                                                                                                       |
