### 换行 Line Breaks

在一行的末尾添加两个或多个空格，然后按回车键（return），即可创建一个换行（line break）或新行 (`<br>`)。

```
![[ ../../examples/line-breaks-1.md ]]
```

渲染效果如下：

![[ ../../examples/line-breaks-1.md ]]


#### 换行（Line Break）用法的最佳实践

几乎每个 Markdown 应用程序都支持两个或多个空格进行换行 (称为 “结尾空格（trailing whitespace）”) 的方式，但这是有争议的，因为很难在编辑器中直接看到空格，并且很多人在每个句子后面都会有意或无意地添加两个空格。由于这个原因，你可能需要使用除结尾空格以外的其它方式来进行换行。如果你所使用的 Markdown 应用程序 支持 HTML 的话[^pandoc-linebreak]，你可以使用 HTML 的 `<br>` 标签来实现换行。

[^pandoc-linebreak]: Pandoc 转换程序不支持 `<br>` 换行。

为了兼容性，请在行尾添加“结尾空格”或 HTML 的 `<br>` 标签来实现换行。

还有两种其他方式我并不推荐使用。CommonMark 和其它几种轻量级标记语言支持在行尾添加反斜杠 (`\`) 的方式实现换行，但是并非所有 Markdown 应用程序都支持此种方式，因此从兼容性的角度来看，不推荐使用。并且至少有两种轻量级标记语言支持无须在行尾添加任何内容，只须键入回车键（ return）即可实现换行。

```
![[ ../../examples/line-breaks-2.md ]]
```

渲染效果如下：

![[ ../../examples/line-breaks-2.md ]]