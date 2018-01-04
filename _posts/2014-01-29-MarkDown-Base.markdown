---
layout:     post
title:      "MarkDown语法基础篇"
date:       2018-01-4 17:06:00
author:     "Pinattsu"
catalog: true
tags:
  MarkDown
  学习
---

*以前一说到文本处理大家直接会想到微软的Office系列，偶然了解到Markdown这种标记语言的存在，不同于Office系列动辄上几GB的体积,markdown作为一种语言的好处体现的淋漓尽致，没有复杂的各种按钮工具，甚至不需要特地安装什么软件，只需要记住常用的十几个标记拿记事本即可畅快码字。本文即是使用MarkDown写的，也是我的第一篇MarkDown文档。*
 # 一、什么是MarkDown
![](https://tse2-mm.cn.bing.net/th?id=OIP.aTLBiY4FXrktf3Ag9fiFyQHaEj&w=299&h=183&c=7&o=5&dpr=1.25&pid=1.7)
> Markdown是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。


> Markdown具有一系列衍生版本，用于扩展Markdown的功能（如表格、脚注、内嵌HTML等等），这些功能原初的Markdown尚不具备，它们能让Markdown转换成更多的格式，例如LaTeX，Docbook。Markdown增强版中比较有名的有Markdown Extra、MultiMarkdown、 Maruku等。这些衍生版本要么基于工具，如Pandoc；要么基于网站，如GitHub和Wikipedia，在语法上基本兼容，但在一些语法和渲染效果上有改动。

 # 二、基本语法
MarkDown的语法基本是 **标识符+空格+文本**或**标识符+文本+标识符** 这样的格式书写。
 ## 1 文本样式
- 标题

用法： ```# 标题```  标识符数量越多标题级数越高，最多支持六级标题。

效果：
 # 这是一级标题 
 ## 这是二级标题
 ### 这是三级标题
 #### 这是四级标题
 ##### 这是五级标题
 ###### 这是六级标题
MarkDown文档：

``` 
# 这是一级标题 
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题
```
- 斜体

用法：```*斜体的内容*```

效果：

*这是斜体*

MarkDown文档：
``` 
*这是斜体*

```
- 引用

用法：```> 引用的内容```

效果：

> 这是引用。

MarkDown文档：
```
> 这是引用。
```
- 高亮

用法：```==高亮的内容==```

示例：

==这里是高亮==

MarkDown文档：

```
==这里是高亮==
```

 ### 更多用法
```
加粗 :**Bold**
*删除线 :~~text~~
段落 : 段落之间空一行
换行符 : 一行结束时输入两个空格
列表 :* 添加星号成为一个新的列表项。
引用 :> 引用内容
内嵌代码 : `alert('Hello World');`
画水平线 (HR) :--------
```
--------
 ## 2 图片与链接
- 链接

用法：``` [显示文本](链接地址) ```

示例：

[Google](www.google.com)

MarkDown文档：
```
[Google](www.google.com)
```
- 图片

用法：``` ![显示文本](图片链接地址)```

示例：
![Google](http://www.logocollect.com/google/images/google_van_gogh.jpg)

MarkDown文档：

```
![Google](http://www.logocollect.com/google/images/google_van_gogh.jpg)
```
--------
以上即是MarkDown基础篇的全部内容，除此之外MarkDown还支持插入数学公式、绘制表格、流程图等进阶用法，我将会在下篇介绍。
