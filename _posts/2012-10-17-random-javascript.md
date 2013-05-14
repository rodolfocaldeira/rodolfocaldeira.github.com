---
layout: post
title: JavaScript Random Number Generator 
excerpt: 
---

Here's an easy to use random number generator function in javascript.

{% highlight javascript %}
function random(min, max) {
  if(!max) { 
    return Math.floor(Math.random() * min);
  }
  return Math.floor(Math.random() * (max - min + 1)) + min;
}
{% endhighlight %}	

I wonder if I can push this to [Bower](http://twitter.github.com/bower/).
