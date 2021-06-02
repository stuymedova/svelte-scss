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

## Setup

Run in terminal:
```
npm i
npm run dev/build
```

## Result

<img width="1440" alt="svelte-sass-postcss" src="https://user-images.githubusercontent.com/53351370/120441917-c05c1f80-c38d-11eb-97e1-aaa97b988a79.png">

Utilizes [Carbon Design System](https://github.com/carbon-design-system/carbon) licensed under the Apache 2.0 License.
