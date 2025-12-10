---
title: "不等式证明"
date: 2025-12-09T00:00:00-07:00
# bookComments: false
# bookSearchExclude: false
---
设\( a_1 \le a_2 \le \ldots \le a_n, b_1 \le b_2 \le \ldots \le b_n \). 并且\( b_1+b_2+ \ldots + b_n=0 \). 求证: \( \sum_{i=1}^n a_i b_i \ge 0 \)

**证明**

若\(b_i\)全都等于0则结论显然成立。现在考虑\(b_n>0\)

因为\(b_1+b_2+ \dots + b_n=0 \) 且\(b_1 \le b_2 \le \ldots \le b_n\)所以\(b_i\)可分为两部分:

$$ b_1 \le b_2 \le \dots \le b_k <0 $$,

$$ 0< b_{k+1} \le b_(k+2) \le \ldots <=b_n $$

因此可记
$$ S = b_{k+1} + b_{k+2} + \dots + b_n = -(b_1+b_2+ \ldots + b_k) > 0 $$

对于\(i<=k\),有\(a_i<=a_k\),又因为\(b_i<0\)
因此\( a_i b_i >= a_k b_i \)

对于\(i>k\),有\(a_i>=a_{k+1}\),又因为\(b_i>0\)
因此\( a_i b_i >= a_{k+1} b_i \)

综合可得
$$ \sum_{i=1}^n a_i b_i >= \sum_{i=1}^k a_k b_i + \sum_{i=k+1}^n a_{k+1} b_i = a_k (0-S)+ a_{k+1}S=S(a_{k+1}-a_k) >=0 $$

