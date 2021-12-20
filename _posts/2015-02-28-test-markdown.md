---
layout: post
title: Markdown 공부
subtitle: github.io에 기록하기 위해서 markdown 배워보기
categories: markdown
tags: [markdown]
---

**Markdownd이란?**  
마크다운(markdown)은 일반 텍스트 기반의 경량 마크업 언어로 일반 마크업 언어보다 문법이 쉽고 간단하다.  HTML과 RTF등 서식 문서로 쉽게 변환되기 때문에 README파일이나 온라인 게시물 등으로 많이 사용된다.

1. typing  
>글을 적을 때는 별다른 조치 없이 그냥 글을 적으면 된다.
2. italics & bold  
>글을 적다가 강조해야 할 부분이 등장하면 이 방법을 사용해보면 된다.  
italics - 손글씨를 말한다. 강조하고 싶은 글 양 옆에 언더바 '_'를 적어주면 적용된다.  
markdown is good! -> _markdown_ is good!

You can write regular [markdown](http://markdowntutorial.com/) here and Jekyll will automatically convert it to a nice webpage.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](http://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.

Here's a useless table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


How about a yummy crepe?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

It can also be centered!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .center-block :}

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
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
