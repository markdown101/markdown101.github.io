---
title: 标题
syntax-id: headings
---

要创建标题， 请在词组或短语前添加井号 (`#`) 。 你使用的井号的数量应与标题级别相对应。例如，要创建三级标题 (`<h3>`)，请使用三个井号（例如， `### 我的标题`)。

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
      <td><code class="highlighter-rouge"># 一级标题</code></td>
      <td><code class="highlighter-rouge">&lt;h1&gt;一级标题/h1&gt;</code></td>
      <td><h1 class="no-anchor" data-toc-skip>一级标题</h1></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">## 二级标题</code></td>
      <td><code class="highlighter-rouge">&lt;h2&gt;二级标题&lt;/h2&gt;</code></td>
      <td><h2 class="no-anchor" data-toc-skip>二级标题</h2></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">### 三级标题</code></td>
      <td><code class="highlighter-rouge">&lt;h3&gt;三级标题&lt;/h3&gt;</code></td>
      <td><h3 class="no-anchor" data-toc-skip>三级标题</h3></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">#### 四级标题</code></td>
      <td><code class="highlighter-rouge">&lt;h4&gt;四级标题&lt;/h4&gt;</code></td>
      <td><h4 class="no-anchor">四级标题</h4></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">##### 五级标题</code></td>
      <td><code class="highlighter-rouge">&lt;h5&gt;五级标题&lt;/h5&gt;</code></td>
      <td><h5 class="no-anchor">五级标题</h5></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">###### 六级标题</code></td>
      <td><code class="highlighter-rouge">&lt;h6&gt;六级标题&lt;/h6&gt;</code></td>
      <td><h6 class="no-anchor">六级标题</h6></td>
    </tr>
  </tbody>
</table>

### 替代语法

或者，在文本下方的行中，为一级标题添加任意数量的 `==` 或为二级标题添加任意数量的 `--` 。

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
      <td><code class="highlighter-rouge">一级标题<br/>===============</code></td>
      <td><code class="highlighter-rouge">&lt;h1&gt;一级标题&lt;/h1&gt;</code></td>
      <td><h1 class="no-anchor" data-toc-skip>一级标题</h1></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">二级标题<br/>---------------</code></td>
      <td><code class="highlighter-rouge">&lt;h2&gt;二级标题&lt;/h2&gt;</code></td>
      <td><h2 class="no-anchor" data-toc-skip>二级标题</h2></td>
    </tr>
  </tbody>
</table>

### 标题的最佳实践

Markdown 应用程序如何处理井号(`#`)和标题名称之间的缺失空格上没有统一标准。为了兼容性，请始终在数字符号和标题名称之间放置一个空格。

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
          # 这是标题<br><br>
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          #这是标题
        </code>
      </td>
    </tr>
  </tbody>
</table>

为了兼容性，你还应该在标题前后放置空行。

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
        尝试在前面放一个空行...<br><br>
        # 标题<br><br>
        ...标题之后也放一个空行。
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        如果没有空行，这可能看起来不正确。<br>
        # 标题<br>
        不要这样做！
        </code>
      </td>
    </tr>
  </tbody>
</table>