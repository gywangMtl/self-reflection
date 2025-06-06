---
title: "LaTeX语法测试"
date: 2024-10-13T00:00:00-07:00
# bookComments: false
# bookSearchExclude: false
---
按照Hugo的文档，使用\( \LaTeX \)并不难，按照
[这里](https://gohugo.io/content-management/mathematics/)说的配置就可以了。


测试公式生成
\[
e^{z+2k \pi i} = e ^z \cdot e^{2k \pi i}=e^z, k = 0, \pm 1, \pm 2, \cdots.
\]

按照同样道理引用tikz 也可以生成图了，只是要注意，Hugo缺省不支持原生html代码，需要
在配置文件中将开关打开
    [markup.goldmark.renderer]
      unsafe = true

然后可以用代码：

<pre><code class="html language-html">&lt;script type="text/tikz"&gt;
  \begin{tikzpicture}
    \draw (0,0) circle (1in);
  \end{tikzpicture}
&lt;/script&gt;
</code></pre>

生成一个圆形

<script type="text/tikz">
  \begin{tikzpicture}
    \draw (0,0) circle (1in);
  \end{tikzpicture}
</script>