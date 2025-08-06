---
title: "多面体"
date: 2025-08-54T00:00:00-07:00
# bookComments: false
# bookSearchExclude: false
---
设\( P \)为正多面体，它的每个面有\( p \)个边，每个顶点是\( q \)个面的交点.用
[Euler公式](https://zh.wikipedia.org/zh-tw/%E6%AC%A7%E6%8B%89%E7%A4%BA%E6%80%A7%E6%95%B0)证明：

\[
\frac{1}{p} + \frac{1}{q} = \frac{1}{2} + \frac{1}{e}
\]

证明：

每个面有\( p \)个边，有\( f \)个面，每条边涉及两个面，所以有
\[
    f \cdot p= 2\cdot e 
\] 
\[ 
    \frac{2\cdot e}{p}=f 
\]
类似的，每个顶点是\( q \)个面交点，也就有\( q \)条边，每条边有两个顶点，所以算了两次
\[
     v \cdot q= 2\cdot e 
\] 
\[
     \frac{2\cdot e}{q}=v 
\]

又根据欧拉公式
\[ f-e+v=2 \]
\[ f+v=2+e \]
两边除以\( 2e \)
\[

\frac{2\cdot e}{p \cdot 2 \cdot e} + \frac{2 \cdot e}{q \cdot 2 \cdot e} = \frac{1}{2} + \frac{1}{e}


\frac{1}{p} + \frac{1}{q} = \frac{1}{2} + \frac{1}{e}
\]
