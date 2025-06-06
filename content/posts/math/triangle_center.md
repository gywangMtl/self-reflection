---
title: "三角形中线共点"
date: 2024-11-11T00:00:00-07:00
# bookComments: false
# bookSearchExclude: false
---
首先推荐一个几何作图网站[GeoGebra](https://www.geogebra.org/geometry)

问题：
求证三角形三条中线共点。

如图，设三角形ABC中，D和F分别是AB和AC的中点，CD和BF交于G，连接AG并延长到BC于E，求证E为中点。
![center](/images/t1.png)
因为D和E为中点，所以三角形ABF和三角形ADC面积同为三角形ABC的\( \frac{1}{2} \)
但两个三角形有共同部分四边形ADGF，因此三角形BDG和GCF面积相等
又因为GD是三角形ABG的中线，所以三角形BDG面积是ABG的一半，同理GCF是AGC的一半
所以三角形ABG和AGC面积相等，而两个三角形有同一条边AG
因此B到AE的距离BH等于C到AE的距离CI
三角形ABE和AEC面积都等于\(AE \cdot BH = AE \cdot CI \)，因此两个三角形面积相等
但是这两个三角形面积分别等于\( BE \cdot AJ  \) 和 \( CE \cdot AJ  \) 
所以BE=CE


