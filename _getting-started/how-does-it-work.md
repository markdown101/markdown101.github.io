## 它是如何工作的？

Dillinger 使使用 Markdown 编写变得容易，因为它隐藏了幕后发生的事情，但值得探索该过程的总体运作方式。

当你在 Markdown 中编写时，文本存储在具有 `.md` 或 `.markdown` 扩展名的纯文本文件中。但是然后呢？你的 Markdown 格式文件如何转换为 HTML 或可打印的文档？

简短的回答是你需要一个能够处理 Markdown 文件的 *Markdown 应用程序*。。有很多可用的应用程序——从简单的脚本到看起来像 Microsoft Word 的桌面应用程序，应有尽有。尽管它们的视觉差异，所有的应用程序都做同样的事情。与 Dillinger 一样，它们都将 Markdown 格式的文本转换为 HTML，以便可以在 Web 浏览器中显示。

Markdown 应用程序使用称为 *Markdown 处理器* （通常也称为“解析器”或“实现”）的东西来获取 Markdown 格式的文本并将其输出为 HTML 格式。此时，你的文档可以在 Web 浏览器中查看或与样式表结合并打印。你可以在下面看到此过程的可视化表示。

<div class="alert alert-info">
  <i class="fas fa-info-circle"></i> <strong>注意：</strong> Markdown 应用程序和处理器是两个独立的组件。为简洁起见，我在下图中将它们组合成一个元素（“Markdown 应用程序”）。
</div>

{% include image.html file="/assets/images/markdown-flowchart.png" alt="Markdown 处理过程" lazy="yes" %}

总而言之，这是一个有四个步骤的过程：

1. 使用文本编辑器或专用 Markdown 应用程序创建 Markdown 文件。该文件应该有一个 `.md` 或 `.markdown` 扩展名。
2. 在 Markdown 应用程序中打开 Markdown 文件。
3. 使用 Markdown 应用程序将 Markdown 文件转换为 HTML 文档。
4. 在 Web 浏览器中查看 HTML 文件或使用 Markdown 应用程序将其转换为另一种文件格式，例如 PDF。

从你的角度来看，该过程会因你使用的应用程序而有所不同。 例如， Dillinger 基本上将步骤 1-3 组合成一个单一的无缝界面——你所要做的就是在左窗格中输入，然后渲染的输出会神奇地出现在右窗格中。但是，如果你使用其他工具，例如带有静态网站生成器的文本编辑器，你会发现该过程更加明显。
