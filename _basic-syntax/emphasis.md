---
title: 强调
syntax-id: emphasis
---

你可以通过将文本设置为粗体或斜体来增加重点。

{% include syntax.html type="basic-sub" syntax-id="bold" %}

{% include syntax.html type="basic-sub" syntax-id="italic" %}

### 粗体和斜体

要同时强调粗体和斜体文本，请在单词或短语前后添加三个星号或下划线。要在单词中间加粗和斜体以表示强调，请在字母周围添加三个不带空格的星号。

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
      <td><code class="highlighter-rouge">这段文字***真的很重要***。</code></td>
      <td><code class="highlighter-rouge">这段文字&lt;em&gt;&lt;strong&gt;真的很重要&lt;/strong&gt;&lt;/em&gt;。</code></td>
      <td>这段文字<em><strong>真的很重要</strong></em>。</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">这段文字 ___真的很重要___。</code></td>
      <td><code class="highlighter-rouge">这段文字&lt;em&gt;&lt;strong&gt;真的很重要&lt;/strong&gt;&lt;/em&gt;。</code></td>
      <td>这段文字<em><strong>真的很重要</strong></em>。</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">这段文字 __*真的很重要*__。</code></td>
      <td><code class="highlighter-rouge">这段文字 &lt;em&gt;&lt;strong&gt;真的很重要&lt;/strong&gt;&lt;/em&gt;。</code></td>
      <td>这段文字<em><strong>真的很重要</strong></em>。</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">这段文字 **_真的很重要_**。</code></td>
      <td><code class="highlighter-rouge">这段文字 &lt;em&gt;&lt;strong&gt;真的很重要&lt;/strong&gt;&lt;/em&gt;。</code></td>
      <td>这段文字<em><strong>真的很重要</strong></em>。</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">这是***非常***重要的文本。</code></td>
      <td><code class="highlighter-rouge">这是&lt;em&gt;&lt;strong&gt;非常&lt;/strong&gt;&lt;/em&gt;重要的文本。</code></td>
      <td>这是<em><strong>非常</strong></em>重要的文本。</td>
    </tr>
  </tbody>
</table>

<div class="alert alert-info">
  <i class="fas fa-info-circle"></i> <strong>注意：</strong><code>em</code> 和 <code>strong</code> 标签的顺序可能会根据你使用的 Markdown 处理器而颠倒。
</div>

#### 粗体和斜体的最佳实践

Markdown 应用程序不同意如何处理单词中间的下划线。为了兼容性，使用星号在单词中间加粗和斜体表示强调。

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
          这是***非常***重要的文本。
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          这是___非常___重要的文本。
        </code>
      </td>
    </tr>
  </tbody>
</table>
