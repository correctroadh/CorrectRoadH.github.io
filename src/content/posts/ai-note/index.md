---
title: "用 AI 整理了最近六年的日记"
description: File over app
published: 2024-09-22
category: 思考
tags: [碎念念] 
---

![](diary.png)

从 18 年开始，我写了好多日记，但是在这六年间，我换了好几个笔记软件，从 OneNote 到 Obsidian 再到 Logseq。这些日记跨越了不同软件、不同格式。之前不敢想像能把多年的日记能聚集在一起，因为确实抽不出来时间来写软件脚本，把他们之前的差异打平。

但是最近用上 Claude 之后发现这个 AI 确实不太一样，能写出来的代码确实很 work。在一顿操作之后，用 claude 写了十几个 one off脚本，，把不同格式、来源的笔记都转换成当前使用的 logseq 的格式。

[正如之前所提到的](ai-change-program)，AI 将可能改变开发的范式，在之前写 one off 的脚本，大家都是用 Ruby，各种文件读写 API 调用的方便，写起来也是又短又快。但是在 AI 时代，这些语法糖、API带来的优势并不重要了，用 Python 反而有优势，一是语料大，二是懂的人多，用 Python 的优势大于 Ruby。

这样类似的事在 V0.dev 出来的时候我就想过，比如 Solid.js 很甜是吧，但是 React 的语料是你的数倍，用 AI 写前端，React 的质量就是会比 Solid.js 高、容易。这些后发的新语言/框架感觉更难出头了。

除非语法糖是对 AI 友好的，比如 Tailwind CSS，把 CSS 和 组件放在一起，这样 AI 写 Tailwind 就比写 SaSS 容易了。

除了对 AI 友好的编程语言会在未来脱颖而出，还有对 AI 友好的软件、内容格式也会在未来的竞争获得超乎想像的竞争优势。更容易与 AI 结合，再与其它工具联动，从而形成 1 + 1 > 2 的效果。

在现在很多软件通过数据库/私有格式来存储数据，但是这种私有格式对 AI 感觉太不友好了。就拿用书籍、文章来做来 AI 的知识库，用 Markdown 的书籍远比用 PDF(更甚是图片形式的PDF)好处理的多。

用可人类理解的文件还有很多好处，比如之前读 Obsidian 作者的 [File over app](https://stephango.com/file-over-app) 哲学，『如果你希望你的文章在 20 世纪 60 年代或 21 世纪 60 年代的电脑上仍可阅读，那么你的笔记在 20 世纪 60 年代的电脑上也能阅读』。用文件来存储数据，可以让数据活的更久。

但是同样可以看到像 Logseq、 Affine、Anytype 等等软件又转向了通过数据结构来存储数据，尽管他们也有难言之隐，比如用 Markdown 存储笔记的 Logseq 以在同步中丢失数据而出名。但是或许我们能在两者之间找到平衡点。