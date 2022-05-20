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

@tab pnpm

```bash
pnpm add -D vuepress-plugin-redirect2@next
```

@tab yarn

```bash
yarn add -D vuepress-plugin-redirect2@next
```

@tab npm

```bash
npm i -D vuepress-plugin-redirect2@next
```

:::

### Usage

::: code-tabs

@tab TS

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

@tab JS

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
