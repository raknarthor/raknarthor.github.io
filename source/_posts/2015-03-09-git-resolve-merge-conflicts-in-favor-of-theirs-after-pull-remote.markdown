---
layout: post
title: "Git: Resolve merge conflicts in favor of theirs after pull remote"
date: 2015-03-09 16:22:00 +0300
comments: true
categories: git
---

Thanks to this answer on SO: [http://stackoverflow.com/a/8888015/1817777](http://stackoverflow.com/a/8888015/1817777)

{% highlight text %}
git fetch --all
git reset --hard origin/master
{% endhighlight %}