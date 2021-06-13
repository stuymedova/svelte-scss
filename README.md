# Svelte + Sass and PostCSS

Svelte template with Sass SCSS and PostCSS Autoprefixer configured.

This setup uses `rollup-plugin-scss` to preprocess `.scss` files. To preprocess SCSS inside Svelte `<style>` tags, set up a preprocessor such as [Svelte Preprocess](https://github.com/sveltejs/svelte-preprocess). For more information, refer [Svelte Preprocess docs](https://github.com/sveltejs/svelte-preprocess/tree/main/docs).

## Overview

SCSS files are located in `src/styles`.

```
.
└── src
    ├── App.svelte
    ├── main.js
    └── styles
        ├── components
        │   ├── _button.scss
        │   ├── _mixins.scss
        │   └── _variables.scss
        ├── typography
        │   ├── _font-face.scss
        │   ├── _mixins.scss
        │   ├── _type-scale.scss
        │   └── _typography.scss
        ├── _page.scss
        ├── _reset.scss
        └── main.scss
```

## Prerequesites

[Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/)

## Setup

Run in terminal:
```
npm install
npm run dev
npm run build
```

## Result

<img width="1552" alt="svelte-sass-postcss" src="https://user-images.githubusercontent.com/53351370/121812850-1ffdd900-cc72-11eb-81ac-774842b77ec0.png">

Utilizes [Carbon Design System](https://github.com/carbon-design-system/carbon) licensed under the Apache 2.0 License.
