# 简介

JS诞生于1995，当时主要目的是处理以前服务器语言的一些输入验证操作。随着时代发展，JS越来越丰富。

#### 为什么叫Javascript？

当时在Netscape（网景）公司的布兰登·艾奇计划开发一款LiveScript的脚本语言，而当时的Java如火如荼，公司为了就为了搭上大红大紫的Java顺风车，更名为JavaScript。

#### ECMA-262

由NetScape、微软、Sun等公司程序员组成的TC39委员会，共同定义的一种名为ECMAScript的新脚本语言标准。

#### JS组成

![](E:\GitHub\Area\about JavaScript\JavaScript组成.png)

#### ECMAScript

由ECMA-262定义的ECMA与Web浏览器没有依赖关系。实际上，这门语言本身不包含输入和输出定义。ECMA-262定义的只是这门语言的基础，在此基础上可以构建更完善的脚本语言。我们常见的Web浏览器只是ECMA实现的可能**宿主环境**之一。

宿主环境不仅提供题本的ECMAScript实现，同时也会提供该语言的扩展（如DOM），以便语言与环境之间对接交互。

#### DOM

针对XML但经过扩展用于HTML的应用编程接口，它把整个页面映射成一个多层节点结构。

为什么需要它？

Netscape和微软两强割据，浏览器互不兼容，负责Web通信标准的W3C（万维网联盟）开始着手规划DOM。

DOM分为0级、1级、2级，2级扩展。

#### BOM

从根本上讲，BOM只处理浏览器窗口和框架；但人们习惯上也把所有针对浏览器的JavaScript扩展算作BOM一部分。