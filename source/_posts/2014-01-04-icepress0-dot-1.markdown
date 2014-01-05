---
layout: post
title: "Ice Press 0.1 Release"
date: 2014-01-04 20:46:24 -0500
comments: true
categories: blog
---

IcePress is a responsive [Octopress](http://octopress.org/) theme that was forked from [PageTurner](https://github.com/elisehein/Pageturner),
a theme created by Elise Hein and Karl Sutt, which unfortunately is not under active development.

IcePress was created to improve upon PageTurner and offers the following additional features:

* ** Icy, native syntax highlighter **

<pre>
Awesome code snippet
</pre>

{% codeblock lang:objc %}
[rectangle setX: 10 y: 10 width: 20 height: 20];
{% endcodeblock %}

{% codeblock Time to be Awesome - awesome.rb %}
puts "Awesome!" unless lame
{% endcodeblock %}

{% codeblock Javascript Array Syntax lang:js http://j.mp/pPUUmW Link %}
var arr1 = new Array(arrayLength);
var arr2 = new Array(element0, element1, ..., elementN);
{% endcodeblock %}

[More native Octopress codeblock examples here](http://octopress.org/docs/plugins/codeblock/)

* ** Pullquote **

{% pullquote %}
Surround your paragraph with the pull quote tags. Then when you come to
the text you want to pull, {" surround it like this "} and that's all there is to it.
{% endpullquote %}

* ** Block Quotes **

{% blockquote %}
Last night I lay in bed looking up at the stars in the sky and I thought to myself, where the heck is the ceiling.
{% endblockquote %}

* ** Video Tags (work in progress) **

{% video http://s3.imathis.com/video/zero-to-fancy-buttons.mp4 640 320 http://s3.imathis.com/video/zero-to-fancy-buttons.png %}


* ** Image Tags (work in progress) **

{% img http://placekitten.com/890/280 %}
Bacon ipsum dolor sit amet exercitation ball tip consectetur tempor. Biltong exercitation aliqua, ribeye consequat veniam consectetur.


{% img left http://placekitten.com/320/250 Place Kitten #2 %}Aliquip nulla do tempor, ball tip dolore anim esse strip steak nisi nostrud. Tri-tip mollit deserunt ut duis, commodo brisket short loin est hamburger sunt consequat rump meatloaf. Exercitation enim aliqua tempor dolore. Non eu venison, officia boudin tri-tip enim beef ribs flank cupidatat in aute. Tail voluptate fugiat aute flank, venison sint.{% img right http://placekitten.com/300/500 150 250 Place Kitten #3 %}


* ** Excerpts (work in progress) **

Just place <code>&lt;!--more--&gt;</code> where you want a post to display an excerpt. Like below:

