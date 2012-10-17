---
layout: post
title: Random JavaScript
---

I wonder if I can push this to [Bower](http://twitter.github.com/bower/).

{% highlight javascript %}
function random(min, max) {
  if(!max) { 
    return Math.floor(Math.random() * min);
  }
  return Math.floor(Math.random() * (max - min + 1)) + min;
}
{% endhighlight %}	