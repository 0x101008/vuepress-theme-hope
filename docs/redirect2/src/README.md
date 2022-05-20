---
home: true
title: Home
icon: home
heroImage: /logo.svg
heroText: vuepress-plugin-redirect2
tagline: Redirect Plugin for VuePress2
action:
  - text: Guide 💡
    link: /guide.html
    type: primary

  - text: Config 🛠
    link: /config.html

footer: MIT Licensed | Copyright © 2019-present Mr.Hope
copyrightText: false
---

## How to use

### Install

::: code-tabs

@codetab pnpm

```bash
pnpm add -D vuepress-plugin-redirect2@next
```

@codetab yarn

```bash
yarn add -D vuepress-plugin-redirect2@next
```

@codetab npm

```bash
npm i -D vuepress-plugin-redirect2@next
```

:::

### Usage

::: code-tabs

@codetab TS

```ts
// .vuepress/config.ts
import { redirectPlugin } from "vuepress-plugin-redirect2";

export default {
  plugins: [
    redirectPlugin({
      // your options
    }),
  ],
};
```

@codetab JS

```js
// .vuepress/config.js
const { redirectPlugin } = require("vuepress-plugin-redirect2");

module.exports = {
  plugins: [
    redirectPlugin({
      // your options
    }),
  ],
};
```

:::
