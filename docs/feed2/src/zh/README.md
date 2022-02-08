---
home: true
title: 主页
icon: home
heroImage: /logo.svg
heroText: vuepress-plugin-feed2
tagline: 为 VuePress2 提供 Feed 生成
actions:
  - text: 快速上手 💡
    link: /zh/guide.html
    type: primary

  - text: 配置 🛠
    link: /zh/config/

footer: MIT Licensed | Copyright © 2019-present Mr.Hope
copyright: false
---

## 使用插件

### 安装

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

### 使用

:::: code-group

::: code-group-item ts

```js
// .vuepress/config.js
import { feed } from "vuepress-plugin-feed2";

module.exports = {
  plugins: [
    feed({
      // 插件选项
    }),
  ],
};
```

:::

::: code-group-item js

```ts
// .vuepress/config.ts
const { feed } = require("vuepress-plugin-feed2");

module.exports = {
  plugins: [
    feed({
      // 插件选项
    }),
  ],
};
```

:::

::::
