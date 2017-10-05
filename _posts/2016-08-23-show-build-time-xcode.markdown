---
layout: post
title:  "Show build time in Xcode"
date:   2016-08-23 11:22:26 +0700
categories: posts
---
Type this in the terminal:

{% highlight shell %}
defaults write com.apple.Xcode ShowBuildOperationDuration YES
{% endhighlight %}

![]({{ site.url }}/assets/xcode_build_time.png)
