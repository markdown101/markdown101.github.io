---
title: 粗体
syntax-id: bold
---

要加粗文本，请在单词或短语前后添加两个星号或下划线。为了强调单词的中间部分，请在字母周围添加两个不带空格的星号。

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
      <td><code class="highlighter-rouge">我只是喜欢**粗体字**。</code></td>
      <td><code class="highlighter-rouge">我只是喜欢 &lt;strong&gt;粗体字&lt;/strong&gt;。</code></td>
      <td>I just love <strong>bold text</strong>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">我只是喜欢 __粗体字__。</code></td>
      <td><code class="highlighter-rouge">我只是喜欢 &lt;strong&gt;粗体字&lt;/strong&gt;。</code></td>
      <td>我只是喜欢 <strong>粗体字</strong>。</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">Love**is**bold</code></td> <td><code class="highlighter-rouge">爱&lt;strong&gt;是&lt;/strong&gt;大胆的</code></td>
      <td>爱<strong>是</strong>大胆的</td>
    </tr>
  </tbody>
</table>

#### 粗体的最佳实践

Markdown 应用程序在如何处理单词中间的下划线上没有统一标准。为了兼容性，使用星号在单词中间加粗以表示强调。

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
          爱**是**大胆的
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          爱__是__大胆的
        </code>
      </td>
    </tr>
  </tbody>
</table>
