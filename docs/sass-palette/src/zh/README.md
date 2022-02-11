---
home: true
title: 主页
icon: home
heroImage: /logo.svg
heroText: vuepress-plugin-sass-palette
tagline: 为 VuePress2 提供代码块一键复制
actions:
  - text: 快速上手 💡
    link: /zh/guide.html
    type: primary

  - text: 配置 🛠
    link: /zh/config.html

footer: MIT Licensed | Copyright © 2019-present Mr.Hope
copyright: false
---

## 使用插件

### 安装

:::: code-group

::: code-group-item yarn

```bash
yarn add -D vuepress-plugin-sass-palette@next
```

:::

::: code-group-item npm

```bash
npm i -D vuepress-plugin-sass-palette@next
```

:::

::::

### 使用

您必须在插件初始化期间调用 `useSassPalettePlugin` 函数来使用此插件。。

:::: code-group

::: code-group-item ts

```ts
// 你的插件或主题入口
import { useSassPalettePlugin } from "vuepress-plugin-sass-palette";
import type { Plugin } from "@vuepress/core";

const yourPlugin: Plugin = (options, app) => {
  useSassPalettePlugin(app, {
    // 插件选项
  });

  return {
    // 你的插件 API
  };
};

export default yourPlugin;
```

:::

::: code-group-item js

```js
// 你的插件或主题入口
const { useSassPalettePlugin } = require("vuepress-plugin-sass-palette");

module.exports = (options, app) => {
  useSassPalettePlugin(app, {
    // 插件选项
  });

  return {
    // 你的插件 API
  };
};
```

:::

::::
