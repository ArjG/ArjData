---
layout: post
title: How to automate the boring repetitive work
subtitle: Aka, cron 101
date: 2019-10-01 20:57:45
categories: [tutorials]
---
#
{% highlight bash %}
# .---------------- minute (0 - 59)
# |  .------------- hour (0 - 23)
# |  |  .---------- day of month (1 - 31)
# |  |  |  .------- month (1 - 12) OR jan,feb,mar,apr ...
# |  |  |  |  .---- day of week (0 - 6) (Sunday=0 or 7)
# |  |  |  |  |
# *  *  *  *  *   command
{% endhighlight %}
# Examples of things you might want to automate


