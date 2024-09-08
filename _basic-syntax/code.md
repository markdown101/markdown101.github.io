---
title: 代码
syntax-id: code
---

要将单词或短语表示为代码，请用反引号（`）将其括起来。

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>渲染输出</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code class="highlighter-rouge">At the command prompt, type `nano`.</code></td>
      <td><code class="highlighter-rouge">At the command prompt, type &lt;code&gt;nano&lt;/code&gt;. </code></td>
      <td>At the command prompt, type <code class="highlighter-rouge">nano</code>.</td>
    </tr>
  </tbody>
</table>

### 转义反引号

如果你想表示为代码的单词或短语包含一个或多个反引号，可以通过使用双反引号（``）将其括起来来进行转义。

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>渲染输出</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>``Use `code` in your Markdown file.``</code></td>
      <td><code class="highlighter-rouge">&lt;code&gt;Use `code` in your Markdown file.&lt;/code&gt;</code></td>
      <td><code>Use `code` in your Markdown file.</code></td>
    </tr>
  </tbody>
</table>

### 代码块

要创建代码块，可以将代码块的每一行前缩进至少四个空格或一个制表符。

```text
    <html>
      <head>
      </head>
    </html>
```

渲染输出看起来是这样的：

```text
<html>
  <head>
  </head>
</html>
```

<div class="alert alert-info">
  <i class="fas fa-info-circle"></i> <strong>注意：</strong> 要创建不缩进行的代码块，可以使用 <a href="/extended-syntax/#fenced-code-blocks">围栏式代码块</a>.
</div>
