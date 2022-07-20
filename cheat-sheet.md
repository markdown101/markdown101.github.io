---
layout: default
title: Markdown 速查表
description: Markdown 语法的快速参考。
last_modified_at: 2021-12-05
---

## 概述

Markdown 速查表提供了所有 Markdown 语法元素的快速概览。它不能涵盖所有边缘情况，因此如果你需要有关任何这些元素的更多信息，请参阅[基础语法](/basic-syntax)和[扩展语法](/extended-syntax)的参考指南。

## 基础语法

这些是 John Gruber 的原始设计文档中概述的元素。所有 Markdown 应用程序都支持这些元素。

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>元素</th>
      <th>Markdown 语法</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="/basic-syntax/#headings">标题</a></td>
      <td><code># H1<br>
          ## H2<br>
          ### H3</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#bold">粗体</a></td>
      <td><code>**bold text**</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#italic">斜体</a></td>
      <td><code>*italicized text*</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#blockquotes-1">块引用</a></td>
      <td><code>> blockquote</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#ordered-lists">有序列表</a></td>
      <td><code>
        1. First item<br>
        2. Second item<br>
        3. Third item<br>
      </code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#unordered-lists">无序列表</a></td>
      <td>
        <code>
          - First item<br>
          - Second item<br>
          - Third item<br>
        </code>
      </td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#code">代码块</a></td>
      <td><code>`code`</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#horizontal-rules">水平分隔线</a></td>
      <td><code>---</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#links">链接</a></td>
      <td><code>[title](https://www.example.com)</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#images-1">图片</a></td>
      <td><code>![alt text](image.jpg)</code></td>
    </tr>
  </tbody>
</table>

## 扩展语法

这些元素通过添加附加功能扩展了基本语法。并非所有 Markdown 应用程序都支持这些元素。

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>元素</th>
      <th>Markdown 语法</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="/extended-syntax/#tables">Table</a></td>
      <td><code>
          | Syntax      | Description |<br>
          | ----------- | ----------- |<br>
          | Header      | Title       |<br>
          | Paragraph   | Text        |
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#fenced-code-blocks">Fenced Code Block</a></td>
      <td><code>```<br>
      {<br>
      &nbsp;&nbsp;"firstName": "John",<br>
      &nbsp;&nbsp;"lastName": "Smith",<br>
      &nbsp;&nbsp;"age": 25<br>
      }<br>
      ```
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#footnotes">Footnote</a></td>
      <td><code>
        Here's a sentence with a footnote. [^1]<br><br>
        [^1]: This is the footnote.
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#heading-ids">Heading ID</a></td>
      <td><code>### My Great Heading {#custom-id}</code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#definition-lists">Definition List</a></td>
      <td><code>
        term<br>
        : definition
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#strikethrough">Strikethrough</a></td>
      <td><code>~~The world is flat.~~</code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#task-lists">Task List</a></td>
      <td><code>
        - [x] Write the press release<br>
        - [ ] Update the website<br>
        - [ ] Contact the media
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#emoji">Emoji</a><br>(see also <a href="/extended-syntax/#copying-and-pasting-emoji">Copying and Pasting Emoji</a>)</td>
      <td><code>
        That is so funny! :joy:
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#highlight">Highlight</a></td>
      <td><code>
        I need to highlight these ==very important words==.
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#subscript">Subscript</a></td>
      <td><code>
        H~2~O
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#superscript">Superscript</a></td>
      <td><code>
        X^2^
      </code></td>
    </tr>
  </tbody>
</table>

## 下载

你可以下载到<a href="/assets/markdown-cheat-sheet.md" download="markdown-cheat-sheet.md">速查表</a>的 Markdown 文档 ，以便在你的 Markdown 应用程序中使用。
