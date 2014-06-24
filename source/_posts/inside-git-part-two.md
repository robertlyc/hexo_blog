title: 深入浅出git(二)
date: 2014-05-13 10:31:24
tags: git
---

基础操作
===

1.建立仓库
---
{% codeblock lang:bash %}
mkdir test
cd test
git init
ls -an
{% endcodeblock %}

![](http://robertlyc.qiniudn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202014-05-13%2010.59.34.png)

2.增加文件
---
用文本编辑器 建立readme.txt 写下
`yiban is a good company`

{% codeblock lang:git %}
git add readme.txt
git status
{% endcodeblock %}

![](http://robertlyc.qiniudn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202014-05-13%2011.11.28.png)

3.提交文件
---
{% codeblock lang:git %}
git commit -m 'first commit'
{% endcodeblock %}

![](http://robertlyc.qiniudn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202014-05-13%2011.17.17.png)

{% codeblock lang:git %}
git status
{% endcodeblock %}

![](http://robertlyc.qiniudn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202014-05-13%2011.30.21.png)

查看一下提交日志
{% codeblock lang:git %}
git log
{% endcodeblock %}

![](http://robertlyc.qiniudn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202014-05-13%2011.31.48.png)


