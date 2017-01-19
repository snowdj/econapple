---
layout: post
title: Ruby初学者教程第3讲：字符串
description: "Ruby中字符串的使用"
tags: [ruby]
image:
  background: xuanzhi.png
---
<iframe width="560" height="315" src="https://www.youtube.com/embed/JtL6R0l-NLA" frameborder="0" allowfullscreen></iframe>

<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#sec-1">1. 字符串</a></li>
<li><a href="#sec-2">2. 输入字符串</a></li>
<li><a href="#sec-3">3. 单引号 vs 双引号</a></li>
<li><a href="#sec-4">4. 编程风格</a></li>
</ul>
</div>
</div>

# 字符串<a id="sec-1" name="sec-1"></a>

![bajie](/images/ruby-03-01.jpg)

字符串是非常非常重要的数据类型,在ruby中也不例外。如果不知道什么叫字符串，可以看下面这个插图。用教材上的话来说，字符串类型是用来存储或者操作一个或者多个字节的序列。大家理解一下啥意思就行。顾名思义，字符串，字符串，就是把字符串成一串。

# 输入字符串<a id="sec-2" name="sec-2"></a>

我们可以用一个变量来存储字符串的值，比如在下面这个例子里，我们从键盘里获取一个字符串，然后将字符串存在一变量里

# 单引号 vs 双引号<a id="sec-3" name="sec-3"></a>

然后，我们再将这个字符串，组成一个新的字符串，打印到屏幕上，使用puts这个函数,在Ruby中，引用一个变量使用的方法是#{}。在这种情况下，变量必须使用双引号，如果使用单引号的话，不会替换里面的变量。

```ruby
print('Enter your name: ')
name = gets()
puts("Hello #{name}")

# ... and so does this:
print 'Enter your name again: '
name = gets
puts "Hello #{name}"
```

# 编程风格<a id="sec-4" name="sec-4"></a>

在Ruby中，和Python有所不同的是，Ruby对语法的要求非常的宽松，多一个空格，或者少一个空格，问题不大，但是，还是希望大家能一直使用自己的风格，否则的话，看起来会比较混乱。

![duilian](/images/duilian.jpg)
