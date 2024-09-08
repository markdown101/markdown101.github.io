---
title: HTML
syntax-id: html
---

许多 Markdown 应用程序允许你在 Markdown 格式化的文本中使用 HTML 标签。如果你更喜欢使用某些 HTML 标签而不是 Markdown 语法，这会很有帮助。例如，有些人发现使用 HTML 标签来处理图片更为方便。使用 HTML 也有助于在需要更改元素属性时，例如指定 [文本颜色](/hacks/#color) 或更改图片的宽度。

要使用 HTML，请将标签放入你的 Markdown 格式化文件的文本中。

```
这个 **字体** 是粗体。 这个 <em>字体</em> 是斜体。
```

渲染输出看起来是这样的：

这个 **字体** 是粗体。 这个 <em>字体</em> 是斜体。

### HTML 最佳实践

出于安全考虑，并非所有 Markdown 应用程序都支持 Markdown 文档中的 HTML。在不确定时，请检查你的 Markdown 应用程序的文档。一些应用程序只支持 HTML 标签的子集。

使用空行将块级 HTML 元素（如 `<div>`，`<table>`，`<pre>`，`<p>` ）与周围内容分开。尽量不要用制表符或空格缩进标签，因为这可能会影响格式。

你不能在块级 HTML 标签内部使用 Markdown 语法。例如， `<p>italic and **bold**</p>` 是无效的。
