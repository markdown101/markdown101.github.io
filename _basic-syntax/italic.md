---
title: 斜体
syntax-id: italic
---

要使文本变为斜体，请在单词或短语前后添加一个星号或下划线。为了强调单词中间的斜体，请在字母周围添加一个不带空格的星号。

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
      <td><code class="highlighter-rouge">斜体文本是 *cat's meow*。</code></td>
      <td><code class="highlighter-rouge">斜体文本是 &lt;em&gt;cat's meow&lt;/em&gt;。</code></td>
      <td>斜体文本是 <em>cat’s meow</em>。</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">斜体文本是 _cat's meow_。</code></td>
      <td><code class="highlighter-rouge">斜体文本是 &lt;em&gt;cat's meow&lt;/em&gt;。</code></td>
      <td>斜体文本是 <em>cat’s meow</em>。</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">A*cat*meow</code></td>
      <td><code class="highlighter-rouge">A&lt;em&gt;cat&lt;/em&gt;meow</code></td>
      <td>A<em>cat</em>meow</td>
    </tr>
  </tbody>
</table>

#### 斜体的最佳实践

Markdown 应用程序在如何处理单词中间的下划线方面没有达成一致。为了兼容性，使用星号将单词中间斜体表示强调。

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; 正确做法</th>
      <th>❌&nbsp; 错误做法</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          A*cat*meow
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          A_cat_meow
        </code>
      </td>
    </tr>
  </tbody>
</table>
