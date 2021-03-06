---
layout: post
title: 2013年JavaScript开发人员调查结果
category : javascript
tagline: "译"
tags : [javascript]
keywords: [javascript]
description: JavaScript开发人员调查现在已经结束，一如既往社区对结果进行了进一步分析
---
{% include JB/setup %}

JavaScript开发人员调查现在已经结束，一如既往社区对结果进行了进一步分析:

- [总结](http://dailyjs.com/files/2013-survey-summary.pdf)（[中文](http://www.csdn.net/article/2013-12-16/2817820-javascript-survey-results)）
- [原始数据（电子表格）](http://dailyjs.com/files/2013-survey-data.zip)
- [2012年结果](http://dailyjs.com/2012/12/24/javascript-survey-results/)

![]({{ BLOG_IMG }}43.png)

51%的被参与者写客户端代码，而28%的人说他们编写服务器端代码。去年客户端的占比是98%，所以我猜想，DailyJS起到了一定的积极作用，但有趣的是服务器端开发怎么发展的如此迅猛。

当被问到在哪里写javascript时，54%的人回答“工作”，45%的人回答“项目”。这可能一个人同时回答两种情况——我发现这对程序员是通用的，无论是专业人士还是业余爱好者。

大多数的参与者编写JavaScript已经有三到五年(34%)。我不禁觉得这得益于Node的增长——人们在经历使用其他的语言进行后台开发后，重新发现JavaScript的魅力，或者得益于前端框架的成长，如AngularJS和Backbone.js。我无法想象设计人员不具备JavaScript技巧。

78%的参与者说他们没有使用可以编译成JavaScript的语言（类似coffeescript）。我已经注意到Node社区的一些颇具影响力的成员对这些语言的声音，所以似乎看起来参与者同意。我在博客中尽量保持关于这些语言的一些报道，但总的来说重点是JavaScript。与其他语言不同，使用tab可以节省一点点尺寸，所以我不太介意使用哪种方法。

CoffeeScript 是最流行的“编译（conpile-to）”语言（64%），TypeScript从去年开始初见端倪（19%）。

代码的样式问题很混乱，结尾的分号，逗号和方法保留一个空格是最受欢迎的选择。有趣的是9%的人使用tab而11%的人使用空格。客户端开发者好像偏爱于四个空格，然而仅有8%的人选择此项。

测试的结果太好笑了：

- 是：25%
- 否：26%
- 有时（Sometimes）/不总是（not enough）/不太多

我喜欢你的诚实，“不总是”可能只是谦虚，所以我意识到“很多参与者仅写些例子，但他们觉得自己可以做的更好”。

Jasmine非常流行，大约占30%。我始终认为tap是最好的方法,但它只占2%。Mocha表现很好，占到27%，QUnit下降到16%。我认为这很能证明参加调查的很大一部分是Node开发者，但也可能是人们看到Mocha作为一个浏览器/Node模块的魅力，而且QUnit很多时候仅配合jQuery使用(这不一定是真的)。

CI服务？36%的人回答是。Node绝对是CI服务的好基友——我最近开始用TeamCity的服务器做objective - c项目并且这是令人吃惊的困难。和搭配Travis CI的开源Node项目比起来，这简直让人可笑。然而，Jenkins是最流行的CI服务（44%），TeamCity斩获（13%），所以也许人们发现跟踪客户端或Node检测很容易，在使用多种语言现有企业CI服务的帮助下。

![]({{ BLOG_IMG }}44.png)

原来人们喜欢AMD!然而如果我们把CommonJS的结果分开来看，我们发现17%的人使用CommonJS而12%的人使用Browserify。很长一段时间我提倡CommonJS，但Browserify的理论很有说服力……

当看到AngularJS和Backbone.js在客户端框架中各占25%时，我很吃惊，他们有各自的内涵，但我不自觉的认为他们用来解决不同的问题。

一般常识认为支持IE似乎应该从IE 8开始(37%)。我猜那是公司的支持要求，这是已经存在十年之久的web开发人员心中的阵痛。

你使用ES6的特性吗？85%的人回答“不”，所以不过你没有使用，其实你一点也不糟糕。我可能仅仅写DailyJS文章的时候会用到，但我们将会在明年看到这种情况开始增长。

PHP是最受欢迎的主要开发语言(24%)，c#有17%。你好.NET成员！

感谢大家参加调查！如果你可以用这些数据做一些很酷的事，我很想听听。

**译者注**

本文为翻译文章，原文为“[JavaScript Developer Survey 2013: Results](http://dailyjs.com/2013/12/12/javascript-survey-results)”