---
title: "形似神似，让人疑似"
summary: "逻辑谬误002：否定前件"
date: 2022-05-31T08:13:26+08:00
draft: false

tags: ["逻辑谬误"]
categories: ["逻辑谬误"]
featuredImage: "https://doraemonj.github.io/pics/qf_1653956219.png"
featuredImagePreview: "https://doraemonj.github.io/pics/qf_1653956219.png"
---

木工行业有句话：锯响就有末
>   如果锯子响了，就会有木屑碎末。<br />现在，锯子没响，<br />
>   **所以，一定没末。**

看起来怪怪的，到底哪里不对？因为这个推理藏着一个逻辑谬误：**否定前件**。

### 什么是否定前件？

否定前件（Denying the antecedent）：这里的前件指前提条件中的前提，即否定前提条件中的前提，以此否定前提条件中的结论：

>  如果P成立，那么Q成立<br />现在，P不成立<br />
>  所以，Q一定不成立。

即：

>  P → Q <br />非P → 非Q 

下面，让我们举起三个抽象的杠铃，训练大脑皮层上具体的肱二头肌。

三个常见的否定前件案例：

> 如果一早路面湿了，那么昨晚就下过雨。<br />
> 今天一早路面没湿。<br />
> 所以，昨晚没下雨。

看起来有道理，实际上是**否定前件**的谬误：昨晚下雨后会，风会把积水刮干，即使没风，也可能因为雨小而快速蒸发。所以『路面没湿』不能保证『昨晚没下雨』——前提不能保证结论的真实性，也就是说，结论不是必然正确。

我们变换[**上篇**](https://doraemonj.github.io/zh-cn/logical_fallacy_001/)开篇的例子：

>   如果车没油，那么车跑不起来。<br />现在，车里有油，<br />
>   **所以，车一定能跑起来。**

注意，这里的前提和结论都有否定词：『没』和『不』，删除否定词，我们发现它的本质依然是『否定前件』：

>   如果P，那么Q。<br />
>   现在，P不成立，<br />
>   所以，Q一定不成立

『车里有汽油』的事实，并不能保证汽车能启动，油门、引擎和驾驶者的驾驶能力，都有能力把车停在原地。所以结论不是必然正确。

本文开篇的例子：

>   如果锯子响了，就会有木屑碎末。<br />现在，锯子没响，<br />
>   **所以，一定没末。**

『锯子没响』的事实，并不能保证没有碎末。木工师傅撒花庆祝拖了三年的尾款回收成功时，可能把碎末当成了花。

那么，人们为什么常常被否定前件所迷惑？我们把目光投向『**否定前件**』的双胞胎哥哥：

### 孪生兄弟：否定后件

参加你生日聚会的朋友后来对你说：

>   你没有喊出你的愿望，因为如果你喊了，愿望就不会实现，而你实现了你的愿望。

要明辨这样的论证，唯一的办法是：在一张白纸上写下这条论证的标准结构，然后反复端详。

首先，这个判断的结论是什么？结论是：『你没有喊出你的愿望』。

你的朋友抛出结论之后，开始论证为什么我得结论成立，即：为什么我认为你没有喊出愿望？原因有两个：

『因为』是个前提标识词，大前提是：『如果你喊了，愿望就不会实现』。小前提是：『你实现了你的愿望』。

我们现在可以按照标准结构，写出你朋友的判断：

>   如果你喊出你的愿望，愿望就不会实现。<br />
>   现在，你的愿望实现了，<br />
>   所以，你没有喊出你的愿望。

这个论证犯了『否定前件』的逻辑谬误么？没有。这是经典的『否定后件』（modus tollens）论证——只有前提无误，结论必然正确。

### 为什么否定前件迷惑人？

回忆下，『否定后件』就是我们高中数学学过的『逆否命题』，如果原命题为真，那么逆否命题为真，即：

>  P → Q <br />非Q → 非P 

高中老师曾让我们这么理解『逆否命题』四个字：如果要**逆**转命题，必须**否**定后者，才能推翻前者。

如果否定了前件，那逻辑上就无可救药了：

>  P → Q <br />非P → 非Q 

而『否定前件』的形式正是如此。

『否定前件』于『否定后件』两兄弟本是同根生，两者形似神似，让人不得不疑似，但终究一对一错，阴阳两隔。

而我们唯一要做的，就是加强刻意练习脑肌，搞清这根分界线。

### 刻意练习

命题：我爱你

转换成标准命题形式：如果有个人是我，那么这个人爱你。

基于上述命题，体会两个不同的判断：

否定前件（逻辑谬误）：如果这个人不是我，那么这个人不爱你。（其他爱你的人排好队指出这个逻辑漏洞）

否定后件（正确逻辑）：如果这个人不爱你，那么这个人不是我。
