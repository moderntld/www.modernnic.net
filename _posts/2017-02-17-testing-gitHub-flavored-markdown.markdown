---
layout: post
title: "Testing GitHub Flavored Markdown"
date: 2017-02-17 00:02:00
categories: Jekyll
---
Jekyll is simple but powerful, and can hosted easily on GitHub. Here's some cheat codes on how to create nice looking posts with GFM ([Github Flavored Markdown](https://help.github.com/articles/github-flavored-markdown/)).

#### Links

Example:

[Click This!](https://github.com/ModernTLD).

Markdown:

```
[Click This!](https://github.com/ModernTLD).
```

#### Italics

Example:

*this is italic!*

Markdown:

```
*this is italic!*
```

#### Bold

Example:

**This is bold!**

Markdown:

```
**This is bold !**
```

#### Lists

Example:

 * Item 1
 * Item 2
 * Item 3

Markdown:

```
 * Item 1
 * Item 2
 * Item 3
```


#### Code Blocks

Example:

```
function hello(){
	return "Hello World!";
}
```

Markdown:

{% highlight text %}
```
function hello(){
	return "Hello World!";
}
```
{% endhighlight %}


#### Inline Code

Example :

`echo "Hello World!";`

Return :

````
`echo "Hello World!";`
````

#### Highlighted Code Blocks

Example:

{% highlight javascript %}
function hello(){
	return "Hello World!";
}
{% endhighlight %}

Markdown:

{% highlight text %}
{%raw%}
{% highlight javascript %}
function hello(){
	return "Hello World!";
}
{% endhighlight %}
{%endraw%}
{% endhighlight %}
