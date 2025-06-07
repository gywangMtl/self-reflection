---
title: "网站迁徙"
date: 2025-06-06T00:00:00-07:00
# bookComments: false
# bookSearchExclude: false
---
昨天起把网站的内容移到了
[Render](https://render.com) 。 今天把DNS指向了新的地址，旧的Apache终于关掉了。

总体过程还算顺利，迁移中发现有几点：

* Render提供的Hugo是比较低版本的，相应的themes也需要用比较低的版本匹配。
* 如果要用www subdomain，Render要求DNS同时解析根域名，这需要添加一个host为@的A记录，指向Render提供的IP。DNS配完后需要在Render里面的设置页面验证并取得SSL证书。

