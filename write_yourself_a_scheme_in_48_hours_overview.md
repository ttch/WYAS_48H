#Write Yourself a Scheme in 48 Hours

##Overview


Most Haskell tutorials on the web use a style of teaching akin to language reference manuals. They show you the syntax of the language, a few language constructs, then tell you to create a few simple functions at the interactive prompt. The "hard stuff" of how to write a functioning, useful program is left to the end, or omitted entirely.

>许多网络上Haskell的教程采用了一个类似计算机语言参考教的形式教学，他们展示给你的是语言的语法，一些语言的构造，然后告诉你如何在语言的交互环境(ghci)上构建一个新的简单函数,对于如果写一个有用的函数式的程序这种“坚硬难啃的东西”，直接放在了最后或者完全忽略。



This tutorial takes a different approach. You'll start off using and parsing the command-line, then progress to writing a fully-functional Scheme interpreter that implements a decent subset of R5RS Scheme. Along the way, you'll learn Haskell's I/O, mutable state, dynamic typing, error handling, and parsing features. By the time you finish, you should become fairly fluent in Haskell and Scheme.


>这份教程需要另辟蹊径。你将始于使用命令行和语法特性，写一个全功能的Scheme解析器，实现一个[R5RS](http://web.archive.org/web/20131411513100/http://www.schemers.org/Documents/Standards/R5RS/HTML/) Scheme完整子集。沿途，你将学习Haskell的I/O,可变状态，动态类型，错误处理和解析特性。当你完成的时刻，你将流利的编写Haskell和Scheme。

This tutorial targets two main audiences:

>这份教程主要针对两类读者

* People who already know [Lisp](https://en.wikipedia.org/wiki/Lisp_(programming_language)) or [Scheme](https://en.wikipedia.org/wiki/Scheme_(programming_language)), and want to learn [Haskell](https://en.wikipedia.org/wiki/Haskell)
* People who don't know any programming language, but have a strong quantitative background, and are familiar with computers

* 已经懂[Lisp](https://en.wikipedia.org/wiki/Lisp_(programming_language))和[Scheme](https://en.wikipedia.org/wiki/Scheme_(programming_language))的人，并想去学习[Haskell](https://en.wikipedia.org/wiki/Haskell)
* 不懂道任何编程语言，并且拥有很强的计算机背景，和熟悉计算机的人(CS专业最佳)

 The second group will likely find this challenging, as this tutorial glosses over several concepts in Scheme and general programming in order to stay focused on Haskell. A good textbook such as [Structure and Interpretation of Computer Programs](https://mitpress.mit.edu/sicp/full-text/book/book.html) or [The Little Schemer](http://www.ccs.neu.edu/home/matthias/BTLS/) should be very helpful

>

Users of a procedural or object-oriented language like C, Java, or Python should beware: You'll have to forget most of what you already know about programming. Haskell is completely different from those languages, and requires a different way of thinking about programming. It's best to go into this tutorial with a blank slate; try not to compare Haskell to imperative languages, because many concepts (including classes, functions, and return) have significantly different meanings in Haskell.

>使用一个面向过程或者面向对象的语言，例如像C,Java或者Python请当心：你将会忘记你已经学会的的编程技巧。Haskell是一个与上面两类语言完全不同的，需要一种完全不同的编程思路。

Since each lesson builds upon code written in previous ones, it's generally best to go through them in order.

>
