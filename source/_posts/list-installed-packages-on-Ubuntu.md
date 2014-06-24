title: 显示Ubuntu上已安装的packages
date: 2014-06-23 17:37:38
tags: 
- Ubuntu
- Daily
---

某些时候 我们需要显示Ubuntu上已安装的软件包
这时候可以简单的输入

{% codeblock lang:bash %}
dpkg --get-selections
{% endcodeblock %}

![](http://robertlyc.qiniudn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202014-06-23%2017.48.46.png)

当然配合grep命令 我们可以更加精确定位,例如
{% codeblock lang:bash %}
dpkg --get-selections | grep git
{% endcodeblock %}

![](http://robertlyc.qiniudn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202014-06-23%2017.49.08.png)