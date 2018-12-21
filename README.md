# Latex_Learn
学习Latex操作，为研究生做准备~

## 可以以《An effective implementation of Lin-Keinighan traveling salesman heuristic》这篇文章为目的进行学习~

## latex学习链接： http://math.ecnu.edu.cn/~latex/ 可以一部分一部分的看。

# Latex学习过程中的总结：
### 2018年12月19日：
\documentclass{article}

\usepackage{CJK}   导入中文模块

\newcommand{\song}{\CJKfamily{song}} % 宋体

\begin{document}   文章编辑开始

\begin{CJK*}{GBK}{song}    导入字体模块,这里表示导入宋体

\**********
要写的内容都在里面操作
***********/

\end{CJK*}

\end{document}

\begin{center}
// 中间的内容会居中
\end{center}

\bfseries 后面跟着的内容字体会加粗 改变字体的时候，操作需要成对出现才能结束上一次的字体
\normalfont 后面的内容字体缺省

\par 表示换行，另起一行后，会空两格
xxx \\ 表示xxx后面的为下一行，不会空两格
\setlength{\parindent}{0em} 可以表示首行不空，{2em}表示空两格

\slshape 表示后面的内容会变成斜体
\upshape 表示后面的内容会变成正体

\dotfill 点状分割线
\hrulefill 条状分割线

### 2018年12月20日：
对于摘要部分可以使用下面的格式：
\begin{abstract}
中间就是摘要部分的内容，有些格式是默认的，也可以自己修改
\end{abstract}

http://math.ecnu.edu.cn/~latex/lect/lect03.pdf 选择字体尺寸
修改字体的大小：
\tiny         5pt
\scriptsize   7pt
\footnotesize 8pt
\small        9pt
\normalsize   10pt
\large        12pt
\Large        14.4pt
\LARGE        17.28pt
\huge         20.74pt
\Hugu         24.88pt

http://math.ecnu.edu.cn/~latex/examples/special-symbols.pdf 特殊符号的使用
特殊符号使用：比如©
\copyright

http://math.ecnu.edu.cn/~latex/lect/lect04.pdf  数学公式的编辑
数学公式的使用：比如n的2.2次方
$ n^{2.2}$

### 2018年12月21日：
对于分栏操作可以参考1102.tex，可以使文档达到任意的分栏格式
\usepackage{multicol}  导入这个包
\begin{multicols}{n}  表示以下的内容都以n分栏形式体现

章节命令：http://math.ecnu.edu.cn/~latex/lect/lect05.pdf
\section{xxx}  xxx为章节名字 \subsection{} 子章节

