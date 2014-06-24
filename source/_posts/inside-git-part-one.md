title: 深入浅出git(一)
date: 2014-05-12 21:47:13
tags: git
---

安装Git
======

OSX
恭喜你 已经自带了git
需要新版本? 推荐homebrew来管理

Linux
for Debian/Ubuntu: sudo apt-get install git
for RHEL/CentOS: yum install git-core

Windows
不推荐在windows上使用git
<http://git-scm.com/download/win> 下载

如何验证安装是否成功?
{% codeblock lang:git %}
git --version
{% endcodeblock %}

正常效果
![](http://robertlyc.qiniudn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202014-05-13%209.40.17.png)

更进一步
-------
设置你的git名字,邮箱

{% codeblock lang:git %}
git config --global user.name 'robertlyc'
git config --global user.name 'lyc@yiban.cn'
{% endcodeblock %}

或者打开~/.gitconfig
![](http://robertlyc.qiniudn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202014-05-13%2010.22.36.png)

