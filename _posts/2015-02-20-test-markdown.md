---
layout: post
title: Test markdown
subtitle: Each post also has a subtitle
---

菲律賓東方海面上的熱帶系統26日增強為第9號颱風「尼莎」，根據中央氣象局的路徑預估，尼莎很可能會成為「穿心颱」，最快周五發布海上颱風警報。

氣象局表示，截止凌晨2時止，尼莎中心位置位於距離鵝鑾鼻東南方大約910公里的海面上，以每小時10轉13公里速度，向北北西進行。颱風中心氣壓 995 百帕，近中心最大風速每秒 20 公尺，瞬間最大陣風每秒 28 公尺，七級風半徑 100 公里。

氣象局指出，尼莎周五（28日）前持續移動至台灣東南部海面一帶，接著路徑再逐漸偏西靠近東部海面，接近程度要看太平洋的高壓而定。周日、一（30、31日）有可能發布陸上警報，不過進一步的預測可能還要再等一、兩天才比較明朗。

You can write regular [markdown](http://markdowntutorial.com/) here and Jekyll will automatically convert it to a nice webpage.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](http://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.

**Here is some bold text**

## Here is a secondary heading

Here's a useless table:
 
| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |
 

How about a yummy crepe?

![Crepe](http://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
/**
 * Does a thing
 */
function helloWorld(param1, param2) {
  var something = 0;

  // Do something
  if (2.0 % 2 == something) {
    console.log('Hello, world!');
  } else {
	return null;
  }

  // @TODO comment
}
{% endhighlight %}
