#Write Yourself a Scheme in 48 Hours

##Overview


Most Haskell tutorials on the web use a style of teaching akin to language reference manuals. They show you the syntax of the language, a few language constructs, then tell you to create a few simple functions at the interactive prompt. The "hard stuff" of how to write a functioning, useful program is left to the end, or omitted entirely.

>许多网络上Haskell的教程采用了一个类似计算机语言参考教的形式教学，他们展示给你的是语言的语法，一些语言的构造，然后告诉你如何在语言的交互环境(ghci)上构建一个新的简单函数,这种“坚硬难啃的东西”对于如果写一个富有功能性的程序可以直接抛弃这样的教程 或者完全省略



This tutorial takes a different approach. You'll start off using and parsing the command-line, then progress to writing a fully-functional Scheme interpreter that implements a decent subset of R5RS Scheme. Along the way, you'll learn Haskell's I/O, mutable state, dynamic typing, error handling, and parsing features. By the time you finish, you should become fairly fluent in Haskell and Scheme.


>本教程需要另辟蹊径。你将始于使用命令行和语法特性，写一个全功能的Scheme解析器，实现一个[R5RS](http://web.archive.org/web/20131411513100/http://www.schemers.org/Documents/Standards/R5RS/HTML/) Scheme完整子集。沿途，你将学习Haskell的I/O,可变状态，动态类型，错误处理和解析特性。当你完成的时刻，你将流利的编写Haskell和Scheme。

This tutorial targets two main audiences:

>本教程主要针对两类读者

* People who already know Lisp or Scheme, and want to learn Haskell
* People who don't know any programming language, but have a strong quantitative background, and are familiar with computers

* 已经懂Lisp和Scheme的人，并想去学习Haskell
* 并不知道任何编程语言，并且拥有强大的计算机背景，和熟悉计算机的人(CS专业最佳)
