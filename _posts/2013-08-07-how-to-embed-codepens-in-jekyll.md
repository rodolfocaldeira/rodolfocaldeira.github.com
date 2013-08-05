---
layout: post
title: How to embed codepens in Jekyll
excerpt: How to create cross browser css arrows like a boss.
---

If you try to embed a codepen inside a Jekyll powered website you get the following error.

	REXML could not parse this XML/HTML: 
	<script async src="http://codepen.io/assets/embed/ei.js"></script>

In order to fix this you need to remove the **async** attribute from the script element. This will render the codepen but if you have any text after it or any other bits on the template it will not show up.

In order to fix this second issue you need to add an empty space inside the script, refresh the page and it should work.

{% highlight html %}
<p data-height="268" data-theme-id="0" data-slug-hash="uAoCb" data-user="rodolfocaldeira" data-default-tab="result" class='codepen'>See the Pen <a href='http://codepen.io/rodolfocaldeira/pen/uAoCb'>Timer</a> forked by Rodolfo Caldeira (<a href='http://codepen.io/rodolfocaldeira'>@rodolfocaldeira</a>) on <a href='http://codepen.io'>CodePen</a></p>
<script src="http://codepen.io/assets/embed/ei.js"> </script>
{% endhighlight %}	

<br>


<p data-height="268" data-theme-id="0" data-slug-hash="uAoCb" data-user="rodolfocaldeira" data-default-tab="result" class='codepen'>See the Pen <a href='http://codepen.io/rodolfocaldeira/pen/uAoCb'>Timer</a> forked by Rodolfo Caldeira (<a href='http://codepen.io/rodolfocaldeira'>@rodolfocaldeira</a>) on <a href='http://codepen.io'>CodePen</a></p>
<script src="http://codepen.io/assets/embed/ei.js"> </script>

Enjoy [codepen.io](http://codepen.io/)!