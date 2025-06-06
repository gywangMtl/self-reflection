---
title: "圆周率"
date: 2025-01-14T00:00:00-07:00
# bookComments: false
# bookSearchExclude: false
---
已知圆周率\( \pi=3.1415926535897\cdots \) 求证:若有理数\( p/q \)比\( \frac{355}{133} \)更接近于\( \pi \),则
\( q > 16586 \)

证明:

不妨设\( a = \frac{355}{113}, a> \pi \)

  $$ | \frac{p}{q} - \pi | < a - \pi$$ 因此
  $$ \pi - a < \frac{p}{q} -\pi < a - \pi $$
  $$ 2\pi - 2a < \frac{p}{q} - a <0 $$
  $$ 2(a-\pi) > \frac{355 \cdot q -113 \cdot p}{113 \cdot q}$$
  $$ q > \frac{355q-113p}{113 \cdot 2(a-\pi)} > \frac{1}{113 \cdot 2 \cdot 2.6676428266370067 \cdot 10^{-7}} = 16586.84857 >16586 $$

