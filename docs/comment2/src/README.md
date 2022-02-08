---
home: true
title: Home
icon: home
heroImage: /logo.svg
heroText: vuepress-plugin-comment2
tagline: Comment and pageview plugin for VuePress2
actions:
  - text: Get Started 💡
    link: /guide/
    type: primary

  - text: Config 🛠
    link: /config/

footer: MIT Licensed | Copyright © 2019-present Mr.Hope
copyright: false
---

## Install

:::: code-group

::: code-group-item yarn

```bash
yarn add -D vuepress-plugin-comment2@next
```

:::

::: code-group-item npm

```bash
npm i -D vuepress-plugin-comment2@next
```

:::

::::

### Usage

:::: code-group

::: code-group-item ts

```ts
// .vuepress/config.ts
import { comment } from "vuepress-plugin-comment2";

export default {
  plugins: [
    comment({
      // your options
    }),
  ],
};
```

:::

::: code-group-item js

```js
// .vuepress/config.js
const { comment } = require("vuepress-plugin-comment2");

module.exports = {
  plugins: [
    comment({
      // your options
    }),
  ],
};
```

:::

::::
