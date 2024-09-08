---
title: 段落
syntax-id: paragraphs
---

要创建段落，请使用空行分隔一行或多行文本。

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
      <td>
        <code class="highlighter-rouge">
我真的很喜欢使用 Markdown。<br /><br />
        我想从现在开始我会用它来格式化我的所有文档。
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">&lt;p&gt;我真的很喜欢使用 Markdown。&lt;/p&gt;<br /><br />
        &lt;p&gt;我想从现在开始我会用它来格式化我的所有文档。&lt;/p&gt;</code>
      </td>
      <td>
        <p>我真的很喜欢使用 Markdown。</p>
        <p>我想从现在开始我会用它来格式化我的所有文档。</p>
      </td>
    </tr>
  </tbody>
</table>

### 段落的最佳实践

除非[段落在列表中](/basic-syntax/#paragraphs)，否则不要使用空格或制表符缩进段落。

<div class="alert alert-info">
  <i class="fas fa-info-circle"></i> <strong>注意：</strong> 如果你需要在输出中缩进段落，请参阅如何 <a href="/hacks/#indent-tab">缩进（制表符）</a>部分。
</div>

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
          不要在段落前面放置制表符或空格。<br><br>
          像这样保持行左对齐。<br><br>
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        &nbsp;&nbsp;&nbsp;&nbsp;这可能会导致意外的
        格式问题。<br><br>
        &nbsp;&nbsp;不要在段落前面添加制表符或空格。
        </code>
      </td>
    </tr>
  </tbody>
</table>
