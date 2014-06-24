title: 深入浅出git(三)
date: 2014-05-13 11:40:42
tags: git
---

文件修改
===
打开文本编辑器 修改readme.txt内容
`yiban is a good company`
`Robert is a good guy`

{% codeblock lang:git %}
git status
{% endcodeblock %}

![](http://robertlyc.qiniudn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202014-05-13%2011.57.10.png)

文件比较
===
git status只能告诉我们文件的改动情况 如果需要更详细的了解文件改动内容 需要这条命令
{% codeblock lang:git %}
git diff reademe.txt
{% endcodeblock %}

![](http://robertlyc.qiniudn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202014-05-13%2012.00.28.png)

版本回退
===
在add之前的解决办法
{% codeblock lang:git %}
git checkout -- readme.txt
{% endcodeblock %}
![](http://robertlyc.qiniudn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202014-05-14%2014.38.13.png)

在add之后, commit之前



