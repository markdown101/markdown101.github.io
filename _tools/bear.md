---
title: 熊掌记
category: 笔记
description: "熊掌记是一款适用于 macOS 和 iOS 设备的 Markdown 笔记软件。"
icon: bear.png
website: https://bear.app
syntax:
  - id: headings
    available: p
    notes: "[Alternative syntax](/basic-syntax/#alternate-syntax) is not supported."
  - id: paragraphs
    available: y
  - id: line-breaks
    available: p
    notes: "The Markdown syntax (trailing whitespace) is not supported, but you can press the Return key once to achieve the same result."
  - id: bold
    available: y
  - id: italic
    available: y
  - id: blockquotes
    available: p
    notes: "[Nested blockquotes](/basic-syntax/#nested-blockquotes) are not supported."
  - id: ordered-lists
    available: y
  - id: unordered-lists
    available: y
  - id: code
    available: y
  - id: horizontal-rules
    available: y
  - id: links
    available: y
    notes: "You can link to other notes by enclosing a note's name in double brackets (i.e., `[[note-name]]`)."
  - id: images
    available: n
    notes: "The Markdown syntax is not supported, but you can drag and drop images into a note."
  - id: tables
    available: n
  - id: fenced-code-blocks
    available: y
  - id: syntax-highlighting
    available: y
  - id: footnotes
    available: n
  - id: heading-ids
    available: p
    notes: "Automatically generated. There's no way to set custom heading IDs. You can copy a link to a heading by clicking the **H#** symbol next to the heading in the margin and selecting **Copy Link to Here**. See the [documentation](https://bear.app/faq/Tags%20&%20Linking/How%20to%20link%20notes%20together/) for more information."
  - id: definition-lists
    available: n
  - id: strikethrough
    available: y
  - id: task-lists
    available: y
  - id: emoji-cp
    available: y
  - id: emoji-sc
    available: y
  - id: highlight
    available: y
    notes: "Use two colons instead of equal signs (e.g., `::word or phrase::`)."
  - id: subscript
    available: n
  - id: superscript
    available: n
  - id: auto-url-linking
    available: y
  - id: disabling-auto-url
    available: y
  - id: html
    available: p
    notes: "HTML is not rendered in Bear notes, but it is apparently rendered in the HTML output from exported notes."
see-also:
  - name: Bear Markdown compatibility mode
    link: https://bear.app/faq/Markup%20:%20Markdown/Markdown%20compatibility%20mode/
---

[熊掌记](https://bear.app) 是一款 macOS 和 iOS 应用程序，专为一件事而设计：记笔记。 它就像 Evernote，但没有臃肿。它就像 [印象笔记](https://evernote.com/)，但没有臃肿。

Bear 中并没有很多爆款功能。相反，Bear 始终如一地兑现其所有承诺。标签、搜索和同步都可以完美运行。该应用程序非常直观，这正是你做笔记时想要的。

{% include image.html file="/assets/images/tools/bear.png" alt="熊掌记中的 Markdown" %}

默认情况下，熊掌记不会自动启用对 Markdown 的支持，但你可以在[首选项](#enabling-markdown-support)中启用它。该应用程序有一个混合的实时编辑器和文本编辑器——你可以看到 Markdown 语法和格式更改文本的方式。需要一段时间才能习惯，但如果你刚刚开始使用 Markdown，它会很有用。

### 开启 Markdown 支持

要在熊掌记中启用 Markdown 支持，请打开“首选项”窗口。在 **通用选项卡** 上，打开 **arkdown 兼容模式** 的设置。

<div class="alert alert-success">
  <i class="fas fa-lightbulb"></i> <strong>提示：</strong> 如果你在多台设备上使用熊掌记，则需要在所有设备上启用 Markdown 兼容模式设置。
</div>

{% include tool-syntax-table.html %}

### 支持其他语法

作为额外的功能，熊掌记提供了对几个不起眼的元素的支持。

<table class="table table-bordered" style="font-size: 14px">
  <thead class="thead-light">
    <tr>
      <th>元素</th>
      <th>Markdown</th>
      <th>渲染输出</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>下划线</td>
      <td><code>~词组或短语~</code></td>
      <td><ins>词组或短语e</ins></td>
    </tr>
  </tbody>
</table>
