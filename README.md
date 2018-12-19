# Latex_Learn
学习Latex操作，为研究生做准备~

## 可以以《An effective implementation of Lin-Keinighan traveling salesman heuristic》这篇文章为目的进行学习~

## latex学习链接： http://math.ecnu.edu.cn/~latex/ 可以一部分一部分的看。

# Latex学习过程中的总结：
### 2018年12月19日：
\documentclass{article}

\usepackage{CJK}

\newcommand{\song}{\CJKfamily{song}} % 宋体

\begin{document}

\begin{CJK*}{GBK}{song}

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
