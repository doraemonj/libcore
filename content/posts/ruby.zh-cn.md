---
title: "Hugo模板内使用拼音注释"
summary: "ruby注释语法"
date: 2022-10-03T20:24:10+08:00
draft: false

tags: ["ruby语法"]
categories: ["ruby语法"]
ruby: true
featuredImage: "https://doraemonj.github.io/img/ruby_format_on_hugo/long.png"
featuredImagePreview: "https://doraemonj.github.io/img/ruby_format_on_hugo/long.png"
---

有些文档以会在某些文字上作拼音或英文标注：

<ruby>语法<rt>yufa</rt></ruby>

其实是在Hugo的md文档中输入：

`<ruby>语法<rt>yufa</rt></ruby>`

又如：

<ruby>
强化学习<rt>reinforcement learning</rt>
</ruby>
有近几十年的研究历史，是 <ruby>
人工智能<rt>artificial intelligence</rt>
</ruby>
的一个研究方向。

实际输入是：

`<ruby>
强化学习<rt>reinforcement learning</rt>
</ruby>
有近几十年的研究历史，是 <ruby>
人工智能<rt>artificial intelligence</rt>
</ruby>
的一个研究方向。`

用户体验普遍不错。





