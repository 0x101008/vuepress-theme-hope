---
home: true
title: Home
icon: home
heroImage: /logo.svg
heroText: vuepress-plugin-feed2
tagline: Feed plugin for vuepress
actions:
  - text: Guide 💡
    link: /guide/
    type: primary

  - text: Config 🛠
    link: /config/

footer: MIT Licensed | Copyright © 2019-present Mr.Hope
copyrightText: false
---

## How to use

### Install

:::: code-group

::: code-group-item yarn

```bash
yarn add -D vuepress-plugin-feed2@next
```

:::

::: code-group-item npm

```bash
npm i -D vuepress-plugin-feed2@next
```

:::

::::

### Usage

:::: code-group

::: code-group-item ts

```ts
// .vuepress/config.ts
import { feed } from "vuepress-plugin-feed2";

export default {
  plugins: [
    feed({
      // your options
    }),
  ],
};
```

:::

::: code-group-item js

```js
// .vuepress/config.js
const { feed } = require("vuepress-plugin-feed2");

module.exports = {
  plugins: [
    feed({
      // your options
    }),
  ],
};
```

:::

::::
