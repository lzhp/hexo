---
title: 在gitee上发布博客
date: 2020-05-27 16:00:56
categories:
tags:
---

gitee号称国内的github，恰巧也支持pages服务，为了让博客多一点人能看到，在github的基础上，增加gitee的发布。

其实很简单，就是用gitee的克隆功能直接将github上的仓库直接克隆过来。操作步骤如下：

1. 在gitee上新建仓库，为了能用上短域名，建议仓库的名字与自己的个性化域名相同，比如，我的个性化域名是zhanchifei，那仓库名设置为zhanchifei，将来可以用[https://zhanchifei.gitee.io/](https://zhanchifei.gitee.io/)这个域名访问。这一点与github不一样，github上如果是用户名是lzhp，那么仓库的名字应该是lzhp.github.io，这样，以后可以用[https://lzhp.github.io/](https://lzhp.github.io/)这样的域名进行访问。

    <!-- more -->

2. 在新建仓库的最下边，选择从github导入即可。

    {% asset_img importfromgithub.png %}

3. 在仓库的页面中，选择服务-gitee pages，按照说明设置即可

    {% asset_img openpages.png %}

4. 现在可以通过 [https://zhanchifei.gitee.io](https://zhanchifei.gitee.io)访问网页了，以后github上更新后，需要到这个页面点一下同步，把github上最新的提交导入，不知道能不能做成自动的。
