---
title: Markmap
icon: fab fa-markdown
---

<!-- #region before -->

Let the Markdown file support markmap in your VuePress site.

<!-- more -->

## Settings

Install `markmap-lib`, `markup-toolbar` and `markmap-view` in your project:

::: code-tabs#shell

@tab pnpm

```bash
pnpm add -D markmap-lib markup-toolbar markmap-view
```

@tab yarn

```bash
yarn add -D markmap-lib markup-toolbar markmap-view
```

@tab npm

```bash
npm i -D markmap-lib markup-toolbar markmap-view
```

:::

Then enabling via:

<!-- #endregion before -->

::: code-tabs#language

@tab TS

```ts {8}
// .vuepress/config.ts
import { mdEnhancePlugin } from "vuepress-plugin-md-enhance";

export default {
  plugins: [
    mdEnhancePlugin({
      // Enable Markmap
      markmap: true,
    }),
  ],
};
```

@tab JS

```js {8}
// .vuepress/config.js
import { mdEnhancePlugin } from "vuepress-plugin-md-enhance";

export default {
  plugins: [
    mdEnhancePlugin({
      // Enable Markmap
      markmap: true,
    }),
  ],
};
```

:::

<!-- region after -->

## Syntax

````md
```markmap
<!-- contents here -->
```
````

Configuring through frontmatter syntax is supported.

## Demo

::: md-demo

````markmap
---
markmap:
  colorFreezeLevel: 2
---

# markmap

## Links

- <https://markmap.js.org/>
- [GitHub](https://github.com/markmap/markmap)

## Features

- links
- **strong** ~~del~~ *italic* ==highlight==
- multiline
  text
- `inline code`
-
    ```js
    console.log('code block');
    ```
- Katex
  - $x = {-b \pm \sqrt{b^2-4ac} \over 2a}$
  - [More Katex Examples](#?d=gist:af76a4c245b302206b16aec503dbe07b:katex.md)
- Now we can wrap very very very very long text based on `maxWidth` option
````

:::