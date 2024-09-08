---
title: 换行
syntax-id: line-breaks
---

要换行或创建换行符 (`<br>`), 请以两个或多个空格结束一行，然后按回车键。

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
          这是第一行。  <br />
          这是第二行。
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">&lt;p&gt;这是第一行。&lt;br&gt;<br />

        这是第二行。&lt;/p&gt;</code>
      </td>
      <td>
        <p>这是第一行。<br />   
        这是第二行。</p>
      </td>
    </tr>
  </tbody>
</table>

### 换行的最佳实践

你几乎可以在每个 Markdown 应用程序中使用两个或多个空格（通常称为“尾随空格”）作为换行符，但这是有争议的。在编辑器中很难看到尾随空格，而且许多人在每个句子后不小心或有意地放置了两个空格。出于这个原因，你可能希望使用尾随空格以外的其他内容作为换行符。如果你的 Markdown 应用程序[支持 HTML](/basic-syntax/#html)，你可以使用`<br>` HTML 标签。

为了兼容性，, 请在行尾使用尾随空格或`<br>` HTML 标签。

这里有两个我不建议使用的选项。CommonMark 和其他一些轻量级标记语言允许你在行尾键入反斜杠(`\`)，但并非所有 Markdown 应用程序都支持这一点，因此从兼容性角度来看，这不是一个很好的选择。也有一些轻量级标记语言不需要在行尾添加任何内容——只需按回车键，它们就会创建一个换行符。

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
          第一行后面有两个空格。 &nbsp;<br>
          第二行。<br><br>
          第一行后面有两个空格。&lt;br&gt;<br>
          第二行。<br><br>
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        第一行后面有两个空格。\<br>
        第二行。<br><br>
        第一行后面有两个空格。<br>
        第二行。<br><br>
        </code>
      </td>
    </tr>
  </tbody>
</table>
