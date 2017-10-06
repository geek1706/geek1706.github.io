---
layout: post
title:  "Git delete branch"
date:   2016-08-24 16:19:26 +0700
categories: posts
comments: true
---
To delete a local branch

{% highlight shell %}
git branch -d the_local_branch
{% endhighlight %}

To remove a remote branch (if you know what you are doing!)

{% highlight shell %}
git push origin :the_remote_branch
{% endhighlight %}


