---
---


# How to redirect an http request

To redirect an http request, use [response code 302](https://en.wikipedia.org/wiki/HTTP_302)

{% highlight text %}
HTTP/1.1 302 Found
Location: http://www.iana.org/domains/example/
{% endhighlight %}
