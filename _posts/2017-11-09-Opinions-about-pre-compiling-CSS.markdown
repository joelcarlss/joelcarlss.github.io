---
layout: post
comments: true
title:  "My opinion about Pre-compiling CSS"
date:   2017-11-09 14:33:14 +0100
categories: Exam 1
---

## What do i think about pre-compiling CSS?

Pre-compiling CSS makes it allot easier to write CSS. For this exam I used SASS.
The structure of the code is very easy to read when we can use curly brackets to tell where all code is for something. In regular CSS we will write it inside curlies as well but everything inside a class(for example) needs to have their own row. Here we can write the class and inside write every value, like a lists appearance inside the class. Here is an example of what i mean:
{% highlight ruby %}
CSS:
.className {
Margin: 5px;
}
.className h1 {
Color: #efefef;
}
.className ul {
Margin: 10px;
}
{% endhighlight %}

{% highlight ruby %}
SCSS:
$colorName: #efefef;
.className {
  Margin: 5px;
  h1 {
    Color: $colorName
  }
  ul {
    Margin: 10px;
  }
}
{% endhighlight %}


This is a very logic way to write and the code gets very organized. When we can write values to variables we only need to change the variable's value to do changes in allot of places.
We also gets the advantage of structuring our code in many files.
 
The negative sides of pre-processing is that it requires the right software running to do changes. A browser doesn’t read SASS for example, therefore it will get translated to CSS. When the code gets translated into CSS it looses all its structure and it becomes very hard to change without the software. The structure is unnecessary when the browser reads it but for a programmer the structure is extremely important.
