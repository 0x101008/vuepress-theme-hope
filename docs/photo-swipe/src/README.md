---
home: true
title: Home
icon: home
heroImage: /logo.svg
heroText: vuepress-plugin-photo-swipe
tagline: Photo swipe plugin for vuepress
actions:
  - text: Guide 💡
    link: /guide.html
    type: primary

  - text: Config 🛠
    link: /config.html

footer: MIT Licensed | Copyright © 2019-present Mr.Hope
copyrightText: false
---

Let your images support preview, zoom, share, swipe view and download.

## How to use

### Install

:::: code-group

::: code-group-item yarn

```bash
yarn add -D vuepress-plugin-photo-swipe@next
```

:::

::: code-group-item npm

```bash
npm i -D vuepress-plugin-photo-swipe@next
```

:::

::::

### Usage

:::: code-group

::: code-group-item ts

```ts
// .vuepress/config.ts
import { photoSwipe } from "vuepress-plugin-photo-swipe";

export default {
  plugins: [
    photoSwipe({
      // your options
    }),
  ],
};
```

:::

::: code-group-item js

```js
// .vuepress/config.js
const { photoSwipe } = require("vuepress-plugin-photo-swipe");

module.exports = {
  plugins: [
    photoSwipe({
      // your options
    }),
  ],
};
```

:::

::::
