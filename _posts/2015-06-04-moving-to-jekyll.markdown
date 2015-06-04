---
layout: post
title:  "Moving to Jekyll"
date:   2015-06-04 15:20:27
categories: jekyll blog
---
I'm finally getting around to moving my blog from Wordpress to Jekyll. Wordpress has mostly met my needs up until now.
The big exception is this: formatting code blocks. Sure, there are Wordpress plugins for just about everything, but if I have to take the time to customize my blog, I figure I might as well just build it to my own specifications.

Jekyll makes formatting code snippets super easy. Here's an example with Ruby syntax highlighting:

{% highlight ruby %}
def say_hello(name)
  puts "Hi, #{name}"
end
print_hi('Rails Mama')
#=> prints 'Hi, Rails Mama' to STDOUT.
{% endhighlight %}

Here's what that looks like in Jekyll:
{% highlight ruby %}
{% raw %}
{% highlight ruby %}
def say_hello(name)
  puts "Hi, #{name}"
end
print_hi('Rails Mama')
#=> prints 'Hi, Rails Mama' to STDOUT.
{% endhighlight %}
{% endraw %}
{% endhighlight %}

And here's what it would look like in Wordpress:

![vomit](../../../../../assets/vomiting_cartoon.jpg)

Well, that's what Wordpress plugins look like to me, anyway.
