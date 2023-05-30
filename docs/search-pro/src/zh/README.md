---
home: true
title: 主页
icon: home
heroImage: /logo.svg
heroText: vuepress-plugin-search-pro
tagline: VuePress2 的客户端搜索插件
actions:
  - text: 快速上手 💡
    link: /zh/guide.html
    type: primary

  - text: 配置 🛠
    link: /zh/config.html

features:
  - title: 高性能
    icon: rocket
    details: 在由 <a href="https://mister-hope.github.io/slimsearch/" _target="_blank">slimsearch</a> 提供支持的独立工作人员中进行高速搜索

  - title: 全索引
    icon: file-zipper
    details: 索引您站点中的所有内容

  - title: 突出显示和上下文
    icon: highlighter
    details: 突出显示关键字并在搜索结果中显示相关上下文

  - title: 自动建议
    icon: lightbulb
    details: 在输入时获取查询建议

  - title: 自定义字段
    icon: gears
    details: 使用选项将数据添加到索引

  - title: 搜索历史
    icon: clock
    details: 保留查询和结果的历史记录

footer: MIT Licensed | Copyright © 2022-present Mr.Hope
copyrightText: false
---

## 使用插件

### 安装

::: code-tabs#shell

@tab pnpm

```bash
pnpm add -D vuepress-plugin-search-pro
```

@tab yarn

```bash
yarn add -D vuepress-plugin-search-pro
```

@tab npm

```bash
npm i -D vuepress-plugin-search-pro
```

:::

### 使用

::: code-tabs#language

@tab TS

```ts
// .vuepress/config.ts
import { searchProPlugin } from "vuepress-plugin-search-pro";

export default {
  plugins: [
    searchProPlugin({
      // 配置选项
    }),
  ],
};
```

@tab JS

```js
// .vuepress/config.js
import { searchProPlugin } from "vuepress-plugin-search-pro";

export default {
  plugins: [
    searchProPlugin({
      // 配置选项
    }),
  ],
};
```

:::

<NetlifyBadge alt="通过 Netlify 部署" />

<script setup lang="ts">
import NetlifyBadge from "@NetlifyBadge";
</script>
